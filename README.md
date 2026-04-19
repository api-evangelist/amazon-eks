# Amazon EKS (amazon-eks)
Amazon Elastic Kubernetes Service (Amazon EKS) is a managed Kubernetes service that makes it easy to run Kubernetes on AWS without needing to install, operate, and maintain your own Kubernetes control plane or nodes. Amazon EKS runs upstream Kubernetes and is certified Kubernetes conformant, so you can use existing tools and plugins from partners and the Kubernetes community.

**URL:** [Visit APIs.json URL](https://aws.amazon.com/eks/)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - AWS, Container Orchestration, Containers, EKS, Kubernetes

## Timestamps

- **Created:** 
- **Modified:** 2026-04-19

## APIs

## Common Properties

- [Portal](https://aws.amazon.com/)
- [DeveloperPortal](https://aws.amazon.com/eks/)
- [Docs](https://docs.aws.amazon.com/)
- [Terms](https://aws.amazon.com/service-terms/)
- [Privacy](https://aws.amazon.com/privacy/)
- [Support](https://aws.amazon.com/support/)
- [Blog](https://aws.amazon.com/blogs/containers/)
- [GitHub](https://github.com/aws)
- [Console](https://console.aws.amazon.com/eks/)
- [SignUp](https://portal.aws.amazon.com/billing/signup)
- [Login](https://signin.aws.amazon.com/)
- [StatusPage](https://health.aws.amazon.com/health/status)
- [KnowledgeCenter](https://repost.aws/knowledge-center)
- [YouTube](https://www.youtube.com/user/AmazonWebServices)
- [StackOverflow](https://stackoverflow.com/questions/tagged/amazon-eks)
- [Contact](https://aws.amazon.com/contact-us/)
- [Security](https://aws.amazon.com/security/)
- [Compliance](https://aws.amazon.com/compliance/)
- [SpectralRules](rules/amazon-eks-spectral-rules.yml)
- [Vocabulary](vocabulary/amazon-eks-vocabulary.yaml)
- [NaftikoCapability](capabilities/eks-management.yaml)

## Features

| Name | Description |
|------|-------------|
| Managed Control Plane | AWS manages the Kubernetes control plane across multiple Availability Zones with automatic upgrades. |
| EKS Auto Mode | Automates cluster infrastructure management for compute, storage, and networking with machine learning optimization. |
| EKS Hybrid Nodes | Connect on-premises and edge infrastructure to EKS clusters for unified management. |
| Fargate Integration | Run Kubernetes pods on serverless compute without managing EC2 node groups. |
| Managed Node Groups | Automate provisioning and lifecycle management of EC2 nodes for Kubernetes clusters. |
| EKS Anywhere | Deploy and manage Kubernetes clusters on customer-managed infrastructure including on-premises. |
| Add-Ons Management | Manage operational software add-ons like VPC CNI, CoreDNS, and kube-proxy through EKS. |

## Use Cases

| Name | Description |
|------|-------------|
| Generative AI Applications | Scale production-grade AI deployments with GPU nodes for distributed training and inference. |
| Microservices Architecture | Deploy and manage containerized microservices with Kubernetes-native service discovery and scaling. |
| Internal Developer Platforms | Standardized Kubernetes environments combining open source with AWS managed services. |
| Hybrid Cloud Applications | Unified Kubernetes management across AWS cloud and on-premises infrastructure. |
| Data Processing Platforms | Scalable batch processing and streaming data workloads using Spark, Flink, or Ray. |

## Integrations

| Name | Description |
|------|-------------|
| Amazon ECR | Pull container images from ECR for Kubernetes workloads with native IAM authentication. |
| AWS Load Balancer Controller | Manage Application and Network Load Balancers for Kubernetes Ingress resources. |
| Amazon EFS CSI Driver | Mount EFS file systems as Kubernetes persistent volumes for stateful applications. |
| AWS IAM Roles for Service Accounts | Grant Kubernetes pods fine-grained IAM permissions using OIDC-based service account annotations. |
| Amazon CloudWatch Container Insights | Collect and analyze metrics, logs, and traces from EKS clusters and workloads. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Amazon Eks](openapi/amazon-eks-openapi.yml)

### JSON Schema

- [Amazon Eks Cluster](json-schema/amazon-eks-cluster-schema.json)
- [Eks Openapi Addon](json-schema/eks-openapi-addon-schema.json)
- [Eks Openapi Cluster](json-schema/eks-openapi-cluster-schema.json)
- [Eks Openapi Create Addon Request](json-schema/eks-openapi-create-addon-request-schema.json)
- [Eks Openapi Create Addon Response](json-schema/eks-openapi-create-addon-response-schema.json)
- [Eks Openapi Create Cluster Request](json-schema/eks-openapi-create-cluster-request-schema.json)
- [Eks Openapi Create Cluster Response](json-schema/eks-openapi-create-cluster-response-schema.json)
- [Eks Openapi Create Fargate Profile Request](json-schema/eks-openapi-create-fargate-profile-request-schema.json)
- [Eks Openapi Create Fargate Profile Response](json-schema/eks-openapi-create-fargate-profile-response-schema.json)
- [Eks Openapi Create Nodegroup Request](json-schema/eks-openapi-create-nodegroup-request-schema.json)
- *...and 20 more*

### JSON Structure

- [Amazon Eks Cluster](json-structure/amazon-eks-cluster-structure.json)
- [Eks Openapi Addon](json-structure/eks-openapi-addon-structure.json)
- [Eks Openapi Cluster](json-structure/eks-openapi-cluster-structure.json)
- [Eks Openapi Create Addon Request](json-structure/eks-openapi-create-addon-request-structure.json)
- [Eks Openapi Create Addon Response](json-structure/eks-openapi-create-addon-response-structure.json)
- [Eks Openapi Create Cluster Request](json-structure/eks-openapi-create-cluster-request-structure.json)
- [Eks Openapi Create Cluster Response](json-structure/eks-openapi-create-cluster-response-structure.json)
- [Eks Openapi Create Fargate Profile Request](json-structure/eks-openapi-create-fargate-profile-request-structure.json)
- [Eks Openapi Create Fargate Profile Response](json-structure/eks-openapi-create-fargate-profile-response-structure.json)
- [Eks Openapi Create Nodegroup Request](json-structure/eks-openapi-create-nodegroup-request-structure.json)
- *...and 20 more*

### JSON-LD

- [Amazon Eks](json-ld/amazon-eks-context.jsonld)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Eks](capabilities/shared/eks.yaml) — 66 operations

### Workflow Capabilities

| Workflow | Tools | Persona |
|----------|-------|---------|
| [Eks Management](capabilities/eks-management.yaml) | 10 | managing EKS clusters, node groups, Fargate profiles, and add-ons for platform engineers |

## Vocabulary

- [Amazon EKS Vocabulary](vocabulary/amazon-eks-vocabulary.yaml) — Unified taxonomy mapping 1 resources, 0 actions, 1 workflows, and 1 personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [Amazon Eks Spectral Rules](rules/amazon-eks-spectral-rules.yml) — 28 rules enforcing Amazon EKS API conventions

## Maintainers

**FN:** Kin Lane
