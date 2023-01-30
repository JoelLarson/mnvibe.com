---
layout: default
title: Home
---
# mnvibe

## Posts
{% for post in site.posts %}
* [{{ post.title }}]({{ post.url }})
{% endfor %}

## Artists
{% for artist in site.artists %}
* [{{ artist.title }}]({{ artist.url }})
{% endfor %}

## Shows
{% for show in site.shows %}
* [{{ show.title }}]({{ show.url }})
{% endfor %}

## Venues
{% for venue in site.venues %}
* [{{ venue.title }}]({{ venue.url }})
{% endfor %}