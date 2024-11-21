---
layout: default
title: Welcome to the Cyber Analysis & Defense (CA&D) department's open source projects
---

<p align="center">
    <img src="https://raw.githubusercontent.com/fkie-cad/fkie-cad.github.io/main/fkie_logo.png" alt="FKIE Logo" width="50%" height="50%"/>
</p>


# Welcome to FKIE CA&D

We are dedicated to advancing the field of cybersecurity to protect against cybercrime, espionage, and sabotage. Our mission is to empower the community with open-source tools and research that bolster security and resilience in the digital age.

## Our Projects

Here are some of the open-source tools and research initiatives we’ve developed:

<ul>
{% assign popular_repos = site.github.public_repositories | sort: "stargazers_count" | reverse | slice: 0, 5  %}
{% for repo in popular_repos %}
  <li>
    <a href="{{ repo.homepage | default: repo.html_url }}">
      {{ repo.name }}
    </a> - {{ repo.description | default: "No description available" }}
  </li>
{% endfor %}
</ul>

<p>For a complete list of all repositories, visit our <a href="https://github.com/fkie-cad/">GitHub organization page</a>.</p>


## Our Approach

At Cyber Analysis & Defense (CA&D) department, we believe that collaboration and transparency are key to tackling the ever-evolving landscape of cyber threats. While we are committed to sharing knowledge, tools, and research, we ensure that confidentiality and sensitive data are never compromised in the process.

We provide open-source projects and solutions that:

- Enhance threat detection and mitigation.
- Support secure software development practices.
- Empower researchers and practitioners to better understand and respond to cyber threats.

## About Us

The Cyber Analysis & Defense (CA&D) department is dedicated to protecting critical systems and infrastructures from cyberattacks by analyzing vulnerable systems, safeguarding friendly systems and infrastructure, and analyzing cyberattacks, attackers’ tools, and actors. With their expertise in these areas of cyber and information security, CA&D researchers make valuable contributions to protecting against cybercrime, espionage and sabotage.

For more information, visit [FKIE-CAD organization page](https://www.fkie.fraunhofer.de/en/departments/cad.html).

