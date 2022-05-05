---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# <i class="fas fa-users"></i>Current Members

{% include list.html data="members" component="portrait" filters="role: pi, group: current" %}
{% include list.html data="members" component="portrait" filters="role: postdoc, group: current" %}
{% include list.html data="members" component="portrait" filters="role: technician, group: current" %}

{% include section.html dark=true %}

{% include section.html background="images/banner.jpg" dark=true%}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

{% include section.html %}

# Former Members

{% include list.html data="members" component="portrait" filters="role: postdoc, group: former" %}
{% include list.html data="members" component="portrait" filters="role: technician, group: former" %}
