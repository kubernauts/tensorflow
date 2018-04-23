Tensorflow on Kubernetes: A Love Story
---
Last update: April 16, 2018


Author: marky@kubernauts.io

Questions: [https://kubernauts-slack-join.herokuapp.com/](https://kubernauts-slack-join.herokuapp.com/)

Meetup Registration: https://www.meetup.com/kubernauts/events/243546992/

Introduction
---
Every person falls in love with someone so deeply at some part of their lives that they can live the rest of their life meaningfully with that person." Love isn't like any other relationship as we know. If you get to ask some young lovers, they just say its more of a feeling of attachment of two understanding hearts than a kind of relationship. Many believe that love is the most gifted asset of anyone's life.
        

Serving Inception Model with TensorFlow Serving and Kubernetes

This tutorial shows how to use TensorFlow Serving components running in Docker containers to serve the TensorFlow Inception model and how to deploy the serving cluster with Kubernetes.

To learn more about TensorFlow Serving, we recommend TensorFlow Serving basic tutorial and TensorFlow Serving advanced tutorial.

To learn more about TensorFlow Inception model, we recommend Inception in TensorFlow.

`Part 1: I will show how to create a TensorFlow Serving Docker image for deployment`

`Part 1: I will show how to run the image in local containers and classify cat images`

`Part 2: I will show how to deploy in Kubernetes and classify cat images`



Part 0
---

Lets get started building the dockerfile we will use.
The assumptions are made:
1. You have a working knowledge of docker [https://engineering.hipolabs.com/understand-docker-without-losing-your-shit/]
2. You have a working knowledge of Kubernetes [https://kubernauts.slack.com/messages/C71S057S7]
3. You have a basic understanding of machine learning [https://www.coursera.org/learn/machine-learning]
4. You have a basic understanding of Tensorflow [https://www.youtube.com/watch?v=cKxRvEZd3Mw]

Above I provided some links to help you get started on addressing those assumptions

