<img alt="1" src="https://github.com/giovannibriones/osticket-ticket-resolution/assets/163789590/b1eeb928-eb01-42ce-b0b2-f081d93274af"/>

</p>

<h1> osTicket - Ticket Resolution and Troubleshooting </h1>


<p> This tutorial is designed to guide you through osTicket, a powerful open-source help desk solution, focusing on ticket resolution and troubleshooting. The ticket lifecycle will be explored, from the beginning of the matter to resolution, and troubleshooting strategies will be examinined to address common issues. This tutorial has as a goal to empower IT professionals, help desk agents, and support teams to navigate challenges without interruption, making sure a smooth and effective support experience is had for end-users.</p>

<h2>Prerequisites</h2>

- <a href="https://github.com/giovannibriones/osticket-prereqs"> osTicket - Prerequisites and Installation </a>

<h2>Main Objectives</h2>

<h4>Mastering Ticket Resolution</h4>

- Understand the complete lifecycle of a ticket within osTicket, from the beginning of the intake process to its successful resolution.

<h4>Efficient Troubleshooting Techniques</h4>

- Explore and integrate troubleshooting strategies for common IT issues, ensuring quick and effective problem-solving.

<h4>Enhancing User Satisfaction</h4>

- Learn how to provide timely and effective support to end-users, promoting a positive experience and minimizing downtime.

<h4>Building a Knowledge Base</h4>

- Develop a comprehensive knowledge base that records common issues and their resolutions, empowering both support teams and end-users.



<h2>Environments and Technologies Used</h2>

- osTicket
- Microsoft Azure (Virtual Machines)
- Remote Desktop
- Active Directory Domain Services

<h2>Operating Systems Used </h2>

- Windows Server 2022
- Windows 10 (22H2)



<h1>Tickets</h1>

<h3>Scenario A: Granting Admin Rights</h3>

<p><strong>User:</strong> James Holden</p>

<h4>Background:</h4>



<p>James Holden, a senior software developer, has successfully obtained approval for elevated administrative rights. As the IT administrator, your task is to grant James the necessary permissions while ensuring a secure and controlled activation process.
</p>

<br>

<img width="593" alt="2" src="https://github.com/giovannibriones/osticket-ticket-resolution/assets/163789590/88584131-ae93-4623-804a-72763854e930">


<br>
<br>

<h3>Approach to Resolution:</h3>

<h5> Verification</h5>

- Validate James's identity and admin rights approval.

<h5> Access Control Configuration:</h5>

- Once verification is done, modify James's user profile and assign the appropriate administrative privileges.
- Ensure that his machine allows him remote access

<img width="300" alt="3" src="https://github.com/giovannibriones/osticket-ticket-resolution/assets/163789590/aba767a8-c7b2-42c6-82a3-dfaa70d3f1a8">


<p><strong>.</strong></p>
<p><strong>.</strong></p>

<p><strong>Configure specific permissions based on James's approved request, such as adding him to the Remote Desktop Users Group</strong></p>

<img width="300" alt="4" src="https://github.com/giovannibriones/osticket-ticket-resolution/assets/163789590/d80d9c28-d583-482a-a568-c546dac40360">


<p><strong>.</strong></p>
<p><strong>.</strong></p>

<h5>Communication:</h5>

- Inform James that his admin rights have been granted successfully.
- Include a summary of the specific permissions he now holds and any relevant guidelines for responsible use.

<h5>Documentation & Closure:</h5>

- Document the completion of the admin rights activation in osTicket.
-Close the ticket, indicating that the task has been completed, and provide documentation for future audits or inquiries.

<img width="592" alt="5" src="https://github.com/giovannibriones/osticket-ticket-resolution/assets/163789590/890ddf6a-537a-4f7f-a1f8-1b7baf41d3b9">



<p><strong>.</strong></p>
<p><strong>.</strong></p>

<h3>Scenario B: Addressing Slow System Performance </h3>

<p><strong>User:</strong> Camina Drummer</p>

<h4>Background:</h4>


<p>Camina Drummer, a marketing manager, submits a ticket through osTicket, reporting a low memory warning and persistent slow performance on her workstation. As the IT helpdesk agent, your objective is to diagnose and resolve the issue to enhance Camina's overall system responsiveness.

</p>

<br>

<img width="593" alt="6" src="https://github.com/giovannibriones/osticket-ticket-resolution/assets/163789590/687afb1c-76bf-4de4-b9bc-22568a3f4772">

<br>
<br>

<h3>Approach to Resolution:</h3>

<h5> Initial Assessment:</h5>

- Engage in a threaded discussion to gather more information about the specific performance issues Camina is encountering.
- Request details such as recent software installations, background processes, and any error messages she might have encountered

<img width="592" alt="7" src="https://github.com/giovannibriones/osticket-ticket-resolution/assets/163789590/cda80fbc-d69e-49b5-81a6-43c5cf550ba1">



<h5> Remote Diagnosis:</h5>

- Utilize a remote desktop connection to conduct a  diagnosis of Camina's workstation.

<h3> Specific Problem Identified:</h3>

<p>Camina Drummer's workstation is experiencing slow performance and low memory warnings mainly due to not having enough RAM for her demanding marketing applications. These include graphic design and video editing software, along with many browser tabs open at once. A lack of regular cleanup, like deleting temporary files and optimizing disk space, has also made the system slower over time.</p>

<h3> Resolution Steps:</h3>

- Go to add or remove programs and delete any unnecessary applications

<img width="400" alt="8" src="https://github.com/giovannibriones/osticket-ticket-resolution/assets/163789590/fa48f047-8783-4000-8219-93a4f96b7be9">

<p><strong>.</strong></p>
<p><strong>.</strong></p>


<p><strong>Check Task Manager to identify resource-intensive processes, unnecessary apps at startup, and potential bottlenecks affecting system performance.</strong></p>

- Empty the recycling bin to free up some disk space

<img width="500" alt="9" src="https://github.com/giovannibriones/osticket-ticket-resolution/assets/163789590/b73891c7-69f7-4b12-9722-2eb14b0fdbdc">


<p><strong>.</strong></p>
<p><strong>.</strong></p>

<p><strong>Open the Disk Cleanup application and perform a cleanup.</strong></p>

<img width="500" alt="10" src="https://github.com/giovannibriones/osticket-ticket-resolution/assets/163789590/4b86c677-7f28-4261-b345-b46340195984">


<p><strong>.</strong></p>
<p><strong>.</strong></p>

<p><strong>Go to Windows Features and turn off features not needed by the user</strong></p>

- After performing the tasks, diagnose the performance of the workstation 

<img width="500" alt="11" src="https://github.com/giovannibriones/osticket-ticket-resolution/assets/163789590/b698acd7-adf2-4a5e-9023-76909444663d">



<h5>Documentation & Closure:</h5>

- Inform Camina through osTicket of the initial assessment findings.
- Document the troubleshooting steps taken within osTicket, detailing the date and specifics of each action.
- Close the ticket within osTicket when Camina confirms the satisfactory resolution of the slow system performance issue or when the case is deemed resolved based on the follow-up assessments.

<img width="591" alt="12" src="https://github.com/giovannibriones/osticket-ticket-resolution/assets/163789590/b90f26fb-7896-4c7c-bc0a-e6b60c3ec3e2">



<p><strong>.</strong></p>
<p><strong>.</strong></p>

<h3>Scenario C: Laptop Camera Not Working on Windows 11</h3>

<p><strong>User:</strong> Alex Kamal</p>

<h4>Background:</h4>


<p>Alex Kamal, a sales representative, submits a ticket through osTicket, reporting that the integrated camera on his laptop is not functioning properly after upgrading to Windows 11. Alex relies on video calls for client meetings and needs a prompt resolution to ensure uninterrupted communication.

</p>

<br>

<img width="593" alt="13" src="https://github.com/giovannibriones/osticket-ticket-resolution/assets/163789590/d6e44982-0360-4e40-b62d-fa340d2875fc">



<br>
<br>

<h3>Approach to Resolution:</h3>

<h5> Initial Assessment:</h5>

- Engage in a threaded discussion within osTicket to gather more information about the issue.

<img width="590" alt="14" src="https://github.com/giovannibriones/osticket-ticket-resolution/assets/163789590/d0fed51c-fdcd-41ee-a180-41baf53af380">


<h5> Remote Diagnosis:</h5>

- Access Alex’s laptop through a remote desktop connection
- Check device manager if the necessary drivers are installed

<be>

<img width="350" alt="15" src="https://github.com/giovannibriones/osticket-ticket-resolution/assets/163789590/37fa2907-9b30-4719-869f-f35cfd999ca6">


<h3> Specific Problem Identified:</h3>

<p>Upon conducting a remote diagnostic session with Alex Kamal's laptop, it was discovered that the integrated camera is not recognized by the Windows 11 operating system. This issue seems to stem from outdated camera drivers that are incompatible with Windows 11.
</p>

<h5> Communication:</h5>

- Inform Alex through osTicket that the initial assessment indicates a potential driver-related issue with the camera after the Windows 11 upgrade

<img width="592" alt="16" src="https://github.com/giovannibriones/osticket-ticket-resolution/assets/163789590/b9b0b36d-9597-42eb-9700-94060aa0c385">




<h3> Resolution Steps:</h3>

- Download the camera drivers from the manufacturers website and install the drivers manually
- Reboot the system after making the changes to ensure proper implementation.

<img width="592" alt="17" src="https://github.com/giovannibriones/osticket-ticket-resolution/assets/163789590/5ec7f66f-3bba-4c33-9439-86e768b4f17e">


<h5>Documentation & Closure:</h5>

- Document the troubleshooting steps taken within osTicket, detailing the date and specifics of each action.

- Document the troubleshooting steps taken within osTicket, detailing the date and specifics of each action.
- Close the ticket within osTicket when Alex confirms the satisfactory resolution of the laptop camera issue

<img width="592" alt="18" src="https://github.com/giovannibriones/osticket-ticket-resolution/assets/163789590/b9f8b876-7e59-4d75-8ff2-f163011c128c">



<p><strong>.</strong></p>
<p><strong>.</strong></p>

<h3>Scenario D: Resolving Email Synchronization Issues</h3>

<p><strong>User:</strong> Amos Burton</p>

<h4>Background:</h4>


<p>Amos Burton, a sales executive, submits a ticket via osTicket, reporting that his email is not synchronizing properly across his devices. As the IT help desk agent, your goal is to troubleshoot and resolve the synchronization issue to ensure seamless access to his emails across all platforms.

</p>

<br>

<img width="587" alt="19" src="https://github.com/giovannibriones/osticket-ticket-resolution/assets/163789590/41b2ffca-2d00-4199-96fa-fbde83009edf">



<br>
<br>

<h3>Approach to Resolution:</h3>

<h5> Initial Assessment:</h5>

- Initiate a detailed conversation with Amos through osTicket, asking for specifics about the devices he uses, the email client or service, and any error messages he has encountered.

<img width="590" alt="20" src="https://github.com/giovannibriones/osticket-ticket-resolution/assets/163789590/5f0e6fef-6eba-4ecd-a057-853ac4e89f6d">

- Determine if the issue started after a particular update or change in settings.
- Establish a remote desktop connection to further diagnose the problem


<h3> Specific Problem Identified:</h3>

<p>During the remote diagnosis, it's discovered that Amos's smartphone and tablet are not set to use IMAP for his email account, which is essential for synchronizing emails across multiple devices. Instead, they are configured with POP3, leading to emails being downloaded to a single device and not being accessible on others.

</p>


<h3> Resolution Steps:</h3>

- Change the email settings from POP3 to IMAP on both his smartphone and tablet.
- Ensure that Amos's laptop is also configured to use IMAP for his email account, ensuring consistency across all devices.

![21](https://github.com/giovannibriones/osticket-ticket-resolution/assets/163789590/2b3a3014-e978-43ac-9a65-6aeef28c384e)


<p><strong>Test email synchronization by instructing Amos  to send a test email to himself and check if it appears across all his devices.</strong></p>

<p><strong>.</strong></p>
<p><strong>.</strong></p>


<h5>Documentation & Closure:</h5>

- Document all steps taken to resolve Amos's email synchronization issue within osTicket, including the initial problem identification, communication logs, and the resolution process.
- Close the ticket within osTicket once Amos confirms the issue is resolved to his satisfaction, ensuring a record of the solution is available for future reference.

<img width="589" alt="22" src="https://github.com/giovannibriones/osticket-ticket-resolution/assets/163789590/4e2f9b5f-7831-498f-8973-be81145831a2">




<p><strong>.</strong></p>
<p><strong>.</strong></p>

<h3>Scenario E: Addressing Printer Connectivity Problems </h3>

<p><strong>User:</strong> Anderson Dawes</p>

<h4>Background:</h4>


<p>Anderson Dawes, an account manager, submits a ticket through osTicket, indicating that he cannot connect to the network printer from his laptop. The printer is essential for his role, as he frequently needs to print contracts and reports for clients. As the IT help desk agent, your task is to diagnose and rectify the connectivity problem to restore Anderson's printing capabilities.

</p>

<br>

<img width="589" alt="23" src="https://github.com/giovannibriones/osticket-ticket-resolution/assets/163789590/5ebd97ae-dd2c-48cc-b833-f6523c907f79">





<br>
<br>

<h3>Approach to Resolution:</h3>

<h5> Initial Assessment:</h5>

- Communicate with Anderson and ask further questions about the problem
- Establish a remote desktop connection to Anderson’s workstation to further diagnose the issue.

<img width="588" alt="24" src="https://github.com/giovannibriones/osticket-ticket-resolution/assets/163789590/e2e20f4d-2abb-4264-9617-88e6d50e19d3">



<h3> Specific Problem Identified:</h3>

<p>The primary issue hindering Anderson Dawes from connecting to the network printer is an incorrect printer IP address configuration on his laptop. After the recent network upgrade, the IP addresses of several devices, including printers, were changed to accommodate the new networking schema. However, Anderson's laptop retained the old IP address for the printer, leading to failed connection attempts. This misconfiguration is a common oversight following network modifications, especially if devices are manually configured or if the update communication does not reach all users effectively.


</p>


<h3> Resolution Steps:</h3>

- Update Printer IP Address on Anderson's Laptop
- This can be done by accessing the printer properties via the Control Panel (or Settings app in Windows 11) and updating the port configuration under the 'Ports' tab to the new IP address. This can be done by accessing the printer properties via the Control Panel (or Settings app in Windows 11) and updating the port configuration under the 'Ports' tab to the new IP address.

<img width="400" alt="25" src="https://github.com/giovannibriones/osticket-ticket-resolution/assets/163789590/ecc4af84-d8a7-47b1-a980-7b1234bd8677">



<p><strong>Verify connectivity by attempting to print a test page.</strong></p>

<p><strong>.</strong></p>
<p><strong>.</strong></p>


<h5>Documentation & Closure:</h5>

- Document the steps taken to resolve the issue within osTicket Additionally, update any internal IT documentation to reflect the new network configuration and troubleshooting steps for related issues.
- Close the ticket once Anderson confirms the issue is resolved. 

<img width="590" alt="26" src="https://github.com/giovannibriones/osticket-ticket-resolution/assets/163789590/a4500391-3f4d-40ba-81ba-28d8e0dba477">


<p><strong>.</strong></p>
<p><strong>.</strong></p>


<h2>Significant Insights & In Conclusion</h2>

<p>
This project serves as an essential guide for IT help desk agents and support teams, offering in-depth scenarios from granting administrative rights to resolving complex email synchronization issues. It highlights the critical role of a structured approach in IT troubleshooting, emphasizing significant insights:</p>

- Structured Problem-Solving: Importance of a step-by-step approach from problem identification to solution documentation.
- User-Centric Communication: Keeping users informed is essential. Keeping users updated is key to trust and a positive experience.
- Adaptability and Continuous Learning: The need for IT professionals to stay adaptable and continuously learn to tackle a wide range of issues.
- Documentation and Knowledge Sharing: Essential for building a knowledge base that facilitates quicker future resolutions.

<p>These points highlight the essentials of effective IT troubleshooting: methodical problem-solving, clear communication, adaptability, and thorough documentation.</p>

<h1>Much obliged! &#127881; </h1>



















