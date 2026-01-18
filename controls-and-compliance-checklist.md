# Controls and Compliance Checklist

This document presents a security controls and compliance assessment for Botium Toys, based on best practices in cybersecurity.

---

## Controls Assessment Checklist

Select **“Yes”** or **“No”** to answer: *Does Botium Toys currently have this control in place?*

| Control | Yes | No | Explanation |
|---------|-----|----|-------------|
| Least Privilege | | X | Currently, all employees have access to customer data; privileges need to be limited to reduce the risk of a breach. |
| Disaster Recovery Plans | | X | There are no disaster recovery plans in place. These need to be implemented to ensure business continuity. |
| Password Policies | | X | Employee password requirements are minimal, which could allow a threat actor to more easily access secure data/other assets via employee work equipment/the internal network. |
| Separation of Duties | | X | Needs to be implemented to reduce the possibility of fraud/access to critical data, since the company CEO currently runs day-to-day operations and manages payroll. |
| Firewall | X | | The existing firewall blocks traffic based on an appropriately defined set of security rules. |
| Intrusion Detection System (IDS) | | X | The IT department needs an IDS in place to help identify possible intrusions by threat actors. |
| Backups | | X | The IT department needs to have backups of critical data in case of a breach to ensure business continuity. |
| Antivirus Software | X | | Antivirus software is installed and monitored regularly by the IT department. |
| Manual Monitoring, Maintenance, and Intervention for Legacy Systems | | X | Legacy systems are monitored and maintained, but there is not a regular schedule, and procedures/policies related to intervention are unclear, which could place these systems at risk. |
| Encryption | | X | Encryption is not currently used; implementing it would provide greater confidentiality of sensitive information. |
| Password Management System | | X | There is no password management system currently in place; implementing this control would improve IT department/employee productivity in case of password issues. |
| Locks (offices, storefront, warehouse) | X | | Physical security is sufficient, including locks at all locations. |
| CCTV Surveillance | X | | CCTV is installed and functioning at the store’s physical location. |
| Fire Detection/Prevention | X | | Botium Toys’ physical locations have a functioning fire detection and prevention system. |

---

## Compliance Checklist

Select **“Yes”** or **“No”** to answer: *Does Botium Toys currently adhere to this compliance best practice?*

### Payment Card Industry Data Security Standard (PCI DSS)

| Best Practice | Yes | No | Explanation |
|---------------|-----|----|-------------|
| Only authorized users have access to customers’ credit card information | | X | Currently, all employees have access to internal data, including credit card information. |
| Credit card information is accepted, processed, transmitted, and stored internally in a secure environment | | X | Credit card information is not encrypted; all employees have access to internal data. |
| Implement data encryption procedures | | X | Encryption is not currently used to ensure confidentiality of customers’ financial information. |
| Adopt secure password management policies | | X | Password policies are minimal, and no password management system exists. |

---

### General Data Protection Regulation (GDPR)

| Best Practice | Yes | No | Explanation |
|---------------|-----|----|-------------|
| E.U. customers’ data is kept private/secured | | X | Encryption is not currently used to ensure confidentiality. |
| Plan in place to notify E.U. customers within 72 hours of a breach | X | | There is a plan to notify E.U. customers of a data breach. |
| Ensure data is properly classified and inventoried | | X | Current assets have been inventoried/listed, but not classified. |
| Enforce privacy policies, procedures, and processes | X | | Privacy policies, procedures, and processes are enforced among IT team members and employees as needed. |

---

### System and Organization Controls (SOC type 1, SOC type 2)

| Best Practice | Yes | No | Explanation |
|---------------|-----|----|-------------|
| User access policies are established | | X | Controls of Least Privilege and Separation of Duties are not in place; all employees have access to internally stored data. |
| Sensitive data (PII/SPII) is confidential/private | | X | Encryption is not currently used. |
| Data integrity ensures consistency, completeness, accuracy, and validation | X | | Data integrity exists. Authorization needs to be limited to only the individuals who need access. |

---

## Recommendations

Multiple controls need to be implemented to improve Botium Toys’ security posture and better ensure the confidentiality of sensitive information, including:  
**Least Privilege, disaster recovery plans, password policies, separation of duties, IDS, ongoing legacy system management, encryption, and password management system.**

To address compliance gaps, Botium Toys should also:  
- Properly classify assets  
- Implement encryption and access controls  
- Establish clear policies and monitoring procedures  

This will help improve security posture and protect sensitive information more effectively.
