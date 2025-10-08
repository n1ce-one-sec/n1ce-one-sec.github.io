# n1ce-one-sec.github.io
N1ce-One writeups

{% for page in site.pages %}
    {% if page.include_on_home %}
        ### {{ page.title }} - {{ page.link | relative_url }} </h2>
    {% endif %}
{% endfor %}