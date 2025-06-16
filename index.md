---
title: lowkey
---


# Courses
[- Biologia i Geologia 4 (ESO)](https://github.com/lveygonz/biogeo4)

# Scripts
- Apps Script

# Liquid test
{% for goal in site.data.learning_goals %}
### {{ goal.id }}: {{ goal.goal }}
{% for crit in goal.criteria %}
- {{ crit }}
{% endfor %}
{% endfor %}
