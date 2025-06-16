---
title: lowkey
---


# Courses
[- Biologia i Geologia 4 (ESO)](https://github.com/lveygonz/biogeo4)

# Scripts
- Apps Script

# Liquid test
{% for lg in site.data.earning_goals.earning_goals %}
## {{ lg.goal }} ({{ lg.id }})
**Criteria:**
<ul>
{% for c in lg.criteria %}
  <li>{{ c }}</li>
{% endfor %}
</ul>
{% endfor %}
