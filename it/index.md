---
layout: default
title: Homepage di esempio
description: Questo è un esempio di homepage con utilizzo del componente "hero"
lang: it
ref: homepage
permalink: /
order: 1
---

{% include hero.html %}

<main class="container my-4" markdown="1">
<div class="container">
  <div class="row">
    <div class="col-sm"> 
      <img src="https://www.gravatar.com/avatar/8cfc128d9a57425c7439f3e5ac981f74?s=1000" style="width: 70vw; height: 70vw; max-width: 70%; max-height: 70%; border-radius: 50%; object-fit: cover; @media (max-width: 1024px) { width: 90vw !important; height: 90vw !important; max-width: 90% !important; max-height: 90% !important; }">
    </div>
    <div class="col-sm"> Una di tre colonne </div>
  </div>
</div>
</main>

