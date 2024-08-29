---
abstract: "Street view imagery (SVI), an emerging geospatial dataset, is useful for evaluating active transportation infrastructure, but it faces potential biases from its vehicle-based capture method, diverging from pedestrians’ and cyclists’ perspectives. Existing literature lacks both an examination of these biases and a solution. This study identifies and quantifies these biases by comparing conventional SVI with views from the road shoulder/sidewalk. To mitigate such perspective biases, we introduce a novel framework with generative adversarial network (GAN)-based image generation models (Pix2Pix and CycleGAN), an image regression model (ResNet-50), and a tabular model (LightGBM). Experiments assessed model effectiveness in translating car-centric views to those from pedestrian and cyclist perspectives. Results show significant differences in semantic indicators (e.g. green view index) between road center and road shoulder/sidewalk SVI, with low Pearson’s correlation coefficients r (0.35–0.55 for road shoulders and 0.45–0.47 for sidewalks) indicating bias. The framework succeeded in creating realistic images and aligning pixel ratios between perspectives, achieving strong correlation coefficients (0.81 for road shoulders and 0.83 for sidewalks), thus reducing bias. This work contributes by providing a scalable and model-agnostic approach to produce accurate SVIs for urban planning and sustainability, setting a foundation for improving bikeability and walkability assessments and promoting active transportation."

author_notes:
- Conceptualization, Methodology, Software, Validation, Formal analysis, Investigation, Data Curation, Writing - Original Draft, Visualization
- Methodology, Writing - Review & Editing
- Conceptualization, Writing - Review & Editing
- Conceptualization, Writing - Review & Editing
- Resources, Writing - Review & Editing, Supervision, Project administration, Funding acquisition
authors:
- admin
- Matias Quintana
- Xianjing Han
- Roger Zimmermann
- Filip Biljecki
date: "2024-08-28T00:00:00Z"
doi: "10.1080/13658816.2024.2391969"
featured: true
image:
  caption: 'an array of real images and generated images both for road shoulder and sidewalk.'
  focal_point: ""
  preview_only: false
projects:
publication: '*International Journal of Geographical Information Science*'
publication_short: ""
publication_types:
- "2"
publishDate: "2024-08-27T00:00:00Z"
slides: ""
summary: This study introduces a novel AI-based framework to mitigate perspective biases in vehicle-captured street view imagery, successfully translating car-centric views to pedestrian and cyclist perspectives for more accurate bikeability and walkability assessments in urban planning.
tags:
- Urban Analytics
- Street View Imagery
- Active Mobility
title: "Translating street view imagery to correct perspectives to enhance bikeability and walkability studies"
url_code: ""
url_dataset: ""
url_pdf: uploads/translating_svi_postprint.pdf
url_poster: ""
url_project: ""
url_slides: ""
url_source: ""
url_video: ""
---

