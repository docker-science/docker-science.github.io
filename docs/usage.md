---
layout: page
title: Cookiecutter Docker Science - Docs
---

# Requirements

- Python 2.7 or Python 3.5
- Cookiecutter 1.6 or later
- Docker version 17 or later


# Getting Started

To generate project from the cookiecutter-doccker-science template, please run the following command.

```
$cookiecutter git@github.com:docker-science/cookiecutter-docker-science.git
```

Then the cookiecutter command ask for several questions on generated project as follows.

```
$cookiecutter git@github.com:docker-science/cookiecutter-docker-science.git
project_name [project_name]: food-image-classification
project_slug [food_image_classification]:
jupyter_host_port [8888]:
description [Please Input a short description]: Classify food images into several categories
data_source [Please Input data source in S3]: s3://research-data/food-images
```

