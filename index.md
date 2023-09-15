---
title: Home
image_sliders:
  - slider2
---

{% include section.html background="images/green.png" dark=true %}

# {% include icon.html icon="fa-solid fa-feather-pointed" %} Just Sustainability Design Lab

{% include section.html %}

## What We Do and Why

The overarching theme of our group is to conduct  **impactful research on designing information technology for sustainability and social justice, which converge in just sustainability**. The aim is often to enact meaningful change in tech to meet the urgent need for sustainability and social justice. 

 The aim is that each project we engage in has the potential to make a difference in shifting our world on a more sustainable and just course, and that some actually do. Design is understood very broadly as the ‘interaction between creation and understanding’ (following Winograd and Flores’ [book]([url](https://www.goodreads.com/es/book/show/53482.Understanding_Computers_and_Cognition))). We engage in designing by building technology, but equally in studies and critique of how things are, visions of how they could be, investigations of socio-technical, social or cognitive phenomena relevant to design, reflections, and other types of research.  

Our research activities involve:
1. critical examinations of the politics, values, and cognitive processes of design,
2. the development of methods and tools for just sustainability design, and
3. design projects to bring forth just sustainabilities in urban contexts

## Recent Projects
{% include list.html component="card" data="projects" filters="group: "%}

## Who We Are
### Current Members
{% include list.html data="members" component="portrait" filters="role: pi" %}
{% include list.html data="members" component="portrait" filters="role: ^(?!pi$)" %}

[##]: #

{%
  include button.html
  type=""
  text="Joining the Lab"
  link= "https://scd-github.github.io/jsd-lab-website-template/lab/#prospective-students"

%}

{%
  include button.html
  type=""
  text="Learn More"
  link= "https://scd-github.github.io/jsd-lab-website-template/lab/"

%}

{% include section.html background="images/green.png" dark=true %}

# {% include icon.html icon="fa-solid fa-microscope" %} Introducing Just Sustainability Design

{% include section.html %}

## What is Just Sustainability Design
Just Sustainability Design, JSD for short, is a framework for systems design practice, research, and pedagogy that privileges sustainability and justice and therefore, the asymmetric and uneven effects of systems design choices at a distance. JSD aims to bring about improvement, not just avoid damage. 

JSD was introduced in Professor Becker's book, Insolvent: How to reorient computing for just sustainability. To learn more about Just Sustainability Design, see the resources below.


{% capture col1 %}

{%
  include figure.html
  image="images/compulsory.png"
%}

{% endcapture %}

{% capture col2 %}

[##]: #

|

|

|

|

|
{%
  include button.html
  type=""
  text="Read Insolvent For Free"
  link="https://direct.mit.edu/books/oa-monograph/5594/InsolventHow-to-Reorient-Computing-for-Just"
%}

{%
  include button.html
  type=""
  text="Get Your Copy"
  link="https://mitpress.mit.edu/9780262545600/insolvent/"
%}

{%
  include button.html
  type=""
  text="Learn More About Insolvent"
  link="/insolvent/"
%}
|
{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}


## Research Funding

{% capture col1 %}

{%
  include figure.html
  image="images/uoft-school-of-cities.jpg"
  caption="School of Cities"
  height="105px"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/ontario research fund.jpg"
  caption="Ontario Research Fund"
  height="105px"

%}

{% endcapture %}

{% capture col3 %}

{%
  include figure.html
  image="images/NSERC.jpg"
  caption="NSERC"
  height="105px"
%}

{% endcapture %}

{% capture col4 %}

{%
  include figure.html
  image="images/innovation-ca-canada-foundation-for-innovation-cfi-logo-vector.png"
  caption="Canada Foundation for Innovation"
  height="105px"
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 col3=col3 col4=col4 %}



