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
      path="assets/img/members/PI_Kanghyun.png"
      class="img-fluid rounded"
      alt="Kang-Hyun Lee"
      cache_bust=true
    %}
  </div>
  <div class="col-sm-9">
    <h3 style="margin-top: 0;">Kang-Hyun Lee, Ph.D.</h3>
    <p>Assistant Professor, School of Mechanical Engineering, Soongsil University</p>
    <p>
      📧 <a href="mailto:kanghyun.lee@ssu.ac.kr">kanghyun.lee@ssu.ac.kr</a>
      &nbsp;·&nbsp;
      <a href="https://www.linkedin.com/in/kang-hyun-lee-125b17206/" target="_blank" rel="noopener" title="LinkedIn"><i class="fa-brands fa-linkedin"></i> LinkedIn</a>
    </p>
    <p>
      Kang-Hyun Lee is an Assistant Professor in the School of Mechanical
      Engineering at Soongsil University. Prior to joining Soongsil University,
      he worked as a Postdoctoral Associate in the Department of Mechanical
      Engineering at the Massachusetts Institute of Technology, where he
      contributed to a DARPA-funded research project on developing generative
      artificial intelligence for the design and manufacturing of reusable
      rocket components. He received his Ph.D. and M.S. from the Department of
      Aerospace Engineering at Seoul National University, with a research focus
      on multiphysics and multiscale simulation of additive manufacturing
      processes. His current research lies at the intersection of generative
      design and advanced manufacturing, aiming to unlock the full potential of
      manufacturing processes and expand the design space for next-generation
      engineered systems.
    </p>
  </div>
</div>

#### Invited Talks

1. **Invited Presentation**, Materials Research Society (MRS) Fall Meeting, 2025.
   *Multiobjective Inverse Design of Compositionally Graded Blisks for Reusable Turbomachinery Using Physics-Guided Diffusion Models.*
2. **Invited Seminar**, Air Force Research Laboratory (AFRL), Materials and Manufacturing Directorate (RX Division), 2025.
   *Exploring Microstructure Design Spaces with Denoising Diffusion Models.*
3. **Invited Talk** (Early Career Researcher), Korean Society for Aeronautical and Space Sciences (KSAS) Workshop, 2025.
   *Multiphysics Modeling for PSP Linkages in Metal Additive Manufacturing.*
4. **Invited Talk**, Korea Institute of Machinery and Materials (KIMM), Department of 3D Printing, 2024.
   *Multiscale and Multiphysics Simulation of Metal Additive Manufacturing Process.*

---

## Graduate Students

We are recruiting M.S. and Ph.D. students. See [Join Us]({{ '/join/' | relative_url }}) for what to send.

---

## Undergraduate Researchers

Open positions. Motivated undergraduates are welcome to contact Prof. Lee — see [Join Us]({{ '/join/' | relative_url }}).

---

## Alumni

This section will be updated as members graduate.
