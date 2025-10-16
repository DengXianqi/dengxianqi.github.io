---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---
<!-- Optional: inline embed (works on Pages; falls back to link) 
<object data="{{ 'https://dengxianqi.github.io/files/Resume-V3.pdf' | relative_url }}" type="application/pdf" width="100%" height="900">
  <p>Your browser can’t display PDFs here.
  <a href="{{ 'https://dengxianqi.github.io/files/Resume-V3.pdf' | relative_url }}">Download the CV</a>.</p>
</object> -->

<div class="pdf-wrap">
  <!-- 关键：用视窗高度而不是固定像素；加 #view=FitH 提示按页宽适配 -->
  <object
    class="pdf-frame"
    data="{{ 'https://dengxianqi.github.io/files/Resume-V3.pdf#view=FitH' | relative_url }}"
    type="application/pdf">
    <p>您的浏览器不支持内嵌 PDF。请<a href="{{ 'https://dengxianqi.github.io/files/Resume-V3.pdf' | relative_url }}">下载查看</a>。</p>
  </object>
</div>

<style>
/* 可放这里，或放到你的全局样式里 */
.pdf-wrap { margin: 1rem 0; }
.pdf-frame {
  width: 100%;
  /* 关键：用视窗高度，避免尾部出现一大片黑色空白 */
  height: calc(100vh - 140px); /* 140px 约等于站点头部+页眉的高度，可按你主题微调 */
  max-height: 95vh;            /* 双保险：别超过视窗 */
  border: 1px solid #e5e7eb;
  border-radius: 8px;
}
</style>

- **Download:** [CV (PDF)]({{ 'https://dengxianqi.github.io/files/Resume-V3.pdf' | relative_url }})
- **Open in new tab:** <a href="{{ 'https://dengxianqi.github.io/files/Resume-V3.pdf' | relative_url }}" target="_blank" rel="noopener">View PDF</a>

<!--
{% include base_path %}

Education
======
* Ph.D in Version Control Theory, GitHub University, 2018 (expected)
* M.S. in Jekyll, GitHub University, 2014
* B.S. in GitHub, GitHub University, 2012

Work experience
======
* Spring 2024: Academic Pages Collaborator
  * GitHub University
  * Duties includes: Updates and improvements to template
  * Supervisor: The Users

* Fall 2015: Research Assistant
  * GitHub University
  * Duties included: Merging pull requests
  * Supervisor: Professor Hub

* Summer 2015: Research Assistant
  * GitHub University
  * Duties included: Tagging issues
  * Supervisor: Professor Git
  
Skills
======
* Skill 1
* Skill 2
  * Sub-skill 2.1
  * Sub-skill 2.2
  * Sub-skill 2.3
* Skill 3

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Currently signed in to 43 different slack teams -->
