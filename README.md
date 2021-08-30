# Aqua Course Breakdown

## Modules

There are 14 modules which make up the course, 5 of which include hands-on lab activities to provide the learners with the opportunity to try out some of the features covered. Below is a list of the modules, an overview of what they will cover and relevant audiences to these modules.

1. **Introduction**
    - Content: Gives an introduction to the course itself, the instructor, and a very brief introduction on Cloud Security
    - Target Audience: Everyone attending the course
2. **Cloud Native Security**
    - Content: Learn about the pillars of cloud native security, and how Aqua fits in to the picture
    - Target Audience: Everyone attending the course
3. **Aqua Architecture**
    - Content: The module is directed at building a fundamental understanding of the Aqua components and how they are used
    - Target Audience: Aqua admins, Infrastructure team members
4. **Installation**
    - Content: How components are deployed, and various methods of how to deploy them
    - Target Audience: Aqua admins, Infrastructure team members
    - Lab: Perform a quick install onto a local Kubernetes cluster
        - Requirements: 
            - Docker
            - Kind
            - Kubectl
5. **Scanning and Image Assurance Policies**
    - Content: How Aqua approaches image scanning (what, how, why, etc) and make use of assurance policies to detect, assess, and reports security issues in images
    - Target Audience: Aqua admins, Security, Development & Container Orchestration teams
    - Lab: Create an Image assurance policy and register image(s) with Aqua
        - Requirements:
            - Access to Testdrive
6. **Runtime Protection**
    - Content: Explore how the runtime policies can protect your infrastructure in realtime with Aqua enforcers
    - Target Audience: Aqua admins, infrastructure, development & security teams
    - Lab: Create and modify a container runtime policy, and see how this changes the behaviour of your affected containers
        - Requirements:
            - Access to Testdrive
            - Kubectl
7. **Services and Firewall Policies**
    - Content: What Aqua are services, scope and workflows and how to use firewall policies to secure network traffic
    - Target Audience: Aqua admins, Security, Development & Container Orchestration teams
    - Lab: Create a Service and apply a firewall policy, and record network activity from your running container
        - Requirements:
            - Access to Testdrive
            - Kubectl
8. **Secrets Management**
    - Content: How Aqua secures and proliferates sensitive data in a microservice and container environment, and integrations with third-party secrets management tooling
    - Target Audience: Aqua admins, Security, Development & Container Orchestration teams
    - Lab: Create a secret within Aqua and securely inject to your running container, and integrate with Hashicorp Vault
        - Requirements:
            - Access to Testdrive
            - Kubectl
            - Helm
9. **Serverless Protection**
    - Content: An overview of Function scanning and Function runtime protection features
    - Target Audience: Developers of Serverless applications, Aqua administrators and Security teams
10. **Role Based Access Control (RBAC)**
    - Content: Important information for those planning to oversee Aqua RBAC and User access control
    - Target Audience: Aqua administrators
11. **CLI and API**
    - Content: An introduction to interacting with Aqua via CLI and APIs, covering some use cases for doing so
    - Target Audience: Aqua administrators and development teams
12. **Aqua for Developers**
    - Content: Some day-to-day use cases and information relevant to developers whose software may be managed by Aqua
    - Target Audience: Development, Container Orchestration & Security teams
13. **Aqua for Admins**
    - Content: Some day-to-day use cases and information relevant to those responsible for administering Aqua
    - Target Audience: Aqua administrators and Security teams
14. **Conclusion**
    - Content: Review of the course, further information and closing out session
    - Target Audience: Everyone attending the course

## Approximate Schedule (3 half-days)
 - Day 1:
    - Introduction
    - Cloud Native Security
    - Architecture
    - Installation
 - Day 2:
    - Scanning and Image Assurance Policies
    - Runtime Protection
    - Services and Firewall Policies
 - Day 3:
    - Secrets Management
    - Serverless Protection
    - Role Based Access Control (RBAC)
    - CLI and API
    - Aqua for Developers
    - Aqua for Admins
    - Conclusion

