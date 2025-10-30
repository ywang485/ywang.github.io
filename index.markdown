---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: single
author_profile: true
---

I'm an AI and HCI researcher. I do research on AI and creativity. In an era increasingly saturated with AI-generated content, I hope to explore how to cultivate more **intentional** content and make it recognizable.

A lot of my recent work is about stories, especially interactive stories implemented with LLMs (games like AI dungeon, or games with LLM-driven NPCs, etc.). I designed [systems for authors to control AI-generated stories](https://arxiv.org/abs/2506.10161), and for interactive stories, to [guide the audience to narratively meaningful directions when they get lost in pure AI-generated content](https://arxiv.org/abs/2502.18641). I also did other work on game design tools and game character modeling, such as turning stories into [game maps](https://arxiv.org/abs/2309.15242) or [character actions](https://arxiv.org/abs/2405.13042).

In terms of technical methods, my research generally involves **Large Language Models**, **Reinforcement Learning** and **neural symbolic methods** for computational reasoning and planning. 

I'm currently a research scientist in [Midjourney storytelling lab](https://mj-storytelling.github.io/). In the past I have worked in Autodesk Research on modeling, executing and simulating design intents for architectural design applications. My work includes [LLM agents for building occupant simulation](https://arxiv.org/abs/2506.12331), [capturing subjectivity in building design intents](https://dl.acm.org/doi/abs/10.1145/3613905.3650815), [turning spatial constraints into building designs](https://arxiv.org/abs/2309.02583), and [critic-driven design process with AI partnership](https://scholar.google.com/scholar?oi=bibs&cluster=15813830137122992288&btnI=1&hl=en).

I did my PhD in Computer Science at Arizona State University, where the majority of my work was on desigining computable logic formalisms for automatic reasoning, especially to [incorporate probabilistic thinking in commonsense reasoning](https://dl.acm.org/doi/10.5555/3032027.3032045) so that we can [build planning agents who can take action in a world with uncertainty ](https://arxiv.org/abs/1805.00634).

### Representative and Recent Work

![storryverse](assets/images/storyverse.png)
[StoryVerse](https://arxiv.org/abs/2405.13042) is a pipeline for injecting authored stories into character simulations through character actions. Under the hood is an LLM-based narrative planning process that iteratively generates and reviews character action sequences using LLM and a simulated game environment. The generated character actions satisfy constraints from both storytelling intents and executability in a game environment. The workflow mediates between the creative input from the story writer and the emergent behaviors exhibited by simulated characters or player controlled characters.

<br />
<br />

![wahtelse](assets/images/whatelse.png)
[WhatELSE](https://arxiv.org/abs/2502.18641) is an authoring tool for LLM-based interactive narratives aiming at balancing authorial control and emergence. WhatELSE distinguishes canonical narrative experience envisioned authors from actual audience experienced narratives. The interface provides three views (narrative pivot, outline, and variants) to help authors understand the possibility space of audience’s experienced narrative, and corresponding tools leveraging linguistic abstraction to shape the possibility space. 
<br />
<br />

![plotmap](assets/images/plotmap.png)
[PlotMap](https://arxiv.org/abs/2309.15242) is a technical pipeline that maps stories into game maps. We use LLMs to extract conceptual locations where key plot events happened in the story, and then assign the conceptual locations to concrete positions on a given geometric map to satisfy spatial constraints extracted from the story. We have implemented two technical methods to solve the location assignment problem: an evolutionary computation based approach through Covariance Matrix Adaptation Evolution Strategy (CMA-ES), and a Reinforcement Learning (RL) based approach.

![IndoorWorld](assets/images/indoorworld.png)
[IndoorWorld](https://arxiv.org/abs/2506.12331) is an LLM-driven agent simulation framework aimed at providing virtual environment and benchmarks that tightly integrates social and physical dynamics in both open-ended simulation and closed-form tasking solving settings. We demonstrated the application of this framework with a series of building occupant simulation experiments to show how it can inform architectural design and resource allocation.



[Full Publication List](https://scholar.google.com/citations?user=e0hRtGUAAAAJ)