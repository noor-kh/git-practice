# Noor's Software Engineering Pick

## [Things You Should Never Do, Part I — Joel Spolsky](https://www.joelonsoftware.com/2000/04/06/things-you-should-never-do-part-i/)

Joel Spolsky argues that throwing away a working codebase and rewriting it from scratch is one of the worst strategic mistakes a software company can make. His main example is **Netscape**, which decided to rewrite its browser from the ground up. The rewrite took years, and during that time the company had no competitive product to ship while Internet Explorer took over the market.

What I find most interesting is his point that **old, ugly code is not the same as bad code**. Those weird-looking lines and strange edge-case checks usually exist because someone found a real bug, often one that only showed up on a specific machine or in a rare situation. Every one of those fixes represents knowledge the team paid for. When you rewrite from scratch, you throw all of that away and have to rediscover the same bugs again. As a student, my instinct is usually to start fresh when code looks messy, so this was a useful reminder that **refactoring incrementally** is often the smarter move than tearing everything down.