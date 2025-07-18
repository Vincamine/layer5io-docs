---
docType: "Chapter"
id: "introduction"
chapterTitle: "Introduction"
description: "Get started with Meshery playground"
title: "Deploying WordPress and MySQL with Persistent Volumes with Meshery"
lectures: 12
weight: 1
---

{{< chapterstyle >}}

In this tutorial, you will learn how to deploy a **WordPress site and a MySQL database with Persistent Volumes** using Meshery Playground. Meshery Playground is an interactive and collaborative live cluster environment that simplifies the deployment process and enhances user experience by providing visual tools for managing Kubernetes resources.

> **NOTE:** If this is your first time working with Meshery Playground, consider starting with the [Exploring Kubernetes Pods with Meshery Playground](https://docs.meshery.io/guides/tutorials/kubernetes-pods) tutorial first.

<h2 class="chapter-sub-heading">Prerequisites</h2>

- Basic understanding of Kubernetes concepts.
- Access to the _Meshery Playground_. If you don't have an account, sign up at [Meshery Playground](https://play.meshery.io/).

<h2 class="chapter-sub-heading">Lab Scenario</h2>

- Import the WordPress and MySQL manifest files into Meshery Playground.
- Create persistent volumes and a secret for the resources using the visual tools provided by Meshery.
- Deploy these resources on the playground.

In this lab, you will import the WordPress and MySQL manifest files into Meshery Playground. You will visualize these Kubernetes resources and create persistent volumes for them using the visual tools provided by Meshery. Finally, you will deploy these resources on the Playground.

<h2 class="chapter-sub-heading">Objective</h2>

Learn how to import manifest files, visualize Kubernetes resources, create new resource components, and deploy the application using Meshery Playground.

<h2 class="chapter-sub-heading">Steps</h2>

<h3 class="chapter-sub-heading">Download the Kubernetes Configuration Files</h3>

Go ahead and download these yaml files [mysql-deployment.yaml](https://kubernetes.io/examples/application/wordpress/mysql-deployment.yaml) and [wordpress-deployment.yaml](https://kubernetes.io/examples/application/wordpress/wordpress-deployment.yaml)

These YAML files contain the Service definitions, Persistent Volume Claims, and Deployment configurations for the WordPress site and the MySQL database.

<h3 class="chapter-sub-heading">Access Meshery Playground</h3>

1. Log in to the [Meshery Playground](https://cloud.layer5.io/) using your credentials. On successful login, you should be at the dashboard. Press the **X** on the _Where do you want to start?_ popup to close it (if required).
2. Click **Explore** in the Cloud Native Playground tile to navigate to _Kanvas_

{{< /chapterstyle >}}