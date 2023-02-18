# Week 0 — Billing and Architecture

## Required Homework
### Link to Architectural Diagram on Lucid Charts

https://lucid.app/lucidchart/1e27f448-3dee-4b12-913a-ff5dd3a4fb48/edit?viewport_loc=-912%2C-134%2C4096%2C1724%2C0_0&invitationId=inv_374f71cd-0a11-41d7-9490-deb5722aa0ee

![Architectural Design](../Images/Architectural_Design.png)

---
### Link to Conceptual Diagram on Lucid

https://lucid.app/lucidchart/1880b560-e920-4f29-a461-d39817fe71f8/edit?viewport_loc=-237%2C-278%2C2048%2C862%2C0_0&invitationId=inv_14dea04d-a2dd-480a-bb38-294c4e2a356f

![Conceptual Diagram](../Images/Conceptual_Diagram.png)

### Install AWS CLI

> I reallly like the *aws --cli-auto-prompt* and how it is able to suggest the commands.

- The main issue I had with the AWS CLI setup was at the point of  pushing my code to my github repo, there was no authorization for gitpod to push, I had to grant the accesson github.

## Summary

This week, I completed the conceptual and architectural diagram of Lucid, I also installed AWS CLI on GitPod. I experienced some Authorization challenges while trying to push my code to my GitHub repository but this was resolved by granting the required access (public_repo) to GitPod to GitHub.

I created an Admin User on AWS and set up 2FA for the newly created user, followed through to get the access keys that were subsequently added to my GitPod workspace.

For my architectural diagram, I added an SQS Queue Service for serverless image processing. This will provide a 100% serverless solution for the image processing section of the implementation.

I was also able to consume the recommended video content. 