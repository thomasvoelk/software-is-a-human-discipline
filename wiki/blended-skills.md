---
status: draft
---

# Blended Skills

**Summary**: Breadth across the software development process is a form of expertise, not a compromise. Specialization is often a choice people make without realizing it is a choice.

**Sources**: Martin Fowler, Unmesh Joshi, Gitanjali Venkatraman, "Expert Generalists" (https://martinfowler.com/articles/expert-generalist.html). Personal career history and current team practice.

**Last updated**: 2026-06-15

---

Most organizations treat specialization as the natural endpoint of a career. You start broad and narrow down. Seniority means depth in a lane: requirements engineer, software engineer, test engineer, architect. The deeper the lane, the more expert you are.

I have always found this wrong. Not for everyone — but wrong as a universal model.

The alternative is not dilettantism. It is what Fowler, Joshi, and Venkatraman call the "expert generalist": someone with genuine depth in more than one area, who can move across the full software development process and see where the real problems are. Breadth is not the absence of specialization. Breadth itself can be a specialization.

## How I developed this

I did not choose blended skills as a philosophy early on. My first employer, SOPHIST — a requirements engineering company, probably the best in its domain in German-speaking countries at the time — shaped me in ways I only understood later. I was an apprentice (*Auszubildender*), which meant I developed software while also going to customers as a junior consultant for requirements engineering and OOA/OOD. I watched senior colleagues like Peter Hruschka run two-day project kickoffs and learned, by observation, what good project management looks like. Requirements were not just a phase there — they were the foundation. That conviction has never left me.

My second company had four managers — three of whom also wrote code — and me. We built Java web applications for Siemens. Every step of the process was mine: understand the requirements, write the code, manage the project, test, deploy, support. There was nobody to hand anything off to. By the time I arrived at a larger organization, I had done everything — not because I chose breadth as a strategy, but because there was no other option.

That changed when I got to my current company. In my first week, I heard that a deployment needed to go to the WebSphere team. I asked why we could not do it ourselves. Someone asked if I was a WebSphere specialist. I said no — I had only deployed to Glassfish — but that it was probably not much different. What I had not fully registered yet was that only the WebSphere team was actually permitted to deploy. The boundary was not just a habit. It was policy. That policy no longer exists. The philosophy today is closer to: you build it, you run it.

## The flex team

At my current company I work in a flex team: we support different product teams for a period, then move on to the next. Most teams draw strict lines around their work. Requirements must be clear before we start. We do not deploy to production. We do not do operations. We need an architect for this.

My team does none of that. When requirements are unclear, we help make them clear. We deploy to production and we operate what we build, because that is how you learn whether the application is actually being used and where the problems are. We do our own architecture and design. We take on problems we have not encountered before.

I believe my approach has *abgefärbt* onto the people around me — the color has bled from one surface to another. Not by instruction, but by working alongside each other. They chose it. And that is the important word.

## Specialization is a hidden choice

The teams that do not deploy, that wait for clear requirements, that defer to architects — they are often less constrained than they believe. They have made a choice, often without realizing it is a choice. The boundary feels like a wall. It is a decision that can be unmade.

Going wide is also a choice. It is not the easier one. It means being willing to be uncomfortable, to not yet know how something works, to own problems that fall outside your official lane. But the opportunity appears more often than people realize.

Fowler's article argues that organizations should recognize this kind of generalist expertise as a first-class career path, not a waystation before you specialize. I think that is right. But I would add: you do not need the organization to recognize it before you start. You can choose it now. See [[it-is-always-your-turn]].

The trade-off is real: time spent broadening is time not spent deepening. A database specialist will know things I never will. A dedicated test engineer will see problems I miss. Blended skills are not superior to specialization — they are a different optimization. I optimize for ownership, adaptability, and understanding the whole system. The expert generalist knows when specialization is necessary and when it is not. Their breadth helps them identify which problems truly require deep specialization and which are being treated as specialist work out of habit. Specialization is one valid path to expertise. The mistake is assuming it is the only one.

## Two ways breadth pays off

Broad experience pays off in two distinct ways, and it is worth keeping them separate.

The first is what [[learning-in-the-gaps]] describes: deliberate practice between tasks. You learn TDD because you are curious, not because anyone asked. You build something just to understand how it works. This is proactive, chosen, quiet.

The second is different: it happens in the heat of the moment, under pressure, with no time to prepare. When you have done deployment in several different contexts, you carry a feel for what is structural and what is incidental — which parts are really about the tool and which parts are about the underlying problem. Fowler's article calls this "mechanical sympathy," borrowed from racing driver Jackie Stewart: you do not need to be a mechanic to have an intuition for how the engine behaves.

The WebSphere story is an example of the second kind. I had not worked with WebSphere. But I had deployed to Glassfish and understood what deployment actually involves. That was enough to make a reasonable assessment in real time: probably not much different. Not a bluff. Pattern recognition from accumulated breadth.

[[learning-in-the-gaps]] builds the reservoir. Mechanical sympathy is what you draw from it under pressure.

Ultimately, blended skills are about ownership. The more of the software development process you understand, the fewer places remain to hand a problem to someone else. That is not a burden. It is an opportunity to learn, contribute, and solve problems end-to-end. In that sense, blended skills are a practical consequence of [[responsibility-process]]: if you repeatedly choose responsibility, you eventually learn whatever is necessary to act on it.

## Related pages

- [[learning-in-the-gaps]]
- [[it-is-always-your-turn]]
- [[software-is-a-human-discipline]]
- [[challenge-the-solution]]
- [[no-absolutes]]
