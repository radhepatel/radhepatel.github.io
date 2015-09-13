---
layout: default
title: Writing
---

<ul>
    {% for post in site.posts %}
    <li>
        <a href="{{ post.url }}" title="Permanent link to: '{{ post.title }}'">{{ post.title }}</a>
        &mdash;
        <time class="post__date" datetime="{{ post.date | date: "%Y-%m-%d" }}" pubdate="">{{ post.date | date: "%B %d, %Y"  }}</time>
    </li>
    {% endfor %}
</ul>

## About Me

I am a senior at Columbia University studying chemical engineering and political science. I'm interested in intersections between science, technology and communications. I want to enter the media field and contribute to programming on these topics. I'm an active member of the CU Engineers Without Borders (EWB) team, and also serve the EWB national office as the New York state representative. I'm always looking for grassroots organizations in need of our teams for water, sanitation, or civil structure-based projects.

I like writing about past field projects, but am also interested in efforts here on campus and the conversations surrounding development, social change, or specific issues affecting the NYC community.

To inquire about Engineers Without Borders projects, donations, or community partnerships, email me at new.york.city.rep@ewb-northeast.org
For anything else: rpp2122@columbia.edu

Find me:

   - [linkedin.com/pub/radhe-patel/80/b08/b97/](http://linkedin.com/pub/radhe-patel/80/b08/b97/)
   - [twitter.com/radhe_16](http://twitter.com/radhe_16/)
