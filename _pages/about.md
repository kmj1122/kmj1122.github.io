---
layout: about
title: about
permalink: /
# subtitle: PhD Candidate, <a href='https://engineering.virginia.edu/departments/computer-science'>Computer Science</a>, University of Virginia

profile:
  align: right
  image: prof_pic.jpg
  image_circular: false # crops the image to make it circular
  more_info: >
    <p>Charlottesville, VA</p>

selected_papers: true # includes a list of papers marked as "selected={true}"
social: true # includes social icons at the bottom of the page

announcements:
  enabled: true # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: false
---

I am a PhD candidate in the Department of Computer Science at the University of Virginia,
advised by [Prof. Lu Feng](https://www.cs.virginia.edu/~lufeng/). Previously, I received a PhD in
mathematics from Kyungpook National University.

My research asks one question: **how can learning systems adapt to changing environments
while maintaining safety at runtime?** Training-time safety guarantees can break when deployment conditions differ from training. My work addresses this problem in three directions:
- **Adaptive runtime safety** — safety wrappers that infer changes in the dynamics at deployment and adjust their safety margin under uncertainty, using basis-adaptive neural ODEs and conformal prediction without retraining the policy.
- **Safe in-context adaptation** — frozen policies that adapt their strategy from
  interaction history while respecting a safety budget, using methods such as safe algorithm distillation and latent Q-barrier filtering.
- **Compositional safe adaptation** — agents that execute unseen compositions of
  temporally structured tasks (specified in linear temporal logic) under distribution shift.

I study these problems in safety-critical domains, including robotic control in MuJoCo simulation environments and healthcare applications such as personalized diabetes management using physiological simulators.