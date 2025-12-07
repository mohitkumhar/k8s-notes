# Kubernetes (CKA 2025) Learning Notes

This repository contains my complete, structured, day-by-day learning notes for the **Certified Kubernetes Administrator (CKA) 2025** curriculum.
The notes follow a progressive learning approach starting from Docker fundamentals and moving towards advanced Kubernetes topics such as RBAC, cluster security, networking, storage, troubleshooting, Operators, and Gateway API.

The purpose of this repository is to **document practical knowledge**, **store YAML files**, **record kubectl commands**, and maintain a clear learning path while preparing for the CKA exam.

---

## 📂 Repository Structure (Day-by-Day Learning)

All learning material is organized under the `learning/` directory with individual folders for each day:

```
learning/
 └─ day1/   → Docker fundamentals, images, containers
```

Each folder contains:

* Markdown notes
* Example YAML manifests
* Commands practiced
* Explanations & diagrams (if needed)
* Troubleshooting steps

---

## 📘 What This Repository Covers (Comprehensive Overview)

### **🧱 1. Kubernetes Fundamentals**

* Architecture (API Server, Scheduler, Controller Manager, Kubelet)
* Nodes, Pods, control plane components
* Declarative & imperative object management

### **🐳 2. Docker & Container Basics**

* Images, containers, Dockerfile, multi-stage builds
* Storage, networking, Volumes, Bind Mounts

### **📦 3. Kubernetes Workloads**

* Pods, Deployments, ReplicaSets
* DaemonSets, StatefulSets
* Jobs & CronJobs
* Sidecar & init containers

### **🔌 4. Networking**

* Services (ClusterIP, NodePort, LoadBalancer, ExternalName)
* DNS (CoreDNS)
* CNI plugins
* Ingress & Gateway API
* Network Policies

### **💾 5. Storage**

* Volumes, PersistentVolume (PV)
* PersistentVolumeClaim (PVC)
* StorageClass
* Dynamic provisioning
* Stateful applications

### **🪪 6. Authentication, Authorization & Security**

* TLS, Certificates, CSR
* RBAC (Roles, RoleBindings, ClusterRoles)
* Service Accounts & tokens
* PodSecurity Standards
* Linux capabilities & SecurityContext

### **🧭 7. Scheduling & Resource Management**

* Taints, Tolerations, Node Affinity
* Resource requests & limits
* HPA & VPA
* Pod priority & preemption

### **🔍 8. Troubleshooting (Big part of CKA)**

* Pod failures
* Control plane failures
* Node issues
* Networking issues
* ETCD backup & restore
* Logs, events & debugging tools

### **⚙ 9. Advanced Kubernetes**

* Helm Charts
* Kustomize
* Operators & CRDs
* Admission Controllers
* Multi-master cluster setup
* Private Docker registry
* Cluster upgrades

---

## 🧪 Practical Content Included

This repo includes:

* Real-world YAML manifests
* Mini-labs & exercises
* Kubernetes debugging commands
* Day-wise cheat sheets
* JSONPath queries
* Cluster setup scripts (Kind & Kubeadm)
* Hands-on troubleshooting steps

Everything is written to **mirror real exam scenarios**.

---

## 🎯 Goal of This Repository

* Build a solid Kubernetes foundation
* Understand real-world cluster operations
* Practice exam-oriented tasks
* Maintain a clean study guide for quick revision
* Prepare efficiently for **CKA 2025** certification

---

## 🛠 Tools Used

* Kubernetes (v1.29+ recommended for CKA 2025)
* Docker / containerd / cri-dockerd
* kind
* kubeadm
* kubectl
* Helm
* Lens / k9s (optional)

---

## 📥 How to Clone This Repository

To download this repository to your local system:

```bash
git clone https://github.com/<your-username>/<repo-name>.git
```

Then navigate into the project:

```bash
cd <repo-name>
```

If you want to pull the latest updates:

```bash
git pull origin main
```


---

## 🤝 Contribution Guidelines

This is primarily a personal learning repository, but contributions that improve clarity, fix mistakes, or add useful examples are welcome.

### ✔ How to Contribute
1. **Fork** the repository  
2. Create a new branch:  
   ```bash
   git checkout -b feature-name
   ```
3. Make your changes (notes, examples, corrections, improvements)  
4. Commit your updates:  
   ```bash
   git commit -m "Description of changes"
   ```
5. Push the branch:  
   ```bash
   git push origin feature-name
   ```
6. Open a **Pull Request** with a clear description  

### ✔ What You Can Contribute
- Correction of notes or explanations  
- Additional examples or better YAML manifests  
- Troubleshooting scenarios
- Improvements in formatting or readability  
- Missing kubectl commands

### ❌ What Not to Add
- Large external files  
- Course videos or copyrighted material  
- Unrelated topics not covered in CKA  

---


## 📜 License

This repository is licensed under the **MIT License**.
Free to use for learning and educational purposes.