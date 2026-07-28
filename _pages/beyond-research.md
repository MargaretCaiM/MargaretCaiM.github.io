---
layout: archive
title: "Beyond Research"
permalink: /beyond-research/
author_profile: true
---

Music
======
I play the piano (Grade 6, Central Conservatory of Music) and enjoy singing.

Badminton
======

Photography
======

<div class="photo-grid">
{% for file in site.static_files %}{% if file.path contains '/images/photography/' %}<img src="{{ file.path | relative_url }}" alt="Photography by Margaret Cai" loading="lazy">{% endif %}{% endfor %}
</div>

<style>
.photo-grid { display: grid; grid-template-columns: repeat(auto-fill, minmax(220px, 1fr)); gap: 10px; margin-top: 0.5em; }
.photo-grid img { width: 100%; height: 220px; object-fit: cover; border-radius: 4px; }
</style>
