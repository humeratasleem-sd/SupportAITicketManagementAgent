# SupportPilot – AI-Powered Customer Support & Ticket Resolution Platform

SupportPilot is an AI-powered customer support and ticket management platform developed as part of the **Infosys Springboard Virtual Internship 7.0 – Batch 1, Group 2**.

The platform is designed to automate and simplify the complete support-ticket lifecycle, from ticket creation and classification to knowledge retrieval, AI-assisted resolution, escalation, customer communication, analytics, and closure.

---

## Project Links

**Live Application:**  
https://sitm-deploy.vercel.app

**GitHub Repository:**  
https://github.com/ananyaravikumar548/Infosys_Support-AI-Ticket-Management-.git

---

## Project Objective

The main objective of SupportPilot is to improve customer support efficiency by reducing repetitive manual work and assisting support teams with AI-based ticket processing.

The system can:

- Create and manage customer support tickets
- Classify tickets automatically
- Identify category and sub-category
- Analyse priority and severity
- Analyse customer sentiment
- Find similar historical tickets
- Retrieve relevant knowledge-base information
- Generate AI-based troubleshooting resolutions
- Validate AI confidence before automated resolution
- Escalate complex or low-confidence issues to human agents
- Integrate with Jira
- Send automated email notifications
- Monitor SLA and ticket progress
- Provide dashboards and analytics

---

## System Users

### Customer

Customers can:

- Create support tickets
- Enter issue details
- Upload attachments
- View submitted tickets
- Track ticket status
- View AI-generated resolutions
- Accept a resolution
- Request human assistance
- Reopen unresolved tickets
- Receive support notifications

### Support Agent

Support agents can:

- View assigned tickets
- Review customer information
- Review AI analysis
- Review suggested resolutions
- Investigate escalated issues
- Communicate with customers
- Update ticket status
- Resolve tickets

### Support Manager

Managers can:

- Monitor ticket queues
- View unassigned tickets
- Assign and reassign tickets
- Monitor workload
- Track escalations
- Review routing information
- Monitor AI diagnosis and confidence

### Administrator

Administrators can:

- Manage users and roles
- Manage categories and priorities
- Configure SLA policies
- Manage knowledge-base settings
- Manage automation rules
- Monitor AI performance
- Generate reports
- Manage system settings
- Review audit information

---

# Complete Ticket Workflow

Customer
   ↓
Create Ticket
   ↓
Validation
   ↓
Ticket Created
   ↓
AI Analysis
   ↓
Classification
   ↓
Priority + Severity + Sentiment
   ↓
Similar Ticket Search
   ↓
Knowledge Retrieval / RAG
   ↓
AI Resolution Generation
   ↓
Confidence Validation
   ↓
 ┌───────────────────────┐
 │                       │
High Confidence       Low Confidence
 │                       │
 ↓                       ↓
AI Resolution        Escalation
 │                       │
 ↓                       ↓
Customer Confirmation  Human Agent
 │                       │
 └───────────┬───────────┘
             ↓
         Resolution
             ↓
       Customer Confirmation
             ↓
           Closed
