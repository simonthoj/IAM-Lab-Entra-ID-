Microsoft Entra ID – Identity and Access Management (IAM) Lab

**Project Overview**

This project is a hands-on Identity and Access Management (IAM) lab built using Microsoft Entra ID. It explores how organizations manage digital identities, user permissions, security groups, administrative access, and application access.

The primary objective is to implement and demonstrate core IAM principles, including Role-Based Access Control (RBAC), least privilege, delegated administration, and employee lifecycle management.

**Project Objectives**

Create and manage user accounts across multiple departments.

Organize users through Microsoft Entra security groups.

Implement Role-Based Access Control (RBAC).

Apply the principle of least privilege.

Delegate group management responsibilities through group ownership.

Establish organizational reporting relationships.

Simulate employee offboarding and account deactivation.

Explore enterprise application integration and group-based access design.

**Technologies Used**

Microsoft Entra ID (Free)

Microsoft Entra Admin Center

Microsoft Azure Portal

GitHub

Windows

**Implemented Features**

1. Identity and User Management

Created and configured user accounts representing common organizational departments and job functions, including IT, Finance, Human Resources, Sales, and Cybersecurity.

2. Security Group Management

Created department-based security groups to organize users according to their organizational responsibilities.

Also created specialized groups, including:

Payroll Access

SOC Analysts

These groups demonstrate how access can be organized around specific job responsibilities rather than relying exclusively on department membership.

3. Role-Based Access Control (RBAC)

Assigned Microsoft Entra directory roles based on administrative responsibilities.

Examples:

Global Administrator

Groups Administrator

Security Administrator

Administrative permissions were limited to designated users rather than assigned based solely on job seniority.

4. Least Privilege

Applied the principle of least privilege by keeping most users as standard accounts while reserving administrative permissions for users with specific responsibilities.

5. Delegated Administration

Assigned department managers as owners of their respective security groups to demonstrate decentralized group management without granting unnecessary tenant-wide administrative privileges.

6. Organizational Hierarchy

Configured manager relationships within the directory to represent reporting structures and demonstrate organizational identity management.

7. Employee Lifecycle Management

Simulated employee offboarding by disabling an employee account and exploring appropriate access-removal procedures.

8. Enterprise Application Access Design

Created enterprise application entries to explore application integration and access management concepts.

Designed application-specific security groups to represent resource-specific access requirements:

Payroll Portal — APP-Payroll-Users

SIEM Platform — APP-SIEM-Users

HR Portal — APP-HR-Users

CRM — APP-CRM-Users

IT Ticketing Platform — APP-IT-Ticketing-Users

Each group is designed to contain only users whose job responsibilities require access to the corresponding application.

This approach separates organizational membership from application access and demonstrates more granular access-control design.

**Licensing and Implementation Limitations**

This project uses Microsoft Entra ID Free. Certain advanced capabilities, including group-based assignment to enterprise applications, require additional licensing.

Specialized security groups were created to demonstrate access-control design; however, group-based enterprise application assignment and enforcement were not implemented due to licensing limitations.

Application-specific groups represent a proposed access model rather than verified application-level enforcement.

**Learning Outcomes**

Through this project, I explored:

Identity and Access Management fundamentals

Microsoft Entra user and group administration

Directory roles and administrative privileges

Role-Based Access Control (RBAC)

Least-privilege access design

Delegated administration

Organizational hierarchy management

Employee onboarding and offboarding concepts

Enterprise application integration and access design

Application-specific security group planning

**Future Improvements**

Explore multifactor authentication (MFA) and authentication policies.

Expand employee onboarding and offboarding procedures.

Implement and test resource-level access permissions in a supported environment.

Explore additional identity security and administrative controls.

Configure and test enterprise application SSO integrations.

Implement group-based application assignments in an appropriately licensed environment.

This project is intended for educational and professional development purposes.
