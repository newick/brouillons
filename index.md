# Trucs

{% for page in site.html_pages %}
  {% if page.url != '/' %}
  - {% if page.dir !='/' %}{{ page.dir }}{% endif %} [{{page.title }}]({{ page.url | relative_url }})
  {% endif %}
{% endfor %}

