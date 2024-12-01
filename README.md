# DevOps Best Resources Compilation
This is a compilation of the best resources and materials that I've used to get started in DevOps & cloud, as well as to prepare for interviews.

# 📝 Table of Contents

- [DevOps Best Resources Compilation](#devops-best-resources-compilation)
- [📝 Table of Contents](#-table-of-contents)
- [Networking ](#networking-)
  - [OSI](#osi)
  - [DNS](#dns)
  - [CDN](#cdn)
  - [CIDR Blocks](#cidr-blocks)
  - [HTTP, HTTPs, and certificates](#http-https-and-certificates)
  - [APIs](#apis)
  - [Netowrk Components](#netowrk-components)
- [Linux ](#linux-)
  - [Intro](#intro)
  - [User Account Management](#user-account-management)
  - [Storage](#storage)
  - [Procceses](#procceses)
  - [Firewalls](#firewalls)
  - [Namespaces \& Cgroups](#namespaces--cgroups)
  - [Interview Questions](#interview-questions)
- [Git ](#git-)
- [Docker ](#docker-)
- [Kubernetes ](#kubernetes-)
- [Helm ](#helm-)
- [CI/CD  ](#cicd--)
  - [Jenkins ](#jenkins-)
  - [Github Actions ](#github-actions-)
  - [ArgoCD ](#argocd-)
- [Cloud Providers ](#cloud-providers-)
  - [AWS ](#aws-)
- [Infrastructure as a Code ](#infrastructure-as-a-code-)
  - [Terraform ](#terraform-)
- [Monitoring ](#monitoring-)
  - [Prometheus \& Grafana ](#prometheus--grafana-)
- [Microservices \& Distributed Systems ](#microservices--distributed-systems-)
- [System Design ](#system-design-)

# Networking <a name = "Networking"></a>
## OSI
- [The OSI Model - Explained by Example](https://www.youtube.com/watch?v=7IS7gigunyI&t=883s)
- [How Application Layer Services Work](https://www.youtube.com/watch?v=mGRClHHgNdk&list=PLQVJk9oC5JKp_8F9LPa3Pv67boA80KLm1&index=5)
## DNS
- [WHat is DNS?](https://www.youtube.com/watch?v=72snZctFFtA)
- [The 8 steps in a DNS lookup](https://www.cloudflare.com/en-in/learning/dns/what-is-dns/#:~:text=The%208%20steps%20in%20a%20DNS%20lookup)
## CDN
- [Content Delivery Network](https://www.youtube.com/watch?v=Bsq5cKkS33I)
## CIDR Blocks
- [Classless Interdomain Routing (CIDR)](https://www.youtube.com/watch?v=Q1U9wVXRuHA)
## HTTP, HTTPs, and certificates
- [What are SSL/TLS Certificates? Why do we need them? and How do they Work?](https://www.youtube.com/watch?v=r1nJT63BFQ0)
- [HTTPS](https://www.youtube.com/watch?v=67kItGjvRs0)
- [SSL, TLS, HTTPS Explained](https://www.youtube.com/watch?v=j9QmMEWmcfo&list=PLCRMIe5FDPse7NNmQP5UziLjXjkHW3gqA&index=14)
- [Certificates and Certificate Authority Explained](https://www.youtube.com/watch?v=x_I6Qc35PuQ)
- [HTTP/1 to HTTP/2 to HTTP/3](https://www.youtube.com/watch?v=a-sBfyiXysI&list=PLCRMIe5FDPse7NNmQP5UziLjXjkHW3gqA&index=3)
## APIs
- [API Protocols](https://www.youtube.com/watch?v=zY2DMpCUfCg&list=PLCRMIe5FDPsd0gVs500xeOewfySTsmEjf&index=64)
- [What Is GraphQL? REST vs. GraphQL](https://www.youtube.com/watch?v=yWzKJPw_VzM&list=PLCRMIe5FDPse7NNmQP5UziLjXjkHW3gqA&index=11)
- [What is RPC? gRPC Introduction](https://www.youtube.com/watch?v=gnchfOojMk4&list=PLCRMIe5FDPse7NNmQP5UziLjXjkHW3gqA&index=12)
## Netowrk Components
- [What is API Gateway?](https://www.youtube.com/watch?v=6ULyxuHKxg8&list=PLCRMIe5FDPse7NNmQP5UziLjXjkHW3gqA&index=10)
- [Proxy vs Reverse Proxy Server Explained](https://www.youtube.com/watch?v=SqqrOspasag&t=346s)
- [Load Balancing Algorithms](https://www.youtube.com/watch?v=dBmxNsS3BGE&list=PLCRMIe5FDPsd0gVs500xeOewfySTsmEjf&index=41)
- [Reverse Proxy vs API Gateway vs Load Balancer](https://www.youtube.com/watch?v=RqfaTIWc3LQ&list=PLCRMIe5FDPsd0gVs500xeOewfySTsmEjf&index=59)

# Linux <a name = "Linux"></a>
## Intro
- [Linux Essentials](https://app.pluralsight.com/paths/certificate/lpi-linux-essentials-010-160)
- [How Does Linux Boot Process Work?](https://www.youtube.com/watch?v=XpFsMB6FoOs&list=PLCRMIe5FDPsd0gVs500xeOewfySTsmEjf&index=52)
## User Account Management
- [User Account Management](https://www.youtube.com/watch?v=UN1QB5BIvps)
## Storage
- [File Permissions](https://www.youtube.com/watch?v=4N4Q576i3zA&list=PLCRMIe5FDPsd0gVs500xeOewfySTsmEjf&index=71)
- [Linux inodes Explained](https://www.youtube.com/watch?v=6KjMlm8hhFA)
- [Linux Hard Links versus Soft Links Explained](https://www.youtube.com/watch?time_continue=422&v=lW_V8oFxQgA&feature=emb_title)
- [Linux systemd](https://www.youtube.com/playlist?list=PLtK75qxsQaMKPbuVpGuqUQYRiTwTAmqeI)
## Procceses
- [The /proc Filesystem](https://www.youtube.com/watch?v=0XdjODvsRN8)
- [Linux Performance Tools](https://www.youtube.com/watch?v=iJ_eIsA5E1U&list=PLCRMIe5FDPsd0gVs500xeOewfySTsmEjf&index=76)
## Firewalls
- [Firewalls(iptables)](https://www.howtogeek.com/177621/the-beginners-guide-to-iptables-the-linux-firewall/)
- [Introduction to Uncomplicated Firewall (UFW)](https://www.linux.com/training-tutorials/introduction-uncomplicated-firewall-ufw/)
## Namespaces & Cgroups
- [Network Namespaces Basics](https://www.youtube.com/watch?v=j_UUnlVC2Ss)
- [NameSpaces & Cgroups](https://www.nginx.com/blog/what-are-namespaces-cgroups-how-do-they-work/#:~:text=%E2%80%9CNamespaces%20are%20a%20feature%20of,isolate%20processes%20from%20each%20other.)
## Interview Questions
- [Top 10 Linux Job Interview Questions](https://faun.pub/top-10-linux-interview-questions-how-many-questions-can-you-answer-correctly-d3a469b9918c)

# Git <a name = "Git"></a>
- [How does Git Work?](https://www.youtube.com/watch?v=e9lnsKot_SQ&list=PLCRMIe5FDPsd0gVs500xeOewfySTsmEjf&index=47)
- [Git MERGE vs REBASE vs SQUASH](https://www.youtube.com/watch?v=0chZFIZLR_0)

# Docker <a name = "Docker"></a>
- [Documentation](https://docs.docker.com/)
- [handbook](https://www.freecodecamp.org/news/the-docker-handbook/)
- [Name Spaces](https://www.nginx.com/blog/what-are-namespaces-cgroups-how-do-they-work/#:~:text=%E2%80%9CNamespaces%20are%20a%20feature%20of,isolate%20processes%20from%20each%20other.)
- [Dockerfile linter, validate](https://github.com/hadolint/hadolint)
- [Docker Tutorial for Beginners](https://www.youtube.com/watch?v=fqMOX6JJhGo)
- [Docker (iptables)](https://docs.docker.com/network/iptables/)
- [Docker Networking](https://youtu.be/OU6xOM0SE4o)
- [Docker in Depth](https://medium.com/@furkan.turkal/how-does-docker-actually-work-the-hard-way-a-technical-deep-diving-c5b8ea2f0422)
- [Intro to Docker Swarm](https://www.sumologic.com/glossary/docker-swarm/)

# Kubernetes <a name = "Kubernetes"></a>
- [Documentation](https://kubernetes.io/docs/home/)
- [hand book](https://www.freecodecamp.org/news/the-kubernetes-handbook/)
- [kubebuilder book](https://book.kubebuilder.io/introduction.html)
- [Kubernetes Cookbook](https://www.oreilly.com/library/view/kubernetes-cookbook/9781491979679/)
- [Nana's Video](https://www.youtube.com/watch?v=X48VuDVv0do)
- [create custom resources](https://www.youtube.com/watch?v=xGafiZEX0YA)
- [Play with Kubernetes](https://labs.play-with-k8s.com/)
- [Kubernetes for dev infrastructure](https://hackernoon.com/kubernetes-for-dev-infrastructure-40b9175cb8c0)
- [Top 10 Kubernetes tips and tricks](https://hackernoon.com/top-10-kubernetes-tips-and-tricks-27528c2d0222)
- [Kubernetes Persistent Volumes](https://loft.sh/blog/kubernetes-persistent-volumes-examples-and-best-practices/)
- [Secrets in K8s(External Secrets & External Secrets Operator )](https://www.kubecost.com/kubernetes-devops-tools/kubernetes-external-secrets/)
- [Understanding Kubernetes networking: pods](https://medium.com/google-cloud/understanding-kubernetes-networking-pods-7117dd28727)
- [kubernetes-network-policy-recipes](https://github.com/ahmetb/kubernetes-network-policy-recipes)
- [kubernetes-security-best-practice](https://github.com/freach/kubernetes-security-best-practice)
- [Nginx Ingress Controller & Cert Manager Setup](https://www.youtube.com/watch?v=N7W_nsEA-Ao)
- [How To Troubleshoot Kubernetes Pods: Beginners Guide](https://devopscube.com/troubleshoot-kubernetes-pods/)
- [Debug Failed Pods](https://www.datadoghq.com/blog/debug-kubernetes-pending-pods/)
- [Certificate Management in k8s using Cert-Manager](https://www.youtube.com/watch?v=hoLUigg4V18)
- [Advanced Kubernetes Objects You Need to Know](https://engineering.opsgenie.com/advanced-kubernetes-objects-53f5e9bc0c28)
- [Certified Kubernetes Application Developer (CKAD)](https://learn.acloud.guru/course/certified-kubernetes-application-developer/overview)

# Helm <a name = "Helm"></a>
- [Helm - The Kubernetes package manager hands-on course](https://www.udemy.com/course/helm-the-kubernetes-package-manager-hands-on-course/)

# CI/CD  <a name = "cicd"></a>
## Jenkins <a name = "Jenkins"></a>
- [Jenkins Tutorial for Beginners](https://www.youtube.com/watch?v=pMO26j2OUME&list=PLy7NrYWoggjw_LIiDK1LXdNN82uYuuuiC)
- [Complete Jenkins Pipeline Tutorial | Jenkinsfile explained](https://www.youtube.com/watch?v=7KCS70sCoK0)
## Github Actions <a name = "GH_Actions"></a>
- [GitHub Actions Tutorial - Basic Concepts and CI/CD Pipeline with Docker](https://www.youtube.com/watch?v=R8_veQiYBjI)
## ArgoCD <a name = "ArgoCD"></a>
- [ArgoCD](https://www.youtube.com/watch?v=MeU5_k9ssrs&t)

# Cloud Providers <a name = "Providers"></a>
## AWS <a name = "AWS"></a>
- [Build a Simple AWS Network](https://www.youtube.com/watch?v=aKtA4bZ2Skc&list=PLDtEWvTEOpw5j_XUN6_atkeWh90lJ6JYT&index=2)
- [AWS Network Design: Getting Started](https://app.pluralsight.com/course-player?clipId=7c488157-9d19-42ab-abd7-255ba61bfdc3)
- [Fundamental Cloud Concepts for AWS](https://app.pluralsight.com/library/courses/fundamental-cloud-concepts-aws/table-of-contents)
- [Architecting for Reliability on AWS](https://app.pluralsight.com/library/courses/5d7122ad-e99e-4d04-bd9b-60bd9c44ba3d/table-of-contents)
- [AWS Well-Architected Framework-White Papers](https://docs.aws.amazon.com/wellarchitected/latest/framework/the-pillars-of-the-framework.html)
- [AWS Essentials](https://www.youtube.com/playlist?list=PLv2a_5pNAko0Mijc6mnv04xeOut443Wnk)
- [How to Create Your First Serverless/Lambda Functions](https://www.progress.com/blogs/how-to-create-your-first-serverless-lambda-functions)
- [Full Arabic Course](https://www.youtube.com/playlist?list=PLOoZRfEtk6kWSM_l9xMjDh-_MJXl03-pf)
- [Various Topics](https://www.youtube.com/c/StephaneMaarek/playlists)

# Infrastructure as a Code <a name = "IaaC"></a>
## Terraform <a name = "Terraform"></a>
- [Terraform Course - Automate your AWS cloud infrastructure](https://www.youtube.com/watch?v=SLB_c_ayRMo&t=4806s)
- [Implementing Terraform with AWS](https://app.pluralsight.com/library/courses/implementing-terraform-aws/table-of-contents)
- [Resources Drift](https://developer.hashicorp.com/terraform/tutorials/state/resource-drift)

# Monitoring <a name = "Monitoring"></a>
## Prometheus & Grafana <a name = "Prometheus"></a>
- [Golang Application monitoring using Prometheus](https://gabrieltanner.org/blog/collecting-prometheus-metrics-in-golang/)
- [Setup Prometheus Monitoring on Kubernetes using Helm and Prometheus Operator(part 1)](https://www.youtube.com/watch?v=QoDqxm7ybLc)
- [Setup Prometheus Monitoring on Kubernetes using Helm and Prometheus Operator(part 2)](https://www.youtube.com/watch?v=mLPg49b33sA)

# Microservices & Distributed Systems <a name = "Microservices"></a> 
- [Startup Project](https://github.com/GoogleCloudPlatform/microservices-demo)
- [Distributed Systems بالعربي](https://www.youtube.com/playlist?list=PLald6EODoOJW3alE1oPAkGF0bHZkPIeTK)
- [Microservices Architecture in Arabic](https://www.youtube.com/playlist?list=PLgAqrVq84PDdfiDow3YVsgc1q34JD415Z)

# System Design <a name = "system_design"></a> 
- [The Art of System Design: Practical guide & Lessons from the field in 45 minutes](https://www.youtube.com/watch?v=3IWpU72eixw)
- [How To Choose The Right Database?](https://www.youtube.com/watch?v=kkeFE6iRfMM&list=PLCRMIe5FDPsdnSszazqVIQFh99t1ExH19&index=1)
- [CAP Thearom](https://www.youtube.com/watch?v=BHqjEjzAicA&list=PLCRMIe5FDPsd0gVs500xeOewfySTsmEjf&index=13&pp=iAQB)
- [API Architecture Styles](https://www.youtube.com/watch?v=4vLxWqE94l4&list=PLCRMIe5FDPsd0gVs500xeOewfySTsmEjf&index=30&t=15s)
- [Architecture Patterns](https://www.youtube.com/watch?v=f6zXyq4VPP8&list=PLCRMIe5FDPseVvwzRiCQBmNOVUIZSSkP8&index=13)
- [Distributed System Patterns](https://www.youtube.com/watch?v=nH4qjmP2KEE&list=PLCRMIe5FDPsd0gVs500xeOewfySTsmEjf&index=26&pp=iAQB)
- [Deployment Strategies](https://www.youtube.com/watch?v=AWVTKBUnoIg&list=PLCRMIe5FDPsd0gVs500xeOewfySTsmEjf&index=31&t=24s)
- [Client Architecture Patterns](https://www.youtube.com/watch?v=I5c7fBgvkNY&list=PLCRMIe5FDPsd0gVs500xeOewfySTsmEjf&index=53)
- [OAuth 2 Explained In Simple Terms](https://www.youtube.com/watch?v=ZV5yTm4pT8g&list=PLCRMIe5FDPsd0gVs500xeOewfySTsmEjf&index=34)
- [What Is Single Sign-on (SSO)? How It Works](https://www.youtube.com/watch?v=O1cRJWYF-g4&list=PLCRMIe5FDPseEIW687mH-LZ-DMNbzAQLF&index=2)
- [Algorithms You Should Know Before System Design Interviews](https://www.youtube.com/watch?v=xbgzl2maQUU&list=PLCRMIe5FDPseVvwzRiCQBmNOVUIZSSkP8&index=12)
- [How Does Live Streaming Platform Work? (YouTube live, Twitch, TikTok Live)](https://www.youtube.com/watch?v=7AMRfNKwuYo&list=PLCRMIe5FDPseVvwzRiCQBmNOVUIZSSkP8&index=6)
- [System Design Interview Question: Design a URL Shortening Service](https://designgurus.org/blog/url-shortening)
- [System Design Interview Question: Design A Location Based Service (Yelp, Google Places)](https://www.youtube.com/watch?v=M4lR_Va97cQ&list=PLCRMIe5FDPseVvwzRiCQBmNOVUIZSSkP8&index=1)
- [Back-Of-The-Envelope Estimation / Capacity Planning](https://www.youtube.com/watch?v=UC5xf8FbdJc&list=PLCRMIe5FDPseVvwzRiCQBmNOVUIZSSkP8&index=5)
