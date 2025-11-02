# Realm9 Terraform Integration

> Native Terraform Lifecycle Management with AI-Powered Infrastructure as Code

[![Terraform](https://img.shields.io/badge/terraform-compatible-purple)](https://www.terraform.io/)
[![OpenTofu](https://img.shields.io/badge/opentofu-compatible-blue)](https://opentofu.org/)
[![AI](https://img.shields.io/badge/AI-powered-green)](https://github.com/realm9-platform/realm9)

## Overview

Realm9's Terraform integration provides enterprise-grade infrastructure as code management with unique AI-powered capabilities that go far beyond traditional Terraform Cloud or Atlantis solutions.

## Key Differentiators

### 🤖 Natural Language to Terraform
```bash
"Create a production Kubernetes cluster with 3 master nodes and auto-scaling workers"
→ Complete, production-ready Terraform configuration in seconds
```

### 🔧 Intelligent Error Resolution
- AI analyzes Terraform errors and automatically fixes them
- Learns from your infrastructure patterns
- Suggests optimizations based on best practices

### 🚀 GitOps Native Workflows
- Auto-plan on pull requests
- Visual plan reviews with cost estimates
- Drift detection and auto-remediation
- Policy as code enforcement

## Features

### Core Capabilities
- **Full Terraform Lifecycle**: Plan, Apply, Destroy, Import, State Management
- **Workspace Management**: Isolated workspaces with variable inheritance
- **Module Registry**: Private module registry with versioning
- **State Backends**: S3, Azure Blob, GCS with encryption
- **Concurrent Runs**: Queue management with priority scheduling

### Advanced Features
- **AI Code Generation**: Natural language to HCL conversion
- **Smart Error Fixing**: Automatic resolution of common Terraform errors
- **Cost Estimation**: Pre-apply cost analysis with budget alerts
- **Compliance Scanning**: Policy validation before deployment
- **Drift Detection**: Continuous monitoring with auto-remediation

## Examples

### Natural Language Examples

#### AWS VPC with Subnets
**Input**: "Create a VPC with public and private subnets across 3 AZs"

**Output**: Complete Terraform configuration with VPC, subnets, NAT gateways, and DNS settings following AWS best practices.

#### Kubernetes Cluster
**Input**: "Deploy a GKE cluster with 3 node pools for web, api, and database workloads"

**Output**: Production-ready GKE configuration with dedicated node pools, networking, and security policies.

### Module Library

#### Cloud Resources
- `aws-vpc` - Production-ready VPC with best practices
- `azure-aks` - Managed Kubernetes with monitoring
- `gcp-gke` - GKE with Workload Identity
- `multi-cloud-network` - Cross-cloud networking

#### Application Stack
- `microservices-base` - Complete microservices infrastructure
- `data-pipeline` - ETL infrastructure with Airflow
- `ml-platform` - ML/AI infrastructure setup

## Integration

### GitHub Integration
Realm9 provides seamless GitHub Actions integration for automated Terraform workflows:
- Automatic plan generation on pull requests
- Visual plan reviews with cost estimates
- Approval workflows with RBAC enforcement
- Policy validation before apply

### CLI Capabilities
The Realm9 CLI provides comprehensive Terraform workflow management:
- Workspace initialization and management
- Natural language code generation
- Cost estimation before infrastructure changes
- Multi-stage approval workflows
- Compliance policy validation

## Comparison

### vs Terraform Cloud

| Feature | Realm9 | Terraform Cloud |
|---------|--------|-----------------|
| Natural Language → Code | ✅ Yes | ❌ No |
| AI Error Resolution | ✅ Yes | ❌ No |
| Built-in Observability | ✅ Yes | ❌ No |
| Cost Estimation | ✅ Advanced | ⚠️ Basic |
| Self-Hosted Option | ✅ Yes | ⚠️ Limited |

### vs Atlantis

| Feature | Realm9 | Atlantis |
|---------|--------|----------|
| UI Dashboard | ✅ Full | ❌ None |
| AI Assistance | ✅ Yes | ❌ No |
| RBAC | ✅ Enterprise | ⚠️ Basic |
| Module Registry | ✅ Yes | ❌ No |
| Cost Analysis | ✅ Yes | ❌ No |

## Security

- **Encrypted State**: AES-256 encryption at rest
- **Secret Management**: Integration with Vault, AWS Secrets Manager
- **Audit Logging**: Complete terraform operation history
- **Policy Enforcement**: OPA policies before apply
- **RBAC**: Fine-grained permissions per workspace

## Documentation

- [Getting Started Guide](./docs/getting-started.md)
- [Module Development](./docs/modules.md)
- [Best Practices](./docs/best-practices.md)
- [API Reference](./docs/api.md)

---

Part of the [Realm9 Platform](https://github.com/realm9-platform/realm9)
