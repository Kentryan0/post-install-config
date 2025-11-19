<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Configure osTicket, post-installation](https://www.youtube.com/watch?v=Eh47MBlkBVQ)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

# osTicket Installation on Azure Windows VM



---

## ⚙️ Post-Install Configuration Objectives
After installation, the following configuration tasks were completed to fully prepare osTicket for use:

- **Secured the installation** by removing the setup directory  
- **Configured core system settings** (organization name, system email, time zone)  
- **Set up email integration** using SMTP/IMAP for ticket alerts and email-to-ticket functionality  
- **Created departments and help topics** to organize incoming support requests  
- **Added agents and assigned roles** based on responsibilities and permissions  
- **Configured ticket settings** including auto-responses, priority levels, and ticket numbering  
- **Created SLA plans** to define response/resolution deadlines  
- **Adjusted user settings** such as registration requirements  
- **Tested full ticket workflow** (creation → assignment → update → close)  

---

## 🛠️ Tools & Technologies Used
- **Microsoft Azure**  
- **Windows Server 2019/2022**  
- **IIS (Internet Information Services)**  
- **PHP 8**  
- **MySQL**  
- **Remote Desktop Protocol (RDP)**  
- **osTicket (open-source)**  

---

## 📸 Screenshots
(Add an image from your repo like this)

```markdown
![osTicket Dashboard](images/osticket-dashboard.png)
