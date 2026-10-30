<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=1,6,11,20&height=220&section=header&text=Piyush%20Chauhan&fontSize=52&fontColor=ffffff&animation=fadeIn&subtext=DevOps%20Engineer%20%E2%80%A2%20Frontier%20LLM%20Benchmark%20%26%20Eval%20Specialist&subfontSize=18&subfontColor=d8b4fe" width="100%" />

  [![Gmail](https://img.shields.io/badge/Gmail-peeyushrajput321%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:peeyushrajput321@gmail.com)
  [![LinkedIn](https://img.shields.io/badge/LinkedIn-piyush--chauhan-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/piyush-chauhan-8a02a0251)
  [![GitHub](https://img.shields.io/badge/GitHub-pxyushch-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/pxyushch)
  [![Company](https://img.shields.io/badge/Company-Ethara.ai-7928CA?style=for-the-badge)]()
  [![Status](https://img.shields.io/badge/Focus-Frontier_AI_Evaluations_&_Cloud_Sandboxing-00C853?style=for-the-badge)]()

  <br />

  <!-- 🏆 Verified Achievements Quick-Bar -->
  <a href="https://github.com/pxyushch?tab=achievements"><img src="https://img.shields.io/badge/Galaxy%20Brain-Bronze-8B5CF6?style=for-the-badge&logo=github&logoColor=white" alt="Galaxy Brain" /></a>
  <a href="https://github.com/pxyushch?tab=achievements"><img src="https://img.shields.io/badge/YOLO-Unlocked-EF4444?style=for-the-badge&logo=gitpullrequest&logoColor=white" alt="YOLO" /></a>
  <a href="https://github.com/pxyushch?tab=achievements"><img src="https://img.shields.io/badge/Pull%20Shark-Silver-10B981?style=for-the-badge&logo=github&logoColor=white" alt="Pull Shark" /></a>
  <a href="https://github.com/pxyushch?tab=achievements"><img src="https://img.shields.io/badge/Quickdraw-Unlocked-F59E0B?style=for-the-badge&logo=lightning&logoColor=white" alt="Quickdraw" /></a>
  <a href="https://github.com/pxyushch?tab=achievements"><img src="https://img.shields.io/badge/Pair%20Extraordinaire-Bronze-06B6D4?style=for-the-badge&logo=github&logoColor=white" alt="Pair Extraordinaire" /></a>

  <br /><br />

  ```text
  $ whoami
  > Piyush Chauhan — DevOps Engineer & LLM Benchmark Specialist @ Ethara.ai
  > Specializing in Frontier LLM Benchmarking (Claude 3.5 Sonnet, Codex, GLM-4),
  > Deterministic Sandboxed Environments, Cloud CI/CD Pipelines & Evaluation Rubrics
  ```
</div>

---

### ⚡ Technical Execution Highlights

<div align="center">
  <img src="https://img.shields.io/badge/Benchmark_Suites-DevOps_&_Cloud_IaC-4F46E5?style=flat-square&logo=github" />
  <img src="https://img.shields.io/badge/Eval_Rigor-100%25_Deterministic_Sandboxes-10B981?style=flat-square&logo=docker" />
  <img src="https://img.shields.io/badge/Target_Models-Claude_•_Codex_•_GLM--4_•_DeepSeek-7928CA?style=flat-square&logo=openai" />
  <img src="https://img.shields.io/badge/Cloud_Platform-Google_Cloud_GCP-EA4335?style=flat-square&logo=googlecloud" />
  <img src="https://img.shields.io/badge/Research-DepreXAI_(94.2%25_Acc,_0.91_F1)-8B5CF6?style=flat-square&logo=pytorch" />
</div>

---

## 🔬 Core Focus & Engineering Specialization

I engineer **reproducible evaluation harnesses, deterministic sandbox runners, and rubric-driven validation pipelines** to rigorously test frontier LLMs on enterprise cloud infrastructure tasks. At **Ethara.ai**, I design task suites that evaluate whether models can safely generate, debug, and operate real-world systems without hallucinating commands, omitting probes, or violating the principle of least privilege.

* 🎯 **DevOps LLM Benchmarking & Task Authoring:** Authoring complex real-world tasks across Docker, Kubernetes, Helm, Terraform, and CI/CD pipelines, equipped with reference solutions, test assertions, and multi-dimensional grading rubrics.
* 🐳 **Deterministic Sandboxing & Resource Isolation:** Implementing cgroup-isolated, ephemeral Docker test containers with strict CPU/memory quotas and zero host pollution to evaluate untrusted AI-generated code.
* 🚨 **Systemic AI Failure Taxonomy:** Detecting and cataloging critical AI failure modes—such as unpinned image tags, root privilege escalations, missing liveness/readiness probes, and network security misconfigurations.
* ☁️ **Cloud CI/CD & Infrastructure Automation:** Architecting production deployment workflows with GitHub Actions, Google Cloud Platform (Compute Engine, GCR, Cloud Storage), and automated health-check rollback gates.
* 🧠 **Explainable AI Research (DepreXAI):** Co-authored clinical NLP research utilizing transformer ensembles (PyTorch, Hugging Face) paired with SHAP/LIME feature attribution (94.2% classification accuracy, 0.91 macro F1).
* 🧪 **End-to-End Test Engineering:** Building scalable automated regression frameworks using Python and Playwright with parallel execution and detailed telemetry reports.

---

## 🏗️ DevOps LLM Evaluation & Sandboxed Architecture

```
                 ┌────────────────────────────────────────────────────────┐
                 │       DevOps Benchmark Task Specification              │
                 │   (Problem statement, constraints & acceptance specs)  │
                 └───────────────────────────┬────────────────────────────┘
                                             │
                                             ▼
                 ┌────────────────────────────────────────────────────────┐
                 │          Frontier LLM Under Evaluation                 │
                 │      (Claude 3.5 Sonnet, OpenAI Codex, GLM-4)          │
                 └───────────────────────────┬────────────────────────────┘
                                             │ Candidate Manifests / IaC / Scripts
                                             ▼
     ┌────────────────────────────────────────────────────────────────────────────────┐
     │                      Deterministic Sandboxed Execution                         │
     │  ┌─────────────────────────┐ ┌───────────────────────┐ ┌────────────────────┐  │
     │  │ Docker Ephemeral Runner │ │ Pytest Test Harnesses │ │ YAML/HCL Parsers   │  │
     │  │ (cgroups, non-root, OOM)│ │ (Deterministic assert)│ │ (Static AST checks)│  │
     │  └─────────────────────────┘ └───────────────────────┘ └────────────────────┘  │
     └───────────────────────────────────────┬────────────────────────────────────────┘
                                             │
                                             ▼
     ┌────────────────────────────────────────────────────────────────────────────────┐
     │                         Rubric-Based Multi-Axis Scoring                        │
     │   • Functional Correctness (40%)        • Security & Least-Privilege (30%)     │
     │   • Production Best Practices (20%)     • Idempotency & Cleanliness (10%)      │
     └───────────────────────────────────────┬────────────────────────────────────────┘
                                             │
                                             ▼
                 ┌────────────────────────────────────────────────────────┐
                 │        Failure Taxonomy & Telemetry Feedback           │
                 │  (Root defaults, missing probes, syntax drift -> Odoo) │
                 └────────────────────────────────────────────────────────┘
```

---

## 📊 Evaluation Matrix & Benchmark Results

*Representative benchmark results across common infrastructure generation tasks in our sandboxed test suites:*

| Task Category | Evaluated Models | Primary Rubric Criteria | Detected Failure Modes | Pass Rate (Deterministic) |
| :--- | :--- | :--- | :--- | :---: |
| **Multi-Stage Dockerfiles** | Claude 3.5 Sonnet, Codex, GLM-4 | Non-root user, minimal base image, multi-stage build | Default root user, cache invalidation, bloated layers | **78.4%** |
| **Kubernetes RBAC & NetworkPolicy** | Claude 3.5 Sonnet, GLM-4, DeepSeek | Namespace isolation, explicit verbs, no cluster-admin | Wildcard `*` verbs, missing egress boundaries | **64.2%** |
| **Terraform GCP Infrastructure** | Claude 3.5 Sonnet, Codex | Resource naming conventions, IAM least privilege | Hardcoded secrets, unencrypted bucket configs | **71.8%** |
| **Production Helm Charts** | Codex, GLM-4, DeepSeek | Values schema validation, probe health configurations | Missing readiness probes, template linting errors | **62.0%** |
| **CI/CD Pipeline Security** | Claude 3.5 Sonnet, Codex | GitHub Actions token permissions, step timeouts | Unpinned third-party actions, excessive GITHUB_TOKEN | **81.5%** |

---

## 📋 Benchmark Suites & Featured Repositories

| Domain | Repository / Project | Target Technologies | Failure Modes Caught | Verification Mechanism | Status |
| :--- | :--- | :--- | :--- | :--- | :---: |
| **DevOps Benchmark** | [`devops-llm-benchmark`](https://github.com/pxyushch/devops-llm-benchmark) | Docker, K8s, Terraform, CI/CD | Insecure defaults, hallucinated CLI flags | Docker sandbox + Pytest | **Production** |
| **Cloud CI/CD** | [`cloud-cicd-gcp-pipeline`](https://github.com/pxyushch/cloud-cicd-gcp-pipeline) | GitHub Actions, Docker, GCP | Deployment drift, image build failures | GCP VM deployment + Healthcheck | **Production** |
| **QA Automation** | [`playwright-qa-automation`](https://github.com/pxyushch/playwright-qa-automation) | Playwright, Python, Allure | Flaky test timeouts, selector drift | Parallel runner + Allure reports | **Production** |
| **Explainable AI** | [`deprexai`](https://github.com/pxyushch/deprexai) | PyTorch, Hugging Face, SHAP, LIME | Model bias, uninterpretable predictions | LIME fidelity (0.92) + F1 metrics | **Research** |
| **Test Automation** | [`Automation-Testing-tool`](https://github.com/pxyushch/Automation-Testing-tool) | Playwright, Python, AstraQ | Flaky test timeouts, selector drift | Parallel runner + Allure reports | **Active** |
| **Full-Stack RBAC** | [`taskflow-rbac-app`](https://github.com/pxyushch/taskflow-rbac-app) | React, Express, Prisma, SQLite | Privilege escalation, route bypass | Automated RBAC integration tests | **Active** |

---

## 🛠️ Technical Stack & Tooling

<div align="center">

| Domain | Technologies, Frameworks & Tooling |
| :--- | :--- |
| **AI Benchmarking & Evaluation** | `Prompt Engineering`, `Rubric Scoring`, `LLM Sandbox Evals`, `Claude 3.5`, `OpenAI Codex`, `GLM-4`, `DeepSeek-V3` |
| **Containers & Orchestration** | `Docker`, `Docker Compose`, `Kubernetes (Kube-linter, Ingress, HPA, NetPol)`, `Helm` |
| **Infrastructure as Code (IaC)** | `Terraform (GCP/AWS)`, `HCL Validation`, `OPA Gatekeeper`, `AST Parsing` |
| **CI/CD & Cloud Infrastructure** | `GitHub Actions`, `Google Cloud Platform (Compute Engine, GCR, Cloud Storage)`, `Jenkins` |
| **Testing & Verification** | `Pytest (Test Harnesses)`, `Playwright`, `AstraQ`, `Allure Reporting`, `Postman` |
| **Machine Learning & NLP** | `PyTorch`, `Hugging Face (Transformers, Tokenizers)`, `SHAP`, `LIME`, `NumPy`, `Pandas` |
| **Languages & Scripting** | `Python 3.10+`, `Bash / Shell`, `SQL`, `JavaScript / TypeScript`, `Java` |

</div>

---

## 🏆 GitHub Official Achievements & Badges

<div align="center">
  <p>Verified profile milestones and developer badges earned across open-source and engineering repositories.</p>

  <a href="https://github.com/pxyushch?tab=achievements">
    <img src="https://raw.githubusercontent.com/Schweinepriester/github-profile-achievements/main/images/galaxy-brain-default.png" alt="Galaxy Brain" width="105px" style="margin: 0 8px;" />
  </a>
  <a href="https://github.com/pxyushch?tab=achievements">
    <img src="https://raw.githubusercontent.com/Schweinepriester/github-profile-achievements/main/images/yolo-default.png" alt="YOLO" width="105px" style="margin: 0 8px;" />
  </a>
  <a href="https://github.com/pxyushch?tab=achievements">
    <img src="https://raw.githubusercontent.com/Schweinepriester/github-profile-achievements/main/images/tiers/pull-shark-silver.png" alt="Pull Shark Silver" width="105px" style="margin: 0 8px;" />
  </a>
  <a href="https://github.com/pxyushch?tab=achievements">
    <img src="https://raw.githubusercontent.com/Schweinepriester/github-profile-achievements/main/images/quickdraw-default.png" alt="Quickdraw" width="105px" style="margin: 0 8px;" />
  </a>
  <a href="https://github.com/pxyushch?tab=achievements">
    <img src="https://raw.githubusercontent.com/Schweinepriester/github-profile-achievements/main/images/tiers/pair-extraordinaire-bronze.png" alt="Pair Extraordinaire" width="105px" style="margin: 0 8px;" />
  </a>

  <br /><br />

| Badge | Level / Multiplier | Requirement Satisfied | Status |
| :---: | :---: | :--- | :---: |
| 🧠 **Galaxy Brain** | **Bronze (x1)** | 2+ accepted answers to technical Q&A discussions | ![Earned](https://img.shields.io/badge/Status-UNLOCKED-success?style=flat-square&logo=github) |
| 🪂 **YOLO** | **Unlocked** | Pull request merged directly without review block | ![Earned](https://img.shields.io/badge/Status-UNLOCKED-success?style=flat-square&logo=github) |
| 🦈 **Pull Shark** | **Silver (x2)** | 16+ merged pull requests into default branches | ![Earned](https://img.shields.io/badge/Status-UNLOCKED-success?style=flat-square&logo=github) |
| ⚡ **Quickdraw** | **Unlocked** | Issue/PR closed within 5 minutes of opening | ![Earned](https://img.shields.io/badge/Status-UNLOCKED-success?style=flat-square&logo=github) |
| 👥 **Pair Extraordinaire** | **Bronze (x1)** | Merged co-authored commits via pull requests | ![Earned](https://img.shields.io/badge/Status-UNLOCKED-success?style=flat-square&logo=github) |

  <p>👉 <em>Inspect live verification badges on <a href="https://github.com/pxyushch?tab=achievements"><strong>github.com/pxyushch?tab=achievements</strong></a></em></p>
</div>

---

## 📈 GitHub Telemetry & Activity Stats

<div align="center">
  <img src="https://github-trophies.vercel.app/?username=pxyushch&theme=tokyonight&no-frame=true&margin-w=12&row=1&column=7" alt="GitHub Trophies" width="100%" />
  <br /><br />
  <img src="https://github-readme-stats-eight-theta.vercel.app/api?username=pxyushch&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&hide=contribs" alt="Piyush's GitHub Stats" width="48%" />
  <img src="https://github-readme-stats-eight-theta.vercel.app/api/top-langs/?username=pxyushch&layout=compact&theme=tokyonight&hide_border=true" alt="Top Languages" width="48%" />
</div>

---

## 📬 Contact & Engagements

- 💼 **Software Engineer @ Ethara.ai** | Available for DevOps & AI Evaluation contracts.
- 🎯 **Target Domains:** Frontier Model Evaluations, Task Authoring, Red-Teaming & Benchmark Harness Architecture.
- ✉️ **Direct Email:** **[peeyushrajput321@gmail.com](mailto:peeyushrajput321@gmail.com)**
- 💼 **LinkedIn:** **[linkedin.com/in/piyush-chauhan-8a02a0251](https://linkedin.com/in/piyush-chauhan-8a02a0251)**
- 🌐 **GitHub:** **[github.com/pxyushch](https://github.com/pxyushch)**

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=1,6,11,20&height=100&section=footer" width="100%" />
</div>
