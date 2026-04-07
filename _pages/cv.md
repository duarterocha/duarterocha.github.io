---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

[Download PDF version](/files/cv.pdf){: .btn .btn--primary}

---

## Education

* **Master's Degree in Mechanical Engineering** — Faculty of Engineering, University of Porto, 2017–2022
  * Specialisation in Fluids and Energy. Final Grade: 85%.
* **Mobility Programme (Erasmus)** — Faculty of Civil and Transport Engineering, Politechnika Poznańska, 2020–2021
  * Final Grade: 95%.

---

## Experience

* **Researcher PhD Student** — Physics of Fluids Dept., University of Twente *(Sep 2022 – Present)*
  * Supervisors: Christian Diddens and Detlef Lohse. Part of the Industrial Partnership Programme *"Fundamental Fluid Dynamics Challenges in Inkjet Printing"*, in collaboration with Canon Production Printing.
  * Co-developed [PYOOMPH](https://pyoomph.github.io/), an open-source object-oriented multi-physics FEM framework in Python, using Git for version-controlled collaborative development.
  * Published 7 peer-reviewed papers (3 as first author) in *J. Fluid Mech.*, *J. Comp. Phys.*, *Advanced Science* and *Soft Matter*; presented at 7 international conferences, 1 supercomputing summer school, and 3 specialist fluid dynamics courses.
  * Developed high-fidelity simulations of microscale droplet physics (µm-scale), resolving Marangoni instabilities and symmetry-breaking transitions.

* **Master's Thesis Research Fellow** — Transport Phenomena Research Center, University of Porto *(Jan 2022 – Jul 2022)*
  * Supervisors: Francisco Galindo-Rosales and José Daniel Araújo.
  * Designed and ran CFD simulations using ANSYS Fluent to optimise nozzle geometry for electronic printing applications, improving flow stability and printing precision.

* **Mechanical Engineer Intern** — IKEA Industry Portugal, Paços de Ferreira *(Jun 2019 – Aug 2019)*
  * Analysed and optimised the mechanical design of a component detection system for packaging lines, improving robustness and reliability of detection by 90% under industrial operating conditions.

---

## Skills

* **Technical:** PYOOMPH, Python, C++, MATLAB, Ansys Fluent (CFD), AutoCAD, SolidWorks, Git
* **Methods & Fields:** FEM, CFD, Numerical Analysis, Inkjet Printing, Microfluidics, Heat Transfer
* **Languages:** Portuguese (Native – C2), English (Full Professional – C1), Spanish (Limited Working – B1), Dutch (Basic – A2)

---

## Publications

<ul>{% for post in site.publications reversed %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>

---

## Talks & Conferences

<ul>{% for post in site.talks reversed %}
  {% include archive-single-talk-cv.html %}
{% endfor %}</ul>

---
## Teaching
<ul>{% for post in site.teaching reversed %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>
