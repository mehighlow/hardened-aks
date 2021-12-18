# Building up a hardened production-ready AKS cluster

In this set of articles, I'll walk you through the steps of creating a bulletproof production-ready AKS cluster using all the best practices.
I will reference official documentation and share my experience(I hope those two match).

By default, creating an AKS requires a couple of clicks in the Azure portal. This is, of course, enough when you want to give birth to another 'Wellcome to NGINX' application. However, building up a production-ready cluster requires a bit more attention.

Bear with me and, I hope, by the end of reading and following some of the recommendations you'll be able to improve your current AKS cluster design or set up a new and better environment.

This set of articles is about managed Kubernetes by Azure(AKS). AKS simply makes your life easier when the strategic decision to go containers has been made.

I'll do my best to update this repo as new features are being released by Kubernetes upstream or the AKS product team.

## Target Audience

Anyone who is planning or running AKS cluster(s) or/and wants to understand how everything fits together.

## Prerequisites

Knowledge of Azure Cloud, AKS, and Kubernetes  at level 200

## Docs

1. [Identities](docs/01-identities.md)
2. Networking(coming soon)
