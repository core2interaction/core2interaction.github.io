---
# layout: students
icon: fas fa-tag
order: 3
---

<h2>
{% for student in site.data.students %}

    <a href="https://github.com/{{ student.github }}">
      {{ student.name }}
    </a>

{% endfor %}
</h2>