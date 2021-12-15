<h1>Cloud Resume Challenge</h1>

As the fall semester comes to an end, I am wrapping up Forrest Brazeal’s *Cloud Resume Challenge*. This is a project I have been working on for the second half of my Networking and Cloud Computing (ISBA 4798) class at Loyola Marymount University taught by Greg Lontok. This challenge aims to help people land a job in the cloud computing industry by giving them the framework to host their resume in the cloud. So far, it has helped dozens break into tech, and I hope to leverage my career with it too.

Through this challenge, I have been able to understand key cloud computing concepts and learn how to use the following services and features in Amazon Web Services (AWS): Identity and Access Management (IAM), Multi-factor authentication (MFA), Amazon Elastic Compute Cloud (Amazon EC2), AWS Command Line Interface (AWS CLI), Elastic Load Balancer (ELB), Auto Scaling Group (ASG), Amazon S3, Relational/NoSQL Cloud Databases, AWS Route 53 for Domain Name System (DNS), AWS CloudFront, AWS Lambda, AWS API Gateway, and navigating the console.

Once I’m done with the challenge, and with further test prep, I am confident that I will have the hard skills necessary to pass the AWS Certified Cloud Practitioner exam (CLF-C01)–the first milestone in my journey to become a cloud professional. I also want to learn how to use Microsoft Azure, Google Cloud, and any other service that may become relevant. My end-goal is to be fully equipped for what is to come in the world of tech (Metaverse, Web 3.0, etc.).

The Cloud Resume Challenge also helped me build upon other coding and DevOps skills outside of the cloud. For instance, this was my first time coding a website in HTML, styling HTML in CSS and Bootstrap, and making an API call in JavaScript. I also got to practice Python, using Git commands, skimming software documentation for quick use, navigating Microsoft Visual Studio and GitHub’s interface, and writing Infrastructure as Code (IaC) in Terraform.

<h2>Obstacles:</h2>
- Not knowing where to start: this obstacle actually benefits those who take on the challenge because it is not meant to be a step-by-step course that outlines everything out for you–that would make it too easy. Instead, the open-ended nature of the project forces you to research the best resources to learn from and determine how much effort you want to put into each step. For example, one can decide to either use a template for their website–thus, gaining a superficial grasp on how HTML works–or they can decide to develop the entire site from scratch. Overcoming this obstacle was tricky, but it was a matter of figuring out where it would be logical to start from and troubleshoot from there. Luckily, I also received guidance from my professor and feedback from members of the Cloud Resume Challenge’s online community.<br>
- Conceptualizing each service: the architecture of the cloud is complex, and I have a difficult time trying to understand how each action in the console works, how services interact, and why they are necessary. I deal with this sort of ‘cloud existentialism’ by studying off visualizations such as architectural diagrams before moving on to the next step. This has taught me that every step is vital. A prime example is how incorrectly setting up IAM users could cost your organization a fortune. <br>
- Writing this blog post: this was the ultimate challenge because putting your work into your own words exhibits the understanding of each step on a deeper level. Also, the goal of the Cloud Resume Challenge is to get hired in the cloud so writing a blog post is great interview prep. <br>

<h2>To-do List:</h2>
- Testing: I need to develop Python tests for the Lambda function <br>
- Infrastructure as Code (IaC): I need to define and deploy my API resources (DynamoDB table, API Gateway, and Lambda function) with Terraform instead of manually through the AWS console. This will allow for faster updates. <br>
- CI/CD (Backend): I need to set up GitHub Actions that will allow me to push and update to my Terraform or Python code and run Python tests. If the tests pass, the Terraform updates should deploy in AWS. <br>
- CI/CD (Frontend): I need to set up GitHub Actions so that when I push new website code (HTML and CSS), the S3 bucket will update automatically. This will also invalidate CloudFront cache. <br>

<br>

Here is my cloud resume: https://sebastianvanhemert.com/.

Here is my Github Repository: https://github.com/svanhemert00?tab=repositories. I would appreciate feedback on how to improve my code.
