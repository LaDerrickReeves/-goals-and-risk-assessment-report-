<h1>  Scope, goals, and risk assessment 
report</h1>

 

<h2>Description</h2>
Defining scope, goals, and performing a risk assessment is useful because it identifies critical assets and potential vulnerabilities.<br />





<h2> Scenario:</h2>

<p align="center">
 Botium Toys IT Audit Scenario: 
  
 Botium Toys is a small U.S. business that develops and sells toys. The business has a single physical location, which serves as their main office, storefront, and warehouse for their products. However, Botium Toys’ online presence has grown, attracting customers in the U.S. and abroad. As a result, their information technology (IT) department is under increasing pressure to support their online market worldwide.

The manager of the IT department has decided that an internal IT audit needs to be conducted. She is concerned about maintaining compliance and business operations as the company grows without a clear plan. She believes an internal audit can help better secure the company’s infrastructure and identify and mitigate potential risks, threats, or vulnerabilities to critical assets. The manager is also interested in ensuring compliance with regulations related to processing and accepting online payments, as well as conducting business in the European Union (E.U.).

The IT manager starts by implementing the National Institute of Standards and Technology Cybersecurity Framework (NIST CSF), establishing an audit scope and goals, listing assets currently managed by the IT department, and completing a risk assessment. The goal of the audit is to provide an overview of the risks and/or fines that the company might experience due to the current state of their security posture.



<br />
<br />
> ## Additional Comments

The potential impact from the loss of an asset is rated as **medium**, because the IT department does not know which assets would be at risk. The risk to assets or fines from governing bodies is **high** because Botium Toys does not have all of the necessary controls in place and is not fully adhering to best practices related to compliance regulations that keep critical data private/secure.  

 **Specific Details:**  
 
 - Currently, all Botium Toys employees have access to internally stored data and may be able to access cardholder data and customers’ PII/SPII.
  
 - Encryption is not currently used to ensure confidentiality of customers’ credit card information that is accepted, processed, transmitted, and stored locally in the company’s internal database.
   
 - Access controls pertaining to least privilege and separation of duties have not been implemented.
     
 - The IT department has ensured availability and integrated controls to ensure data integrity.
     
 - The IT department has a firewall that blocks traffic based on an appropriately defined set of security rules.

 - Antivirus software is installed and monitored regularly by the IT department.
    
- The IT department has not installed an intrusion detection system (IDS).

- There are no disaster recovery plans currently in place, and the company does not have backups of critical data.
    
- The IT department has established a plan to notify E.U. customers within 72 hours if there is a security breach. Additionally, privacy policies, procedures, and processes have been developed and are enforced among IT department members and other employees to properly document and maintain data.

- Although a password policy exists, its requirements are nominal and not in line with current minimum password complexity requirements (e.g., at least eight characters, a combination of letters and at least one number; special characters).
  
 - There is no centralized password management system that enforces the password policy’s minimum requirements, which sometimes affects productivity when employees/vendors submit a ticket to the IT department to recover or reset a password.
   
 - While legacy systems are monitored and maintained, there is no regular schedule in place for these tasks, and intervention methods are unclear.
   
- The store’s physical location, which includes Botium Toys’ main offices, storefront, and warehouse of products, has sufficient locks, up-to-date closed-circuit television (CCTV) surveillance, as well as functioning fire detection and prevention systems.

<br />
<br />
>  Controls Assessment Checklist

| Control | Yes | No |
|---------|:---:|:--:|
| Least Privilege | ☐ | ✔ |
| Disaster Recovery Plans | ☐ | ✔|
| Password Policies | ☐ | ✔ |
| Separation of Duties | ☐ | ✔ |
| Firewall | ✔ | ☐ |
| Intrusion Detection System (IDS) | ☐ | ✔ |
| Backups | ☐ | ✔ |
| Antivirus Software | ✔| ☐ |
| Manual Monitoring, Maintenance, and Intervention for Legacy Systems | ☐ | ✔ |
| Encryption | ☐ | ✔ |
| Password Management System | ☐ | ✔ |
| Locks (Offices, Storefront, Warehouse) | ✔ | ☐ |
| Closed-Circuit Television (CCTV) Surveillance | ✔ | ☐ |
| Fire Detection/Prevention (Fire Alarm, Sprinkler System, etc.) | ✔ | ☐ |


<br />
<br />
>  PCI DSS Controls Checklist

| Best Practice | Yes | No |
|---------------|:---:|:--:|
| Only authorized users have access to customers’ credit card information | ☐ | ✔ |
| Credit card information is stored, accepted, processed, and transmitted internally in a secure environment | ☐ | ✔ |
| Implement data encryption procedures to better secure credit card transaction touchpoints and data | ☐ | ✔ |
| Adopt secure password management policies | ☐ | ✔ |


<br />
<br />
> ## GDPR Controls Checklist

| Best Practice | Yes | No |
|---------------|:---:|:--:|
| E.U. customers’ data is kept private/secured | ☐ | ✔ |
| There is a plan in place to notify E.U. customers within 72 hours if their data is compromised / there is a breach | ✔ | ☐ |
| Ensure data is properly classified and inventoried | ☐ | ✔ |
| Enforce privacy policies, procedures, and processes to properly document and maintain data | ✔| ☐ |

<br />
<br />
> ## SOC Controls Checklist (SOC Type 1 & Type 2)

| Best Practice | Yes | No |
|---------------|:---:|:--:|
| User access policies are established | ☐ | ✔ |
| Sensitive data (PII/SPII) is confidential/private | ☐ | ✔ |
| Data integrity ensures the data is consistent, complete, accurate, and has been validated | ✔ | ☐ |
| Data is available to individuals authorized to access it | ✔ | ☐ |

<br />
<br />
 Recommendations:  <br/>


 1. Implement least privilege access policies and establish separation of duties to minimize the attack surface.  
> 2. Develop a comprehensive disaster recovery plan and implement routine backups for critical data.  
> 3. Introduce data encryption to protect stored and transmitted PII, SPII, and credit card data.  
> 4. Implement an intrusion detection system (IDS) to detect and respond to malicious activity in real time.  
> 5. Deploy a centralized password management system to enforce strong password policies and streamline resets.  
> 6. Classify and inventory all sensitive data to ensure compliance with GDPR and SOC 2 principles.  
> 7. Regularly schedule monitoring and maintenance of legacy systems to reduce vulnerabilities and operational risks.



<hr>
<p><strong>Source:</strong> Scenario adapted from <a href="https://www.coursera.org" target="_blank">Coursera</a> course materials.

> **Learning Source:** I completed the [Google Cybersecurity Certificate](https://www.coursera.org/professional-certificates/google-cybersecurity) program on Coursera, which helped me understand and apply the concepts demonstrated in this scenario.  
</p>


</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
