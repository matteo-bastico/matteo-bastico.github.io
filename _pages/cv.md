---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* PhD in in AI and Computer Vision Methods for Medical Imaging and Knee Mechanical Modelling, Mines Paris - PSL Univeristy, France, 2025 (Expected)
* MSc in ICT for Internet and Multimedia (Honours), Università degli Studi di Padova, Italy, 2021 - Double Master's Degree Scholarship
* MSc in Telecommunication Engineering, Universidad Politecnica de Madrid, Spain, 2021 - Double Master's Degree Scholarship
* BSc in Information Engineering, Università degli Studi di Padova, Italy, 2018

Work experience
======
* 2021 - 2022: AI Research Scientist @ Universidad Politécnica de Madrid, Spain
  * Involved in international European Union’s Horizon 2020 projects, such as <a href='https://genomed4all.eu/'>GenoMed4All</a> and <a href='https://rescuerproject.eu/'>RESCUER</a>.
  * Developed AI models in Python, using the PyTorch framework, with medical applications (DNA Analysis, Patient Identification).
  * Proactively participated in teamwork, meetings, business trips, article publications, and conferences.

* 2018 - 2019: ICT Help Desk Agent @ IL GAZZETTINO, Venice, Italy
  * Troubleshot and resolved a vast range of hardware, software, and network connectivity problems both remotely and in-place.
  * Answered calls, responded to emails, and spoke with clients face-to-face.
* 2014 - 2015: Front-End Programmer @ Valore4IT, Venice, Italy 
  * Developed websites for clients 
  
Skills
======
* Computer Vision
* Deep Learning Architectures
* Medical Image Analysis
* Image Segmentation
* Point Clouds
* Python Programming
  * PyTorch, Numpy
  * Data Parallel
  * CUDA
* Git and GitHub
* Communication and Teamwork 
* Article Writing and Graphics Design 

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
