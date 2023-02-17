# Week 0 — Billing and Architecture

## Home work submission

### Install AWSCLI

I was able to install awscli using shared script as explained
When I opened Gitpod from Github, script automatically ran and awscli was installed. 

### Set MFA, IAM role
I created a new account, which means that root account is not in use for security reasons
I also setup an admin group with Admin permission. I also ensured that my user is a member of the admin group
I also setup up MFA using Duo authenticator.

![Proof of Access Keys setup](/journal/assets/Accesskeys.PNG)

![Proof of IAM role setup](/journal/assets/IAMROle.PNG)

![Proof of MFA setup](/journal/assets/MFA.PNG)




### Use EventBridge to hookup Health Dashboard to SNS and send notification when there is a service health issue
I setup a health alert using eventbridge to monitor a Guardduty alert. Subsequent notification would be initiated by
SNS
![Proof of Eventbridge health hookup setup](/journal/assets/Eventbridge.PNG)


### Create an architectural diagram (to the best of your ability) the CI/CD logical pipeline in Lucid Charts

I created an architectural diagram using Lucid chart. Same architectural diagram from training video was replicated

![Proof of architectural diagram](/journal/assets/Cruddur%20Logical%20Diagram%20.png)

[Lucid Chart share Link](https://lucid.app/lucidchart/37d9f2d4-1387-463a-a59c-3f991b351c5f/edit?viewport_loc=43%2C-89%2C2827%2C1177%2C0_0&invitationId=inv_e6683c3f-b029-4076-85b7-0830c6af58f6)
