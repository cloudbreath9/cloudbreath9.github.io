---
layout: post
title: Ninth Week
---

And another week has whizzed by. The Allocator project was due this week, and it turned out to be very manageable, especially given that we didn’t have to maintain free lists and I had already written two heaps before this one.

This week was heavier on Downing having us write code in class. I like this approach, as we get to collaborate with our peers and learn through conversations, which I prefer much more to the lectures (even if Downing makes them more fun than most other lectures). This week, we continued to focus on vectors, continuously iterating over our implementation of them, slowly introducing more features using keywords such as explicit or friend to define explicit constructors and declare friend functions respectively. We finally began to get into actual object-oriented design concepts with the Policy Design Pattern on Wednesday, which emphasized how the user should be able to alter a class’s behavior by providing alternative implementations, but the class should provide defaults regardless. 

The papers this week wrapped up the last of the articles on Object-Oriented Design with a description of the notion of stability, which basically meant that more stable classes were less likely to change and thus should be depended upon. Less stable classes should always depend upon more stable classes. The readings also included an article that cites the disadvantages to using Java’s extends keyword, including coupling, loss of flexibility, and fragile base classes.

Tip of the week:

It may be worth your while to learn dependency injection libraries such as Guice and Dagger, as many large companies make use of these tools.
