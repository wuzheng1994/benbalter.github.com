---
title: Removing a feature is a feature
description: Features aren't what make a product great. Being the best at solving a problem is what makes a product great. Every time you remove a feature that doesn't support your product's core use case, you're adding an implicit feature that does.
---

Features aren't what make a product great. Being the best at solving a problem is what makes a product great. Every time you remove a feature that doesn't explicitly support your product's core use case, you're adding an implicit feature that does.

Your users use your product because [they're trying to solve a specific problem](https://strategyn.com/jobs-to-be-done/). It could be getting from point A to point B, finding their next romantic interest, or having some place to store their vacation photos. Whatever reason, they have a specific task in mind, and your product is simply the most effective tool to accomplish it, at least, that's the idea. That means that every feature that doesn't solve the problem they're trying to solve, isn't just product cruft, it actively stands in their way.

### Features aren't free

Features come with a very real cost to users. As [I wrote a few months back](http://ben.balter.com/2016/03/08/optimizing-for-power-users-and-edge-cases/):

> We have a motto at GitHub, part of the [GitHub Zen](http://ben.balter.com/2015/08/12/the-zen-of-github/), that "*anything added dilutes everything else*". In reality, there is always a non-zero cost to adding that extra option. Most immediately, it's the time you spend building feature A, instead of building feature B. A bit beyond that, it's the cognitive burden you've just added to each user's onboarding experience as they try to grok how to use the thing you've added (and if they should). In the long run, it's much more than maintenance. Complexity begets complexity, meaning each edge case you account for today, creates many more edge cases down the line.

> The WordPress community [has a similar philosophy](https://wordpress.org/about/philosophy/), "*decisions not options*." Every time you provide a user with an option, you're asking them to make a decision, and [those decisions quickly add up](https://en.wikipedia.org/wiki/Analysis_paralysis), especially when the user doesn't care or doesn't fully understand the implications. Ultimately, many of these decisions are technical or domain-specific decisions, and as a project maintainer, as the subject-matter expert, it's your obligation to absorb all that complexity on behalf of your users, not to simply kick the decision can down the line.

And with every new feature you add, they'll need to go through that process all over again, not to mention, that new knob you added for User B, because "why not?", is going to make it harder for User A to find the knob they're actually looking for.

### Reducing feature creep

Which feature to remove is likely going to be specific to your product, but if it doesn't *bring your target user joy*, to borrow a popular criterion for eliminating real-world clutter, cut it. Easier still, don't add the feature in the first place.

Absent your intervention, projects have a tendency to become feature Christmas trees, each stakeholder adding their own purpose-specific ornaments. This happens for several, easily avoidable reasons, at least if you can learn to spot them:

* **Being reactive to ad-hoc requests** - customer feedback is invaluable, but your users are experts at using your product, not at building it. A one off feature request that might satisfy a single user, might not be the right move for your product in the long run, if they're not your target user. Avoid the temptation to play feature whack-a-mole. Instead, make your taste, vision, and foresight a feature in and of itself, building products that proactively solve your target users' needs, rather than reactively implementing individual features to satisfy your loudest users.

* **Scope creep** - projects have a natural tendency to drift towards solving problems beyond their original purpose. Once you've got the 0.1 that tackles one problem, it's all to easy to start seeing related problems that could be tackled in similar ways. When problems are similar but not the same, your product becomes sort of good at lots of things, rather than really good at the thing your users want to use it for. Define the scope early on and purposefully revisit that discussion before agreeing to tackle any feature beyond it.

* **Scratching a technical itch** - Technology can often make new user-centric functionality possible, but some of the highest impact features are also the most boring to implement technically. Borrowing another phrase form [GitHub Zen](http://ben.balter.com/2015/08/12/the-zen-of-github/), favor practicality over purity. Philosophically impure features that violate the rules of computer science textbook may be the most useful to users, and vice versa. Avoid the temptation to fixate on the shiny new thing, just because it's shiny, or because it'd be a fun technical challenge to tackle, and focus on the most practical route to putting useful features in the hands of your users.

* **Not understanding your users' needs** - Who's your target user? What problem are they trying to solve? How is your product uniquely positioned to solve it? It's easy enough to look at what features your competitors implement, and match them point-for-point, without regard for why you're actually building it. Unless your team has a shared understanding of your users' unique needs, and in many cases, how your vision of the world differs from your competitors', you'll quickly change course from solving one problem to not solving lots of problems.


http://neverworkintheory.org/2016/06/09/too-many-knobs.html
https://daringfireball.net/2004/06/broken_windows
https://xkcd.com/1172/