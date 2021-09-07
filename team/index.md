---
title: Participants
nav:
  order: 3
  tooltip: Participants
---

# <i class="fas fa-users"></i>Participants

The project was proposed by the following Primary Investigators, but we hope to make this a resource and a collaborative project that engages the broad mycological community.

{% include section.html %}

{% include list.html data="members" component="portrait" filters="role: pi, group: current " %}
{% include list.html data="members" component="portrait" filters="role: collaborator, group: current: " %}
{% include list.html data="members" component="portrait" filters="role: postdoc, group: current: " %}
{% include list.html data="members" component="portrait" filters="role: phd, group: current: " %}
{% include list.html data="members" component="portrait" filters="role: staff, group: current: " %}

{:.center}

{% include section.html background="images/banners/fungus_7.jpg" dark=true%}


{% include list.html data="members" component="portrait" filters="role: pi, group: alum" style="small" %}
{% include list.html data="members" component="portrait" filters="role: postdoc, group: alum" style="small" %}
{% include list.html data="members" component="portrait" filters="role: phd, group: alum" style="small" %}
{% include list.html data="members" component="portrait" filters="role: staff, group: alum" style="small" %}


{:.center}

{% include section.html %}

## Funding

Our work is made possible by funding from several organizations.
{:.center}

{%
  include gallery.html
  style="square"

  image1="images/nsf.png"
  link1="https://nsf.gov/"
  tooltip1="National Science Foundation"

  image2="images/jgi_logo.svg"
  link2="https://jgi.doe.gov/"
  tooltip2="DOE Joint Genome Institute"
%}
