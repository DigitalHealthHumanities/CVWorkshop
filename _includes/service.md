<h2 id="publications" style="margin: 2px 0px -15px;">Service</h2>

<div class="publications">
<ol class="bibliography">

{% for link in site.data.service.main %}
{% if link.type contains "education" %}

<li>
<div class="pub-row">
  <div class="col-sm-9" style="position: relative;padding-right: 15px;padding-left: 20px;">
      <div class="title">{{ link.title }}</div>
      <div class="author">{{ link.institution }} | {{ link.department }} | {{ link.years }}</div>
      <div class="periodical">{{ link.year }}
      </div>
  </div>
</div>
</li>
{% endif %}
{% endfor %}
</ol>
</div>