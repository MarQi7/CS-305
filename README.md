# CS-305
Software Security

# Briefly summarize your client, Artemis Financial, and its software requirements. Who was the client? What issue did the company want you to address?

Artemis Financial is a consulting company that develops individualized financial plans for its customers including savings, retirement, investments, and insurance plans. The client wished modernize its operations by updating its RESTful web API with the latest and most effective software security. We were tasked with identifying vulnerabilities and refactoring the code for the web application to meet the security needs of our client.

# What did you do well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall well-being?

After discovering the vulnerabilities of the software using static testing, we reviewed the solutions available for the known vulnerabilities as they are recorded in the National Vulnerability Database. In addition to utilizing the known solutions, we researched industry standard solutions to implement additional layers of security to ensure the code was secure against attacks. The software's security is the greatest defense against exploits from malicious actors who are looking to gain from our client's user's personal information and monetary assets. Even one significant breach could damage the reputation of our client and the trust their users place in them.

# Which part of the vulnerability assessment was challenging or helpful to you?

The vulnerability assessment was very complex in the beginning, but it was very insightful as to how important security is for applications. There are near unlimited ways for software to be "hacked" or used for unintended purposes and the National Vulnerabilities Database is a crucial collaborative defense resource to fight against these exploits.

# How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?

I have been experimenting with the NVD's solutions and researching more about where and how exploits can be found. There are an unlimited number of examples to learn from and using additional security measures like TSL/HTTPS connections along with a hash algorithm to create and verify a checksum is useful for validation, but there are several other possible issues to address.

# How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?

I used the industry standard SHA-256 cryptographic function that was built into the Java SDK to create a checksum verification for data integrity. Additionally, I created a self-signed certificate to test the connection to the application using a secure connection with TLS/HTTPS. After refactoring the code, I used the automated Dependency-Check Maven tool to generate a vulnerability report and check for new vulnerabilities. 

# What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?

I learned how to utilize automated static testing using the Maven Dependency-Check tool, how to research and keep up with known vulnerabilities via the National Vulnerabilities Database, and the importance and impact of defensive security using industry leading security methods. 

# Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?

There is a much larger pool of information for me to pull from and refer to when developing applications with secure code. Having the knowledge of just how vast the pool of vulnerabilities motivates a developer to take secure coding seriously. I would likely show them how I implemented additional security and continued to search for new vulnerabilities during development. 
