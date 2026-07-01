# DevOps Interview Prep

Interactive HTML interview guides covering the tools and practices I've worked with as a DevOps engineer — Karpenter, GitOps with ArgoCD + Kargo, and a full 2-day interview war room.

These guides are self-contained HTML files. Open them directly in a browser — no server needed.

## Guides

### [Karpenter Deep Dive](karpenter-study-guide.html)
A tabbed reference guide covering everything about Karpenter v1:
- Why Karpenter vs Cluster Autoscaler (side-by-side comparison)
- How the provisioning and consolidation loops work
- NodePool and EC2NodeClass configuration with annotated YAML
- Disruption policies, drift, and node expiry
- Spot handling — interruption flow, CreateFleet strategy
- Real-world two-NodePool architecture (system vs application)

### [GitOps Interview Guide](gitops-interview-guide.html)
Deep dive into the GitOps stack with ArgoCD and Kargo:
- GitOps principles and push vs pull-based CD
- ArgoCD core concepts, App of Apps pattern, sync waves
- Kargo — Warehouse, Freight, Stage, promotion templates
- Real Blinq.IO pipeline (11 warehouses, 14 stages, dev → stage → prod)
- ECR image copy flow across accounts
- Mock Q&A with model answers

### [2-Day Interview War Room](interview-war-room.html)
A structured 2-day prep plan with checklists and STAR stories:
- **Day 1**: AWS cost optimization ($16K → $8K), Kubernetes & EKS, GitOps, Observability
- **Day 2**: Terraform & IaC, CI/CD (GitHub Actions + Jenkins), AWS services, Behavioral
- Savings breakdown table per initiative (Inspector, GuardDuty, CloudWatch IA, EKS consolidation, Karpenter)
- Pre-built STAR stories for cost reduction and incident response
- Likely interview questions with model answers
- Live readiness tracker that updates as you check off topics

## How to use

```bash
# Open any guide in your browser
open karpenter-study-guide.html
open gitops-interview-guide.html
open interview-war-room.html
```

Or clone and open from GitHub Pages once the repo is published.

## About

Built by [Megha Shivhare](https://github.com/MeghaShivhare) — DevOps engineer with experience at Blinq.IO and C&R Software, working with EKS, Karpenter, ArgoCD, Kargo, Terraform, and GitHub Actions.

The numbers in these guides (50% AWS cost reduction, specific YAML configs, pipeline counts) reflect real implementations — not theoretical examples.
