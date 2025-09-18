# Entra ID IAM & Policy Enforcement Project

### Brief Introduction
Implemented a comprehensive identity and access management solution in Azure to enforce organizational security policies, strengthen account protections, and monitor user activity. The project focused on aligning technical controls with internal Access Control and Password Policies while adhering to ISO 27001 best practices.

## Skills Learned
- Designing and enforcing least-privilege access controls in Entra ID
- Configuring password and authentication policies with complexity and lockout settings
- Implementing multi-factor authentication via Security Defaults
- Monitoring and auditing user activity using Sign-in and Audit Logs
- Integrating Sign-in and Audit Logs into Microsoft Sentinel for oversight
- Mapping technical controls to compliance standards (ISO 27001)

## Steps Taken
1. Created users and groups in Entra ID, assigning RBAC roles to enforce least-privilege access.
   
   <img width="596" height="221" alt="image" src="https://github.com/user-attachments/assets/ee5c0c89-3a90-471d-9ca2-2986428a4ef5" /> <br>
   *Ref 1: Added users*

   <img width="851" height="207" alt="image" src="https://github.com/user-attachments/assets/c3ab416b-5613-46db-83b5-ee74bed7551e" /> <br>
   *Ref 1a: Groups created*

   <img width="1189" height="366" alt="image" src="https://github.com/user-attachments/assets/305b16c5-2188-4994-a0d0-207fef1a5abc" /> <br>
   *Ref 1b: User assigned a role*

2. Enabled Security Defaults to enforce MFA requirements for all users. <br>

    <img width="424" height="392" alt="Screenshot 2025-09-18 163014" src="https://github.com/user-attachments/assets/a01450b9-7f50-48cd-bf15-38f385be9ea2" /> <br>
   *Ref 2: Security default enabled for MFA*

3. Configured password complexity and lockout policies in Entra ID.
   
   <img width="680" height="446" alt="Screenshot 2025-09-18 163228" src="https://github.com/user-attachments/assets/18c5f276-0c0e-4645-8f75-f3973dd5ab99" /> <br>
  *Ref 3: Password lockout configuration*

    <img width="692" height="157" alt="Screenshot 2025-09-18 163318" src="https://github.com/user-attachments/assets/622a73f9-46cc-4196-a1ff-ba5900be066b" /> <br>
  *Ref 3a: Password complexity configuration*

4. Integrated Sign-in and Audit Logs with Microsoft Sentinel through a Log Analytics Workspace for monitoring.
   <img width="849" height="191" alt="image" src="https://github.com/user-attachments/assets/003fe1e1-13e6-49f9-b539-4a5a229c8d0e" /> <br>
   *Ref 4: Captured logs*

5. Developed policies and SOPs for access control, password management, and elevated permission requests.

## Final Deliverables
- [Access Control Policy](https://github.com/sylenajb/Azure-IAM-Policy-Enforcement-Project-/blob/main/Azure%20Access%20Control%20Policy.pdf)
- [Monitoring & Audit Policy](https://github.com/sylenajb/Azure-IAM-Policy-Enforcement-Project-/blob/main/Azure%20Monitoring%20%26%20Audit%20Policy.pdf)
- [Acceptable Use Policy](https://github.com/sylenajb/Azure-IAM-Policy-Enforcement-Project-/blob/main/Azure%20Environment%20Acceptable%20Use%20Policy%20(AUP).pdf)
- [Password & Authentication Policy](https://github.com/sylenajb/Azure-IAM-Policy-Enforcement-Project-/blob/main/Azure%20Password%20%26%20Authentication%20Policy.pdf)
- ISO 27001 Control Mapping

