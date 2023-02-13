# Week 0 — Billing and Architecture
## Student Discord name : Kang The Conqueror#6060
## Homework Hard Assignments
1. Set a Billing alarm  
![Billing alarm](/_docs/assets/week0/1.png)

2. Set a AWS Budget 
![AWS Budget](/_docs/assets/week0/2.png)

3. Generating AWS Credentials  
    I have created the IAM account and access keys. 

4. Using CloudShell 
![Cloudshell](/_docs/assets/week0/4.png)

5. Conceptual Architecture Diagram or your Napkins 
![Lucid chard conceptual](/_docs/assets/week0/5.png)

## Homework Stretch Assignments 
6. Destroy your root account credentials, Set MFA, IAM role.    
For root account, I deleted the access keys, set MFA and IAM role. 

7. Use EventBridge to hookup Health Dashboard to SNS and send notification when there is a service health issue.
![Event bridge](/_docs/assets/week0/7.png)

8. Review all the questions of each pillars in the Well Architected Tool (No specialized lens).  
I have created a workload in the AWS Well-Architected Tool and went over the questions for each pillar.
There are six pillars of a AWS Well-Architected Framework : (acronym CROPSS)
        * Cost optimization
        * Reliability
        * Operational Excellence
        * Performance Efficiency
        * Security
        * Sustainability

9. Create an architectural diagram (to the best of your ability) the CI/CD logical pipeline in Lucid Charts
![logical pipeline](/_docs/assets/week0/9.png)

10. Research the technical and service limits of specific services and how they could impact the technical path for technical flexibility.   
Each service has specific technical and service limits that can impact the technical path for technical flexibility. 
The more we use a service, the more we will explore about its limits. We can also read its documentation to know more about its service limits.
Another way is to choose from the top right drop down Service Quotas to observe the quota for each service being used.
![Service quota](/_docs/assets/week0/10.png)

11. Open a support ticket and request a service limit.  
Go to the AWS Support Center by clicking the "Support" button in the top right corner of the AWS Management Console.
Click the "Create a new case" button.
Select "Service Limit Increase" as the type of case.
Select the AWS service for which you want to request a limit increase.
Fill out the form with the required information, including the current limit, the desired limit, and the reason for the request.
Click the "Submit" button to submit your case.
![support ticket](/_docs/assets/week0/11.png)
