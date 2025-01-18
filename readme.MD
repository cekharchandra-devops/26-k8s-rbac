# Role-Based Access Control (RBAC) in Kubernetes
Role-Based Access Control (RBAC) is a method of regulating access to resources based on the roles of individual users within an organization. In Kubernetes, RBAC is used to control who can perform actions on resources in the cluster.

Key Concepts

Role:

Defines a set of permissions within a namespace.
Permissions are specified as rules that determine what actions can be performed on which resources.

ClusterRole:

Similar to a Role, but it applies cluster-wide.
Can be used to grant permissions across all namespaces or for cluster-scoped resources.

RoleBinding:

Associates a Role with a user or group within a specific namespace.
Grants the permissions defined in the Role to the specified user or group.

ClusterRoleBinding:

Associates a ClusterRole with a user or group cluster-wide.
Grants the permissions defined in the ClusterRole to the specified user or group.