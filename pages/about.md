---
layout: page
title: About
permalink: /about/
weight: 3
---

# **About Me**

I am Tianci (Dylan) Zheng, a data analyst focused on healthcare reimbursement, financial reporting, and decision support.

- Senior Data Analyst at M.S. Hall and Associates (Remote)
- M.S. in Information Management, University of Illinois Urbana-Champaign
- B.S. in Business, University of Minnesota Twin Cities

I work across Python, SQL, Tableau, and Excel to automate reporting workflows, improve audit readiness, and deliver reliable insights from complex multi-source datasets.

## Skills

<div class="row">
  {% include about/skills.html title="Programming Skills" source=site.data.programming-skills %}
  {% include about/skills.html title="Tools and Platforms" source=site.data.other-skills %}
</div>

## Timeline

<div class="timeline-body bg-themed mt-4">
  {% for item in site.data.timeline %}
    <div class="timeline-item">
      <div class="content">
        <h2>{{ item.title }}</h2>
        <h6 class="date">{{ item.from }} - {{ item.to }}</h6>
        <p>{{ item.description }}</p>
      </div>
    </div>
  {% endfor %}
</div>

