--- 
layout: page 
title: Crew 
permalink: /crew/ 
--- 
- Nate
- Elaina
- Eric
- Brian
- Arun
- Suganya
- Ashwin
- Cliff
- Stacey
- Katie
- Ana
- Dean
- Zara
- Ally
- Julien
- Sergio
- Akshob

{% if site.crew_members.size > 0 %}
{% for crew_member in site.crew_members %}
<h2>
    <a href="{{ crew_member.url }}">
      {{ crew_member.name }} - {{ crew_member.position }}
    </a>
</h2>
<p>{{ crew_member.content }}</p>
{% endfor %}
{% endif %}