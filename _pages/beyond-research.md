---
layout: archive
title: "Beyond Research"
permalink: /beyond-research/
author_profile: true
---

When I step away from my data, you will usually find me at a piano, behind a microphone, on a badminton court, or behind a camera.

Music
======
I have played the piano since childhood (Grade 6, Central Conservatory of Music), and I sing whenever anyone lets me. I once made it through the auditions for *The Voice of China* — which I still count as one of my braver life choices.

Badminton
======
Always up for a game. Consider this an open invitation.

Photography
======
I like catching the moments that would otherwise slip by — campuses, cities, and the occasional very photogenic cup of coffee. A few recent favorites:

<div class="photo-grid">
{% for file in site.static_files %}{% if file.path contains '/images/photography/' %}<img src="{{ file.path | relative_url }}" alt="Photography by Margaret Cai" loading="lazy">{% endif %}{% endfor %}
</div>

<style>
.photo-grid { display: grid; grid-template-columns: repeat(auto-fill, minmax(220px, 1fr)); gap: 10px; margin-top: 0.5em; }
.photo-grid img { width: 100%; height: 220px; object-fit: cover; border-radius: 4px; }
</style>
