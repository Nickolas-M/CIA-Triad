# CIA Triad
The CIA Triad is a model used by organizations to design and develop their security systems and frameworks. 
It encompasses three core principles: Confidentiality, Integrity, and Availability. These principles act as 
the foundation for addressing and prioritizing security concerns within an organization.

## Confidentiality
Confidentiality ensures that sensitive information is protected from unauthorized access. It’s crucial that 
only individuals who have a legitimate need to know can access specific data. One way to manage this is by 
implementing a data classification system where information is categorized based on its sensitivity. 
This helps control access by providing clear guidelines on who can view or handle particular types of data.
It’s also important to regularly update user permissions to ensure that access rights remain aligned with 
current roles. As employees change positions or leave the organization, permissions should be adjusted accordingly. 
Tools like strong passwords, multi-factor authentication (MFA), and data encryption play a key role in preventing 
unauthorized access, especially for privileged or administrative accounts. Role-based access control is another 
effective approach, ensuring users only have access to the data they need to perform their duties, minimizing 
unnecessary exposure to sensitive information.

## Integrity
Integrity refers to maintaining the accuracy and trustworthiness of data throughout its lifecycle. This principle 
ensures that information remains unaltered, except by authorized individuals. Protecting data integrity is vital 
because even small errors or tampering can compromise decision-making and operational processes. To maintain integrity, 
organizations use methods such as checksums, cryptographic hash functions, and digital signatures to verify that data 
hasn’t been changed. Additionally, audit logs track access and modifications to sensitive data, providing transparency 
and accountability. These tools help identify any unauthorized changes and maintain the authenticity of data. An important 
aspect of integrity is non-repudiation, which ensures that actions such as sending a message or making a data change can 
be traced back to their origin, preventing parties from denying their involvement. This is essential for maintaining 
accountability in business processes.

## Availability
Availability ensures that data and systems are accessible when needed by authorized users. Without availability, 
even well secured data is useless. An organization must ensure its systems remain operational and that authorized users can 
access data without interruptions. For example, if a company’s systems go down due to a DDoS attack or critical files are 
locked by ransomware, it can severely disrupt business operations. To support availability, organizations employ strategies 
like redundancy (having backup systems in place), data backups, and disaster recovery plans. These help to ensure that if 
something goes wrong, the organization can recover quickly. Incident response plans also provide predefined steps for 
mitigating damage and restoring operations after an attack or failure. Additionally, implementing tools like firewalls, 
intrusion detection systems, and load balancing helps safeguard against disruptions and maintain system performance, 
even under attack.

Resources:
https://www.geeksforgeeks.org/the-cia-triad-in-cryptography/
https://www.fortinet.com/resources/cyberglossary/cia-triad
https://www.sailpoint.com/identity-library/cia-triad
