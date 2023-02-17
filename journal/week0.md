# Week 0 — Billing and Architecture

## Home work submission

### Install AWSCLI

I was able to install awscli using shared script as explained
When I opened Gitpod from Github, script automatically ran and awscli was installed. 

### Set MFA, IAM role
I created a new account, which means that root account is not in use for security reasons
I also setup an admin group with Admin permission. I also ensured that my user is a member of the admin group
I also setup up MFA using Duo authenticator.

![Proof of Access Keys setup].(_docs/assets/Access%20keys.PNG)




### Use EventBridge to hookup Health Dashboard to SNS and send notification when there is a service health issue
I setup a health alert using eventbridge to monitor a Guardduty alert. Subsequent notification would be initiated by
SNS


### Create an architectural diagram (to the best of your ability) the CI/CD logical pipeline in Lucid Charts

I created an architectural diagram using Lucid chart. Same architectural diagram from training video was replicated
