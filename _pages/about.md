---
permalink: /
title: "About"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a Senior Lecturer in the School of Criminology and Criminal Justice at Griffith University and a registered clinical psychologist. I am also Director of the Social Analytics Lab at the Griffith Criminology Institute.

My research sits at the intersection of mental health, neurodevelopment, and offending across the life course. I draw on large-scale linked administrative data to examine trajectories of mental illness, justice system contact, and victimisation, with a particular focus on youth justice, sexual offending, and neurodevelopmental disorders. This work is informed by clinical and forensic practice, including my time as a Senior Clinician with the Griffith Youth Forensic Service and as a consultant psychologist in private practice.

Research interests
======
* Mental health and criminal justice system involvement
* Developmental and neurocriminology
* Youth offending, sexual offending, and intervention
* Neurodevelopmental disorders in justice populations
* Advanced longitudinal and administrative data methods

Recent publications
======
{% assign shown = 0 %}
<ul>
{% for post in site.publications reversed %}{% if post.category == 'manuscripts' and shown < 5 %}{% assign shown = shown | plus: 1 %}
  <li>{{ post.citation }}{% if post.paperurl %} <a href="{{ post.paperurl }}">Link</a>{% endif %}</li>
{% endif %}{% endfor %}
</ul>

A full list is on the [publications](/publications/) page, and my [CV](/cv/) has details of funding, teaching, and service.

Contact
======
School of Criminology and Criminal Justice, Griffith University, Brisbane, Australia  
Email: [j.ogilvie@griffith.edu.au](mailto:j.ogilvie@griffith.edu.au)  
[Griffith Experts profile](https://experts.griffith.edu.au/8499-james-ogilvie) · [Google Scholar](https://scholar.google.com/citations?user=lHqkqQ4AAAAJ&hl=en) · [ORCID](https://orcid.org/0000-0003-2294-5665)
