---
layout: default
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

## Communication Projects

 - [Storify - #SouthAsianAnd Identity Campaign](https://storify.com/SouthAsianAnd/southasianand-identity-campaign) &mdash; August 3, 2015

## About Me

[Learn more about my experiences here.](/resume.pdf)

I am a health policy staffer and former Urban Fellow interested in urban planning,  development, local government, South Asian political engagement, and exploring how to promote equity and access in NYC. I graduated from Columbia University studying chemical engineering and political science. To me, the intersection of these fields is international development and public health, which is why I spent time in Costa Rica and Ghana during my studies on building development projects. 

I like writing about past field projects and the things I'm experieincing at City Hall -- but am also interested in conversations surrounding development, social change, and specific policies/challenges affecting communities in NYC. 

Check out my work with Rikers here: http://rikersdebateproject.org/







