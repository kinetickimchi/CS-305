# CS-305: Software Security

## Briefly summarize your client, Artemis Financial, and its software requirements. Who was the client? What issue did the company want you to address?
Artemis Financial is a financial consulting company based around developing tailored financial plans for its customers. Global Rain was brought on to assist Artemis Financial with assisting in securing their web-based software from external threats, as well as integrating a file verification step to their web application. As a whole, we were to help Artemis protect their client data and financial information.

## What did you do well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall well-being?
Upon discovering security vulnerabilities in the client's software, I chose to focus on a flowchart-style method of tackling their vulnerabilities, starting from the easiest to mitigate and progressing to the most difficult, or ones with the highest impact. Coding securely is particularly important because it is part of the foundation in which the security of the program or even the entire company is based on. If code is written with outdated security practices in mind, a vulnerability is left wide open before a hostile actor is even given a chance to attack. By emphasizing software security, employees of a company can be confident that what they are working on is ethical, as well as proving the company is focused on keeping up with modern standards.

## Which part of the vulnerability assessment was challenging or helpful to you?
I found determining false positives during the vulnerability assessment to be particularly challenging, simply because of the amount of research I had to take for each reported vulnerability. Not only would I have to look into the CVE itself, but I also needed in-depth knowledge of the codebase in order to make an informed decision on whether a potential vulnerability would have a significant impact.

## How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?
My main method of increasing layers of security was to begin with ensuring baseline security practices were met before moving on to any more complex tasks. This way, I was able to begin with the simplest solutions and begin working my way up.

## How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?
To ensure the code and application were functional, I would re-run both the program as well as the dependency check tool after each iteration of refactoring code or changing any versions, and ensure the application still had full functionality.

## What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?
I learned to emphasize the habit of ensuring all dependency and development kit versions are up-to-date before progressing with further vulnerability checks. This way, I can avoid spending too much time trying to resolve a vulnerability that may have been addressed in a security patch several versions back.

## Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?
I would try to put a focus on my thought process behind my code review and the research methods I used when analyzing each vulnerability. Reviewing the code base, I had to make sure I had a full understanding of what the program was doing and the intended result of every line, otherwise I would not be able to effectively determine what would be a potential security risk. While researching vulnerabilities, I had to make use of as many resources as possible to get the best idea of the impact of the vulnerability on my specific program and its importance.
