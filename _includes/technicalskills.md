| Skill | Level |
| ---- | ---- |
{% assign skills = site.data.skills.technical | sort: "level" -%}
{% for skill in skills -%}
| {{skill.title}} | {{skill.level}} |
{% endfor %}