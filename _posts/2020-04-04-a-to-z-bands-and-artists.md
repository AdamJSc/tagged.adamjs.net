---
permalink: /a-to-z-bands-and-artists
layout: post
title:  A-Z Bands and Artists
date:   2020-04-04 20:14:00 +0100
tagged_by: J Crookie
brief: |
    Can you name a band/collective (not solo artist) you've seen live for every letter of the alphabet?
    
    Forgive the poetic licence for "X" (he's still technically not a solo artist...)
    
    Otherwise here's a complete set 🙌
    
    Have a listen on <a href="#" onclick="modal('spotify', 'A to Z I\'ve Seen Live', {spotifyID: 'playlist/5G0BVIPOOYOwRuIrGyiuPa'});">Spotify</a> too!
---
{% assign items = site.data["2020-04-04-a-to-z-bands-and-artists"] %}
{% include carousel.html id="bands-carousel" items=items carouselInner="image_with_title_and_caption" %}
