---
layout: default
title: Blog
---
<h1>{{page.title}}</h1>
<p>Cikkek az üzeneted közvetítéséről...</p>

<div class="container">
    {% for post in site.posts %}
        <div class="post">
            <h2><a href="{{post.url}}">{{post.title}}</h2>
            <p>{{post.excrept}}</p>
        </div>
    {% endfor %}
</div>