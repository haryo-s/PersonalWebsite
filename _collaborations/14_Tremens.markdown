---
layout: collaborations
title: Tremens
year: 2024-2026
partner: CREW
partner_url: https://crew.brussels/en/productions/tremens
description: VR, Theatre, Unreal Engine, LBE
img: /img/collaborations/tremens/tremens1.jpg
offsetx: -75%
offsety: -30%
---

_Tremens is an immersive experience at the intersection of theater and embodied virtual reality. Inspired by Shakespeare’s misanthrope Timon of Athens, the work explores the tension between human connection and withdrawal in a world where people risk being reduced to data points._

Tremens is a hybrid theatre piece developed in co-creation by [CREW](https://crew.brussels/en) and the [Residenztheater](https://www.residenztheater.de/) in Munich, Germany. This feature explores the themes of social media and data as a commodity. It incorporates stage acting and immersive VR experiences, performed in the foyer of the Residenztheater in Munich. 

The creation of this piece lasted several years, with three on-location residencies at the Residenztheater with the final residency culminating in the piece's premiere shows. During the first two residencies I was lead on-site technician and developer. Following the second residency I became the lead developer where I co-ordinated a small team of developers while communicating with the artistic team to determine which technical approaches and what features were needed to achieve the artistic vision.

Tremens is constructed of two distinct components, the first being a live drama piece performed by a stage actor and the second piece being two large scale free-roaming VR experiences, the latter of which I led its development. These VR experiences encompassed the whole foyer of the Residenztheater. In one experience, visitors freely walked a space of 260m<sup>2</sup> in VR while an actor in a motion capture suit performed live. In the other experience, visitors were personally guided for a physical walk of 225 metres in VR through the corridors and the atrium of the Residenztheater's foyer.

Tremens was developed with support from EMIL, MAX-R, the Flemish Community and the Fédération Wallonie-Bruxelles

#### Press

- ZDFheute. (2026, February 26). _[Virtuelles Theater: Schauspiel neu gedacht](https://www.zdfheute.de/video/heute-journal/lange-virtuelles-theater-100.html)_
- Süddeutsche Zeitung. (2026, February 22). _[Das Drama mit der virtuellen Welt](https://www.sueddeutsche.de/muenchen/muenchen-residenztheater-immersive-performance-virtuelle-realitaet-tremens-li.3385801)_

<hr>

<div>
{% for image in site.static_files %}
    {% if image.path contains '/img/collaborations/tremens' %}
        <img class="projectimage" src="{{ site.baseurl }}{{ image.path }}"/>
    {% endif %}
{% endfor %}
</div>
