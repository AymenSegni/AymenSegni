# Aymen Segni

I am a Principal Platform Engineer and Cloud Architect based in Berlin. I build the infrastructure that makes production AI systems reliable, and the internal platforms that let product engineers ship without waiting on operations.

**Currently:** Principal Engineer for ML, Data and Platform Engineering at Roam. Founder of [Shipmoor](https://shipmoor.dev), and Founder & Principal Consultant at [Drizzle Systems](https://drizzle.systems). Previously Deputy Head of Cloud and SRE at Spryker.

Open to Principal/Staff IC and hands-on engineering leadership roles  in AI platforms, ML infrastructure, or Platform Engineering. Also available for consulting, freelance, and advisory engagements (architecture reviews, platform builds, or fractional tech-leadership)
If you're building an AI-native platform and need someone who's done it before, let's talk: work.aymen.segni@gmail.com

## What I work on

- **Agentic AI infrastructure.** Serving layers for autonomous agents and reasoning loops on Kubernetes, built with vLLM, KServe, and KubeRay. I also build MCP servers that let agents operate cloud accounts, and I decide what that surface is allowed to do.
- **Platform engineering.** Internal developer platforms with self-service provisioning and golden paths. I have established them from greenfield at Spryker, AUTO1, and ING.
- **Reliability and cost.** SLO programs, incident practice, and observability rebuilds. At Spryker, I cut platform cost by 1.5 million dollars a year, and the result was then sold to five enterprise customers as a product.

## Shipmoor

I founded [Shipmoor](https://shipmoor.dev), a verification platform for code written by AI agents.

Blocking verdicts come only from deterministic probes. Model inference never decides a verdict. Evidence ships as in-toto attestations, and two runs are compared byte for byte rather than trusting a rerun. The command line tool, a VS Code extension, and an agent harness are shipped. An AI lab runs it daily in continuous integration.

## Community

Member of [Kubernetes SIGs](https://github.com/kubernetes-sigs), the [Gateway API Inference Extension](https://github.com/kubernetes-sigs/gateway-api-inference-extension) working group, and the [Knative Serving](https://github.com/knative) working group.

Acknowledged by the Microsoft Security Response Center for co-disclosing an AKS privilege-escalation misconfiguration in 2020, fixed and backported across releases.

Lightning talk, Berlin 2025: self-hosting DeepSeek-R1 on AWS EKS with vLLM for inference, KubeRay for distributed scaling, and Terraform with Karpenter for infrastructure.

## Selected milestones

- **2026 to now, Roam AI.** Own the platform and data architecture end to end. This includes hybrid GPU-accelerated Kubernetes on bare metal and a customer-hosted deployment built for data residency.
- **2022 to 2025, Spryker.** Designed AI infrastructure for multi-GPU, multi-agent, and multi-LLM workloads. Rebuilt the observability stack on OpenTelemetry, Prometheus, and Grafana with Loki and Tempo, saving 1.5 million dollars a year. Operated more than 300 customer AWS environments across more than 3,000 services. Delivered an internal developer platform on Terraform, GitHub Actions, Atlantis, and Argo CD.
- **2022, AUTO1.** Led five staff SREs. Rolled out an SLO operating model that hundreds of service teams adopted, across more than 5,000 microservices.
- **2020 to 2022, ING and Lendico.** Led the cloud-native transformation on Azure AKS. Built in-house infrastructure tooling and GitOps for a regulated banking subsidiary.
- **2019 to 2020, Deutsche Bank and Yunar.** Ran about 1000 microservices on Azure AKS with an Istio service mesh and a full SLO practice.

## Selected open source

**Python**

- [AWS MCP Gateway](https://github.com/AymenSegni/aws-mcp-gateway)
- [Pre-commit SOPS Hook](https://github.com/drizzle-ai-systems/pre-commit-sops)
- [ZFS File Storage Manager API](https://github.com/AymenSegni/zfs-manager-api)
- [Incident Manager Slack Bot](https://github.com/AymenSegni/py_incident_bot)

**Kubernetes operators**

- [Kube Admission Controller](https://github.com/AymenSegni/kube-admission-controller)
- [Hibernates](https://github.com/AymenSegni/hibernates) (work in progress)

**Terraform**

- [vLLM EKS Helm Module](https://registry.terraform.io/modules/drizzle-ai-systems/terraform-aws-vllm-eks-helm)
- [EKS vLLM Production Stack Blueprint](https://github.com/drizzle-ai-systems/eks-vllm-production-stack-terraform-blueprint)
- [AWS OpenID Connect for GitHub Actions](https://registry.terraform.io/modules/drizzle-ai-systems/oidc-github-actions/aws/latest)
- [Linkerd2 Helm Module](https://registry.terraform.io/modules/AymenSegni/linkerd2/helm/latest)
- [GKE and PostgreSQL Terraform](https://github.com/AymenSegni/gcp-gke-terraform-k8s)

## Expertise

- **AI infrastructure:** vLLM, KServe, KubeRay, MLflow, LangGraph, MCP and FastMCP, Vertex AI, GPU scheduling, NVIDIA drivers on bare metal, fine-tuning with LoRA and quantization
- **Cloud:** AWS, Google Cloud, Azure, Hetzner, OpenStack
- **Kubernetes:** EKS, GKE, AKS, K3S, bare metal, operators and CRDs with Kubebuilder, Karpenter, KEDA, Istio, Linkerd
- **Platform engineering:** Backstage, Argo CD, Atlantis, internal developer platforms, golden paths
- **Infrastructure as code:** Terraform, Terragrunt, Ansible, Kustomize, Helm, GitHub Actions
- **Observability and SRE:** OpenTelemetry, Prometheus, Grafana with Loki, Tempo, and Mimir, Datadog, SLOs, error budgets, incident management
- **Data:** PostgreSQL, Redis, Elasticsearch, ClickHouse, Kafka, Ceph
- **Security and compliance:** SOC 2, ISO 27001, OPA Gatekeeper, Kyverno, HashiCorp Vault, supply chain security
- **Languages:** Python, Go, TypeScript

## Certifications

Google Cloud Professional Cloud Architect (2019). Google Cloud Associate Cloud Engineer (2018).

## Contact

- Website: [aymen-segni.com](https://aymen-segni.com) and [drizzle.systems](https://drizzle.systems)
- LinkedIn: [linkedin.com/in/aymen-segni](https://www.linkedin.com/in/aymen-segni)
- X: [@axsegni](https://x.com/axsegni)
