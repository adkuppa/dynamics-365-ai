---
title: "Overview of GDPR compliance for Dynamics 365 Customer Service Virtual Agent"
description: "Learn how to respond​ to GDPR Data Subject Requests for Dynamics 365 Customer Service Virtual Agent."
keywords: ""
ms.date: 1/14/2019
ms.service:
  - "dynamics-365-ai"
ms.topic: article
ms.assetid: 
author: stevesaunders1952
ms.author: stevesaunders1952
manager: shellyha
---

# Overview of GDPR compliance for Dynamics 365 Customer Service Virtual Agent

This article helps you and your organization comply with the European Union's General Data Protection Regulation (GDPR). This article not only describes what Microsoft is doing to comply with the GDPR but also shares examples of steps you can take to support GDPR compliance when using Dynamics 365 Customer Service Virtual Agent.

   **Note:**   Because access to your virtual agent is managed by your Azure Active Directory (Azure AD) tenant administrator, other users with admin permissions have access to your virtual agent content.

## Prerequisites

Users and tenant administrators can perform the actions outlined in this article.

## Responding to Data Subject Requests for Dynamics 365 Customer Service Virtual Agent customer data

The GDPR gives rights to people (known in the GDPR as data subjects) to manage the personal data that has been collected by an employer or other type of agency or organization (known as the data controller or just controller). Personal data is defined very broadly under the GDPR as any data that relates to an identified or identifiable natural person. The GDPR gives data subjects specific rights to their personal data; these rights include obtaining copies of personal data, requesting corrections to it, restricting the processing of it, deleting it, or receiving it in an electronic format so it can be moved to another controller. A formal request by a data subject to a controller to take an action on their personal data is called a Data Subject Request (DSR).

This article describes how to use Microsoft's products, services, and administrative tools to help controllers find and act on personal data when responding to DSRs. Specifically, this article includes how to find, access, and act on personal data that resides in the Microsoft Cloud. Here’s a quick overview of the processes outlined in this guide:

<!--note from editor: In 2nd para of Step 3 below, is "customer" the same as the "you" in other steps in procedure?-->

<!--note from editor: I changed lowercase "cloud" to "Cloud" per this style guidance: "Microsoft Cloud (Microsoft Cloud Style Guide)
Microsoft Cloud is used in enterprise marketing spanning Azure, Dynamics CRM, and Office 365. There is no single offering or service by this name.
Example: 
Getting started with the Microsoft Cloud." -->

1. Access: Retrieve personal data that resides in the Microsoft Cloud, and, if requested, make a copy of it that can be available to the data subject.
2. Rectify: Make changes or implement other requested actions on the personal data, where applicable.

    If a data subject asks you to rectify their personal data that resides in your organization, you and your organization must determine if it’s appropriate to honor the request. Rectifying the data might include taking actions such as editing, redacting, or removing personal data.

    You can use AD to manage Dynamics 365 Customer Service Virtual Agent users' identities. Enterprise customers can manage DSR rectify requests, including limited editing features, per the nature of a given Microsoft service. As a data processor, Microsoft doesn't offer the ability to correct system-generated logs because these logs reflect factual activities and constitute a historical record of events within Microsoft services. [Learn more about DSR](https://docs.microsoft.com/en-us/microsoft-365/compliance/gdpr-dsr-azure).
3. Restrict: Restrict the processing of personal data, either by removing licenses for various online services or turning off the desired services where possible. You can also remove data from the Microsoft Cloud and retain it on-premises or at another location.

    Data subjects can request that you restrict processing of their personal data. Microsoft provides APIs and user interfaces (UIs) for this purpose. These interfaces allow the enterprise customer’s tenant administrator to manage such DSRs through a combination of data export and data deletion. A customer can (1) export an electronic copy of the personal data of the user, including accounts, system-generated logs, and associated logs, and then (2) delete the account and its associated data residing within Microsoft systems.

4. Delete: Permanently remove personal data that resides in the Microsoft Cloud. [Learn more about deleting personal data.](gdpr-delete.md)
5. Export: Provide an electronic copy (in a machine-readable format) of personal data to the data subject. Each section in this article outlines the technical procedures that a data controller organization can take to respond to a DSR for personal data in the Microsoft Cloud. [Learn more about exporting personal data.](gdpr-export.md)