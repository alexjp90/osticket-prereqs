# osticket-prereqs
<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Install osTicket with Prerequisites](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Computer)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)
- macOS
- Linux (Ubuntu, Fedora, Debian, etc.)

<h2>List of Prerequisites</h2>

- Item 1. Operating System:

    Linux-based OS (Ubuntu, CentOS, Debian, etc.)
    Windows Server (with WAMP/XAMPP)
  
- Item 2. Web Server:

    Apache (Preferred) or Nginx
    IIS (for Windows-based setups)
  
- Item 3. PHP: Version 8.0 - 8.1 (Recommended)

    Required extensions:
        mysqli (MySQL Improved)
        gd (for image processing)
        mbstring (multibyte string functions)
        xml (XML processing)
        imap (for email fetching)
        json (JSON support)
        intl (Internationalization)
        apcu (for caching - optional but recommended)
  
- Item 4. Additional Requirements

    Storage: At least 2GB of disk space (depends on ticket volume).
    Memory: 2GB+ RAM (More for larger deployments).
    SMTP/IMAP: Required for email fetching and sending notifications.
    SSL Certificate: Recommended for security (especially for production).
  
- Item 5. Optional Requirements

    Cron Job (Linux) or Task Scheduler (Windows) – Needed for automated tasks like email fetching.
    Composer – Required if installing via Git.

<h2>Installation Steps</h2>

<p>
![Screenshot (58)](https://github.com/user-attachments/assets/9e98a465-ca89-4a86-ba6f-93d7b53223b4)

</p>
<p>
1 Create a Virtual Machine (VM)

    Use VirtualBox, VMware, or Hyper-V.
    Allocate 2+ CPU cores, 2GB+ RAM, and 20GB+ storage.
    Install a Linux OS (Ubuntu 22.04 recommended) or Windows Server.
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
