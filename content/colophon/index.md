---
title: Colophon
layout: layouts/post.njk
date: 2023-09-19
backgroundLight: '0, 0%, 95%'
textLight: '0, 0%, 10%'
linkLight: '350, 50%, 35%'
activeLinkLight: '350, 90%, 60%'
backgroundDark: '210, 15%, 10%'
textDark: '0, 0%, 85%'
linkDark: '210, 100%, 85%'
activeLinkDark: '210, 75%, 50%'
---

{% css %}{% include "public/css/pantone-chip.css" %}{% endcss %}

This site is built using [Eleventy](https://11ty.dev). I used the [Eleventy Base Blog v8](https://eleventy-base-blog.netlify.app) as a starting point, but my hope is that it diverges enough to be considered my own.

My design sensibility is somewhere between brutalism and minimalism—I’ve decided the closest descriptor is probably “essentialism.” I touch just enough to hint at an identity, but generally, my designs look like they belong to the client, not to me. (Except this site, where I am both client and designer... and like most designers know, that gets complicated quickly!)

This site implements [Modern Font Stacks](https://modernfontstacks.com/) for the site for speed and accessibility. 
* the Humanist stack for headings
* the Transitional stack for paragraphs
* the Geometric Humanist stack for buttons and labels
* the Monospace stack for metadata and code

### Colors

#### Default Display

<div class="chip-container">

  {% set colorCode = backgroundLight %}
  <div class="chip">
    <div class="chip-color backgroundLight">
    </div>
    <div class="chip-label-box">
      <div class="chip-label">
        <h3>HSL</h3>
        <p>{{ colorCode }}</p>
      </div>
    </div>
  </div>

  {% set colorCode = textLight %}
  <div class="chip">
    <div class="chip-color textLight">
    </div>
    <div class="chip-label-box">
      <div class="chip-label">
        <h3>HSL</h3>
        <p>{{ colorCode }}</p>
      </div>
    </div>
  </div>

  {% set colorCode = linkLight %}
  <div class="chip">
    <div class="chip-color linkLight">
    </div>
    <div class="chip-label-box">
      <div class="chip-label">
        <h3>HSL</h3>
        <p>{{ colorCode }}</p>
      </div>
    </div>
  </div>

  {% set colorCode = activeLinkLight %}
  <div class="chip">
    <div class="chip-color activeLinkLight">
    </div>
    <div class="chip-label-box">
      <div class="chip-label">
        <h3>HSL</h3>
        <p>{{ colorCode }}</p>
      </div>
    </div>
  </div>

</div>

#### Dark Mode
<div class="chip-container">

  {% set colorCode = backgroundDark %}
  <div class="chip">
    <div class="chip-color backgroundDark">
    </div>
    <div class="chip-label-box">
      <div class="chip-label">
        <h3>HSL</h3>
        <p>{{ colorCode }}</p>
      </div>
    </div>
  </div>

  {% set colorCode = textDark %}
  <div class="chip">
    <div class="chip-color textDark">
    </div>
    <div class="chip-label-box">
      <div class="chip-label">
        <h3>HSL</h3>
        <p>{{ colorCode }}</p>
      </div>
    </div>
  </div>

  {% set colorCode = linkDark %}
  <div class="chip">
    <div class="chip-color linkDark">
    </div>
    <div class="chip-label-box">
      <div class="chip-label">
        <h3>HSL</h3>
        <p>{{ colorCode }}</p>
      </div>
    </div>
  </div>

  {% set colorCode = activeLinkDark %}
  <div class="chip">
    <div class="chip-color activeLinkDark">
    </div>
    <div class="chip-label-box">
      <div class="chip-label">
        <h3>HSL</h3>
        <p>{{ colorCode }}</p>
      </div>
    </div>
  </div>

</div>

### Website Changelog

* **2023-09-19**: Launched the “good enough” version, i.e. the first draft.