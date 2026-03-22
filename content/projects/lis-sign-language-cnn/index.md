---
title: "LIS Sign Language Recognition"
description: "A machine learning project built around CNN-based recognition of the LIS sign-language alphabet."
summary: "A machine learning project focused on LIS alphabet recognition through custom and AlexNet-based CNNs, dataset work, and data acquisition tooling."
draft: false
weight: 40
projectSeries: "Academic"
categories: ["Academic"]
tags: ["Python", "PyTorch", "Computer Vision", "CNN", "OpenCV", "Torchvision", "TensorBoard"]
series: ["Academic"]
series_order: 1
date: 2024-07-25
---

{{< lead >}}
A computer-vision project for recognizing the LIS sign-language alphabet using convolutional neural networks and a custom data workflow.
{{< /lead >}}

{{< github repo="Darakuu/LIS-Project" >}}

<div class="project-brief">
  <article>
    <span>Type</span>
    <strong>Academic machine-learning project</strong>
    <p>Built around model design, training, and the practical side of dataset preparation.</p>
  </article>
  <article>
    <span>Focus</span>
    <strong>Recognition pipeline</strong>
    <p>Model architecture, data collection, preprocessing, training, and evaluation.</p>
  </article>
  <article>
    <span>Stack</span>
    <strong>Python and PyTorch</strong>
    <p>Deep-learning experimentation with supporting OpenCV and TensorBoard tooling.</p>
  </article>
</div>

{{< keywordList >}}
{{< keyword icon="github" >}} GitHub {{< /keyword >}}
{{< keyword >}} Python {{< /keyword >}}
{{< keyword >}} PyTorch {{< /keyword >}}
{{< keyword >}} OpenCV {{< /keyword >}}
{{< keyword >}} Torchvision {{< /keyword >}}
{{< keyword >}} TensorBoard {{< /keyword >}}
{{< /keywordList >}}

## Problem Framing

The project goal was to recognize signs from the LIS alphabet through a computer-vision pipeline. That makes
it a model problem, but not only a model problem. Accuracy depends heavily on how data is collected,
organized, and cleaned before training ever begins.

That is why this project matters to me more than a simple "trained a model" summary. The interesting work
was in building the surrounding pipeline well enough that the experiments meant something.

## Model Work

I implemented both custom CNN architectures and AlexNet-based variants, comparing approaches rather than
treating the first solution as final.

The practical goal was to understand the tradeoff space:

- how much complexity the task actually needed
- how the models behaved under different data assumptions
- what architecture decisions improved generalization instead of only fitting the training set

## Dataset and Tooling

Data acquisition and data engineering were a core part of the project. In machine-learning work, that stage
often determines whether the modeling phase is credible or just decorative.

I built the pipeline around:

- dataset preparation for training and evaluation
- image handling and preprocessing support
- experiment visibility through tooling such as TensorBoard

That combination made it possible to iterate with feedback rather than treat training as a black box.

## What This Project Shows

This article belongs in the portfolio because it demonstrates comfort outside game-engine work. It shows that
I can move into a different technical domain, reason about pipelines end to end, and structure experiments in
a way that is useful rather than superficial.
