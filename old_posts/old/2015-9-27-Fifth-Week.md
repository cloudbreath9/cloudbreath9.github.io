---
layout: post
title: Fifth Week
---

Apologies for the late post. This past week has been crazy. Career fair threw a wrench into my studies, and I’ve been playing catch-up since. I was unable to finish the Voting project on time due in part to this and several other factors. I suspect a lot of the other students in the class are going through similar things. 

This Wednesday, a really cool guy named Alex Menzies came to give a presentation. Alex works at NASA’s Jet Propulsion Laboratories, and he talked about how his team came about and how their workflow went. Alex, clearly a proponent of agile programming, also described how his team’s programming sprints work. Overall, this talk was engaging and fun; I enjoyed it more than the previous guest speaker.

After continuing a bit more on pointers and references in C++, this week’s lectures nicely segued into an explanation of iterators and their types. I was quite intrigued by this part, as I had never used iterators in C++ before. The way the methods implicitly require certain levels of iterators simply through the use of certain operators really amazed me, though I can’t decide whether or not this is truly preferable to Java’s requirements of explicit sub-classing in order to achieve similar results. C++ is definitely more convenient, but perhaps the safety provided by Java might be worth it in some cases.

This week’s reading was, again, about how small bugs in important systems can cause massive failures. This time, it was with the Patriot missile air defense system deployed in the 1990s. Unfortunate side effects of using a non-terminating binary expression in a floating point along with flaws with an outdated design caused the system to fail, leading to the system’s inability to prevent a ballistic missile attack on a battalion of American soldiers. I feel that this reading further stressed the importance of trying to ensure good code.

Tip of the week:

Use git pull --rebase, which will do an incremental merge with each of your commits instead of merging with all your commits at once. The merges will usually be much easier to understand this way.
