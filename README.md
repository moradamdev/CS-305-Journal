# CS-305-Journal

Briefly summarize your client, Artemis Financial, and its software requirements. Who was the client? What issue did the company want you to address?
-The client was a consulting company named Artemis Financial that develops financial plans for their customers. They want to modernize their operations and because they deal with sensitive financial information, they need us to use the best software security. They wanted us to address security concerns in their RESTful web API 

What did you do well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall well-being?
-I did a good job first realizing their vulnerabilities and using proper methods to fix them. I used the SHA-256 encryption algorithm to ensure the best security for this context. It's extremely important to code securely all the time, but especially when dealing with sensitive financial information, because it's extremely dangerous for really sensitive data to fall into the wrong hands. There are so many nefarious people out there who will mess things up for you if they somehow got into your account. Not only is it just terrible for data to enter the wrong hands, but if a customers data remains safe because you go the extra distance for them, then they will stick around and your company will have a better reputation.

Which part of the vulnerability assessment was challenging or helpful to you?
-Setting up everything was challenging at first, but very worth it in the end. The dependency checks were really incredible and helped out a lot since it displayed so much information on every error and their severity that was present in the code.

How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?
-Other than using SHA-256 encryption, I increased the layers of security by ensuring the web app ran on HTTPS which ensured a higher level of security. I also used dependency checks to see all the errors in the code and use their severity level to determine which ones were crucial to fix. I will continue to use dependency checks in the future.

How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?
Well first I just check to see if the code runs to begin with and to see if it functions properly by outputting the results, but I could also just see in the dependency check whether or not a new vulnerability was introduced from some change that I had made. I made sure to keep open the previous version of the dependency check to see the differences between them.

What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?
-I always go through the Java documentation whenever I need to find an obscure function or just something I don't know and using stackoverflow was a good resource when I ran into an error I didn't recognize.

Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?
I'd definitely show future employers this project since it not only includes code samples, but also proves I can set up HTTPS, SHA-256 encryption and most importantly, explain the work that I've done.
