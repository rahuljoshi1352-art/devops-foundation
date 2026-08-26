# DevOps Foundations

This repository contains my research and notes on the basics of DevOps, including its history, core principles, CI/CD, automation, and commonly used DevOps tools.

## What is DevOps?

DevOps is a way of working that brings development and operations teams closer together. It focuses on collaboration, automation, continuous integration, continuous delivery, and regular feedback.

The main aim is to make software development and deployment faster, more reliable, and easier to manage.

## Topics Covered

* History and evolution of DevOps
* The Three Ways of DevOps
* CI/CD pipeline
* Automation and collaboration
* Containerization
* Infrastructure as Code
* Monitoring
* Comparison of popular DevOps tools

## DevOps Lifecycle

A typical DevOps workflow can be represented as:

```text
Plan → Code → Build → Test → Release → Deploy → Operate → Monitor
  ↑                                                                  ↓
  └──────────────────────── Feedback ───────────────────────────────┘
```

Each stage is connected to the next, allowing teams to find problems early and improve the software continuously.

## Tools Studied

| Area                   | Examples                |
| ---------------------- | ----------------------- |
| Version Control        | Git, GitHub             |
| CI/CD                  | Jenkins, GitHub Actions |
| Containerization       | Docker, Kubernetes      |
| Infrastructure as Code | Terraform, Ansible      |
| Monitoring             | Prometheus, Grafana     |

## Main Takeaways

During this research, I learned that DevOps is not only about using automation tools. It also involves communication between teams, shorter feedback cycles, reliable processes, and continuous improvement.

CI/CD helps automate the process of testing and delivering code. Containers make applications easier to package and move between environments, while IaC tools help manage infrastructure in a repeatable way. Monitoring provides information about how applications and systems are performing after deployment.

## Repository Structure

```text
devops-foundations/
├── README.md
├── docs/
│   ├── devops_principles.md
│   └── tool_comparison.md
├── presentation/
│   └── devops_overview.pdf
└── assets/
    └── pipeline_diagram.png
```

## Conclusion

DevOps brings development, operations, automation, and feedback together throughout the software lifecycle. Understanding these basic principles and tools provides a foundation for working with modern software development and deployment practices.
