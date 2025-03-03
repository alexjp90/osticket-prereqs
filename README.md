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


</p>
<p>
1 Create a Virtual Machine (VM)

    Use VirtualBox, VMware, or Hyper-V.
    Allocate 2+ CPU cores, 2GB+ RAM, and 20GB+ storage.
    Install a Linux OS (Ubuntu 22.04 recommended) or Windows Server.
</p>
<br />

<img ![Screenshot (55)](https://github.com/user-attachments/assets/5ac4ecc9-f5eb-4819-9d2a-54a899423037)

<img ![Screenshot (56)](https://github.com/user-attachments/assets/329d5e3a-dd43-4e4d-b44c-5b594ff63fd9)

</p>

<p>
Install Required Software (For Ubuntu)

Update your system:

sudo apt update && sudo apt upgrade -y

Install Apache, MySQL, and PHP (LAMP Stack)

sudo apt install apache2 mariadb-server php php-mysql php-mbstring php-xml php-imap php-gd php-json php-intl unzip -y

Enable and Start Services

sudo systemctl enable --now apache2 mysql

Secure MySQL

sudo mysql_secure_installation

    Set a strong root password.
    Remove anonymous users & test database..

</p>
<br />

<p>
<img ![Screenshot (57)](https://github.com/user-attachments/assets/b11a959d-f431-425d-a9cd-24048442d5dd)

</p>
<p>
As an entry-level IT Specialist at the Help Desk, I gained valuable experience in troubleshooting and resolving technical issues for end users. I quickly became adept at diagnosing hardware and software problems, guiding users through step-by-step solutions, and ensuring minimal downtime. One of my most rewarding challenges involved resolving a network connectivity issue for a department with multiple users, where I systematically tested network cables, reset routers, and reconfigured settings to restore connectivity. By maintaining clear communication with users, I ensured they were informed throughout the process, building trust and confidence. Additionally, I gained proficiency in using ticketing systems to manage and prioritize requests, ensuring timely resolutions. This hands-on experience strengthened my problem-solving skills and deepened my understanding of IT systems and support..
</p>
<br />
