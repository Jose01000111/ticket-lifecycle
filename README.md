<p align="center">
<img src="https://i.imgur.com/9dYCotk.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
My goal with this project is to replicate a real-world IT helpdesk environment using osTicket on an Azure VM. I want to get hands-on with a ticketing system that IT teams actually use, practice troubleshooting workflows, SLAs, and helpdesk operations, and build confidence in handling service requests—all while preparing for the CompTIA A+ certification. At this stage, I’m not just learning concepts—I’m applying them. This setup will help me think like an IT professional, work through realistic support scenarios, and sharpen the skills I’ll need when I land my first IT role<br />


<h2>Install osTicket on an Azure VM</h2>

- ### Steps to Install osTicket on an Azure VM
- ### Step 1: Deploy an Azure Virtual Machine
Log into Azure and navigate to Virtual Machines.

Create a Linux (Ubuntu) or Windows Server VM.

Choose a Standard_B2s or better instance for smooth performance.

Enable public IP access so I can reach it remotely.

Select SSH (Linux) or RDP (Windows) for authentication.

Deploy the VM and wait for it to spin up.

Step 2: Connect to the VM
Linux: SSH into the server.

Windows: Use Remote Desktop (RDP) to connect.

Step 3: Install the Required Software Stack
For Linux: Install Apache, MySQL, PHP (LAMP stack).

For Windows: Set up IIS, MySQL, and PHP.

Verify that the web server and database are running properly.

Step 4: Download and Configure osTicket
Download the latest osTicket release from GitHub.

Extract and move the files to the web server directory.

Adjust file permissions to ensure proper functionality.

Step 5: Set Up the Database
Create a MySQL database specifically for osTicket.

Create a database user and assign the necessary privileges.

Step 6: Complete the osTicket Installation
Open a browser and go to http://your-vm-ip/osticket/setup/.

Enter database credentials and create an admin account.

Finish the setup and remove the installation folder for security reasons.

Step 7: Customize osTicket for IT Helpdesk Training
Create ticket categories (e.g., Hardware Issues, Software Troubleshooting, Networking Problems).

Set up Service-Level Agreements (SLAs) to mimic response and resolution time policies.

Assign user roles (Admin, IT Technicians, End Users) to simulate real team structures.

Start logging test tickets, resolving them, and documenting troubleshooting steps.

Step 8: Secure and Optimize the System
Configure firewall rules to control access to the web interface.

(Optional) Implement SSL encryption for a secure, professional-grade setup.

Step 9: Simulate an IT Support Workflow
Open http://your-vm-ip/osticket/ to submit tickets and track requests.

Use the Admin Panel (/scp/) to manage and resolve issues.

Practice handling end-user requests, troubleshooting, and enforcing SLAs.

Review ticket history to analyze problem trends and resolution efficiency.
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

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />
