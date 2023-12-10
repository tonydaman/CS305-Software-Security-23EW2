CS-305-Software-Security-23EW2

•	Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?
Artemis Financial (client) is a consulting company that develops individualized financial plans for its customers. The financial plans they have include savings, retirement, investments, and insurance. The issues they wanted to address were the modernization of their operations and to have current/effective software security. 

•	What did you do very well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing?
The issue found in the client’s software was not having any time of encryption or dependency check on their software either. This is important because as a finance company, they are bound to have attackers come at them from all sides. Having software security added to the company’s software is not only good for their customers but also good for their reputation. Being a company that cares about security will bring in more business and have reliable service for many customers to come.

•	What part of the vulnerability assessment was challenging or helpful to you?
The portion of the vulnerability assessment that I found challenging was trying to get the SSLServerApplication.java to launch at the start. Had tried running the program over OneDrive and found a class file would get deleted and then had my firewall blocked as well. This led to me having to move the directory over to my local drive and running it there helped along with excluding the folder path on my firewall application.  


•	How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?
Increased the layer of security by adding AES and RSA to the project. This also included adding 4 libraries to the program as well to function. Speaking of which, I would suggest having all the dependencies checked and up to date as you work on the software. Include weekly evaluations in case there is a vulnerability found in the software.

•	How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?
To make sure the code and application were functional and secure, I would run the program each time I made a change. This would also include any issues that I came across as well, as I can revert to my old code and figure out another solution for the problem. Did many dependency-check scans as well on the application.


•	What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?
All the resources given in each model are a must for learning along the way. The book “Iron-Clad Java: Building Secure Web Applications.” Helps explain part of the process when building security for an application. Also, learning how to conduct dependency checks will stay with me forever as it's amazing how many vulnerabilities there can be in software. 

•	Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?
The first thing would be running a dependency check on their software and then showing how many vulnerabilities a software can have and what versions would be needed to update to. Maybe even having to look at their vendor's page on what else could be done if version updating is not an immediate solution. Having documentation of this process along the way with updates included and comments in the code.  

Reference

Manico, Jim, and August Detlefsen. “Iron-Clad Java: Building Secure Web Applications.” O’Reilly Online Learning, McGraw Hill Computing, https://learning.oreilly.com/library/view/iron-clad-java/9780071835886/ch06.html#ch06lev1sec16
