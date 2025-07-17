<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
This tutorial demonstrates the full ticket lifecycle in osTicket, from the moment a user submits a ticket through assignment, communication, troubleshooting, and resolution. This process generally simulates a real-world IT help desk workflow.
osTicket.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Ticket Lifecycle Stages</h2>

- Intake
- Assignment and Communication
- Working the Issue
- Resolution

<h2>Lifecycle Stages</h2>

**INTAKE**
<img width="1920" height="631" alt="1" src="https://github.com/user-attachments/assets/426ab1a3-ed39-4568-a753-c1b6f98db2bb" />
<img width="1920" height="1041" alt="2" src="https://github.com/user-attachments/assets/e0b559a9-43cc-477c-8748-e3f55b6e58ef" />
<img width="846" height="489" alt="3" src="https://github.com/user-attachments/assets/eccb82ec-71f4-4f0d-8810-c1086ac4ad0b" />


- the above images shows the typical ticket submission proccess for an end-user through the user panel
- Ticket fields typically include:
  - Help Topic
  - Issue Summary
  - Message/Description
- After submission, the ticket appears in the system with a timestamp and a ticket number.

**AGENT VIEW AND CATAGOTIZATION**
<img width="1920" height="500" alt="5" src="https://github.com/user-attachments/assets/443044df-2679-4f2e-9a16-8c880fa95d17" />


- this is the typical dashboard for an agent showing all tickets organized into several catagories.
- From the Agent Dashboard, staff can view incoming tickets.
- Tickets are automatically or manually categorized to:
  - Open
  - Assigned
  - Overdue
  - Closed
- This ensures visibility and allows agents to prioritize their workload.

**WORKING THE ISSUE**
<img width="960" height="476" alt="6" src="https://github.com/user-attachments/assets/495ac265-c71b-4e3a-9320-65570ad0f54d" />
<img width="1920" height="1041" alt="7" src="https://github.com/user-attachments/assets/54600f0e-720d-41f1-ad18-c00d870e0d5c" />

- This is where tickets gets handled with options to assign a priority, department, user, and/or SLA so that it can be worked and directed efficiently
- When handling a ticket, agents can:
  - Assign it to a department or specific team
  - Set priority level (e.g., Low, Normal, High, Emergency)
  - Attach a Service Level Agreement (SLA) to enforce response deadlines
  - Communicate with the user via threaded messages, mostly updates
  - the threads can also be used for general updates or transparent internal communication, there is also internal notes which can be seen exclusively by agents and admins
- Communication typically happens in the comments and status gets updated until it is resolved

**RESOLUTION**
- Once the issue is resolved:
  - The agent updates the ticket status to Resolved or Closed
  - The system can trigger a confirmation or feedback request to the user
  - A full ticket history remains available for auditing, knowledge base creation, or SLA review

*This simulates the flow of how IT teams work through user issues. Leveraging osTicket’s built-in features, agents maintain clarity, admins track performance, and end-users experience professional service delivery.*
