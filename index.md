---
layout: default
---

## Writing

<ul>
    {% for post in site.posts %}
    <li>
        <a href="{{ post.url }}" title="Permanent link to: '{{ post.title }}'">{{ post.title }}</a>
        &mdash;
        <time class="post__date" datetime="{{ post.date | date: "%Y-%m-%d" }}" pubdate="">{{ post.date | date: "%B %d, %Y"  }}</time>
    </li>
    {% endfor %}
</ul>

## Communication Projects

 - [Storify - #SouthAsianAnd Identity Campaign](https://storify.com/SouthAsianAnd/southasianand-identity-campaign) &mdash; August 3, 2015

## About Me

[Learn more about my experiences here.](/resume.pdf)

I am an Urban Fellow interested in international relations, development, local government, economics, South Asian political engagement, and exploring how to promote equity and access in NYC. I currently work in Operations at the NYC Department of Education and am slowly trying to wrap my head around everything that is involed in the world of education policy. I graduated from Columbia University in 2015, studying chemical engineering and political science.

I like writing about past field projects and the things I'm experieincing at Ed -- but am also interested in conversations surrounding development, social change, and specific policies/challenges affecting communities in NYC.



