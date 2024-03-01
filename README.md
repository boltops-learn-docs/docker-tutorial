<!-- note marker start -->
NOTE: This repo contains only the documentation for the private BoltsOps repo code.
Original file: https://github.com/boltops-learn/docker-tutorial/blob/master/README.md
The docs are publish so they are available for interested subscribers.
For access to the source code, you can become a BoltOps subscriber.
See: https://learn.boltops.com

<!-- note marker end -->

# Docker Tutorial: Commands Crash Course

[![BoltOps Badge](https://img.boltops.com/boltops/badges/boltops-badge.png)](https://www.boltops.com)

This tutorial focuses covers on the initial useful commands you'll need to know when getting started with Docker.

* It installs some common commands to help with debugging and useful.
* It builds an Docker image with apache from using the amazonlinux:2 image as a base: [Dockerfile](Dockerfile)
* Relevant Blog Post: [Docker Intro Tutorial: Common Commands Crash Course](https://blog.boltops.com/2018/04/19/docker-introduction-tutorial)

## Build

    docker build -t boltops/docker-tutorial .

## Run

    docker run boltops/docker-tutorial

## Push

    docker push boltops/docker-tutorial

## Notes

Replace boltops with your own DockerHub username if you are going through the tutorial.

## Video

[![Watch the video](https://uploads-learn.boltops.com/prcqr9jlkk2dwnniraklqiqpam55)](https://learn.boltops.com/courses/docker/lessons/docker-intro-common-commands-crash-course)
