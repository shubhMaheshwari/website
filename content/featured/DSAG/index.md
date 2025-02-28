---
date: '6'
title: 'Full Body Action Generation'
cover: './dsag-teaser.jpg'
github: 'https://github.com/skelemoa/dsag'
cta: 'https://skeleton.iiit.ac.in/dsag'
tech:
  - WACV 22'
  - SMPL
  - ExPose
  - Self-Attention
  - VAE
---

DSAG is a controllable deep neural framework for action-conditioned generation of full body actions. To overcome shortcomings in existing generative approaches, we introduce dedicated representations for encoding finger joints. We also introduce novel spatiotemporal transformation blocks with multi-head self attention and specialized temporal processing. The design choices enable generations for a large range in body joint counts (24 - 52), frame rates (13 - 50), global body movement (inplace, locomotion) and action categories (12 - 120), across multiple datasets (NTU-120, HumanAct12, UESTC, Human3.6M).
