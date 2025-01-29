---
layout: archive
title: ""
permalink: cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}


# CV [[pdf](../files/YasFindik_resume.pdf)]


## Education

* <b>Ph.D in Computer Science</b>, UMass Lowell, Feb 2025 (expected)
* <b>M.S. in Computer Science & Engineering</b>, Sabanci University, 2018
* <b>B.S. in Computer Engineering</b>, Izmir Institute of Technology, 2016

## Research experience

* <ins>August 2021 -- Present</ins>: <b>Research Assistant @ Persistent Autonomy and Robot Learning lab ([PeARL](https://www.pearl-robotics.com/))</b>, University of Massachusetts Lowell.
  * Currently, exploring how Large Language Models (LLMs) can be used within Multi-Agent Reinforcement Learning (MARL) frameworks to improve agents' performance and encourage the emergence of novel behaviors.
  * Conducted research on MARL and emergent behaviors in collaborative environments. Designed and implemented a graph-based approach to guide and influence the agents' behavior in multi-agent settings.
  * Implemented existing single-agent deep reinforcement learning architectures (DQN, A2C, DDPG, PPO). Implemented and extended existing multi-agent deep reinforcement learning architectures, both value-based (VDN, QMix) and policy-based (MADDPG, MAPPO).
  * Designed and implemented a novel algorithm, D-CBRS, to address intra-class diversity in continuous learning.

* <ins>September 2016 -- July 2021</ins>: <b>Research Assistant @ Behavioral Analytics and Visualization Lab ([BAVLAB](https://analyticslab.sabanciuniv.edu/))</b>, Sabanci University. <i>BAVLAB</i> is cofounded by Sabanci University and MIT Media Lab Human Dynamics Group
  * Conducted research on human-agent interaction, integrating methods such as visualization, computer vision, and natural language processing. 
  * Developed an analytical agent capable of interpreting the environment and generating insights for data analysis based on presented data and cues from human subjects.
  * Performed research on collaborative computer-aided designs using a tabletop setup.
  * Conducted studies on Twitter data and analyzed patterns using data mining methods.

* <ins>September 2015 -- May 2016</ins>: <b>Research Student @ Visual Intelligence Research Group</b>, Izmir Institute of Technology.
  * Worked on obstruction removal from images and implemented a computational approach to remove impediments such as fences, windows and reflections from images.

## Work experience

* <ins>June 2022 -- August 2022</ins>: <b>Data Science Intern @ Novartis</b>, New Jersey, USA. <i>Novartis</i> operates in the pharmaceutical and healthcare sector, focusing on the research, development, and commercialization of innovative medicines and healthcare solutions. 
  * Developed Mixed Marketing Model(s) using Turkey sales data for Jakavi and Kisqali.
  * Preprocessed and mined data for the Belgium Sentiment Analysis Project.
  * Reviewed literature and designed experiments for the Genomics Project on breast cancer.

* <ins>March 2020 -- July 2021</ins>: <b>Machine Learning Engineer @ Cicek Sepeti</b>, Istanbul, Turkey. <i>Ciceksepeti.com</i> is an online floral and gourmet foods, gift retailer operating in Turkey with subsidiaries (lolaflora.com) in other countries.
  * Led a team of three junior engineers in designing and building an efficient framework to find the optimal price of products.
  * Combined modern machine learning approaches with structural models to maximize company profits.
  * Trained the underlying model on prior market data to predict optimal prices by learning market dynamics.
  * Enabled respective employees to inspect price differences of the company's products among e-commerce websites.

* <ins>November 2018 -- June 2019</ins>: <b>Machine Learning Engineer @ Softtech</b>, Istanbul, Turkey. <i>SoftTech</i> is the tech company behind IsBank, Turkey's largest bank.
  * Implemented a platform for chatbot model training and management.
  * Utilizes deep learning (LSTM/GRU architectures) for larger datasets and similarity algorithms (e.g., n-grams, word mover's distance) for smaller datasets.
  * Platform is currently used by IsBank, where millions of users interact with the company's chatbot daily.

* <ins>August 2015 -- June 2016</ins>: <b>Software Engineer @ Secube</b>, Izmir, Turkey
  * Worked as a full-time software engineer during my senior year of college.
  * Developed [CubeBox](https://www.secube.com.tr/en/cubebox-document-management-system), an application similar to GoogleDrive that allows users to store their files, access them remotely, share them with others, and encrypt files before storing them, unlike other available apps.
  * Developed a mobile application for members of the Turkish parliament to securely sign and share documents.

## Technical skills

* <b>Languages</b>: Python, C, Matlab, R, Object-Oriented (Java/C++/C\#), Web Development (HTML/CSS/Javascript/PHP)
* <b>Frameworks</b>: Pytorch, Tensorflow, Keras, Flask, OpenCV, OpenGL, D3, Android
* <b>Others</b>: AWS, Docker, Kafka, Solr, MongoDB, Git

## Publications

  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
## Talks

  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
## Teaching Experience

  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

