---
title: Research Timeline  (csv)
---

<section id="timeline">
  <h1>Research Timeline Summary</h1>
<ul class="timeline_ul">
{% for Rstats in site.data.ResearchStatsFbs %}
  <li  class="timeline_card">
    
    <div class="timeline_head online">
      <div class="date_online" > {{ Rstats.Date }} </div>
      {{ Rstats.Title }}
    </div>
    <div class="timeline_body">
            <h2>{{ Rstats.Title}}</h2>
             {{ Rstats.Description }}
    </div>
    </a>
  </li>
{% endfor %}
</ul>
</section>
