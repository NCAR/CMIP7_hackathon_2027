---
layout: default
title: Code of Conduct
permalink: /code-of-conduct/
# Set to true (or delete this line) once the text is final, and restore the nav link in _layouts/default.html.
published: false
---
<div class="section"><div class="wrap prose" markdown="1">

# Code of Conduct

*TBD: Replace this with your organization's code of conduct, or link to it.*

We are committed to providing a welcoming, inclusive, and harassment-free experience for everyone,
regardless of background, identity, career stage, or experience level.

**Expected behavior:** be respectful and considerate, collaborate openly, and give credit to others' work.

**Unacceptable behavior:** harassment, intimidation, discriminatory language or imagery, and
disruption of the event.

**Reporting:** If you experience or witness unacceptable behavior, contact the organizers:
{% for c in site.data.contacts %}[{{ c.name }}](mailto:{{ c.email }}){% unless forloop.last %} or {% endunless %}{% endfor %}. All reports will be handled confidentially.

</div></div>
