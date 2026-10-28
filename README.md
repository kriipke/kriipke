# Spencer Smolen

**DevOps / Platform Engineer · Kubernetes · GitOps · Developer tooling**

I build tools that make infrastructure easier to configure, changes easier to review, and development environments easier to reproduce. My work spans Kubernetes delivery, Helm chart generation, Vault secrets workflows, and Linux automation, with Go as my main language for platform tooling.

I'm open to **DevOps and platform engineering opportunities**, especially work on Kubernetes platforms, delivery automation, and developer experience.

## Selected work

| Project | What it does | Engineering focus |
| --- | --- | --- |
| [Chartpress](https://github.com/kriipke/chartpress) | Generates umbrella Helm charts and subcharts from one configuration, with Deployment, StatefulSet, and DaemonSet support. Provides a CLI, HTTP API, and web interface. | Go, Helm, Kubernetes operators, reusable templates |
| [GitOps repository template](https://github.com/kriipke/cookiecutter-gitops-multirepo) | Generates Argo CD ApplicationSets and per-cluster Helm values, separating application charts from environment configuration. Includes render checks and promotion workflows. | Argo CD, multi-cluster configuration, GitHub Actions, Python |
| [VaultSync](https://github.com/kriipke/vaultsync) | Syncs HashiCorp Vault KV v2 secrets with local YAML files. Supports HCP Vault namespaces, dry-run diffs, and reuse as a Go library. | Secrets management, CLI design, reusable Go APIs |
| [DriftMap](https://github.com/kriipke/driftmap) | Shows changed, added, and removed YAML values across files, directories, or Git refs, including Helm values and VaultSync exports. | Configuration review, drift detection, Go |
| [Provii](https://github.com/kriipke/provii) | Installs precompiled CLI tools using recipes that select assets by operating system, architecture, and Linux libc. Includes installation smoke tests on Linux and macOS. | Bash, environment setup, cross-platform automation |

## How I approach platform work

- **Make repeatable work reusable.** Turn setup steps into templates, CLI commands, and libraries that other developers can use.
- **Make changes inspectable.** Use configuration diffs, dry-run previews, and rendered manifests to help people understand a change before applying it.
- **Build verification into delivery.** Chartpress has a verification gate covering Go tests and vet, frontend tests and builds, Helm lint, generated charts, and archives. The GitOps template includes render gates and version promotion between environments.

My earlier [Terraform, Packer, and Rancher provisioning project](https://github.com/kriipke/terraform-rancher-ovirt) documents VM image preparation and Kubernetes cluster provisioning on oVirt.

## Find me

[GitHub](https://github.com/kriipke) · [Writing on Medium](https://medium.com/@spencersmolen)
