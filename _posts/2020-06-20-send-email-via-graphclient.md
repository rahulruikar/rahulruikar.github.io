---
layout: post
title: "Send email using MS GraphClient C# SDK"
---
Sending email using GraphClient Sdk requires bit of setup. This post explains how I achieved this using Azure AD, GraphClient SDK and Azure App Service.

MS Graph API support various authentication providers, in this usage scenario, I used 

[*client_credentials*]: https://docs.microsoft.com/en-us/azure/active-directory/develop/v2-oauth2-client-creds-grant-flow

 flow where application would send email on behalf of user without any user interaction. you can find more on choosing specific authentication provider here https://docs.microsoft.com/en-us/graph/sdks/choose-authentication-providers?tabs=CS

###### Setup Authentication Provider

