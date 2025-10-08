# n1ce-one-sec.github.io
N1ce-One writeups

{% for page in site.pages %}
    {% if page.include_on_home %}
        <section>
            <h2> {{page.title}} </h2>
        </section>
    {% endif %}
{% endfor %}