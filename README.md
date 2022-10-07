# Architecture Workshop - Kubernetes Native
## What is it
The *Architecture Workshop - Kubernetes Native* is a two-days learning experience for developers who want to understand and make use of the benefits of Quarkus in an OpenShift environment in their daily work. They learn everything they need to understand the concepts, the architectural principles and components of Quarkus and OpenShift and related products for successfully discussing and developing Cloud Native Applications at a customer site from a developer’s perspective.

## Key takeaways
- Benefits of using Quarkus
- Concepts of Quarkus
- Basic understanding
- Making use of Quarkus Dev Services
- Understanding and using Quarkus to build a micro service
- Developing Quarkus Apps with OpenShift 
  - Using Source to Image
  - Understanding Serverless (Knative)
  - Deployment of Quarkus apps on OpenShift
- Using and understanding of Kustomize and Helm Charts
- Use OpenShift Pipelines (Tekton Pipelines) to do CI/CD
- Use of ArgoCD and OpenShift GitOps

## Format
The workshop is designed as a two-days experience with a mix of presentations and quite a lot of demos.

To make it more enjoyable for everyone, we are going to implement a multiplayer game (Pac-Man / FatCat inspired) with an already existing JavaScript client and a server part, written with Quarkus. 

Have a look at [GitHub](https://github.com/wpernath/quarkus-grumpycat) to see a demo of the game.

## Target Audience
- Sales Engineers
- Delivery
- Solution Architects
- Developers

## Prerequisites
- Basic knowledge of Red Hat 
- Basic understanding of Containers and Container Images
- Basic understanding of OpenShift and / or Kubernetes
- Java programming language

## Agenda
The two days are full of technical demos and presentations. 

### Day #1
Start | End | Topics
------|-----|------
9:00 | 9:30| Intro & Welcome
9:30 | 10:30| Quarkus Introduction
**10:30**|**10:45**| **break**
10:45|12:15|Working with Quarkus
**12:15**|**13:15**|**Lunch Break**
13:15|15:30|Application Packaging - Templates - Kustomize - DIY - Helm Charts
15:30|16:00|Open Questions / Answers


### Day #2
Start | End | Topics
------|-----|------
9:00 | 9:15| Welcome
9:15 | 10:45| Quarkus in a Serverless world
**10:45**|**11:00**| **break**
11:00|12:30|CI/CD - OpenShift Pipelines - Tekton - Tekton Security - Working with the examples
**12:30**|**13:30**|**Lunch Break**
13:30|15:30|GitOps - Basics / Concepts - Using ArgoCD - Working with the examples - Building a complete demo
15:30|16:00|Open Questions / Answers


## Resources
The slides and presentations can be found in this repository.

- [Intro](material/1_Introduction%20to%20Kubernetes%20Native%20Development.pdf)
- [Working with Quarkus](material/2_Working%20with%20Quarkus.pdf)
- [Application Packaging](material/3_Application%20Packaging.pdf)
- [Quarkus Serverless](material/5_GitOps.pdf)
- [GitOps](material/5_GitOps.pdf)

## Demo Repositories & Requirements
All sources and demos are publicly available on GitHub. 
- [Quarkus GrumpyCat](https://github.com/wpernath/quarkus-grumpycat.git)
- [Quarkus GrumpyCat Config](https://github.com/wpernath/grumpycat-config.git)
- [Quarkus Super Heroes Example](https://github.com/quarkusio/quarkus-super-heroes)
  

