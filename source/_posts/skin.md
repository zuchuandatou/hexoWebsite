---
title: Food Detection Web Application served by Kubernetes
date: 2024-06-23 01:14:39
tags:
---
### [Github Repo](https://github.com/zuchuandatou/k8s-ml)
- - Tech Stack
  - Language: Python
  - Framework: Flask
  - Deploy: Kubernetes
-	Built a food detection tool with Python Flask, enabling users to attain outcomes by submitting images of food
- Used Keras to build the CNN modle on Food-11 dataset to classify 11 types of food, achieving a 90% accuracy
-	Deployed the app on Kubernetes with Horizontal Pod Autoscaler and Load Balancer, which reduce response time by 40%, verified by Siege for load testing
-	Analyzed testing results including response times, availability, CPU/memory usage, using Tableau to optimize resource allocation

## Screenshots
### Load Balancer view
{% asset_img load_balancer.png Load Balancer%}
### Topology view
{% asset_img topology_view.png Topo%}
### Report of performance
{% asset_img report.png Report%}