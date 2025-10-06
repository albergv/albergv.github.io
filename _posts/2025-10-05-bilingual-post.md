---
layout: post
title: Publicación bilingüe
date:       2025-10-05
author:     "Alberto"
header-img: "img/pexels-optical-chemist.jpg"
catalog:    true
multilingual: true
tags:
    - Bilingual
---

<!-- Chinese Version -->
<div class="zh post-container">
    {% capture bilingual-post_zh %}{% include example/bilingual-post-zh.md %}{% endcapture %}
    {{ bilingual-post_zh | markdownify }}
</div>

<!-- English Version -->
<div class="en post-container">
    {% capture bilingual-post_en %}{% include example/bilingual-post-en.md %}{% endcapture %}
    {{ bilingual-post_en | markdownify }}
</div>


