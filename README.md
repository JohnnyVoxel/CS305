# CS305
SNHU Software Security 22EW3

## Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?

The client, Artemis Financial, is a financial consulting firm that develops individualized financial plans for investments, savings, retirement, and insurance for their clients. Their goal is to modernize their operations with a web-based application that utilizes a RESTful API.

## What did you do particularly well in identifying their software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing?

I feel I did particularly well in identifying potential solutions for vulnerabilities that were discovered during static testing. It is important to not only consider the security of the code you write yourself, but the third-party libraries and APIs you are using as well. Without making security a priority from the very first steps of development, you will in a best-case scenario have to spend a lot of time and effort down the line to fix vulnerabilities that your insecure coding practices created. The worst-case scenario leaves the client legally and financially responsible for damages and can destroy their reputation as well as your own.

## What about the process of working through the vulnerability assessment did you find challenging or helpful?

The most challenging part of working through the vulnerability assessment was identifying the severity of the issues found. While the Maven Dependency Check provides a wealth of information, it is difficult to understand how those vulnerabilities affect your implementation and to what extent. 

## How did you approach the need to increase layers of security? What techniques or strategies would you use in the future to assess vulnerabilities and determine mitigation techniques?

The Vulnerability Assessment Process Flow was helpful in assessing the security of the application. I would Identify which sections were applicable to the particular feature of the application I was looking at, then evaluate each step sequentially. 

## How did you ensure the code and software application were functional and secure? After refactoring code, how did you check to see whether you introduced new vulnerabilities?

To ensure that the code was functional and secure, I would perform comprehensive static and dynamic testing. Vulnerabilities would be addressed as they were found. After that initial assessment was completed, the refactored code would be compiled, and a new round of static and dynamic testing would occur to check that the original issues were corrected and attempt to identify new issues.

## What resources, tools, or coding practices did you employ that you might find helpful in future assignments or tasks?

The Maven Dependency Check was an invaluable tool for identifying security issues with dependencies, and even just to identify when packages are out of date. For reviewing self-generated code, the Vulnerability Assessment Process Flowchart was immensely helpful in determining all the aspects of the application that need to be addressed.

## Employers sometimes ask for examples of work that you have successfully completed to demonstrate your skills, knowledge, and experience. What from this particular assignment might you want to showcase to a future employer?

I was happy with the results of Project Two. By identifying which packages were out of date and updating them, I was able to reduce the number of vulnerable in the dependency check report from 48 down to 1. I was also satisfied with my implementation of a self-signed certificate and the implementation of a hash function.
