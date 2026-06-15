# Systems and API design

- [Everything I know about good system design by Sean Goedecke](https://www.seangoedecke.com/good-system-design)
- [Writing a good design doc](https://grantslatton.com/how-to-design-document)
- [Don't expose too much in your API](https://yusufaytas.com/good-apis-age-slowly). Just common sense saying that whatever you expose is public, yet it's well said.

# Techniques

- [Some tips to achieve idempotency](https://lightfoot.dev/why-arent-you-idempotent)
- [Sur les vertical slices](https://www.milanjovanovic.tech/blog/vertical-slice-architecture-where-does-the-shared-logic-live), not so much for the article in itself (which is good but not revolutionary), but for the mantra
> Duplication is cheaper than the wrong abstraction.

that should be in golden letters in all and every software engineering office. I want T-shirts and mugs.
- [Concise enough yet clean and exhaustive example of state machines in .NET+EFCore](https://adrianbailador.github.io/blog/59-trip-state-machine-dotnet/)

## Algorithms & data structure

- [Very didactic and visual explanations of quad-trees](https://growingswe.com/blog/quadtrees)
- [Probabilistic fair queuing N users on a fixed number of queues](https://brooker.co.za/blog/2026/02/25/sfq.html)
- [Shuffle sharding](https://aws.amazon.com/blogs/architecture/shuffle-sharding-massive-and-magical-fault-isolation/), i.e how to probabilistically de-correlate faults between customers with just a bit of per-customer controlled randomness

# Practice, soft skills, ...

- [What actually makes you a senior](https://terriblesoftware.org/2025/11/25/what-actually-makes-you-senior/)
    - TL;DR : reduce ambiguity, plan, de-risk. _Then_ and only then using your technical skills
- [A few git commands to get a glimpse on a repo](https://piechowski.io/post/git-commands-before-reading-code/)

## Practice around AI
### 2026
- [If AI writes your code, why use Python?](https://medium.com/@NMitchem/if-ai-writes-your-code-why-use-python-bf8c4ba1a055). On why it's now more easy than ever using "harder" languages like Rust rather than sloppy ones like Python

# Curated lists

- [Privacy-oriented alternatives to many services](https://github.com/pluja/awesome-privacy?tab=readme-ov-file)
- [Self-hosted apps](https://selfh.st/apps/)
- [Summary of all SE "laws"](https://newsletter.techworld-with-milan.com/p/the-20-software-engineering-laws)

# Hardware
- [Very detailed about storage latency](https://planetscale.com/blog/io-devices-and-latency)

# Tools

- [AI models fit to GPU model](https://www.canirun.ai/device/rtx-a6000)
