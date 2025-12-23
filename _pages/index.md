---
title: "A computational approach to science"
layout: splash
permalink: /
date: 2020-04-08
header:
  overlay_color: "#000"
  overlay_filter: "0.0"
  overlay_image: /assets/images/napoli.jpg
  caption: "Photo credit: [**Luigi Selmi**](https://www.luigiselmi.eu)"
excerpt: "
 <br>
 <br>
 <br>
"
#-------------------------- 1st feature row ------------------------------
feature_row1:
  - image_path: assets/images/sentinel-2.png
    title: "Earth Observation"
    excerpt: "Climate change is already having an impact on our lives and it is something we will have to deal with for many decades to come. We have seen how data and information are important to address a pandemic. We will need much more to mitigate the consequences of the climate change, to adapt to it and make our social and physical infrastructures resilient. Satellites play a fundamental role in monitoring the essential climate variables that can allow citizens and political leaders to make the appropriate decisions to avoid the worst-case scenarios. We have already been working with the Copernicus services, the Sentinel-1 and Sentinel-2 satellite data. The open data policy under which the Copernicus data is released allows many more actors to participate in raising awareness and in enabling communities to adapt to a changing environment."
    url: "https://www.luigiselmi.eu/copernicus/ecrs2022-best-presentation-award.html"
    btn_label: "Read More"
    btn_class: "btn--primary"

#-------------------------- 1st feature row ------------------------------
feature_row2:
  - image_path: assets/images/hough_transform/hough_transform_detected_lines.png
    title: "Data Science and Machine Learning"
    excerpt: "Nowadays software engineers have to process data that does not come just as tables. Text and images are much more common input data than structured data. Classical algorithms are still useful but we need the machines to learn from the data. This requirement is not at all new since scientists and engineers are used to analyze data using statistics to build a model of the system they are dealing with. Machine learning, and in particular Deep Learning, allows us to perform tasks such as image segmentation, object detection or text translation, that were simply impossible just 10 years ago. We have successfully implemented an application for land use and land cover classification using a Deep Learning architecture and we are ready to apply the technology in many other tasks in computer vision and digital image processing."
    url: "https://www.luigiselmi.eu/dip/hough_transform.html"
    btn_label: "Read More"
    btn_class: "btn--primary"

#-------------------------- 3rd feature row ------------------------------
feature_row3:
  - image_path: assets/images/thessaloniki.png
    title: "Big Data"
    excerpt: "In real world applications we usually need different frameworks for messaging, indexing, processing and storage. We also need our systems to operate in high availability with low latency and to be able to scale to handle an increase in the number of requests or in the amount of data. These requirements can be fulfilled by using a more powerful machine up to a certain point. Most of the time applications are deployed in a cloud environment where standard machines are made available to the application so that the requests can be distributed to different servers. In such environment the system components are partitioned, replicated and distributed to the machines. Furthermore nowadays these components are deployed as docker containers onto virtual machines. We have deployed distributed systems in production environments on AWS and on-premises to address the needs of companies and public administrations."
    url: "https://github.com/luigiselmi/kafka-clients"
    btn_label: "Read More"
    btn_class: "btn--primary"

#-------------------------- 4th feature row ------------------------------
feature_row4:
  - image_path: /assets/images/ontology.png
    title: "Knowledge Graphs and Linked Data"
    excerpt: "Google added a knowledge graph infobox to its search results in 2012. Since then users have been able to access content not just by keywords but following meaningful links between different types of resources. That was the first realization of the Semantic Web idea: using terms from a shared vocabulary to power intelligent applications and to \"unleash a revolution of new possibilities\". We have been working on knowledge graphs since they were only an academic field of study. We believe that we are still just at the beginning and that many more actors can benefit from the Linked Data principles and technologies."
    url: "https://github.com/luigiselmi/p3-silkdedup"
    btn_label: "Read More"
    btn_class: "btn--primary"

#-------------------------- 5th feature row ------------------------------
feature_row5:
  - image_path: assets/images/bde-components.png
    title: "Software Engineering"
    excerpt: "Software development involves people. As obvious as such statement may appear it is just a reminder that software development is a challenging endeavor that can succeed only when a team follows a development process and has access to a version control system, an issue tracker, a documentation system and writes tests before implementing the solution. An issue tracker allows the team to measure its performance and to address any problem that may arise before it is too late. We have been involved in many projects with partners from all over the world. We share the best practices, tools and processes to fulfill our projects' requirements and achieve our clients goals. We use docker containers to build applications on top of microservices that can be easily deployed on a cloud environment or on-premises."
    #url: "#test-link"
    #btn_label: "Read More"
    #btn_class: "btn--primary"

#-------------------------- 6th feature row ------------------------------
feature_row6:
  - image_path: assets/images/security.png
    title: "Information Security"
    excerpt: "Security is a major concern. We have created resources about cryptography and Public key Infrastructure to help citizens using open source tools to keep their data private."
    url: "/message-encryption-and-signature.html"
    btn_label: "Read More"
    btn_class: "btn--primary"

---
{% include feature_row id="feature_row1" type="right" %}
{% include feature_row id="feature_row2" type="left" %}
{% include feature_row id="feature_row3" type="right" %}
{% include feature_row id="feature_row4" type="left" %}
{% include feature_row id="feature_row5" type="right" %}
{% include feature_row id="feature_row6" type="left" %}
