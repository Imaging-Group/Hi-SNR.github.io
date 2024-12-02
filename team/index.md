---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

At HI-SNR Lab, we believe that a joyful and inclusive environment drives innovation. Our team is dedicated to collaboration and creativity, celebrating our differences, and supporting one another. Join us on our journey to bring new imaging systems and methods to our communities!

{% include section.html %}

{% include list.html data="members" component="portrait" filters="role: pi" %}
{% include list.html data="members" component="portrait" filters="role: ^(?!pi$)" %}
