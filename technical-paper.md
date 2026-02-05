# Scaling

## Introduction

When I joined a new project, the application was facing performance and scaling issues. During high traffic, response time increased and some services became slow. After analysis, the team lead asked me to study scaling techniques and the role of load balancers. Scaling helps applications handle increased load while maintaining performance and availability.

## What Is Scaling

Scaling is the process of increasing or decreasing system resources to handle changes in workload. It allows applications to support more users without failure.

### Two types of Scaling are

### Vertical Scaling

Vertical scaling means increasing the capacity of a single server.

### Key Points

* Add more CPU, RAM, or storage to one machine.
* Easy to implement.
* Limited by hardware capacity.
* Downtime may be required.

### Example

Upgrading a server from 8 GB RAM to 32 GB RAM to handle more requests.

### Horizontal Scaling

Horizontal scaling means adding more servers to the system.

### Key Points

* Multiple servers share the workload.
* High availability and fault tolerance.
* No single point of failure.
* Requires a load balancer.

### Example

Running multiple application servers instead of one powerful server.

## Load Balancers

A load balancer distributes incoming traffic across multiple servers to prevent overload.

### Benefits

* Improved performance.
* Better reliability.
* Efficient traffic distribution.

### Load Balancing Algorithms

* Round Robin
* Least Connections
* IP Hash

## Conclusion

Vertical scaling is simple but limited. Horizontal scaling provides better scalability and availability. Load balancers are essential for distributing traffic and maintaining system stability. Modern applications prefer horizontal scaling with load balancing to support growth.

## References

* https://www.geeksforgeeks.org/software-engineering/overview-of-scaling-vertical-and-horizontal-scaling/
* https://www.cloudflare.com/learning/performance/what-is-load-balancing/
