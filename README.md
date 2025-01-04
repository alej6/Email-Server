# Email-Server
<h2>Overview</h2>
<p>This email server project was assigned as part of <strong>ITC4200: Network Security</strong> at Northeastern University. This repository serves as a comprehensive write-up for the project, documenting the steps taken to configure and test the server. For this project, I built an email server using Postfix, one of the most popular and robust mail transfer agents (MTAs). The server was configured on an Ubuntu virtual machine within a Hyper-V environment, following a series of steps to ensure basic functionality and compatibility with external domains.
  
The primary objectives of the project were:
<ul>
<li><strong>Understanding Email Protocols:</strong> Gain familiarity with protocols such as SMTP, IMAP, and POP3, and how they interact within an email server.</li>
<li><strong>Configuring a Mail Server:</strong> Install and configure Postfix as the MTA and test its ability to send and receive emails locally and externally.</li>
<li><strong>Securing Communications:</strong> Explore security measures, including authentication, encryption, and access restrictions.</strong></li>
<li><strong>Troubleshooting and Testing:</strong> Diagnose common issues using log files and testing tools to ensure the server's proper operation.</li>

This project challenged my ability to research, adapt, and problem-solve independently, simulating real-world scenarios where resources and instructions are often scattered or incomplete.
</ul>
</p>

<h2> Video Demonstration</h2>
<p>
  You can view a video demonstration of my server setup and functionality 
  <a href="https://drive.google.com/file/d/1EJo_It9cXRjq0E6PVVA7WHkvOxcNirws/view?usp=sharing" target="_blank">
    here
  </a>.
</p>


<h2>Setting up the mail server </h2>
<p>To complete this assignmenet, I followed these key steps: </p>
<ol>
  <li><strong> Created a new VM in Hyper-V</strong></li>
  <ul>
    <li>This provided a clean environment to install and configure the mail server</li>
  </ul>
  <li><strong>Installed Post Fix</strong></li>
  <ul>
    <li> Used the package manager download and install Postfix</li>
    <li>Selected the appropriate mail server configuration during installation</li>
    <li>Edited the main.cf configuration file to add my domain name to the parameters</li>
  </ul>

  <img width="722" alt="main cf" src="https://github.com/user-attachments/assets/52cc8701-d356-42e4-bc1f-ca20c5d670d4" />
<p> In the screenshot shown above, the main.cf file now includes my domain name.  </p>

<li><strong> Tested mail server installation </strong></li>
<ul>
  <li> Installed the mail utility to test email functionality</li>
  <li> Used this to verify the successful setup of local email communication</li>
</ul>
</ol>

<img width="735" alt="mail ss" src="https://github.com/user-attachments/assets/cf7e0726-1168-47f7-b9a0-11f6e3297bb9" />

<h2>Takeaways </h2>
<p> This project provided invaluable hands-on experience and reinforced several key concepts related to email server configuration and network security. Through this assignment, I was able to install and configure an email server (Postfix) from scratch, including modifying configuration files like main.cf to control server behavior. Not only that, but working with protocols such as SMTP and exploring how emails are sent, received, and processed gave me a deeper understanding of the email ecosystem.This project has significantly enhanced my confidence in setting up and administering email servers, a skill that will be directly applicable to my future roles in IT and network security.
 </p>
