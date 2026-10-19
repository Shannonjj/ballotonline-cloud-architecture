# Cloud Deployment Architecture — BallotOnline (CCA 630)

Architecture planning project from my UMGC CCA 630 coursework. BallotOnline is the case-study company used across the UMGC cloud program.

## Final Cloud Deployment Architecture Plan
- Compared **AWS, Microsoft Azure, and Google Cloud** as candidate platforms for four workloads: **email, development, backup, and archiving**
- Selected providers per workload based on performance, capacity, and cost against documented requirements

## Cloud Service Offering for E-Mail
Requirements-driven design for a hosted email service:
- **5,000 mailboxes, scalable to 10,000**
- **Recovery Time Objective (RTO): 15 minutes**
- **Recovery Point Objective (RPO): 0**
- Multi-factor authentication and encryption requirements
- Evaluated **Amazon WorkMail vs. Gmail vs. Microsoft Office 365** against the requirements
- Included an email flow architecture using **Amazon SES** with **Amazon S3**

## Supporting analyses
- **Growth Projection Analysis** for capacity planning
- Cloud user and administrator training presentation materials

## Skills demonstrated
- Multi-cloud architecture evaluation and workload placement
- Requirements engineering (RTO/RPO, scale, security controls)
- Cloud email platform selection


---
*Shannon Javone Jenkins — MS in Cloud Computing Architecture, University of Maryland Global Campus (UMGC). Graduate coursework and hands-on labs.*
