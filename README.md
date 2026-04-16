~~~~
Aurélien Campergue
München Obermenzing
aurelien.campergue.pro@pm.me
~~~~

# <center>Senior DevOps Engineer</center>

### <center>Specialties: CI/CD, GitLab, Kubernetes, Maven, Java, Linux, Docker, Ansible</center>

<br/>

Senior Platform / DevOps Engineer with 20+ years of experience designing and operating CI/CD platforms, container infrastructures, and deployment workflows across large-scale environments in defense, gaming, telecom, and payroll/HR software. Specialized primarily in Linux, Docker, and Kubernetes, with strong hands-on experience in GitLab, Helm, GitOps, and infrastructure automation. CKA, CKAD, LFCS, and LFCE certified.

Languages: French (native), English (fluent), German (fluent)

# Skills Summary

| Domain | Skills |
|:-----------|:------------|
| Core stack | **Linux**, **Docker**, **Kubernetes**, **GitLab**, **Ansible**, **Helm**, **Maven**, **Java** |
| Platforms & Containers | OpenShift, VMware, VMware VCD, KVM, AWS, LXD/LXC, Packer |
| Deployment & Automation | **ArgoCD**, Helmfile, Puppet, Terraform, **Gradle**, **Git**, SonarQube, Nexus |
| Operating systems | **Debian**, **Ubuntu**, Red Hat, CentOS, Fedora, Arch Linux, OPNsense, TrueNAS |
| Programming languages | **Java**, **Python**, **Bash**, Groovy |
| Application stack | HAProxy, NGINX, Apache HTTP Server, JBoss, Tomcat, Redis, Cassandra, Spring, SLF4J, Logback, JUnit, Mockito, JaCoCo |

# Certifications

| Date | Training | Certification |
|:-----------|:------------|:------------|
| 02.2022 | Linux Foundation Certified Engineer | [**LFCE**](https://www.credly.com/badges/a5ca5dae-3dbf-4778-ba45-1b389241f9b7) |
| 01.2021 | Linux Certified Systems Administrator | [**LFCS**](https://www.credly.com/badges/cd83d80a-01cb-48e4-8bc1-1952ba1895b3) |
| 02.2020 | Certified Kubernetes Application Developer | [**CKAD**](https://www.credly.com/badges/bcb68031-0217-4273-8341-3cfe8bb7526e) |
| 01.2020 | Certified Kubernetes Administrator | [**CKA**](https://www.credly.com/badges/b88ec8db-9094-44b1-86aa-9c523afa91b8) |

# Professional experience

## 2024-Present - Senior Platform / DevOps Engineer - _GIP GmbH (Frankfurt)_

* Installed and operated a GitLab instance on the Kubernetes infrastructure supporting a payroll and HR software platform.
* Designed and maintained fully modular GitLab CI/CD pipelines for Java applications built with Maven and Gradle, including container builds with Buildah and Kaniko, Helm chart packaging, quality gates (SonarQube, Helm smoke tests, Dive), and automated review environment deployments to Kubernetes using GitLab Review Apps.
* Used Claude to document and harden a fragile, business-critical release process, reducing a major single point of failure by capturing long-held tacit knowledge and automating the Jira-driven biweekly workflow without breaking compatibility with established internal processes.
* Reworked base container images from Ubuntu to Alpaquita to reduce image size and attack surface while retaining glibc compatibility.
* Installed and configured Renovate Bot in GitLab to keep project dependencies up to date automatically.
* Automated changelog generation by introducing Conventional Commits and defining a tailored git-cliff configuration to publish release notes in GitLab instead of maintaining them manually in `README.adoc`.
* Supported multiple teams with GitLab onboarding, migrations from Bitbucket/Jenkins to GitLab, Helm packaging, and day-to-day enablement and training.

## 2020-2024 - Senior SRE / DevOps Engineer - _Camptocamp (Munich)_

### Deutsche Telekom

* Modernized deployments by moving a traditional Helmfile-based setup to a GitOps model with ArgoCD (Helm, Helmfile, ArgoCD, GitOps).
* Improved GitLab pipelines for building Docker images and deploying them to an OpenShift cluster (GitLab, Bash, Python, OpenShift).
* Migrated deployment Helm charts from OpenShift-specific resources (DeploymentConfig, ImageStream) to vanilla Kubernetes deployments.
* Enabled daemonless container image builds in Kubernetes with Kaniko-based GitLab pipelines (Kaniko, Kubernetes, GitLab, Bash).
* Built a GitLab project dependency analyzer to trigger Docker builds from the Docker dependency tree (Python, GitLab API).
* Supported developers on build and deployment issues.

### Camptocamp

* Built and automated a documentation platform using Antora, AsciiDoc, and GitHub Actions.
* Contributed to workshops focused on improving CI/CD practices across the organization.
* Helped create training materials.

## 2018-2020 - Senior DevOps Engineer - _Onpex (Munich)_

* Rewrote the Puppet deployment codebase in Ansible, simplifying ongoing maintenance (Ansible, Puppet).
* Built and maintained a Kubernetes cluster in AWS (Kubernetes, Kops, EKS).
* Maintained automated deployment pipelines built on Kubernetes, Helm, and GitLab.
* Containerized applications with Docker and Maven.

## 2016-2018 - DevOps Engineer - _Travian Games (Munich)_

* Built a scalable container platform using Kubernetes, DC/OS, Docker, Packer, and Vagrant.
* Managed cloud infrastructure based on VMware VCD, AWS, and Terraform.
* Partnered with a development team to establish a CI/CD pipeline.
* Refactored the configuration management codebase (Puppet, Python, Git, Stash).

## 2016 - Build Engineer - _Workday (Dublin / Munich)_

* Delivered a Jenkins-based CI environment on a Docker cluster with centralized log management (Ansible, Docker, Swarm, Consul, Registrator, Elasticsearch, Fluentd, Kibana, Jenkins).
* Automated data synchronization between web services (Groovy, Bamboo, Jira, Confluence).
* Contributed to a partial migration from Ant to Gradle.

## 2010-2016 - DevOps Engineer - _Thales Services (Paris)_

### Software development park management

* Created pre-equipped and pre-configured base images for development computers, including Ubuntu (10.04, 11.04, 12.04, 13.04), Mint (14, 15), and Debian (6.0, 7.0, 8.0).
* Implemented a mass cloning infrastructure using Clonezilla to effortlessly provision pre-configured developer computers.
* Automated park inventory using OCS Inventory NG and GLPI.

### Packaging, integration, and industrialization of deployments

* Automated hypervisor deployment using Preseed, Puppet, and Ansible.
* Streamlined virtual machine deployment using Shell Scripts and Python development.
* Created native Debian packages from Maven projects utilizing Jdeb.
* Established a continuous deployment process with platform-specific settings using Ansible.
* Implemented a log management architecture with ELK (Elasticsearch, Logstash, Kibana).
* Deployed a performance monitoring architecture using Munin.

### Implementation, deployment, and maintenance of a software development platform

_Managed a software development platform used by a team of 60 people_

* Implemented continuous integration with Maven, Jenkins, Nexus, Sonar, and Squale.
* Orchestrated continuous deployment with Jenkins, Debian, Ansible, and Docker.
* Configured collaborative work tools, including Jira, SVN, Git, XWiki, and OpenLDAP.
* Ensured security and network stability with pfSense and HAProxy.

### Integration and testing platform

* Installed and configured 40 hypervisors, including VMware ESXi/vSphere, KVM, and Docker.
* Managed integration and test platforms consisting of approximately 800 VMs across 20 platforms.
* Conducted daily deployments of complete platforms, including OS and application software stacks (40 VMs, 35 JBoss, 2 PostgreSQL, 2 Cassandra, 10 Redis, 2 ActiveMQ, 6 lemonldap-ng, 10 Apache HTTP Server).
* Set up an infrastructure for acceptance tests using Selenium Hub with Ubuntu and Windows nodes.

### Referent on software integration and system integration

* Led the design and implementation of the Maven architecture, incorporating Maven 3, Corporate POM, BOM, automated delivery projects, and archetypes.
* Ensured the quality of system versions with weekly releases.
* Provided support to development and production teams.

## 2010 - DevOps Engineer & Software Developer - _Thales Services (Paris)_

_1 development mission, 2 system administration missions_

* Developed a demonstrator for RATP (French train company), showcasing innovative solutions.
* Managed deployment and administration of the development server, supporting a team of fifteen developers.
* Created Linux masters for development laptops and streamlined the deployment of pre-configured development environments.

_Ubuntu 10.04, CentOS 5.5, Eclipse 3.5 JEE, Java EE 1.6, VMware ESXi, vCenter, GWT, SmartGWT, Hibernate, SLF4J, Logback, JDepend, PMD, Checkstyle, FindBugs, JUnit, Emma, Clonezilla_

## 2009-2010 - Software Developer - _Thales Services (Paris)_

_1 development mission, 2 system administration missions_

* Designed and developed a comprehensive public transportation management application.
* Established a master configuration for development stations, ensuring consistency and efficiency.
* Installed a Linux Debian development server (version 5.0) for enhanced software development processes.

_Java EE 1.6, AspectJ, Spring 2.5, GWT 1.7 & 2.0, GXT, WSDL, Eclipse 3.5 JEE, Subversion, Redmine, Maven 2, JDepend, PMD, Checkstyle, FindBugs, JUnit, Emma, Test Driven Development, Pair Programming, Iterative schedule_

## 2008-2009 - Software Developer - _Thales Air Systems (Paris)_

_5 development missions, 2 system administration tasks_

* Designed and developed a simulation framework for radar systems detecting missiles.
* Created a persistence framework for efficient storage and retrieval of simulation data.
* Collaborated on the development of an OpenGL-based windowing API to visually display the simulation in real-time.
* Implemented enhancements and modifications to the multi-language code generation tool named Comet.
* Developed a model-to-model (M2M) transformation tool enabling seamless communication between radars using different protocols, by generating necessary stubs to bridge the communication gap.
* Managed deployment and administration of a development server, supporting a team of approximately 30 users across three departments.
* Automated the deployment process for development laptops, streamlining setup and configuration.

_Java J2SE version 1.6, Maven 2 Eclipse 3.5, Subversion, Redmine, GOF Design Patterns & GRASP_

## 2006-2008 - Software Developer - _Thales EPM (Paris)_

_3 development missions_

* Designed and implemented a thermal data export engine specifically for electronic map thermal simulation software.
* Developed an engine utilizing population-based genetic algorithms to generate thermal models with simplified geometry.
* Created a simplified thermal simulation engine enabling faster pre-simulations compared to professional software.

_Java J2SE version 1.4 & 1.6, Eclipse 3.4 / 3.3 / 3.2_, FloTHERM & Ansys Icepak

## 2005-2006 - Consultant & Trainer - _CMS Informatic (Paris)_

_Training, development and administration_

* Delivered technical training courses focused primarily on Linux system administration and software development.
* Oversaw the management of company servers and network infrastructure.
* Created tailored software solutions and advanced macros in MS Office using VBA.


# Education

| Date | Certificate |
|:-----------|:------------|
| 2003-2008 |  Engineering degree (apprenticeship) - Computer Science specialization, Polytech Paris-Saclay (formerly Polytech Paris-Sud / FIIFO) |
| 2002-2003 |  CPGE TSI (Technological and Industrial Science Preparatory Classes) - Electronic and Mechanical focus  |
| 2001-2002 |  French secondary school diploma (Baccalauréat) - Electronic specialization, graduated with highest honors |

# Additional Information

* Experience working on classified defense projects in France.
* Swing dancing teacher in Munich.
