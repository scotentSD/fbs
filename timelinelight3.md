---
title: Research Timeline  (v2)
---


<section id="timeline">
  <h1>Research Timeline Summary</h1>
  <ul class="timeline_ul">
    {% for post in site.posts %}
        <li class="timeline_card">
          <div>
            <a href="{{site.url}}/{{site.github.repository_name}}{{post.url}}">
              {{ post.display_date }} :: {{ post.title}}
            </a>
          </div>
       </li>
    {% endfor %}
  </ul>
</section>

