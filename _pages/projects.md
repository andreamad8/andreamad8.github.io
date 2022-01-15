---
layout: page
title: Curriculum
permalink: /CV/
description: You can download my CV in <a href="/assets/pdf/CV.pdf" target="_blank"><b>PDF</b></a>
nav: true
---


## 🧑‍💻   Work Experience
- **Reasearch Scientist** at Meta Reality Lab. 
- **Reasearch Intern** at FacebookAI. Working with the Assistant team on Task-Oriented Dialogue Systems. 
- **Reasearch Intern** at UberAI. Working with the Converational AI team on RL problems.
- **Research Assistant** at the Hong Kong University of Science and Technology.
- **Mentor2017** the Pisa CoderDojo (Volunteer Activity).

## 🎓   Education
- Ph.D. in ECE at HKUST supervised by Prof. [Pascale Fung](https://en.wikipedia.org/wiki/Pascale_Fung).
- M.Sc. in CS at Pisa University 110/110 Honours supervised by Prof. [Giuseppe Attardi](http://pages.di.unipi.it/attardi/).
- M.Sc. in AIS at HKBU 3.89/4.0 Distintion supervised by Prof. [Jiming Liu](https://www.comp.hkbu.edu.hk/~jiming/).
- B.Sc. in CS at Perugia University 110/110 Honours supervised by Prof. [Pinotti Maria Cristina](https://sites.google.com/view/cristinampinotti/home).

## 🗃️   Professional Activity
- **General Chair** of the [Student Research Workshop 2022](https://sites.google.com/view/acl-srw-2022/organisers?authuser=0) (SRW 2022)
- **Area Chair** of the ARR 2022 
- **Reviewer** NAACL 2019, EMNLP 2019, ACL 2019, AAAI 2020, ACL 2020, EMNLP 2020, ICLR 2020, NeurIPS 2020, AAAI 2021, ICML 2021, NAACL 2021, and CSL.
- **Tutorial** co-presenter of "[Deeper Conversational AI](https://medium.com/@NeurIPSConf/tutorial-selections-for-neruips-2020-33b79f4915c4)" at NeurIPS 2020. 

## 🏆   Awards
- **PhD. Award 2020**: [SENG Academic Award](/assets/pdf/MADOTTO-Andrea-12232564.pdf) for Continuing PhD Students 2019-20.
- **ConvAI-NeurIPS 2019** [best paper award](https://signalprocessingsociety.org/community-involvement/speech-and-language-processing/newsletter/neurips-2019-convai-workshop-recap#:~:text=The%20best%20paper%20award%20was,in%20a%20joint%20conversational%20setting.) for Attention Over Paramters for Dialogue Systems.
- **ACL 2019** [outstanding paper award](https://acl2019.org/EN/winners-of-acl-2019-best-paper-awards.xhtml) (top 0.1% of the submission) for Transferable Multi-Domain State Generator for Task-Oriented Dialogue Systems.



<!-- 
<div class="projects grid">

  {% assign sorted_projects = site.projects | sort: "importance" %}
  {% for project in sorted_projects %}
  <div class="grid-item">
    {% if project.redirect %}
    <a href="{{ project.redirect }}" target="_blank">
    {% else %}
    <a href="{{ project.url | relative_url }}">
    {% endif %}
      <div class="card hoverable">
        {% if project.img %}
        <img src="{{ project.img | relative_url }}" alt="project thumbnail">
        {% endif %}
        <div class="card-body">
          <h2 class="card-title text-lowercase">{{ project.title }}</h2>
          <p class="card-text">{{ project.description }}</p>
          <div class="row ml-1 mr-1 p-0">
            {% if project.github %}
            <div class="github-icon">
              <div class="icon" data-toggle="tooltip" title="Code Repository">
                <a href="{{ project.github }}" target="_blank"><i class="fab fa-github gh-icon"></i></a>
              </div>
              {% if project.github_stars %}
              <span class="stars" data-toggle="tooltip" title="GitHub Stars">
                <i class="fas fa-star"></i>
                <span id="{{ project.github_stars }}-stars"></span>
              </span>
              {% endif %}
            </div>
            {% endif %}
          </div>
        </div>
      </div>
    </a>
  </div>
{% endfor %}

</div> -->
