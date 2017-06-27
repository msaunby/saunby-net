---
layout: page
title: Museum of ideas
permalink: /museum/
---
## Some of my ideas (mostly half baked)

From time to time I'll have an idea.  Often just a thought or two about something I'd like to make.
Here are a few of the more interesting ones along with pictures, notes, wishlists and the rest.
Feel free to browse and maybe have a go at taking them further, borrowing elements, or simply sending me a message saying "that will never fly".

 <ul class="post-list">
    {% for post in site.museum %}
      <li>
        <!--
        <span class="post-meta">{{ post.date | date: "%b %-d, %Y" }}</span>
        -->
        <h2>
          <a class="post-link" href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
        </h2>
         <img width="320px" src="{{ post.image }}">
      </li>
    {% endfor %}
  </ul>
