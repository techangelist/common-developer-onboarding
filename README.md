# Summary

## Melco DX engineering product development principle

Melco DX engineering team targets to deliver software as a service (SaaS) applications.  SaaS removes the need for project teams to install and run applications on their own computers or in data centers. This eliminates the expense of hardware acquisition, provisioning and maintenance, as well as software licensing, installation and support.  To complete this goal, DX engineering team and DX team partners must use Twelve Factor App principle as best practice to deliver all DX related products.

## What is Twelve Factor App principle

The (twelve-factor app)[https://12factor.net/] is a methodology for building software-as-a-service apps that:

- Use declarative formats for setup automation, to minimize time and cost for new developers joining the project;
- Have a clean contract with the underlying operating system, offering maximum portability between execution environments;
- Are suitable for deployment on modern cloud platforms, obviating the need for servers and systems administration;
- Minimize divergence between development and production, enabling continuous deployment for maximum agility;
- And can scale up without significant changes to tooling, architecture, or development practices.
- The twelve-factor methodology can be applied to apps written in any programming language, and which use any combination of backing services (database, queue, memory cache, etc).

Key principles:
* Codebase - One codebase tracked in revision control, many deploys
* Dependencies - Explicitly declare and isolate dependencies
* Config - Store config in the environment
* Backing services - Treat backing services as attached resources
* Build, release, run - Strictly separate build and run stages
* Processes - Execute the app as one or more stateless processes
* Port binding - Export services via port binding
* Concurrency - Scale out via the process model
* Disposability - Maximize robustness with fast startup and graceful shutdown
* Dev/prod parity - Keep development, staging, and production as similar as possible
* Logs - Treat logs as event streams
* Admin processes - Run admin/management tasks as one-off processes

Based on 12 factor app princeiple, we have come up the following section about developer onboarding guideline and best practice.

# Developer Onboarding guidelines

## Local machine environment

## DevSecOps practice

### CI

#### Docker

#### Docker Compose

### Docker registry

### CD

#### Kubernetes

#### Automatic QA and Security Test

#### SIT, UAT

#### Blue/Green Deployment

## Project kick-start basic stack

### SPA Development

### Mobile App Development

### API Development