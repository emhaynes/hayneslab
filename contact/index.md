---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

If you are interested in joining the lab, please see the "Join Our Team!" tab for instructions on what information to include with your email.

For all other inquiries, please email Liz at:

{%
  include button.html
  type="email"
  text="ehaynes 2 @wisc.edu"
  link="ehaynes2@wisc.edu"
%}

{%
  include button.html
  type="address"
  text="Find us at the Wisconsin Institute for Medical Research"
  tooltip="The Department of Cell and Regenerative Biology at UW-Madison"
  link="https://maps.app.goo.gl/1NmgK6p9ipwvsxgW7"
%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/photo.jpg"
  caption="Our Lab"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/photo.jpg"
  caption="The Beckman Center for Light Sheet Microscopy at WID"
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}

