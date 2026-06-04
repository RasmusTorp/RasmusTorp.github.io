---
layout: page
permalink: /research/
title: research
description: My research focuses on adversarial machine learning, AI security and privacy, and the broader societal implications of modern AI systems.
nav: true
nav_order: 1
---

I use adversarial methods to study how machine learning systems interact with the people, data, and incentives that shape them. My work spans training data privacy, data attribution and compensation, model ownership, and the robustness of foundation models.

## Published

<div class="publications">

{% bibliography --query @*[status!=preprint] %}

</div>

## In Preparation

<div class="publications">

{% bibliography --query @*[status=preprint] %}

</div>
