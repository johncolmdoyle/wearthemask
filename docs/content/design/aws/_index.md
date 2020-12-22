---
title: "AWS Infrastructure"
date: 2020-12-21T23:50:18-05:00
---

![AWS Diagram](/wearthemask/design/aws.png)

## Description

Initial design is sticking with a very basic serverless architecture. 

## Open Questions

### Access & Authorization

Should Cognito be used? What are the cost implications? Multi region is a problem with it.

Auth0 would be the preferred, implement a free tenant. See about setting it up with Cognito maybe.

