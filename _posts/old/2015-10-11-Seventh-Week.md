---
layout: post
title: Seventh Week
---

Test week! The test turned out to be a lot easier than I expected. The code we went through during lectures was more than enough study material for the test.

On Monday, we briefly went over a different way of implementing Range iterators, more closely emulating how STL classes do it. The Wednesday lecture, however, was quite a bit more interesting. This lectured covered using the const keyword and array semantics in C++. I had never really considered how to properly use the const keyword in C++, and this lecture really cleared things up for me. Downing’s wonderful paintball gun analogy was quite entertaining as well! The short section on arrays also helped quite a bit, as I didn’t quite understand the nuances that differentiate arrays and pointers in C++. After this lecture, I was much more confident in my knowledge of how the const keyword and arrays in C++ work.

The readings were a bit more technical this week. They covered the Liskov Substitution Principle (LSP) and the Interface Segregation Principle (ISP). LSP was all about not modifying method behavior semantics when extending a class. One really needs to carefully consider the relationship between the superclass and the subclass when performing inheritance in order to ensure that the relationship is an ISA relationship in terms of behavior, not static properties. With LSP, one is not allowed to strengthen the preconditions of a method or weaken the postconditions of a method when overriding it. ISP, on the other hand, attempts to minimize interface pollution through delegation or multiple inheritance. I really enjoyed these articles, as they provided good practical advice that I could use to analyze my previous attempts at object-oriented design.

Tip of the week:

Sleep. Sleep enough. Sleep consistently. Please.
