---
title: About
layout: page
permalink: /about/
---

I am developing theoretical methods to describe
chemistry at large scales with quantum mechanical
accuracy. The focus is in particular on solvation phenomena
and spectroscopy of condensed phase systems.
Our long standing goal is formulation of fragmentation
method that goes beyond standard classical *ab initio* force fields
and is applicable to a wide range of problems in material and medicinal chemistry.

Currently, following our fragmentation philosophy, 
we developed two methods that are currently applicable
for:
 - calculation of vibrational spectra of local IR probes
 - excitonic energy transfer couplings

We are currently merging the approaches used in the above two
examples of application.

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
