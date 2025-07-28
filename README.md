# Awesome Cilium 🚀

> A curated list of awesome resources, tools, articles, and projects related to Cilium and its ecosystem.

---

## Table of Contents

* [💡 About This List](#-about-this-list)
* [✨ Categories](#-categories)
    * [Official Resources](#official-resources)
    * [Getting Started & Tutorials](#getting-started--tutorials)
    * [Articles & Blog Posts](#articles--blog-posts)
    * [Talks & Presentations](#talks--presentations)
    * [Integrations & Tools](#integrations--tools)
    * [Use Cases & Case Studies](#use-cases--case-studies)
    * [eBPF Deep Dives (Cilium Context)](#ebpf-deep-dives-cilium-context)
    * [Community](#community)
* [💖 Contributing](#-contributing)
* [License](#license)
* [Acknowledgements](#acknowledgements)

---

## 💡 About This List

This list is a community-driven effort to gather the most valuable and high-quality resources for anyone working with, learning about, or interested in **Cilium**. Cilium is a powerful open-source project for providing, securing, and observing network connectivity between workloads in cloud-native environments, leveraging the revolutionary Linux kernel technology eBPF.

Whether you're looking for:
* Official documentation
* Hands-on tutorials
* Deep dives into eBPF concepts as applied by Cilium
* Real-world use cases and success stories
* Community discussions and events

We aim to make it easy to find what you need. Each entry includes a direct link and a concise, informative description.

---

## ✨ Categories

### Official Resources

* **Cilium Website** - The official homepage for the Cilium project, with links to documentation, use cases, and community.
    * [https://cilium.io/](https://cilium.io/)
* **Cilium GitHub Repository** - The main source code repository for Cilium.
    * [https://github.com/cilium/cilium](https://github.com/cilium/cilium)
* **eBPF.io** - The official website for eBPF, a core technology behind Cilium, offering a wealth of information about eBPF itself.
    * [https://ebpf.io/](https://ebpf.io/)
* **Hubble GitHub Repository** - The repository for Hubble, the observability platform built on Cilium and eBPF.
    * [https://github.com/cilium/hubble](https://github.com/cilium/hubble)
* **Tetragon GitHub Repository** - The repository for Tetragon, a flexible Kubernetes-aware security observability and runtime enforcement tool using eBPF.
    * [https://github.com/cilium/tetragon](https://github.com/cilium/tetragon)

### Getting Started & Tutorials

* **Cilium Getting Started Guide** - Official documentation for quickly deploying and experimenting with Cilium.
    * [https://docs.cilium.io/en/stable/gettingstarted/](https://docs.cilium.io/en/stable/gettingstarted/)
* **Interactive Cilium Labs** - Hands-on, browser-based labs to explore various Cilium features without a local setup.
    * [https://labs.cilium.io/](https://labs.cilium.io/)
* **Kubernetes Network Policies in Action with Cilium** - A practical guide to implementing network policies using Cilium.
    * [Link to Article/Video]
* **Deploying Cilium on [Your Favorite Cloud/Platform]** - A specific tutorial for setting up Cilium on AWS EKS, Google GKE, Azure AKS, K3s, etc.
    * [Link to Resource]

### Articles & Blog Posts

* **Understanding Cilium's eBPF Dataplane** - A detailed blog post explaining how Cilium leverages eBPF for networking.
    * [Link to Article]
* **Cilium and Kube-Proxy Replacement** - An article discussing how Cilium can replace `kube-proxy` for improved performance and scalability.
    * [Link to Article]
* **Service Mesh with Cilium and Envoy** - Exploring Cilium's capabilities as a service mesh or in conjunction with Envoy.
    * [Link to Article]
* **Transparent Encryption with Cilium** - How Cilium provides transparent encryption for pod-to-pod communication.
    * [Link to Article]

### Talks & Presentations

* **KubeCon North America [Year]: Cilium Deep Dive** - Video and slides from a major conference deep diving into Cilium.
    * [Link to Video/Slides]
* **eBPF Summit [Year]: Beyond Networking with Cilium & eBPF** - A presentation showcasing advanced use cases of Cilium.
    * [Link to Video/Slides]
* **CiliumCon [Year] Keynotes & Sessions** - Links to recordings or summaries of key talks from official Cilium conferences.
    * [Link to Event Page/Playlist]

### Integrations & Tools

* **Prometheus & Grafana for Cilium Metrics** - How to set up monitoring and visualization for Cilium.
    * [Link to Guide/Dashboard Repo]
* **Cilium Helm Charts** - Official and community-maintained Helm charts for deploying Cilium.
    * [Link to Helm Repo/Docs]
* **Cilium + Istio Integration** - Resources on running Cilium as the CNI for an Istio service mesh.
    * [Link to Docs/Article]
* **NetworkPolicy Editor for Kubernetes & Cilium** - A tool or guide for visualizing and creating network policies.
    * [Link to Tool/Resource]

### Use Cases & Case Studies

* **[Company Name] Uses Cilium for [Problem Solved]** - A case study detailing how a company leverages Cilium in production.
    * [Link to Case Study/Blog Post]
* **Multi-Cluster Networking with Cilium Cluster Mesh** - Real-world examples or guides on connecting multiple Kubernetes clusters with Cilium.
    * [Link to Article/Demo]
* **Edge Deployments with Cilium** - How Cilium is used in edge computing scenarios.
    * [Link to Article/Presentation]

### eBPF Deep Dives (Cilium Context)

* **Learning eBPF: From Basics to Advanced** - Resources that explain eBPF concepts specifically relevant to how Cilium utilizes them.
    * [Link to Resource]
* **Cilium's BPF and XDP Reference Guide** - In-depth documentation on Cilium's specific eBPF and XDP implementations.
    * [Link to Docs]
* **Understanding Cilium's Dataplane with eBPF (Advanced)** - A highly technical explanation of Cilium's interaction with the Linux kernel via eBPF.
    * [Link to Resource]

### Community

* **Cilium Slack Channel** - Join the official Cilium Slack workspace for community discussions and support.
    * [Link to Slack Invite]
* **Cilium Mailing List / Forum** - For broader discussions and announcements.
    * [Link to Mailing List/Forum]
* **Cilium Community Meetings** - Information about regular community calls and how to participate.
    * [Link to Meeting Info]

---

## 💖 Contributing

We thrive on community contributions! If you know of an awesome Cilium-related resource that isn't on this list, or if you find any broken links or inaccuracies, please help us keep this list up-to-date and valuable.

To contribute:

1.  **Fork** this repository.
2.  **Clone** your forked repository: `git clone https://github.com/your-username/awesome-cilium.git`
3.  Create a new **branch**: `git checkout -b add/new-resource-name` (or `fix/broken-link`)
4.  **Add** your resource to the most appropriate category, ensuring it follows the existing formatting (`* **Resource Name** - Brief description. [Link]`).
5.  **Commit** your changes: `git commit -m "feat: Add [Resource Name] to [Category]"`
6.  **Push** to your branch: `git push origin add/new-resource-name`
7.  Open a **Pull Request**.

Please read our **[CONTRIBUTING.md](CONTRIBUTING.md)** for detailed guidelines, including criteria for inclusion (e.g., must be Cilium-specific or highly relevant) and formatting standards.

---

## License

This project is licensed under the **[MIT License](LICENSE)** - see the [LICENSE](LICENSE) file for details.

---

## Acknowledgements

* Inspired by the [Awesome List](https://github.com/sindresorhus/awesome) project by Sindre Sorhus.
* Special thanks to the entire Cilium community and all contributors who help keep this list comprehensive and up-to-date!

---
