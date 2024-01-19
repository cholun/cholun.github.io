---
layout: page
title: archive
permalink: /archive/
---
<div class="archive-page">

    <table>
    {% for post in site.posts %}
        <tr>
            <td>{{ post.date | date: '%F' }}</td>
            <td><a href="{{ post.url }}">{{ post.title }}</a></td>  
        </tr>  
    {% endfor %}
    </table>

</div>
