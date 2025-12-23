---
permalink: /about/
title: "About Us"

header:
  overlay_color: "#000"
  overlay_filter: "0.0"
  overlay_image: /assets/images/italy_layout.png
  show_overlay_excerpt: true

excerpt: "Our company is headquartered in Rome, Italy.<br>
We are happy to collaborate with people
and organizations all over the world
on data that matters<br><br>"

author: selmilab
author_profile: true
---
Selmilab is a science and technology consultancy firm. We share here our technology stack, the software we have been using in our projects. The list is not written in stone. We may add other tools and frameworks if we find they are better or if other tools are required for a project.


# Technology Stack
<img src="/assets/images/selmilab_tech_stack.jpg" align="center" width="501" height="516">

Our reference architecture follows the principles of the [reactive manifesto](https://www.reactivemanifesto.org/): a system must be responsive, resilient, elastic and message driven. A software system must be able to ingest and process data streams from different data sources as they become available. We have selected open source frameworks for message-passing, indexing and data storage. These frameworks are the building blocks of our software infrastructure. Applications are developed on top of the infrastructure to fulfill a project's requirements. Both the infrastructure and the application components are released in containers (e.g. Docker) that can be deployed on a cloud environment (e.g. AWS) or on-premises.

### Development Process
The software development process follows the principles of the [agile manifesto](https://agilemanifesto.org/principles.html), in particular [Scrum](https://scrumguides.org/index.html), and is based on a series of tools and practices for

* Test-driven development
* Version control system (e.g. Git)
* Issue tracking (or ticketing system)
* Continuous integration (e.g. Travis)
* Documentation

### Programming Languages
We are fluent in Java and Python but not afraid to use other languages such as JavaScript, R or C/C++. The reference framework for Java is [Spring](https://spring.io/).

### Big Data Frameworks
The open source frameworks we have been using, divided by category:
* Message Passing: Apache Kafka
* Processing: Apache Flink, Apache Spark
* Storage and Indexing: Apache Cassandra, Elasticsearch, Apache Solr

### Machine Learning Frameworks
Our reference framework for machine learning is scikit-learn. We use both PyTorch and TensorFlow for Deep Learning projects.

### Geospatial Tools and Frameworks
We use open source software for geospatial data.
* SAR and optical satellite imagery: Snap Toolbox
* Desktop GIS: QGIS
* Spatial Databases: PostgreSQL, PostGis
* Tile Server: MapServer, Geoserver.

### Knowledge Graphs and Linked Data
* RDF Processing Framework: Jena
* RDF Database and SPARQL server: Virtuoso, Jena
