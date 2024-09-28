# 16 essentials of k8s

1. **High Availability**: Ensures that Kubernetes workloads continue running by distributing them across multiple nodes or zones, minimizing downtime.
2. **Namespaces**: Logical partitions in Kubernetes that allow separation and management of resources within the same cluster.
3. **Observability**: Provides insight into the cluster and workloads using tools for logging, monitoring, and tracing to detect and resolve issues.
4. **Self-healing**: Kubernetes automatically restarts or reschedules failed containers to ensure application uptime and stability.
5. **Abstraction**: Kubernetes abstracts infrastructure complexities, allowing developers to focus on application deployment rather than underlying hardware or cloud specifics.
6. **Extensibility**: Kubernetes can be extended through Custom Resource Definitions (CRDs) and APIs, enabling the platform to accommodate additional functionalities.
7. **Networking**: Handles internal and external communication for pods using virtual networks, Services, and ingress controllers.
8. **Distributed**: Kubernetes manages applications across distributed clusters, ensuring scalability and fault tolerance.
9. **Declarative**: Uses a declarative model where desired state is specified, and Kubernetes continuously works to match actual state to it.
10. **Scheduling**: Automatically assigns pods to nodes based on resource availability and other constraints to optimize workload distribution.
11. **Resources**: Represents compute power, memory, and other operational requirements allocated to containers, defined in Kubernetes using Resource Requests and Limits.
12. **Portability**: Enables applications to be moved across different environments, such as on-prem, cloud, or hybrid systems, without modification.
13. **Balancing**: Kubernetes balances traffic load across services and replicas using built-in load balancing mechanisms.
14. **Volumes**: Persistent or ephemeral storage attached to containers, allowing data persistence across pod lifecycles.
15. **Security**: Enforces security policies via role-based access control (RBAC), network policies, secrets management, and pod security policies.
16. **Scalability & Elasticity**: Automatically scales applications up or down based on demand using Horizontal Pod Autoscaling (HPA) and node scaling features.
