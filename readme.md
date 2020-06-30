## Summary:
This repo is a collection of JSON files designed for automating the monitoring of Kubernetes in Dynatrace, with the BizOpsConfigurator.

## Contents:
* managementZone_kubernetes-namespace.json - Template for configuring a Management Zone for each Kubernetes Namespace
* managementZone_kubernetes-cluster.json - Template for configuraing a Management Zone for the entire Kubernetes Cluster
* taggingRule_kubernetes-namespace.json - Creates a tagging rule for 1 tag with a value for each Kubernetes Namespace
* taggingRule_kubernetes-pod.json - Creates a tagging rule for 1 tag with a value for each Kubernetes Base Pod
* dashboard_kubernetes-namespace.json - Creates a dashboard template for viewing a Kubernetes Namespace

## Variables:
### managementZone_kubernetes-namespace.json:
* managementZone_id -> unique 64 bit identifier of management zone
* managementZone_name -> unique name of management zone
* kubernetes_cluster-name -> name of kubernetes cluster as configured in Dynatrace
* kubernetes_cloud-type -> cloud type for kubernetes cluster nodes
* kubernetes_namespace -> kubernetes namespace for management zone

### managementZone_kubernetes-cluster.json:
* managementZone_id -> unique 64 bit identifier of management zone
* managementZone_name -> unique name of management zone
* kubernetes_cluster-name -> name of kubernetes cluster as configured in Dynatrace
* kubernetes_cloud-type -> cloud type for kubernetes cluster nodes
