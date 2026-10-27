# DevOps Setup Guides

A collection of step-by-step notes for setting up common DevOps tools and assembling a CI/CD environment. The guides are intended for learning and lab use; verify commands against the versions you install.

## Guide index

| Guide | Topic |
|---|---|
| [01 — Jenkins Server Setup](./01-Jenkins-Server-Setup.md) | Jenkins on a Linux VM |
| [02 — Docker Setup](./02-Docker-Setup.md) | Docker installation and validation |
| [03 — Docker Compose Setup](./03-Docker-Compose-Setup.md) | Multi-container workflows |
| [04 — Jenkins + Docker Project](./04-Jenkins-Docker-Project.md) | Pipeline building and container integration |
| [05 — EKS Setup](./05-EKS-Setup.md) | Kubernetes on AWS EKS |
| [06 — Sonar Setup](./06-Sonar-Setup-Docker.md) | SonarQube and code-quality analysis |
| [07 — Nexus Setup](./07-Nexus-Setup-Docker.md) | Artifact repository setup |
| [08 — ELK Stack Setup](./08-ELK-Stack-Setup.md) | Centralized logs and search |
| [09 — DevOps Project Setup](./09-DEVOPS-PROJECT-SETUP.md) | End-to-end project notes |
| [10 — Jenkins, Docker & Kubernetes](./10-Jenkins-Docker-K8S.md) | CI/CD deployment workflow |
| [11 — Ansible Setup](./11-Ansible-Setup.md) | Configuration-management automation |
| [12 — MySQL Database Setup](./12_MySQL_DB_Setup.md) | MySQL installation and initialization |
| [13 — Minikube Setup](./13_MiniKube_Setup.md) | Local Kubernetes environment |

## How to use these notes

1. Read the guide's prerequisites before running commands.
2. Use a disposable lab VM or test environment.
3. Adapt commands to your operating system and installed versions.
4. Verify firewall rules, user permissions, and service ports after each step.
5. Tear down test infrastructure when finished.

## Security

Do not commit real passwords, access tokens, private keys, kubeconfig files, or cloud credentials. Use environment variables or approved secrets stores. Treat the commands as learning references, not hardened production deployment instructions.
