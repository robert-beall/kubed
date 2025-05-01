# Clusters
A set of nodes (worker machines) that run containerized applications.

Every cluster has at least *one* worker node.

## Components of a Cluster
Every cluster has the following parts:

- A Control Plane
- Worker Nodes
  - Each node runs processes

### Control Plane
Coordinates all activities in a cluster

Responsibilities include:
- Scheduling applications
- Scaling applications
- Maintaining desired state of applications
- Rolling out new updates

### Node
A VM or physical computer that acts as a worker machine in a kubernetes cluster.


