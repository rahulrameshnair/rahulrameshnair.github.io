---
title: A Generalized Schema to Publish and Share Life Cycle Inventories (LCI)
subtitle: A novel and user-centric schema to improve the transparent reporting of LCI data 

# Summary for listings and search engines
summary: A novel, minimalistic, user-centric, machine-accessible, and extensible schema based on the Brightway LCA framework to share the foreground life cycle inventories

# Link this post with a project
# projects: []

# Date published
date: '2024-08-07T00:00:00Z'

# Date updated
#lastmod: '2020-12-13T00:00:00Z'

# Is this an unpublished draft?
draft: true

# Show this page in the Featured widget?
featured: false

# Featured image
# Place an image named `featured.jpg/png` in this page's folder and customize its options here.
image:
  caption: 'The four phases in life cycle assessment'
  focal_point: ''
  placement: 2
  preview_only: false

authors:
  - admin

tags:
  - life cycle assessment
  - life cycle inventory schema
  - LCIS
  - Python tool
  - FAIR Life cycle data
  - Data transparency

categories:
  - Posts
---


Life cycle assessment (LCA) has quickly become one of the most popular techniques for evaluating the environmental viability of product systems across various technical domains. These systems can range from the valorization of refuse biomass as biochar, and direct air capture of CO2 to sustainable fuel supply chains for next-generation aircraft. 

LCA studies of systems can be easily undertaken through many open-source, commercial, or domain-specific tools provided that the end-user has access to the necessary life cycle data. This has led to a widespread adoption and utilization of LCA approach in the evaluations of emerging technologies. Furthermore, even non-subject experts are also able to publish LCA research to forecast the potential environmental impacts of such complex engineering systems. The increased availability of such assessment reports can theoretically support in improving and optimizing the development of these systems for a sustainable future. However, such benefits are negated due to the lack of FAIR (findable, accessible interoperable, reusable) data in LCA. A quick search in Scopus reveals that the past 5 years have seen a considerable increase in LCA investigations claiming novel findings about predicted life cycle impacts of technologies at low-medium technology readiness levels. However, only a small number of these investigations has transparently made the data available.  An even smaller fraction of this available data is in a reusable form with minimal ambiguities. This lack of data availability, assumptions, and metadata regarding the product system in a structured manner results in non-reproducible and irrefutable LCA calculations. Thus, conclusions from LCA investigations must be accepted at face value.

No standardized methods exist for publishing and sharing foreground LCIs with the relevant contextual information. As a first step to address this gap, this work proposes a novel, simple, user-centric, machine-accessible, and extensible schema based on the Brightway LCA framework to share the foreground LCI. It is initially developed for generalized non-temporal LCAs. In this schema, an inventory is made up of five components: dataset, dataset properties, metadata, dependencies, and network. This schema is demonstrated for the use case of an aviation fuel supply chain using direct air capture units. A Python-based open-source tool has also been developed to convert LCIs according to the specifications of this schema. 


Read the pre-print at [HAL Science](https://hal.science/hal-04652703v1)
Github repo for the DLR tool [GitHub](https://github.com/rahulrameshnair/lcis/)