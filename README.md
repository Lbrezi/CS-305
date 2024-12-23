# CS-305

Briefly summarize your client, Artemis Financial, and its software requirements. Who was the client? What issue did the company want you to address?

-Artemis Financial needed to address software vulnerabilities in their application. The job was to improve security in the software by utilizing industry standard methods such as cryptography, secure API design, and improve general code quality health.

What did you do well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall well-being?

-In order to fix the software vulnerabilities in the code we first needed to identify the vulnerabilities via maven dependency checks. We then  refactored the code using the security practices previously mentioned. We then finally would give it a test run and repeat the process until the vulnerabilities were gone. Secure coding is important in order to prevent data breaches, fraud, and the general exposure of private information. Meeting with the proper regulations and standards is essential to maintain the trust in our customers.

Which part of the vulnerability assessment was challenging or helpful to you?

-For me getting the checksum verification was super problematic for me. It was supposed to be something that was easy for most but I kept running into errors. It took me hours to figure things out but the experience helped me learn a lot more about security and general vulnerability assessment because of the extra work I had to put in to fix the issues I was running into.

How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?

-In order to increase security I leveraged SHA-256 to protect our data, ensured error handling, and unneeded data exposure was minimalized, as well as incorporating the usage with extra security layers with HTTPS. In the future I will continue to use static tests to test for vulnerabilities. As my skills continue to improve, testing to expose the code myself will be something I plan to do.

How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?

-I tested to make the code secure by going through the code myself to check manually for any potential vulnerabilities. As well as using static analysis tools to automate the process more accurately for me. After I refactored the code for the improvement I wanted, I would repeat the process until there were no new vulnerabilities.

What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?
-In future tasks the use of static code analyzers, automated penetration testers, and API security scanners would all be very beneficial to polish security. Abiding by industry security standards, and incorporating a strong modular design can help create a scalable and secure system. 

Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?

-I would show future employers my ability to identify and fix security vulnerabilities for their systems.
-The capability to apply the best industry standards into their code (ex. cryptography standards, strong API design)
-The ability to provide a detailed assessment of the security changes made to the refactored code. 
