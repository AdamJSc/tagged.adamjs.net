---
permalink: /top-10-influential-albums
layout: post
title:  Top 10 Influential Albums
date:   2020-05-19 13:12:00 +0100
tagged_by: Mark N
brief: |
    You've seen this one doing the FB rounds. You know the drill...

    10 albums that greatly influenced my taste in music. One album per day for ten consecutive days.
    Or all at once, because this is a GITHUB/NETLIFY HOSTING COMBO (you don't own us Zuckerberg).

    !! **NO** explanations !! **NO** reviews !!

    JUST. Straight. Up. **Album Covers**...

    (I can do that, right?)
    
    Oh... By the way...
    
    Definitely don't click on the Spotify icon beneath each image, because
    that launches an embedded playlist for each one and them's against the rules...
    :blush:
---
{% assign items = site.data["2020-05-19-top-10-influential-albums"] %}
{% include carousel.html id="albums-carousel" items=items carouselInner="image_with_spotify" %}
