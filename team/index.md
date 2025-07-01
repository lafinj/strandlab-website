---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %} Current Members

The Strand Lab is made up of a diverse team of trainees, technicians, and scientists working together to advance our understanding of the lower urinary tract.
{% include section.html %}

{% include list.html data="members" component="portrait" filter="role == 'principal-investigator'" %}
{% include list.html data="members" component="portrait" filter="role != 'principal-investigator' and role != 'alumni'" %}

{% include section.html %}

# Former members

{% include list.html data="members" component="portrait" filter="role =~ /alumni/" %}
