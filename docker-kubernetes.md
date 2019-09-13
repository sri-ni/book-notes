# Docker and Kubernetes

## VMs
Every OS in a VM is an attack vector. They steal resources from the VM hardware resources. Licensing cost. Operating costs in electricity. 

- Multiple VMs
- Multiple OSs
- Hypervisor on top of hardware

## Containers

- Single OS
- Multiple containers/apps
- 1 container : 1 app
- Space for more containers

```
 Docker container start web
```

Docker can start an app from an image by mentioning port and app name. It starts in seconds. It can be started or stopped.

> It is cool

Containers are the 2.0 version of Virtualization.
Microservices are enabled with containers. Each app service can run in it’s own containers. Cloud native also means running containers with microservices on your premises.

## Docker

Nigel has a book on this subject.
Dock Worker = Docker

Containerized services for businesses and orchestrating them.

Containers are light VMs. Docker makes running apps inside containers really easy. 

Community Edition. Enterprise Edition. Containerized Apps.

Take an app > create image > push to registry > create a container

### Key to modern apps. 
Apps in Containers. Microservices that are cloud native.

Doing this at scale >>> Docker Swarm || **Kubernetes**

## Kubernetes
Cloud native computing foundation.
Amazon, Azure, Google - good cloud platforms
Onprem
Enterprise class support

Stateless, stateful, batch, security, serverless, machine learning. 

It can do anywhere.

Laptop development environment.

It’s name means helmsman. K8s.

Scheduling, Scaling, healing, updating...

Kubernetes cluster - with bunch of nodes. k8s software & container runtime. sitting above is brains of k8s control plane. When load goes up on nodes, k8s will automatically distribute the load to other nodes.

It is also self-healing on nodes.

Moving the app cluster between clouds on-prem or otherwise is a cinch.

Maintaining containerized apps at scale.

## Prep to thrive in a container world

Get your hands dirty. Docker desktop. Play with (docker | kubernetes) links online.
Many related pluralsight courses of course.

Talk to various teams. Have a small team initiative with a SWAT team.

Logging and Monitoring.

Talk! Prepare!

## Suitable Workloads

Types of applications that containers are good for or not.

D & K are good at both stateful and stateless. Have added features for stateful apps.
Stateful - has to remember stuff.
Stateless - does not remember stuff.

Develop apps that are...
- modern
- scalable
- portable
- self-healing 

Docker Inc. lift and shift. modernizing legacy/vintage/heritage apps.

> Get ready for change.

## Enterprise and Production readiness

Docker
- Community and Enterprise editions.
- EE gets a ton of stuff. Private regs. FIPS. Support etc.

Kubernetes
- On Prem
- Cloud 
    - Azure, Google, AWS
- Alpha, beta, GA
- Open source

They have a sizable ecosystem.

## Orchestration

Like a football team players have different roles. Coach orchestrates.

Have a game plan. Describe the app and it's pieces.
Ensure startups and scheduling. Give key to k8s. Orchestrator manages the app.
App manifest is the gameplan. Services are the players.

## Next Steps

Courses. Books. Online playgrounds. Events. 
Nigel Poulton is the author.
 
