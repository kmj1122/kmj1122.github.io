---
layout: page
permalink: /cv/
title: CV
nav: true
nav_order: 3
description: Curriculum vitae.
---

{% assign cv_href = '/assets/pdf/cv.pdf' | bust_file_cache %}
<div style="margin-bottom: 1rem;">
  <a class="btn btn-primary" href="{{ cv_href }}" target="_blank" rel="noopener">Download CV (PDF)</a>
</div>

<embed src="{{ cv_href }}" type="application/pdf" width="100%" height="1100px" style="border: none;">
