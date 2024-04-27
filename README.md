# CS-305-Software-Security

1. Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?

   The client, Artemis Financial, is a financial services provider that was looking to implement new functions via a web application. They were concerned with security and the following regulations and standards that needed to be complied with to keep government contracts they have in good standing. 

2. What did you do very well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing?

    When coming across vulnerabilities in the client's software, it is important to look for secure measures that can be taken to minimize the change of those vulnerabilities being used, while also not bringing new vulnerabilities to the table. If you fix one issue but bring another as a result, if those have the same level of risk, no real progress was made. Having a secure application allows the company to operate with less stress about what data is secure and extra precautions they may or may not need to take. Knowing client data is secure can allow the company to retain client trust. 


3. What part of the vulnerability assessment was challenging or helpful to you?

    The challenges and helpful parts were creating the keystore and certificate that would be used to verify the server in the Project Two. This was new to me and so navigating what all of that meant took some time, but I am now familiar with how it works and realize the importance of it all.


4. How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?

    Increasing the layers of security came in the forms of updating frameworks and libraries as well as adding ciphers and checksums to validate the data coming and going was not altered in transit. Using tools like dependency checks help guide a manual code review and give areas that you should go and check for vulnerabilities. 


5. How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?
 
    To make sure that the application was functional, functional tests were run to validate it operated as it was supposed to. The local server was launched, and I was able to verify that all the functionality was the same and there were no new vulnerabilities as I ran a secondary dependency check on the new operational code. 


6. What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?

    Using dependency checks was new and something that I will surely use moving forward. I also learned the importance of input validation in places you might not think need it. Looking at how different types of injection attacks can compromise an application certainly lead me to double check all areas where input in taken.


7. Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?

    I would display my ability to dive into something I am not familiar with and learn, comprehend, and act on those skills. I know have a strong and growing foundation in locating web vulnerability and how to mitigate the effects they could have on an application. 
