# Web Deployment

## Introduction

This challenge was submitted by Dave Lusty.

Traditional web deployment often has multiple static environments into which code is pushed. While this works well, there are other ways to achieve the goal of deploying code. This challenge is designed to make you think about the possibilities, not necessarily to show you a best practice.

As a part of this challenge you'll need to think differently, innovate, and possibly do things you wouldn't normally do. We'll be deploying a simple web site using Azure DevOps. Your site can be a simple html file - I recommend using different colour backgrounds in each code release so you can easily see which version of the site you're looking at. You'll end up with several endpoints - test, QA and production, and you'll promote your new html code between them.

![example image](images/example.png)

## Instructions


### Deployment

Your web server/web server cluster must be deployed fresh with each new revision of code. The server/cluster itself should be deployed as code, allowing you to upgrade the operating system or patch by creating a new deployment.

### Security

As a part of this challenge, the web server should not allow any external access other than the web site being served to users. This includes access to deploy code, so you'll need to think of ways to get your code onto the server without a logon. There should be no available username/password or certificate at the end of deployment.

### Scalability

You should be able to amend the number of web nodes for each deployment, or deploy multiple servers/clusters into one of your three environments to meet demand.

### Testing

You should be able to serve multiple versions of the site from each of your endpoints at any time. This could be used for blue/green deployments or A/B testing.

## Solutions
