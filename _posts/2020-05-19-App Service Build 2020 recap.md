---
title: "App Service //Build 2020 Recap"
author_name: "Jason Freeberg"
---

This year, [Microsoft Build](https://mybuild.microsoft.com/) is entirely online. Live and pre-recorded sessions are available for anyone to view. This article is a recap of the sessions from the App Service team, along with links to more information.

## Building and Managing .NET Core with App Service

*Building web apps with .NET Core? Check out the latest from the App Service team including how to build a continuous delivery pipeline using GitHub Actions, how to use Event Grid to subscribe and act on deployment events and how to monitor your production apps with Health Checks.*

### GitHub Actions

GitHub Actions is a flexible automation framework that allows developers to (among other things) continuously deploy their applications to App Service.

- [Webapps deploy Action](https://github.com/Azure/webapps-deploy)
- [GitHub Actions for Azure](https://github.com/azure/actions)
- [GitHub Actions Marketplace](https://github.com/marketplace?type=actions)

### App Service Health Checks

App Service Health Checks will automatically remove and restart unhealthy instances of your application when you are scaled out.

- [Documentation](https://github.com/projectkudu/kudu/wiki/Health-Check-(Preview))

### Event Grid Integration

Event Grid is a high performance publish/subscribe messaging system. App Service now emits events that can be handled with Functions, Logic Apps, and more.

- [Getting started guide](https://azure.github.io/AppService/2020/05/11/event-grid-integration.html)
- [Event Grid overview](https://docs.microsoft.com/azure/event-grid/overview)
- [Comparison of Azure messaging services](https://docs.microsoft.com/azure/event-grid/compare-messaging-services)