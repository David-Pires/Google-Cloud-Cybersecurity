🔄 The Security Life Cycle & DevSecOps | O Ciclo de Vida de Segurança e DevSecOps
This document introduces the modern approach to integrating security throughout the software development process, focusing on automation, pipelines, and the software supply chain.
Este documento introduz a abordagem moderna de integração da segurança em todo o processo de desenvolvimento de software, focando em automação, pipelines e na cadeia de suprimentos de software.

📍 Table of Contents | Índice
From DevOps to DevSecOps

CI/CD Pipelines & Automation

Software Supply Chain Security

Infrastructure & Policy as Code (IaC/PaC)

🛡️ From DevOps to DevSecOps | De DevOps para DevSecOps
A segurança não é mais uma etapa final, mas um processo contínuo e integrado.

🇺🇸 English Version
DevSecOps is the integration of security practices into the software development (Dev) and IT operations (Ops) workflow. By shifting security "to the left" (addressing it earlier in the cycle), organizations reduce downtime and human errors, creating a more resilient software life cycle.

🇧🇷 Versão em Português
DevSecOps é a integração de práticas de segurança no fluxo de trabalho de desenvolvimento de software (Dev) e operações de TI (Ops). Ao mover a segurança para "a esquerda" (abordando-a mais cedo no ciclo), as organizações reduzem o tempo de inatividade e erros humanos, criando um ciclo de vida de software mais resiliente.

🚀 CI/CD Pipelines & Automation | Pipelines CI/CD e Automação
O uso de pipelines de Integração Contínua (CI) e Entrega Contínua (CD) permite que as equipes de segurança garantam consistência em escala.

Continuous Integration (CI): Automating the merging of code changes and testing.

Continuous Delivery (CD): Ensuring that the software is always in a state where it can be deployed to production.

Security Goal: Leverage automation to scan for vulnerabilities without slowing down the development team.

📦 Software Supply Chain | Cadeia de Suprimentos de Software
Proteger apenas o seu código não é suficiente; você deve proteger tudo o que seu código consome.

Artifacts: Managing the security of libraries, dependencies, and containers.

Vulnerability Mitigation: Identifying and fixing threats within third-party components that your software relies on.

📜 Infrastructure & Policy as Code (IaC / PaC)
Transformar a infraestrutura e as regras de segurança em código permite que a segurança seja auditável, repetível e automatizada.

Infrastructure as Code (IaC): Provisioning servers and networks via scripts (e.g., Terraform, Ansible).

Policy as Code (PaC): Defining security rules (like "no public S3 buckets") as code that is automatically enforced during deployment.