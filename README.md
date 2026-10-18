## Hi, I'm Jashitha Desu 👋
**MSc Software Engineering student at Blekinge Institute of Technology (BTH), Sweden.**
I'm  focused on DevOps, cloud infrastructure, and platform engineering.
What draws me to DevOps is the gap between deploying code and running it reliably. I like working on the parts that keep systems healthy after deployment: automated pipelines, orchestration, monitoring, and fast recovery when things break, later performing the required tests. That interest shapes what I build. I wrote a Kubernetes controller in Go to understand orchestration from the inside, built an LLM agent that diagnoses cluster failures and proposes fixes under strict safety policies, and as part of coursework a research proposal on  measuring how rollback automation affects production downtime was planned.

---
# Current Coursework (MS Software Engineering)
    • Research Methodologies 
    • Software Metrics
    • Artificial Intelligence
    • Software Evolution and Maintenance Project
These courses strengthen my understanding of modern systems, how to evaluate and understand the system, research practices.

---
# Undergraduate Coursework
    • Software Engineering
    • DevOps 
    • Machine Learning 
    • Software testing
    • Artificial Intelligence 
    • Natural Language Processing 
    • Data Analytics 
    • Computer Networks 
    • Operating Systems 
    • Cryptography and Network Security 
    • Database Management Systems 
    • Mobile Application Development 
    

---
# Tech Stack
- **Languages**: Python ,Go, Java,  C, JavaScript,  SQL.
- **Cloud & DevOps**: Kubernetes,  Docker,  AWS (S3, Lambda, EC2, DynamoDB, Cognito),  GitHub Actions, Prometheus,  Linux
- **Testing & Quality**: pytest, unittest, mutation testing, test selection, UI automation, SonarQube
- **AI / ML**: PyTorch,  scikit-learn,  Pandas,  NumPy,  Ollama,  LLM tool-calling
- **Web & Data**: FastAPI,  Flask, Node.js,  React,  PostgreSQL,  MySQL

---
# Featured Projects
- **1. AI Agent for Kubernetes Incident Diagnosis**: A tool-calling LLM agent (Qwen via Ollama) that diagnoses Kubernetes faults from pods, events and logs, and applies fixes under a policy layer that decides between auto-execution, human approval, or denial.
   Tech stack: Python Ollama  Kubernetes  RBAC
- **2. Simple FaaS**: Function-as-a-Service on Kubernetes. A serverless platform built from scratch without Knative or OpenFaaS, using a custom CRD and a Go controller that manages the full function lifecycle through a gateway.
   Tech Stack: Go Kubernetes controller-runtime kind
- **3. Deepfake Video Detector**: A video classifier (YOLOv8n + EfficientNet-B0, 0.986 ROC-AUC) deployed as a FastAPI service on AWS EC2 through a GitHub Actions pipeline, running two models in 1 GB of RAM.
  Tech Stack: PyTorch  FastAPI   Docker   AWS EC2   GitHub Actions
- **4. Selection & Mutation testing Lab**: Which tests CI run on a commit, and what does skipping the rest cost? A staged unit/ integration/ e2e chain for a simple FaaS gateway, 254 regressions injected by my own AST mutation engine, and a kill matrix used to compare 8 selection strategies (line/file coverage, Bazel build graph, LLM ). Coverage-based selection caught 90.8% of bugs at 1.4$ of the test cost. Reproducible via Nix, devcontainer and Bazel.
   Tech stack: Python Mutation testing Bazel Nix GitHub Actions

---
# Currently
    • Working on software evolution and code quality in Home Assistant Core (BTH course project): SonarQube analysis and a new feature for the Whois integration 
    • Looking for a master's thesis or other roles related to  DevOps, cloud orchestration, or AI for operations (starting 2027)

 
   **Feel free to explore my repositories, and reach out if you'd like to collaborate.**

