# Principles And Maxims
Software engineering principles or maxims that have served me very well.

## Reduce costs
Our engineering time is the most expensive resource we spend and it is governed by system complexity. One hour of engineering time is equal to leasing a server for three-plus months. If it saves you time to add a server, then just add the server.

## Make all future work easier
Do work that makes all future work easier. Sometimes this means the immediate work will take longer but will pay dividends in the future. 

## Focus on our business
We should maximize our time on our product features and not support or manage the IT systems that run the product. Our clients like us because of our product and not the underlying services we run our product on. Cloud providers are better at managing these services than we are.

## Reduce complexity
We should strive to make our servers less important in every decision we make. By servers, I really mean the server hard disk. We should work toward the goal of having the server rebuild the disk image on every code deployment. This concept also applies to development workstations. We should have a goal of getting our source to compile immediately from version control checkout without spending days setting up a development workstation.

## Don't solve problems we don't have
We should try to catch ourselves before we over-engineer things. While engineering one feature, it's a common occurrence to think, "We might need this other feature in the future." We should add that feature only if we know for certain that we will need it in the future. If we are not certain, then we should hold off on it; we can always add it later if we need it later. If we were to add it now and never need it in the future, we would be adding unnecessary complexity, adding to the list of things we need to support, and wasting company time by delaying the project's completion date.

## Consistently bad is better than inconsistently good
Consistency makes the code and product easier to understand and work with. Inconsistency makes the code and product more complex, and it increases the risk of a developer missing something. A consistent flaw is more obvious and easier to change than inconsistent flaws.

## Go with the grain
Try to follow the path of other developers. There is usually a reason the most popular option is the most popular. Similarly, if the solution to a problem is growing more complicated the more you dive into it, that is a sign that it is the wrong solution.

## Strong opinions but held loosely
Software engineers should learn to have strong technical opinions, but to survive you must also learn to hold them lightly.

## Estimates
> You need to be willing to endure the discomfort of looking someone in the face, saying “I don’t know”, and then standing your ground when they pressure you to lie to them. They probably don’t want you to lie, but there is a small chance that they pressure you to. If you don’t resist this pressure, you can end up continually giving estimates that are 10x off-target, blowing past them as you **lose credibility**, and running your brain ragged with sleep deprivation against a problem you haven’t given it the time to break down and understand.

- https://news.ycombinator.com/item?id=19671673
- https://erikbern.com/2019/04/15/why-software-projects-take-longer-than-you-think-a-statistical-model.html

## Rewrites
Suggesting a total rewrite of an application is almost always a mistake. Find and propose another solution.

## Scaling Teams
If your company management makes a request to scale up a software team the correct response is always 'Yes'. You can educate them about the mythical man month and all the other reasons why it won't work, but agree with them to scale up the team. If you are unwilling to try to scale up the team because you believe it will be damaging to productivity it would be best for everyone, including your career, to find a new job.

- https://en.wikipedia.org/wiki/The_Mythical_Man-Month

## Psychology
Senior software engineers need to be both arrogant and humble. We need to be arrogant to believe we solve any technical problem. However, we need to be humble in we will be wrong 90% of the time. We just have learned to correct our mistakes before others see them. It is okay to be wrong. When you are wrong just admit and continue solving technical problems.

## Difficult Software Developers

https://neilonsoftware.com/difficult-people-on-software-projects/developers/
