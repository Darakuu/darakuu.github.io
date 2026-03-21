---
title: "Arcas Champions"
description: "A multiplayer UE5 project where I worked across AI, gameplay systems, level design, and build workflows."
summary: "Professional multiplayer game work spanning AI bots, gameplay systems, level design support, and custom UBT/UAT build workflows in Unreal Engine 5."
draft: false
weight: 10
categories: ["Professional"]
tags: ["Unreal Engine 5", "C++", "AI", "Multiplayer", "Build Pipelines", "Level Design", "Steamworks"]
series: ["Portfolio"]
series_order: 1
date: 2025-11-01
---

{{< lead >}}
A multiplayer 3D platformer and third-person shooter hybrid where I worked as a gameplay programmer with a generalist production role.
{{< /lead >}}

<div class="project-brief">
  <article>
    <span>Type</span>
    <strong>Professional game project</strong>
    <p>Commercial multiplayer development inside a live production team.</p>
  </article>
  <article>
    <span>Focus</span>
    <strong>AI, gameplay, and pipelines</strong>
    <p>Bots, NPC behavior, gameplay code, level design support, and build automation.</p>
  </article>
  <article>
    <span>Stack</span>
    <strong>UE5, C++, Blueprints</strong>
    <p>Server-aware gameplay work plus designer-facing systems and Steamworks build flow.</p>
  </article>
</div>

{{< keywordList >}}
{{< keyword icon="ue5" >}} Unreal Engine 5 {{< /keyword >}}
{{< keyword icon="code" >}} C++ {{< /keyword >}}
{{< keyword icon="steam" >}} Steamworks {{< /keyword >}}
{{< keyword >}} Blueprints {{< /keyword >}}
{{< keyword >}} Behavior Trees {{< /keyword >}}
{{< keyword >}} UBT {{< /keyword >}}
{{< keyword >}} UAT {{< /keyword >}}
{{< keyword >}} Level Design {{< /keyword >}}
{{< /keywordList >}}

## Project Scope

Arcas Champions sits in the space between a platformer and a shooter, so movement, combat readability,
and encounter pacing all need to work at the same time. My contribution was not limited to a single
system. I moved between AI implementation, core gameplay support, level design work, and project-facing
pipeline tasks depending on what the team needed most.

That generalist role is important context for the rest of this article: the value here was not just
writing isolated features, but helping keep multiple production surfaces moving without losing the
technical standard underneath them.

## What I Owned

### AI bots and enemy behavior

I implemented player-like AI bots and enemy NPC behavior using Unreal's AI stack, with behavior trees,
perception, and gameplay-driven decision logic. The goal was not only to make agents functional, but to
make them readable and maintainable for future tuning.

That meant building behavior in a way that supported iteration by design and gameplay needs:

- clear decision boundaries between sensing, selecting actions, and executing them
- enough flexibility in Blueprint-facing hooks to keep designers unblocked
- behavior that stayed compatible with multiplayer and authoritative game flow

A more detailed, technical write-up of how I implemented the custom systems required are on Bevium's website,
in an another article written by me, here: [Arcas AI on Bevium.it](https://bevium.it/blog/2025-11-03-arcasai-implementation-retrospective).

(Should the website ever die, please notify me)

### Gameplay systems

On the gameplay side I worked in both C++ and Blueprint-oriented workflows. The practical goal was to
keep the core logic robust in code while still allowing fast iteration on content and tuning.

This kind of split mattered in this project. We had to migrate a lot of core logic that only lived in Blueprints, made
by a previous team. This was causing technical debt in the long-term.

During this BP to C++ migration, we built new Blueprint based APIs, interfaces and Data-Driven assets so that the game's
designers could tweak and iterate easily upon gameplay.

### Level design

I also took over level design, from grayboxing and playtest iteration through final polish and
optimization passes. That included practical layout work and the technical side of making spaces run well
enough for the intended experience.

For multiplayer projects, level design is rarely isolated from code. Bot behavior, traversal, combat flow,
spawn logic, and performance all feed back into how spaces should be shaped. Working across both sides
helped reduce that gap.

I personally enjoyed working on the game's level design as I was working on the AI bots: it really made me
appreciate how they would slowly come to life as they learned to use their environment.

## Pipeline and Production Work

One of the more infrastructure-heavy parts of my work on the project was the build pipeline. I created and
maintained a fully-fledged internal plugin (Bevium Tools) built around the Unreal Build Tool and Unreal Automation Tool 
to reduce friction in building andshipping the project.

That work matters because iteration speed compounds:

- repeatable build steps reduce avoidable human error,
- automated workflows shorten the path from change to playable build,
- a maintained Steamworks deployment flow lowers release risk,

I also took on internal coordination when needed. That did not mean formal management ownership in the
traditional sense, but it did mean staying aware of the project's state, helping align day-to-day work,
and supporting onboarding new team members and manage daily tasks when the team needed it.

## Engineering Takeaways

Arcas Champions is the strongest example in my portfolio of how I operate in production:

- I can work close to game feel without losing engineering discipline.
- I can build systems that remain editable by designers.
- I can move from feature work, to creative work, into technical operations when a project needs stability more than novelty.

