require 'html-proofer'
require 'yaml'

namespace :assets do
  task :precompile do
    sh 'bundle exec jekyll build'
  end
end

def config
  config = YAML.load_file('_config_test.yml')
  config['proofer'].keys.each do |key|
    config['proofer'][key.to_sym] = config['proofer'].delete(key)
  end
  config
end

def serve_site
  sh 'bundle exec jekyll serve -c _config.yml,_config_test.yml --detach'
end

def html_proofer
  puts "HTML Proofer version: #{HTMLProofer::VERSION}"
  HTMLProofer.check_directory('./_site', config['proofer']).run
end

task :test do
  begin
    serve_site
    html_proofer
  ensure
    `pkill -f jekyll`
  end
end
