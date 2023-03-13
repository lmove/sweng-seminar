---
layout: post
permalink: /thomas-durieux/
---

> Thomas Durieux is an Assistant Professor at Delft University of Technology since June 2022, after completing his post-doc at KTH, Sweden, and INESC-id, Portugal.
His research focuses on automating software maintenance tasks such as program repair, software debloat, and improving the maintenance of Docker environments.
To know more about him, visit his [personal website](https://durieux.me/).

<br>

### Software Engineering for Docker
In this talk, Thomas Durieux will present his new research line on Software Engineering for Docker, with a focus on introducing automatic maintenance tasks in the Docker environment.
He will introduce his first contribution in this research line, Parfum, a tool that can automatically fix Docker "smells".
A demonstration of the tool can be found at https://durieux.me/docker-parfum/. Currently, Parfum can handle 32 Docker smells using template-based repair, AST transformation, and pretty print techniques.
Parfum has been evaluated on 370k Dockerfiles, where 800k Docker smells have been identified.
Out of the 35 pull requests that have been submitted (15 are still pending), 20 have been merged, resulting in a reduction of Docker images by 2.68G in total and estimated savings of 1.37T bandwidth per week.
Thomas will also discuss current shortcomings in the Docker environment and potential future works such as Dockerfiles refactoring, improving vulnerabilities detection in Docker images or testing of Docker.

**Time:** 13:00-13:45 <br>
**Related paper:** [Parfum: Detection and Automatic Repair of Dockerfile Smells](https://arxiv.org/abs/2302.01707)
