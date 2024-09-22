Here’s a comprehensive list of Kubernetes YAML files categorized by their purpose:

# Core Resources
1. Pod
2. ReplicaSet
3. Deployment
4. DaemonSet
5. StatefulSet
6. Job
7. CronJob
8. Service
9. Endpoints
10. EndpointsSlice
11. Namespace
12. Node
13. PersistentVolume
14. PersistentVolumeClaim
# StorageClass
15. Configuration and Secrets
16. ConfigMap
17. Secret
18. LimitRange
19. ResourceQuota
20. PodDisruptionBudget
# Networking
21. Ingress
22. IngressClass
23. NetworkPolicy
24. ServiceMonitor (Prometheus Operator)
25. ServiceProfile (Linkerd)
26. Gateway (Gateway API)
27. HTTPRoute (Gateway API)
28. EndpointSlice
# Security
29. Role
30. ClusterRole
31. RoleBinding
32. ClusterRoleBinding
33. ServiceAccount
34. PodSecurityPolicy
35. NetworkPolicy
# Custom Resources
36. Custom Resource Definition (CRD)
37. Custom Resource
# Admission Control
38. MutatingWebhookConfiguration
39. ValidatingWebhookConfiguration
40. AdmissionWebhookConfiguration
41. TokenReview
42. SelfSubjectAccessReview
43. SelfSubjectRulesReview
# Monitoring and Metrics
44. PrometheusRule (Prometheus Operator)
45. AlertmanagerConfig (Alertmanager Operator)
# Scheduling and Autoscaling
46. HorizontalPodAutoscaler
47. PriorityClass
48. PodTemplate
49. NodeAffinity (part of Pod spec)
# Storage Management
50. VolumeSnapshot
51. VolumeSnapshotClass
52. CSIDriver
53. VolumeAttachment
# Configuration Management
54. KubeletConfiguration
55. KubeProxyConfiguration
# Miscellaneous
56. CertificateSigningRequest (CSR)
57. SecretProviderClass (used with Secrets Store CSI Driver)
58. PodSecurityAdmission (for Pod Security Standards)