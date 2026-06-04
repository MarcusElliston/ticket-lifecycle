<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

# osTicket - Ticket Lifecycle: Intake Through Resolution

This tutorial outlines the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket.

---

## Video Demonstration

- ### [YouTube: How to Create, Work, and Resolve Tickets Within osTicket](https://www.youtube.com)

---

## Environments and Technologies Used

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

---

## Operating Systems Used

- Windows 10 (21H2)

---

## Ticket Lifecycle Stages

- Intake
- Assignment and Communication
- Working the Issue
- Resolution

---

## Lifecycle Stages

### Stage 1: Intake — User Submits a Ticket

![Screenshot - End user portal with new ticket being submitted](SCREENSHOT_1_intake.png)

Open the end-user ticket portal at `localhost/osTicket` and log in as one of your users (e.g. Karen). Click **Open a New Ticket**, select a help topic such as **Business Critical Outage**, and describe the issue — for example, "the entire mobile banking system is down." Submit the ticket. This simulates how a real end user would report a problem to the help desk.

---

### Stage 2: Assignment and Communication

![Screenshot - Ticket detail view with SLA, department, and agent assigned](SCREENSHOT_2_assignment.png)

Log into the **Agent Panel** and open the ticket that was just submitted. Observe that it comes in with default settings. Update the ticket: set the **SLA Plan** to Sev-A (1 hour), assign the **Department** to System Administrators, and assign the ticket to an agent (e.g. Jane Doe). Post an internal note or reply to communicate the status with the team.

---

### Stage 3: Working the Issue

![Screenshot - Ticket thread showing agent replies and internal notes](SCREENSHOT_3_working.png)

As the assigned agent, work through the ticket by posting updates in the reply thread. Use **Post Reply** to communicate with the user and **Post Internal Note** for team-facing updates. This simulates the back-and-forth that happens during active troubleshooting — for example, coordinating with a vendor or escalating to Level II Support.

---

### Stage 4: Resolution

![Screenshot - Ticket status set to Resolved with final reply posted](SCREENSHOT_4_resolution.png)

Once the issue is resolved, post a final reply to the user explaining what was done. Change the ticket status from **Open** to **Resolved** using the dropdown at the bottom of the reply box, then click **Post Reply**. The ticket will move to the closed queue. You can view resolved tickets under **Tickets > Closed** in the Agent Panel.
