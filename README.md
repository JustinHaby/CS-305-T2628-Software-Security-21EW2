# CS-305-T2628-Software-Security-21EW2
Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?
What did you do particularly well in identifying their software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing?

In this project, I worked for a client, Artemis Financial. Artemis Financial is a financial industry company that required a security upgrade to its application. First, they needed an encryption algorithm to send data. They wanted their application to use HTTPS for a secure connection while also managing safe and secure combinations throughout their application.

What about the process of working through the vulnerability assessment did you find challenging or helpful?
Reading through and understanding the process of the verbality reports was quite tricky and challenging at first. It was very complex as you were to identify and address these listed dependencies to maintain the high-level security of the application.

Regarding OWASP Dependency-Check, we used MD5 Dependency-Check, also Known as a Software Composition Analysis (SCA) tool in eclipse that attempts to detect publicly disclosed vulnerabilities contained within a project’s dependencies. First, it determines a Common Platform Enumeration (CPE) identifier for a given dependency. Then, it will generate a report linking to the associated CVE entries if found. With this, you can review Know vulnerabilities, which will take additional measures to fix these threats once suppressed through a supression.XML file, eliminating any false positives.

How did you approach the need to increase layers of security? What techniques or strategies would you use in the future to assess vulnerabilities and determine mitigation techniques? How did you ensure the code and software application were functional and secure? After refactoring code, how did you check to see whether you introduced new vulnerabilities?

As described above, to ensure the code and software application was functional and secure, I performed static and dynamic testing to ensure every use case was handled and that none of the dependencies could be exploited. This would lead to suppression of any Vulberabitlies in the HTML report, Later leading to a risk mitigation plan for handling threats by eliminating or reducing their possible impact. This takes prudent measures to lessen the negative effect of risks and disasters during the system development life cycle. 


What resources, tools, or coding practices did you employ that you might find helpful in future assignments or tasks?
I found the Maven Dependency checker tool extremely useful and will use it in the future.

Employers sometimes ask for examples of work that you have successfully completed to demonstrate your skills, knowledge, and experience. What from this particular assignment might you want to showcase to a future employer? 

I would want to demonstrate my skills by identifying and implementing security measures through a Dependency checker. With this, I would showcase my ability and competence in finding vulnerabilities through a code base and implementing the proper measures through a risk mitigation plan to a future employer.

 
