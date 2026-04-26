---
layout: page
permalink: /team/
title: Team
description: Members of the IDMM Lab.
nav: true
nav_order: 2
---

{% comment %}
Team page is intentionally written as plain Markdown for now (no Liquid loops over
_data/members.yml). When the lab grows past a couple of students, refactor the
Graduate Students / Undergraduate Researchers / Alumni sections to iterate over
site.data.members. The data file is already structured for that ({} arrays in
_data/members.yml).
{% endcomment %}

## Principal Investigator

<div class="row mt-3">
  <div class="col-sm-3">
    {%
      include figure.liquid
      loading="eager"
      path="assets/img/prof_pic.jpg"
      class="img-fluid rounded"
      alt="Kang-Hyun Lee"
      cache_bust=true
    %}
  </div>
  <div class="col-sm-9">
    <h3 style="margin-top: 0;">Kang-Hyun Lee, Ph.D.</h3>
    <p><em>Assistant Professor, School of Mechanical Engineering</em><br>
    Soongsil University</p>
    <p>📧 <a href="mailto:kanghyun.lee@ssu.ac.kr">kanghyun.lee@ssu.ac.kr</a></p>
    <p>
      Prior to joining Soongsil University, Dr. Lee was a Postdoctoral
      Associate in the Department of Mechanical Engineering at MIT, where he
      worked on a DARPA project applying generative AI to the design and
      manufacturing of reusable rocket components. He received his Ph.D. and
      M.S. in Aerospace Engineering from Seoul National University, with a
      dissertation on multiphysics and multiscale simulation of metal additive
      manufacturing. His current research interests are generative design,
      multiphysics simulation, and digital engineering for advanced
      manufacturing.
    </p>
  </div>
</div>

---

## Graduate Students

We are recruiting M.S. and Ph.D. students. See [Join Us]({{ '/join/' | relative_url }}) for what to send.

---

## Undergraduate Researchers

Open positions. Motivated undergraduates are welcome to contact Prof. Lee — see [Join Us]({{ '/join/' | relative_url }}).

---

## Alumni

This section will be updated as members graduate.
