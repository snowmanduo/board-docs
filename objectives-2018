# Nordix Foundation Launch Objectives - 2018

## Purpose of the document
This document is intended to provide a space for community members to discuss and 
brainstorm around topics to address during 2018 as Nordix is launched.  A good way
to approach this is to consider the infrastructure needs for the eventual code to 
be written, to derive solutione for those needs from open source technologies and 
use the establishment of that infrastructure as a first target.

Topics should be:
  1. Based on Open Source technologies and projects
  1. Achievable to establish without significant up front investment
  1. Supporting the objectives and scope of Nordix members
  1. Able to be furter developed through collaborative opewn source project work

##  Nordix objectives and activities

#### Identify labs that can be used for Nordix
A selection of Nordix participants will be able to make labs or equipment available
to the Nordix community.  We should establish a mechanism and set of requirements
for the integration of them into the "Nordix environment".  This should be simple 
and efficient with the bare minimum of process for onboarding.

Groups who have demonstrated interest in participating by providing infrastructure:
  1. CityNetworks
  1. Ericsson
  1. ENEA

We will need to identify what type of infrastructure and how we integrate it moving
forward in order that we have sufficient information as input to the first TC workshop.

#### Implement a multisite Infrastructure as a Service layer
Infrastructure as a service will play an important role in enabling multiple parallel 
activities to occur in the Nordix environment.  The IaaS layer should provide multitenancy
and a hosting service for the various projects and initiatives to be performed in Nordix.
It is importnt that the IaaS layer can be implemented on labs and infrastructure as it is
made available to the Nordix community and seamlessly extend projects into that domain.

Propose to leverage OpenStack as our IaaS, I would also suggest that we leverage the 
OPNFV CI/CD workflows for deployment of OpenStack to automate and simplify the effort
of deployment and lab management.

#### Enable distributed container and runtime environments
Nordix will require a way of deploying various technologies on our infrastructure to enable
development and innovation through project work.  The common solution for this today is to 
either orchestrate deployment through OpenStack or use a container runtime.  

  * OpenStack will be available t our cmmunity through the IaaS layer.
  * Kubernetes can be made available through OpenStack services, or via a cloud provider.  I suggest
    we implement a provider layer for multicloud orchestration and allow the use of OpenStack services.
  * Docker swarm is an additional solution that we can support in our environment, although I would start with Kubernetes.

#### Define and implement a data pool solution for Big Data and analytics activity

#### Establish code repositories and CI workflows for the community
We will require the TC to help drive decisions around how our CI/CD solution is implemented and the
code repository toolset.  We have GitHub, GitLab, and local Git as options for code storage.  In addition
we can leverage Gerrit, Zuul & Jenkins for workflows.

Suggest we workshop this topic at a first meeting of the TC.

#### Identify tools for software development in Nordix
As above we have many options and the TC should be invlved in helping make initial selections.  We do not
need to set binding decisions on these topics however we do need to define our "starting pint" which allows
us to make progress.
