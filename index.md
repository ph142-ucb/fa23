---
layout: home
title: Home
nav_order: 0
description: >-
    UC Berkeley's PH 142: Introduction to Probability and Statistics in Biology and Public Health
---

# Introduction to Probability and Statistics in Biology and Public Health
{: .mb-2 }
PH 142, Fall 2023
{: .mb-0 .fs-6 .text-grey-dk-000 }

{% assign instructors = site.staffers | where: 'role', 'Instructor' %}
<div class="role">
  {% for staffer in instructors %}
  {{ staffer }}
  {% endfor %}
</div>

{% if site.announcements %}
We will not be updating this page with announcements. For the latest announcements, make sure to check our [Ed](https://edstem.org/us/courses/44261).
{% endif %}

## Important Information

- **Lectures**: Monday, Wednesday, & Friday, 8:00 to 9:00 AM PST
- **Location**: [Internet/Online](https://berkeley.zoom.us/j/94810858973) 
- **Content**: Please refer to the [course schedule]({{ site.baseurl }}/course-schedule)
- **Course number**: 30033
- **Email for non-content inquiries**: [ph142fall2023@berkeley.edu](mailto:ph142fall2023@berkeley.edu)

## Goals

- Build strong foundations in statistics and introduce students to programming to prepare students for more advanced courses involving data analysis.
- Foster a mindset of statistical thinking to give students the tools to understand experiments and research studies and evaluate their validity.
- Empower students to address real-world problems with technical prowess.
- Develop the skills to assess statistical information in scientific and lay publications, and to communicate statistical information to various audiences.

## Course Description

This course is an introduction to statistics and data science, primarily for MPH and undergraduate public health majors, and others interested in public health topics. The course can be divided into three parts: 

- **Part I:** We will be focusing on learning to explore and summarize univariate and bivariate distributions. We will be using the R statistical software to do this, specifically, we will use the dplyr and ggplot2 packages. 
- **Part II:** We will be learning about classical problems in probability and the some commonly used probability distributions: the Normal, Binomial, and Poisson distributions. In Part II we will also make the link between theoretical distributions and sampled distributions and cover a key concept called the Central Limit Theorem. 
- **Part III:** We introduce statistical inference, the process of estimating statistics from samples to make inference about populations. 

Throughout the course, we will follow the **PPDAC model**, which stands for “Problem, Plan, Data, Analysis, and Conclusion”. 
