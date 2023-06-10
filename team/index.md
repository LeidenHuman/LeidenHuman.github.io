---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

Our group is comprised of researchers and students coming from a very diverse background, including computational linguistics, Korean studies, computer science and more.

{% include section.html %}

## Staff
{% include list.html data="members" component="portrait" filters="name: Jelena Prokic" %}
{% include list.html data="members" component="portrait" filters="priority: staff, role: phd" %}
{% include list.html data="members" component="portrait" filters="priority: other_staff" %}

{% include list.html data="members" component="portrait" filters="priority: affiliate" %}
## Visiting researchers
{% include list.html data="members" component="portrait" filters="priority: guest" %}

## {% include icon.html icon="fa-regular fa-envelope" %}Contact

Questions about our research🔬, looking for a collaboration opportunities💡or simply want to grab a coffee☕? Please feel free contact us!

{%
  include button.html
  type="email"
  text="Email"
  link="j.prokic@hum.leidenuniv.nl"
%}