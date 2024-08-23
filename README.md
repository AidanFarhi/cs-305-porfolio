# cs-305-porfolio

- Briefly summarize your client, Artemis Financial, and its software requirements. Who was the client? What issue did the company want you to address?

Artemis Financial is a consulting company that creates financial plans for its clients. These plans include savings, retirement, investments, and insurance. The task that was presented by Artemis Financial was to develop secure communication mechanisms in order to meet security requirements. They wanted a data verification step involving a checksum after data was transferred. A production-quality application implementing secure coding protocols was the expected deliverable.

- What did you do well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall well-being?

I was able to understand and remediate the vulnerabilities found in the code as it was first received. I promptly updated the versions of the dependencies and suppressed any false positives. It is important to code securely to ensure that all software we build protects the integrity of the organization. All data, information, and access must be strictly controlled to prevent any possible breaches or legal repercussions. By doing so, the company or organization will maintain its reputation and prevent financial loss or breaches of trust with its clients.

- Which part of the vulnerability assessment was challenging or helpful to you?

The static analysis tool dependency check was sometimes difficult to use. When I first worked with it, I found the vulnerability report slightly difficult to read and comprehend. I found it helpful to click the links provided in the report to gain more understanding of what needed to be addressed and how to manage suppressing false positives.

- How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?

Layers of security were increased by performing a static analysis with dependency check, a manual review of the code, and reviewing the layers of security flowchart provided in the course materials. In the future, I would incorporate automated builds with static security checks built into the CI/CD pipeline. In terms of mitigation, I would follow the same approach of manually reviewing the code and vulnerability report and remediating issues as needed.

- How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?

I made certain the application was functional and secure by running the dependency check after I introduced new code. I then remediated the vulnerabilities and verified the application build was still successful.

- What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?

A practice I found helpful was reviewing the vulnerability assessment chart to reference all areas of security that should be addressed. I think it would also be helpful to include static vulnerability scanning of my future tasks in school and at work.

- Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?

In all honesty, I would provide examples from my software engineering experience in the field. Although, if were a new grad, I would probably build off the concepts from this course and create a project that incorporates secure coding practices to showcase.
