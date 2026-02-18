VLANs

by Cyber.SoHo

This is the list of all of the Course' materials into GitHub :

<ul>
{% for file in site.static_files %}
{% comment %} Change ".html" to ".pdf" to list PDF files {% endcomment %}
{% if file.extname == ".pdf" %}
<li><a href="{{ file.path | relative_url }}">{{ file.basename }}</a></li>
{% endif %}
{% endfor %}
</ul>
