---
title: "Docker & Kubernetes Deployment – DevOps Setup"
date: 2024-01-20
tags: ["docker", "kubernetes", "devops", "aws", "ci-cd"]
---

## Overview
A fully containerized DevOps environment used to deploy modern PHP + Node + React applications to AWS.

## Features
- Single Docker image containing Nginx + PHP + MySQL (local dev)
- Kubernetes manifests for deployments & services
- GitLab CI/CD pipeline for automated deployment to EC2
- Makefile for:
  - Composer install
  - Build
  - Deploy
- Terraform optional for infrastructure provisioning

## Responsibilities
- Built Dockerfile with optimized layers
- Configured Kubernetes deployment & service YAML
- Added Nginx reverse proxy rules
- Created GitLab CI pipeline for build → push → deploy
- Deployed to AWS EC2 via kubectl

## Tech Stack
**Docker, Kubernetes, AWS EC2, GitLab CI/CD, Makefile, Nginx**.
