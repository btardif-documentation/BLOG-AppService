---
title: "Avoid downtime due to Docker Hub's scheduled maintenance window on August 25th"
author_name: Yi Liao MSFT
layout: post
hide_excerpt: true
---
      [Yi Liao MSFT](https://social.msdn.microsoft.com/profile/Yi Liao MSFT)  8/20/2018 10:46:46 AM  **Summary** Docker has scheduled a [maintenance window for Docker Hub](https://success.docker.com/article/planned-downtime-on-hub-cloud-store) on Saturday August 25th, which has potential impacts to App Service customers.  For Web App for Containers (using custom Docker image), customers will not be able to create new web apps using a Docker container image from Docker Hub during the maintenance window. Customers can still create new apps using Docker images hosted on Azure Container Registry or a private Docker registry. For App Service on Linux (using non-preview built-in stacks), customers will not be impacted as we have Docker container images cached on our Linux workers.  **Recommendation** To avoid unnecessary service interruptions, we recommend Web App for Containers customers not make any changes or restart your apps, or use an alternative Docker registry during the Docker Hub maintenance window.     