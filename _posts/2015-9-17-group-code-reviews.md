---
layout: post
title: In Defense of Group Code Reviews
published: false
---

Nothing stirs the pot more than discussing the merits of code reviews. Some folks love 'em, others hate 'em. No matter what side of the debate you're on, odds are you are at least on _a side_. I personally fall into the "love `em" category. Code reviews provide to me a venue for both learning and explaining that doesn't require me to constantly pester the nearest developer who may or may not be able to answer my question. Code reviews have given me insight into particular systems of code that would otherwise be a total black box to me. 

If you happen to fall into the "anti-code review" camp, odds are its because you prefer the direct nature of Paired Programming. Paired programming is fantastic in that it provides immediate feedback and thorough understanding of the "driving" developer's cognitive processes. I'd say few people actively dislike this practice, as opposed to often being too busy to commit to it. 

Both of these practices serve to distribute knowledge across a team while maintaining a constantly evolving product. This is a virtuous goal and one that should not be discounted. However, both of these practices go about accomplishing this in radically different ways, and that serves to divide developers into the two camps I mentioned previously.

## An Appeal to Pragmatism

I personally delight in both of these practices. I love grabbing my morning cuppa and reading through my coworker's code before anyone has had time to interrupt me in the morning. It's like my own morning Hegel. I also love getting the opportunity to sit with a fellow developer and watch their metaphorical cogs spin. Understanding how another person thinks and solves problems is key to understanding and optimizing one's own cognitive skills. 

Both of these approaches, however, have their downsides. Code reviews can quickly start to seem like a chore (especially if you're not a super-nerd who loves to read code), and tend to be ignored or forgotten. This creates a huge process bottleneck if your team relies on code reviews as a criteria of acceptance (which, IMO they absolutely should). Paired programming essentially removes a full developer resource for as long as a pair commits to it, and business goals will seldom allow this for any substantial period of time. It also limits the amount of developers who properly review the code to a small subset of the team that already has a direct investment in the code. No es bueno.

What if there was an approach that accomplished the benefits of both approaches, while also mitigating the pitfalls of each? This is where group code reviews shine!

## Better Knowledge Sharing

In a group code review, any more than two developers sit down together with the author of a particular feature, and listen and watch as the developer walks them through the changes in their entirety. 

## Group Code Reviews are NOT a Panacea

Group code reviews *absolutely* should not be the only form of review that developers participate in. For starters, there is no feasible way to _group_ code review _every_ feature or change that is made. More often than not, your standard code review will be enough. This also doesn't eliminate the benefits of paired programming, which provides even more inde
