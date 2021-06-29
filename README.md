[![CircleCI](https://circleci.com/gh/circleci/circleci-docs.svg?style=svg)](https://circleci.com/gh/circleci/circleci-docs)

## Project Overview

A pre-trained, `sklearn` model that has been trained to predict housing prices in Boston according to several features, such as average rooms in a home and data about highway access, teacher-to-pupil ratios, and so on. You can read more about the data, which was initially taken from Kaggle, on [the data source site](https://www.kaggle.com/c/boston-housing). 

### Project Tasks

The project goal is to operationalize this working, machine learning microservice using [kubernetes](https://kubernetes.io/) with using AWS EKS.

---

### What we have inside?

* Check docker lint and make sure there is no problems there.
* Build a new docker image and push it to docker.io
* Deep image inspection and vulnerability scanning.
* Create a AWS Cluster and deployment our docker image. 
