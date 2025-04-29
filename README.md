# CS-305-Software-Security

**Briefly summarize your client, Artemis Financial, and its software requirements. Who was the client? What issue did the company want you to address?**

The client was Artemis Financial, this consulting company specializes in creatiing financial plans for their customers. Although the company already has a web interface which the customers and themselsves utilize to make operations more efficient, they want to ensure that their own data and the customer information is private and secure. They specifically wanted a file verfication step to further ensure secure communications. 

**What did you do well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall well-being?**

I think one of my biggest strengths in this project was static testing and finding the most effective ways to make the code secure. This step was an important factor. Ensuring that the code was secure and used best practices enhanced security and made it easier to change in the future. 

**Which part of the vulnerability assessment was challenging or helpful to you?**

One of the hardest parts was reading the dependency report. This was a bit challenging since a lot of research on vulnerabilities had to be done, and determining if they were false and if they truly reflected vulnerabilities in the code was challenging. 

**How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?**

I increased layers of security by implementing a checksum route using SHA-256, which insured secure verification. I also used Java MessageDigest for fixed data representation, which added an extra layer of security. I would use dependency reports and static testing and from their use refactor code or research vulnerabilities and how to eliminate them. 

**How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?**

Apart from running the code, I also made sure to take note of the dependency report, and the number of reported vulnerabilities. Once I refactored the code, I visually inspected the code, ran the code, and once more analyzed the dependency report and took note that the number of vulnerabilities did not increase. 

**What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?**

One resource I found extremely valuable was the Secure Coding Guidelines for Java SE from Oracle's website. This allowed me to know what look for when reviewing and creating my code, in order to adhere to best practices. In addition, the National Vulnerability Database was extremely helpful in understanding why each vulnerability is present. 

**Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?**

I would show future employers how I use certain tools to find vulnerabilities, I would show them how I would analyze refactored code and also how I would read a dependency report and how I would go about eliminating vulnerabilities. 
