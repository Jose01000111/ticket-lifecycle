<p align="center">
<img src="https://i.imgur.com/9dYCotk.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
My goal with this project is to replicate a real-world IT helpdesk environment using osTicket on an Azure VM. I want to get hands-on with a ticketing system that IT teams actually use, practice troubleshooting workflows, SLAs, and helpdesk operations, and build confidence in handling service requests—all while preparing for the CompTIA A+ certification. At this stage, I’m not just learning concepts—I’m applying them. This setup will help me think like an IT professional, work through realistic support scenarios, and sharpen the skills I’ll need when I land my first IT role<br />


<h2>Install osTicket on an Azure VM</h2>

- ### Steps to Install osTicket on an Azure VM
- ####  Step 1: Deploy an Azure Virtual Machine
<p style="text-indent: 40px;"> Open Azure and navigate to Virtual Machines. 
</p>

<p style="text-indent: 40px;">Create a new Linux (Ubuntu) or Windows Server VM.</p>

<p style="text-indent: 40px;">Select a Standard_B2s instance or better.

<p style="text-indent: 40px;">Enable public IP access for remote connection.

<p style="text-indent: 40px;">Choose SSH (Linux) or RDP (Windows) for authentication.

<p style="text-indent: 40px;">Deploy the VM and wait for provisioning to complete.

- #### Step 2: Connect to the VM
<p style="text-indent: 40px;">Linux: Use SSH to connect.

<p style="text-indent: 40px;">Windows: Use Remote Desktop (RDP) to log in.

- #### Step 3: Install Required Software Stack
<p style="text-indent: 40px;">Linux: Install Apache, MySQL, and PHP (LAMP stack).

<p style="text-indent: 40px;">Windows: Install IIS, MySQL, and PHP.

<p style="text-indent: 40px;">Verify that the web server and database are functioning correctly.

- #### Step 4: Download and Configure osTicket
<p style="text-indent: 40px;"> Download the latest osTicket release.

<p style="text-indent: 40px;"> Move the files to the web server’s root directory.

<p style="text-indent: 40px;">Set correct file permissions to allow execution.

- #### Step 5: Set Up the MySQL Database
<p style="text-indent: 40px;">Create a MySQL database for osTicket.

<p style="text-indent: 40px;">Create a database user with the necessary privileges.

- #### Step 6: Run the osTicket Installer
<p style="text-indent: 40px;">Open a web browser and access http://your-vm-ip/osticket/setup/.

<p style="text-indent: 40px;">Enter database credentials and set up an admin account.

<p style="text-indent: 40px;">Complete the installation and remove the setup directory for security.

- #### Step 7: Customize osTicket for IT Helpdesk Training
<p style="text-indent: 40px;">Configure ticket categories (e.g., Hardware, Software, Network).

<p style="text-indent: 40px;">Set up Service-Level Agreements (SLAs) to define response times.

<p style="text-indent: 40px;">Assign user roles (Admin, Technician, End User) for realistic workflows.

<p style="text-indent: 40px;">Start logging and resolving test tickets to simulate real IT scenarios.

- #### Step 8: Secure the System
<p style="text-indent: 40px;">Configure firewall rules to restrict access.

<p style="text-indent: 40px;">(Optional) Install an SSL certificate for secure access.

- #### Step 9: Simulate an IT Support Environment
Submit tickets via http://your-vm-ip/osticket/.

<p style="text-indent: 40px;">Use the Admin Panel (/scp/) to manage and resolve tickets.

<p style="text-indent: 40px;">Analyze ticket history to identify recurring issues and resolution trends.

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
