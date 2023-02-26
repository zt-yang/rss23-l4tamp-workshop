---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

permalink: /
title: Home
layout: all
---

This workshop will investigate the role of learning within Task and Motion Planning (TAMP). TAMP has shown remarkable capabilities in scaling to long action sequences, many objects and a variety of tasks. However, TAMP often relies on simplified models, assumes perfect world knowledge, and requires long computation time, which limits the real world applicability. To address these limitations, there has been significant recent interest in integrating learning methods into TAMP [
<span class="secret"><a href="https://proceedings.mlr.press/v164/ortiz-haro22a.html" target="_blank">1</a></span><span class="reveal">Ortiz-Haro, J., Ha, J. S., Driess, D., & Toussaint, M. Structured deep generative models for sampling on constraint manifolds in sequential manipulation. CoRL 2022.</span>,
<span class="secret"><a href="https://arxiv.org/abs/2210.12250" target="_blank">2</a></span><span class="reveal">Agia, C., Migimatsu, T., Wu, J. & Bohg, J. TAPS: Task-Agnostic Policy Sequencing. arXiv 2022.</span>,
<span class="secret"><a href="https://arxiv.org/abs/2210.12631" target="_blank">3</a></span><span class="reveal">Cheng, S. & Xu, D. Guided skill learning and abstraction for long-horizon manipulation. CoRL Workshop on Learning, Perception, and Abstraction for Long-Horizon Planning 2022.</span>,
<span class="secret"><a href="https://arxiv.org/abs/2103.00589" target="_blank">4</a></span><span class="reveal">Silver, T., Chitnis, R., Tenenbaum, J., Kaelbling, L. P., & Lozano-Pérez, T. Learning symbolic operators for task and motion planning. IROS 2021.</span>,
<span class="secret"><a href="https://arxiv.org/abs/2211.01576" target="_blank">5</a></span><span class="reveal">Yang, Z., Garrett, C. & Fox, D. Sequence-based plan feasibility prediction for efficient task and motion planning. CoRL Workshop on Learning, Perception, and Abstraction for Long-Horizon Planning 2022.</span>,
]. Despite this progress, there remain many open questions that must be addressed before learning-based TAMP can be applied in real-world settings and in full generality.

This workshop is a continuation of previous, successful RSS workshops by the same organizers [
<span class="secret"><a href="https://ipvs.informatik.uni-stuttgart.de/mlr/rss2020Workshop" target="_blank">6</a></span><span class="reveal">Learning (in) Task and Motion Planning, RSS 2020 </span>,
<span class="secret"><a href="https://planandlearn.net/" target="_blank">7</a></span><span class="reveal">Integrating Planning and Learning, RSS 2021</span>
] that discussed the role of learning within TAMP. There are three factors that make this new workshop unique and necessary. (1) This workshop will take place after the recent successes of Large Language Models (LLMs) and other foundation models. There are many questions in the community about the implications for TAMP; this workshop will provide a forum to discuss these questions. (2) This workshop will feature speakers from adjacent communities, including classical AI planning (Hector Geffner) and language-based decision-making (Pratyusha Sharma). There have been many recent advances in these communities that have not yet been applied to TAMP. (3) There has been substantial progress within learning-based TAMP itself since the last workshop was held.

The goal of this workshop is to bring together a diverse set of researchers from TAMP, learning for TAMP, computer vision, classical AI planning, and NLP to discuss not only the current state of learning for TAMP, but also the broader state of learning for planning in robotics. Subtopics include: benchmarks, language, perception, skill learning, manipulation, closed-loop TAMP, and policy learning. All of these discussions will take place against the backdrop of recent progress in foundation models.


#### Discussion Topics

- *Benchmarks*: What benchmark environments will help the community better measure the progress of TAMP and integrate learning with TAMP?
- *Large Language Models for Task Planning*: LLM has shown promises in generalizable task planning. What are the potentials and challenges in integrating LLM with TAMP?
- *Perception*: Perception in TAMP and the latest developments in this area, including 3D computer vision, open-world recognition, and sensor fusion.
- *Error Recovery / Closed-Loop TAMP*: Techniques and principles that allow TAMP to be more robust and recover from errors and interventions.
- *Skill Learning / Manipulation*: Skill learning and manipulation for TAMP, including but not limited to deep reinforcement learning and imitation learning. How do we make the learned skills generalizable and composable?
- *Model Learning*: Techniques and principles for learning discrete or continuous transition models from interaction data.

#### Tentative Schedule

<table>
<thead>
  <tr>
    <th>Time (<a href="https://www.worldtimeserver.com/current_time_in_KR.aspx?city=Daegu">KST</a>, GMT+9)</th>
    <th>Event</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>09:00 am - 09:10 am</td>
    <td>Introductory Remarks</td>
  </tr>
  <tr>
    <td>09:10 am - 09:45 am</td>
    <td>Invited Speakers 1, 2, and 3</td>
  </tr>
  <tr>
    <td>09:45 am - 10:15 am</td>
    <td>Invited Speaker Panel 1</td>
  </tr>
  <tr>
    <td>10:15 am - 10:45 am</td>
    <td>Spotlight Posters 1</td>
  </tr>
  <tr>
    <td>10:45 am - 11:20 am</td>
    <td>Invited Speakers 4, 5, and 6</td>
  </tr>
  <tr>
    <td>11:20 am - 11:50 am</td>
    <td>Invited Speaker Panel 2</td>
  </tr>
  <tr>
    <td>11:50 am - 01:00 pm</td>
    <td>Lunch</td>
  </tr>
  <tr>
    <td>01:00 pm - 01:35 pm</td>
    <td>Invited Speakers 7, 8, and 9</td>
  </tr>
  <tr>
    <td>01:35 pm - 02:05 pm</td>
    <td>Invited Speaker Panel 3</td>
  </tr>
  <tr>
    <td>02:05 pm - 02:35 pm</td>
    <td>Spotlight Posters 2</td>
  </tr>
  <tr>
    <td>02:35 pm - 02:45 pm</td>
    <td>Conclusion Remarks</td>
  </tr>
  <tr>
    <td>02:45 pm - 04:45 pm</td>
    <td>Poster Session</td>
  </tr>
</tbody>
</table>
