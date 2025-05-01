# Glossary
A collection of simple, easy to remember definitions.

## Deployment
A resource that manages a set of [pods](#pod) to run an application based on a *declared state*.

## Pod
1. **Smallest** deployable unit in kubernetes.
2. A collection of *one or more* containers that share storage and network resources, acting as a single unit.

## ReplicaSet
A low level resource that maintains a stable number of identical replica [pods](#pod), replacing any that fail or terminate. 
