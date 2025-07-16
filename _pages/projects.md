---
layout: archive
title: "Research Projects"
permalink: /projects/
author_profile: true
---

I am passionate about developing algorithms for robots to perform complex tasks in the real world. Here are the projects I have worked on:

## Zero-shot deployment of End2End framework on a imperfect robot

Our training pipeline takes only 20 minutes for self-supervised learning, but demonstrate high performance. 
Recently, we zero-shot deploy the trained model without any post process. 

<iframe width="560" height="315" src="https://www.youtube.com/embed/RQKesPclD94?si=lq35ahsua-tmfBa4" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

## Parallel trajectory optimization

After reading the [tutorial of distributed optimization](https://arxiv.org/abs/2301.11313), I'm wondering though the distributed optimization takes unacceptable time for real-time solving due toe the network latency, can we make it parallel on single machine to speed up the optimization process.
Therefore, we rewrite the problem formulation of general motion planning problem and develop an algorithm based on consensus alternating direction multipliers method (CADMM). 
We found our new pipeline surpassed GCOPTER in some domains, which has demonstrate state of the art performance performance in its paper.
Meanwhile, due to the problem is formulated to a convex form, the algorithm is guaranteed to converge to the global optimal.

<iframe width="560" height="315" src="https://www.youtube.com/embed/00LBW0G8CwU?si=EOkoMg8erNjLdzbi" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

## Air-ground collaboration

Just as some groups of humans can overcome difficulties by actively helping other groups, I'm wondering if robots can do same things. 
We treat the UAV as a mobile sensors of a group of blind UGVs, and let the UAV fly to perceive unknown environments while let the blind UGV navigation in the known environment simutaneously.

<iframe width="560" height="315" src="https://www.youtube.com/embed/1Hn2U4-WZ7Q?si=oaF8bPKmYGIl6mAg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

## Universal differential drive robot trajectory optimization

The widely used differential flatness introduced a singularity point at angular speed and its high-order derivatives when robot's line speed is zero. 
To tackle the problem in principle, we develop a new trajectory formulation based on robot's motion states.

<iframe width="560" height="315" src="https://www.youtube.com/embed/fo64QufedPo?si=__moHW1dzJvThFad" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

## Multi-modal drone

Developed an aerial-ground autonomous navigation system for drones using FAST-LIO and ego-planner. Achieved point cloud map relay sharing during exploration.

<!-- <iframe height="315", width="560" src="videos/Rofly.mp4"></iframe> -->
<video src="../videos/Rofly.mp4" controls width="560" height="315"></video>

## Swarm of drones' navigation

Deployed swarm of drones equipped with ORB SLAM for localization, navigation safely within obstacles.

<!-- <iframe height="315", width="560" src="videos/Swarm.mp4"></iframe> -->
<video src="../videos/Swarm.mp4" controls width="560" height="315"></video>