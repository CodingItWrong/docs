# How I Learned to Stop Worrying and Love Development

## Abstract

Is your life as a developer characterized by worry? Mine is. But we don't have to be stuck there, because worry can be a pointer to what we need to change. At this talk we'll discuss what you can do about your stress over schedule slips, defects, difficult-to-write tests, or building the wrong thing. You'll learn to apply agile development practices that will help turn your fear into confidence.

## Description

New programming languages and frameworks are great, but they don't address the fundamental problems we tend to experience on every project: long hours, late releases, and unhappy customers. We're told that agile development practices help with these problems, but getting started can be a catch-22. For example, agile suggests you should test your code, but to do so it has to be well-designed, but to change the design it needs to be tested. How can you get started?

I'd like to tell you the story of how I got started — how I made it through a series of worries one at a time. Each worry came from a real need, and identifying that need helped me find an agile development process to meet it. Another worry would crop up afterward, but I just repeated the process of following the worry again. Now my day-to-day development involves a lot less stress and a lot more fun!

Here's the series of worries I went through, and the need that underlies each:

- **"Will we get the code done in time?"** — Predictability
- **"Will I break something?"** — Reliability
- **"Why is it so hard to write tests?"** — Testability
- **"Can my code handle future changes?"** — Maintainability

For each of these worries, you'll learn:

- What need is the underlying cause of the worry, and why it's important to get that need met.
- Which agile development practice addresses that need.
- What that development practice looks like in a simple scenario.
- Articles and books you can read to learn that development practice.

You'll walk away being able to identify which of the above development needs is your biggest right now and what steps you can take to begin to resolve it.

This session won't remove all your worry: it isn't counseling! But these practices are likely to make a significant change in your quality of developer life. You may even find that you fall in love with development all over again.

## Submission Note

A great way to get into agile development is to apply one practice at a time, based on which will provide the most benefit first. This sequence of practices worked well for me--in fact, some of the later practices weren't even comprehensible until applying earlier practices surfaced the need for them. My hope is to help people who are uninterested in agile, or who are overwhelmed by it, or who are starting with the wrong practices, to get started with a practice that will meet them where they are.

The agile development practices I'll be presenting are:

- The need for predictability can be met by delivering **user stories**, small slices of customer-visible functionality. Working a slice at a time rather than a layer at a time gives you a better sense of how long features will really take to complete.
- The need for reliability can be met by writing **automated tests** to regression-test your code. We'll look briefly at both end-to-end tests and unit tests.
- The need for testability can be met by applying **object-oriented design principles**. Specifically, we'll look at reducing coupling to make a unit test that better isolates the class under test, and therefore is more readable and changeable.
- The need for flexibility can be met by **refactoring** your code in response to new requirements. We'll look at how applying small changes, running the tests after each change, can help us to "make the change easy, then make the easy change."
