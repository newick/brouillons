# Trucs

{% for page in site.html_pages %}
  {% if page.url != '/' %}
  - [{{ page.title }}]({{ page.url | relative_url }}) {{page.dir}}
  {% endif %}
{% endfor %}

