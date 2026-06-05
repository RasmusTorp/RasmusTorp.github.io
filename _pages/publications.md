---
layout: page
permalink: /research/
title: research
description: 
nav: true
nav_order: 1
---

My research focuses on developing algorithms that _protect humans from AI misuse and failure_. Using techniques from **adversarial AI**, I study the robustness, privacy, and transferability of learned representations in machine learning systems. In particular, I investigate how non-robust features relate to training data privacy, and how manipulating representations through **data poisoning** can influence the downstream behavior of large models.

## Published

<div class="publications">

{% bibliography --query @*[status!=preprint] %}

</div>

## In Preparation

<div class="publications">

{% bibliography --query @*[status=preprint] %}

</div>
