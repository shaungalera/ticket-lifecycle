<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
This tutorial outlines the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket.<br />


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

<h3>1.) Create Tickets as End-Users</h3>

- **Scenario 1:** Create a ticket as an end-user with the following details:
  - **Subject:** "Entire mobile/online banking system is down"
  - **Details:** Describe the issue briefly (e.g., "The entire mobile/online banking system is down, preventing users from accessing their accounts.")
 
![image](https://github.com/user-attachments/assets/ccab1960-8f0e-4036-8489-26305fe51255)

<h3>2.) Observe Ticket Properties as Help Desk Agent</h3>

- Log in as **Help Desk Agent (john)**.
- Observe the ticket’s properties:
  - **Priority:** Default value.
  - **Department:** Default department.
  - **SLA:** Default SLA.
  - **Assigned To:** Not yet assigned.
 
![image](https://github.com/user-attachments/assets/fa0da7dc-8f99-4f51-bc64-ad98aea846e9)

<h3>3.) Set Ticket Properties</h3>

- Update the ticket with the following properties:
  - **SLA:** Sev-A (1 hour, 24/7).
  - **Assigned To:** Online Banking Team.

![image](https://github.com/user-attachments/assets/c3e693d2-8875-402f-b3f6-e43daa20a14e)
![image](https://github.com/user-attachments/assets/bf7e3ac3-8a6f-4e6d-b285-e4be6209cee4)
![image](https://github.com/user-attachments/assets/343c2930-46eb-445b-ac73-1e39121c5186)

<h3>4.) Verify Ticket Permissions</h3>

- Log back in as **Help Desk Agent (john)**.
- Attempt to view or modify the ticket. Verify whether the changes are accessible or editable.

<h3>5.) Work the Ticket to Completion</h3>

- Log in as **Help Desk Agent (jane)**.
- Take ownership of the ticket, work the issue, and resolve it.
- Mark the ticket as **Closed** once the issue is resolved.

![image](https://github.com/user-attachments/assets/aaf05197-931c-4a40-bc9e-3c4a9f837d12)
![image](https://github.com/user-attachments/assets/18ca30da-8e7d-4eef-9e7f-f60fbfc5a5d2)
![image](https://github.com/user-attachments/assets/79904402-86de-41b9-9cd0-8df66f6a7473)

---

<h3>6.) Create Another Ticket as End-User</h3>

- **Scenario 2:** Create a ticket as an end-user with the following details:
  - **Subject:** "Accounting department needs Adobe upgrade, broken"
  - **Details:** Describe the issue briefly (e.g., "The Adobe software used by the accounting department is broken and needs an upgrade.")

![image](https://github.com/user-attachments/assets/853911b9-0d12-4717-a1a3-e5016a3fec25)

<h3>7.) Observe Ticket Properties as Help Desk Agent</h3>

- Log in as **Help Desk Admin (john)**.
- Observe the ticket’s properties:
  - **Priority:** Default value.
  - **Department:** Default department.
  - **SLA:** Default SLA.
  - **Assigned To:** Not yet assigned.
 
![image](https://github.com/user-attachments/assets/b39db87e-d0d9-4622-b6b0-e9bff92a5ed7)

<h3>8.) Set Ticket Properties and Work the Ticket to Completion</h3>

- Update the ticket with the following properties:
  - **SLA:** Sev-C (8 hours, M-F 8am-5pm).
  - **Assigned To:** John
  - **Department:** Support.
  - Take ownership of the ticket, work the issue, and resolve it.
  - Mark the ticket as **Closed** once the issue is resolved.
  
![image](https://github.com/user-attachments/assets/97d13a21-20d7-4c2f-8826-aeb0b8dbdc94)
![image](https://github.com/user-attachments/assets/cd134593-628c-4796-b3e9-c4fb99c1502c)
![image](https://github.com/user-attachments/assets/2c5081d2-fb2d-467b-a305-9564c4ae4ab2)
![image](https://github.com/user-attachments/assets/9b821641-f574-4ac0-b3e8-17e1b01dd9f4)
![image](https://github.com/user-attachments/assets/cf0f510f-d29e-4b0c-bcdf-f31e9680f5ef)
![image](https://github.com/user-attachments/assets/5f5ba8ea-c3fa-4d96-a9b0-961c29def2bc)

---

<h3>10.) Create a Final Ticket as End-User</h3>

- **Scenario 3:** Create a ticket as an end-user with the following details:
  - **Subject:** "CFO states he is unable to use laptop"
  - **Details:** Describe the issue briefly (e.g., "The CFO's laptop is not powering on, despite pressing the power button.")

![image](https://github.com/user-attachments/assets/c9df0bba-8a22-4337-8e70-f5db45e28c46)

<h3>11.) Observe Ticket Properties as Help Desk Agent</h3>

- Log in as **Help Desk Agent (john)**.
- Observe the ticket’s properties:
  - **Priority:** Default value.
  - **Department:** Default department.
  - **SLA:** Default SLA.
  - **Assigned To:** Not yet assigned.
 
![image](https://github.com/user-attachments/assets/f5947328-6b67-4835-bc5e-69bd5fc86df8)

<h3>12.) Set Ticket Properties</h3>

- Update the ticket with the following properties:
  - **SLA:** Sev-B (4 hours, 24/7).
  - **Department:** Support.
  - **Assigned To:** John Doe
 
![image](https://github.com/user-attachments/assets/4d0b54b6-94bd-43cb-a0c7-ff4e10f1e4c1)
![image](https://github.com/user-attachments/assets/6491e911-1d97-4402-b0f7-f683b991008a)

<h3>13.) Work the Ticket to Completion</h3>

- Log in as **Help Desk Agent (john)**.
- Take ownership of the ticket, work the issue, and resolve it.
- Mark the ticket as **Closed** once the issue is resolved.

![image](https://github.com/user-attachments/assets/d6457300-1d09-4f5e-b2b1-e709b9366ab4)
![image](https://github.com/user-attachments/assets/c3084336-0264-4e3f-9175-b65f1a084145)
![image](https://github.com/user-attachments/assets/b5c2f4a3-384e-4410-8951-89a9d181db82)

---

<h2>Conclusion</h2>

By following these steps, you have successfully demonstrated the lifecycle of a ticket from intake to resolution within osTicket. This lab highlights the importance of ticket properties, proper assignment, and resolution processes in a help desk environment.  
