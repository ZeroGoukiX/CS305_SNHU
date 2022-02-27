Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?  

The client Artemis Financial was a company responsible for financial plans for customers regarding savings, retirement, investments, and insurance. For this project the company wanted us to add a file vertification step to their web application to ensure secure communications between users and their client.

What did you do particularly well in identifying their software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing?

I was able to identify numerous vulernabilities by the use of running a dependency check via a maven build. This gave me information on numerous vulernabilites in the software and how to repair them. As for why it is important to code securely, business often deal with customers vital information and that data needs to be protected from attackers that would try to steal people's info. Vulnerable information needs to be stored securely for the customers well being as well as the company's wellbeing as a company that has their data stolen will be percieved as unsafe to do business with and can be disasterous for the company.

What about the process of working through the vulnerability assessment did you find challenging or helpful?

Learning how to use the java keytool to generate a certification was very helpful as it led to the creation of the https secure communication protocol. The certification the site looks for is the one you created and have in the resources folder. 

How did you approach the need to increase layers of security? What techniques or strategies would you use in the future to assess vulnerabilities and determine mitigation techniques?

I had to see what kind of vulnerabilties were in the software to begin with, by running the maven build I was able to see the dependency check and identify several vulnerabilities. Outside of that the code needed to be refactored to hav an algorithm be implemented and the site was connection to an HTTP protocol. That needed to be changed to an HTTPS protocol to secure the site. In the future I would do the same with running a maven build to check for any software holes that can be patched up. As for reading the code I would need to identify where the connection is being made on the server and see if it is acutally secure or not and to update it if it isn't.

How did you ensure the code and software application were functional and secure? After refactoring code, how did you check to see whether you introduced new vulnerabilities?

I ran another maven build and dependency check to search for any more vulnerabilities and as they came up I suppressed them and reran tests until no more new vulnerabilites arose.

What resources, tools, or coding practices did you employ that you might find helpful in future assignments or tasks?

The use of the Vulnerability Assessment Process Flow was a good checklist to see what went into securely designing software as well as guides from Spring Boot on their webiste for creating and maintaining using Spring Boot software.

Employers sometimes ask for examples of work that you have successfully completed to demonstrate your skills, knowledge, and experience. What from this particular assignment might you want to showcase to a future employer?

From this assignment I would like to showcase my understanding of creating a self signed certificate, the implementation of the algorithim in order to generate a key and the ability to run a dependency check in order to locate and vulerabilities. 
