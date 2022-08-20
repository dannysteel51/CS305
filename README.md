# CS305

•	Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?

Artemis Financial is a financial consulting company that develops individualized financial plans for their customers' savings, retirement, investments, and insurance. Artemis came to us, Global rain, to help them modernize their operations: specifically, their software security. 

•	What did you do particularly well in identifying their software security vulnerabilities? Why is it important to code securely? What value does software security add to a company's overall wellbeing?

Finding the false positives from the check report was one of the highlights of the work. Whittling down the false errors makes the developer’s work that much easier, focusing on the real issues. And from there, the work can truly start on secure coding, which is paramount in today's world. With so many cyber-attacks, safe coding from the very beginning can create a lasting relationship with a company and its clientele, breeding a place of trust and security. 

•	What about the process of working through the vulnerability assessment did you find challenging or helpful?

The most challenging part of the vulnerability assessment was simply getting to know it. At first glance, the report is loaded with many things a novice like me did not understand. But once I found my way, I found it quite fun to find the vulnerability and try to match it with the instances of the error, making sure they were in fact real errors and not false positives. And then using the suppression.xml to suppress these unneeded warnings. 

•	How did you approach the need to increase layers of security? What techniques or strategies would you use in the future to assess vulnerabilities and determine mitigation techniques?

Lesson one learned from this course: don't trust input. 
With that said:
First, I think checking to see the code bass's vulnerabilities, using a check report, would be step one. From there, suppression of false positives. Then, decide on a good cipher for the program to ensure data is getting to the correct places. 

•	How did you ensure the code and software application were functional and secure? After refactoring code, how did you check to see whether you introduced new vulnerabilities?

After refactoring the code, I did a manual check to ensure the code was up to date, and without errors, and once this check was done, I went back and ran another check report using maven. I would repeat the process, ridding the report of false positives and suppressing them in an .xml file. 

•	What resources, tools, or coding practices did you employ that you might find helpful in future assignments or tasks?

Once more, maven and the check report are both vital tools that are used everywhere in the industry. 

•	Employers sometimes ask for examples of work that you have successfully completed to demonstrate your skills, knowledge, and experience. What from this particular assignment might you want to showcase to a future employer?

I think the best show of my newly gained skills and my security competency is to showcase the generated checksum. This part of the project touched on Spring, security, and general coding practices. 
