# Chapter 1: Introduction to Ansible

•     What is Ansible? (automation, agentless, YAML-based)
•     Why use Ansible? (simplicity, scalability, DevOps integration)
•     Comparison with other tools (Puppet, Chef, SaltStack)
•     Core concepts: Control node vs Managed nodes

# Chapter 2: Installation & Setup

•     Installing Ansible on RHEL/CentOS
•     Configuring 
•     Understanding inventory files ()
•     First test: 

# Chapter 3: Inventory & Ad-hoc Commands

•     Static inventory (groups, host variables)
•     Dynamic inventory (cloud providers, scripts)
•     Running ad-hoc commands:

# Chapter 4: Playbooks & Modules

•     YAML basics (syntax, indentation)
•     Playbook structure: hosts, tasks, handlers
•     Common modules: , , , , 
•     Writing your first playbook (install Apache, start service, open firewall)

# Chapter 5: Variables, Templates & Handlers

•     Defining variables (host/group vars, )
•     Jinja2 templates ( files for configs)
•     Handlers (restart services only when needed)
•     Facts ( for system info)

# Chapter 6: Roles & Reusability

•     Role structure (, , )
•     Creating and using roles
•     Ansible Galaxy (download and share roles)
•     Best practices for reusable automation

# Chapter 7: Security & Secrets

•     Ansible Vault (encrypting passwords/keys)
•     Managing sensitive data in playbooks
•     Role-based access control (when using Tower/AWX)

# Chapter 8: Advanced Playbook Features

•     Conditionals (), loops (, )
•     Error handling (, )
•     Strategies (, , )
•     Tags (run specific parts of playbooks)

# Chapter 9: Scaling & Integration

•     Dynamic inventory for AWS, Azure, GCP
•     CI/CD integration with Jenkins
•     Using Ansible for container orchestration (Docker, Kubernetes)
•     Performance tuning (parallelism, async tasks)

# Chapter 10: Enterprise Automation

•     Ansible Tower / AWX (web UI, RBAC, job scheduling)
•     Compliance automation (CIS benchmarks, server hardening)
•     Hybrid cloud orchestration
•     Building custom modules & plugins
•     Designing automation frameworks for large teams
