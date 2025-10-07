# 🌐 byepast-net

Welcome to the **byepast-net** GitHub organization —  
a collection of modular services, apps, and libraries that power our products.

Our architecture is built around **small, focused components**, making it easy to scale, maintain, and reuse functionality across multiple frontends, backends, and internal tools.

---

## 🚀 Mission

We build modern, performant, and user-friendly digital solutions.  
Our codebase is designed to be **clean, modular, and transparent**, enabling both internal teams and open-source contributors to navigate easily.

---

## 🧭 Repository Structure

To keep things clear and consistent, repositories follow a naming convention based on their **responsibility**:

| Prefix         | Type                     | Purpose                                                                 |
|---------------|---------------------------|-------------------------------------------------------------------------|
| `app-*`       | Applications              | User-facing frontends (web, admin, mobile, etc.)                        |
| `svc-*`       | Services / Backends       | Small, domain-specific APIs (e.g. auth, tickets, timelines)             |
| `lib-*`       | Libraries & SDKs          | Shared code, SDKs, design systems, schemas                              |
| `infra-*`     | Infrastructure            | Terraform, Helm charts, CI/CD, environment definitions                  |
| `ops-*`       | Operational Tooling       | Observability, security, monitoring, SRE utilities                      |
| `template-*`  | Templates / Boilerplates | Skeleton projects for bootstrapping new apps or services quickly       |

### 🗂 Example Layout

```
├── app-website            # Public website (landing page, blog, project previews)
├── app-customer-portal    # Authenticated customer frontend
├── app-admin-console      # Internal admin dashboard
│
├── svc-auth               # Authentication & authorization
├── svc-tickets            # Ticketing system
├── svc-timelines          # Customer timelines & activity
├── svc-api-gateway        # API gateway & BFF
│
├── lib-design-system      # Reusable UI components and styles
├── lib-sdk-js             # TypeScript SDK for frontend apps
├── lib-domain             # Shared domain types, events, and schemas
│
├── infra-terraform        # Terraform IaC for cloud resources
├── infra-charts           # Helm charts and K8s manifests
├── infra-ci               # Centralized CI/CD workflows
│
├── ops-observability      # Monitoring, logging, tracing configs
├── ops-security           # Security policies and scanners
│
├── template-service       # Boilerplate for a new service
└── template-app           # Boilerplate for a new app
```

---

## 🧠 Philosophy

- **Small, focused repositories** → Easier ownership, testing, and scaling.  
- **Clear contracts** → Each service exposes OpenAPI/AsyncAPI specs.  
- **Shared domain** → Common types and events live in `lib-*`.  
- **Automation-first** → Infrastructure and CI/CD are fully versioned and reproducible.

---

## 🧰 Tech Stack

While each service or app may use its own tools, the common stack includes:

- **Frontend:** Next.js / React / Tailwind CSS  
- **Backend:** Modern languages & frameworks (e.g. Go, C#, Java Spring Boot, Rust)  
- **Infra:** Kubernetes, Terraform, Helm, GitHub Actions  
- **APIs:** REST + event-driven messaging

---

## 🤝 Contributing

We welcome contributions — whether it's bug reports, ideas, or pull requests.  
Before starting, please:

- Read the [Contribution Guide](CONTRIBUTING.md) *(to be added)*  
- Follow the naming conventions above  
- Keep PRs focused and well-described

---

## 🛡 License

Each repository may specify its own license. Unless otherwise stated, code is provided under the **MIT License**.

---

## 🌍 More Info

👉 Website: [https://byepast.net](https://byepast.net)  
👉 Blog: Coming soon  
👉 Contact: [contact@byepast.net](mailto:contact@byepast.net)
