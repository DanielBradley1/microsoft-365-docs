---
title: "Enable users for Microsoft Copilot for Microsoft 365"
f1.keywords:
- NOCSH
ms.author: camillepack
author: camillepack
manager: scotv
ms.date: 09/20/2023
audience: Admin
ms.topic: article
ms.service: microsoft-365-copilot
ms.localizationpriority: medium
ms.collection: 
- Tier2
- scotvorg
- M365-subscription-management 
- Adm_O365
- Adm_TOC
- m365copilot
description: "Learn about the steps to deploy Microsoft Copilot for Microsoft 365 to your users."
---

# Enable users for Microsoft Copilot for Microsoft 365

There are three main steps to deploy Microsoft Copilot for Microsoft 365 in your organization:

1. Review the [prerequisites](microsoft-365-copilot-requirements.md) and verify that your organization is prepared for Microsoft Copilot for Microsoft 365.

2. Assign the required licenses to your users.

3. Send an email to your users announcing Microsoft Copilot for Microsoft 365 and its features.

You can use the [Microsoft Copilot for Microsoft 365 setup guide](https://setup.microsoft.com/microsoft-365/copilot-setup-guide) in the Microsoft 365 admin center to perform all three steps, or use the steps described in this article.

## Assign licenses

This article assumes that you have already provisioned users in your tenant. If you haven't already done so, follow the steps in the [Microsoft Copilot for Microsoft 365 setup guide](https://setup.microsoft.com/microsoft-365/copilot-setup-guide) or those documented in [Add users and assign licenses in Microsoft 365](/microsoft-365/admin/add-users/add-users). If you use either of these resources, you can create users and assign the necessary licenses at the same time. To learn more about assigning Microsoft 365 licenses with PowerShell, see [Assign licenses to user accounts](/microsoft-365/enterprise/assign-licenses-to-user-accounts-with-microsoft-365-powershell).

After a user has been assigned a license for Microsoft Copilot for Microsoft 365, the Copilot experience will automatically appear for them in the Microsoft 365 Apps. In some experiences, like Word, for example, a Copilot dialog will appear when creating a new document. In other experiences, Copilot is quickly accessible on the Ribbon. To use Copilot in Teams, users must [add the Copilot app](https://support.microsoft.com/office/add-an-app-to-microsoft-teams-b2217706-f7ed-4e64-8e96-c413afd02f77).

## Send welcome email

After licensing your users for Microsoft Copilot for Microsoft 365, we recommend sending them a welcome email to introduce them to Microsoft Copilot for Microsoft 365 and help them understand what it can do for them. The easiest way to do this is to use the [Microsoft Copilot for Microsoft 365 setup guide](https://setup.microsoft.com/microsoft-365/copilot-setup-guide), which includes an option for sending a welcome email to your Copilot users. Here’s an example of this email:

:::image type="content" source="media/eap-welcome-email.png" alt-text="A preview image of an email template for introducing Microsoft Copilot for Microsoft 365 and its capabilities that an admin can provide to users.":::

The welcome email also includes a link to an interactive website for [Microsoft Copilot for Microsoft 365](https://support.microsoft.com/copilot).

## Enable feedback

We recommend that you enable all feedback settings for the Microsoft 365 Apps. This allows Microsoft Copilot for Microsoft 365 users to provide details with their thumbs up or thumbs down reaction to what Copilot produced from their prompt. You can use either the [cloud policy service](https://config.office.com) or group policies to enable the feedback for your users. Once all the policies are enabled, users will have the option to provide logs, screenshots, an email address for further contact about their feedback submission.

## Microsoft Copilot for Microsoft 365 usage activity report

After your users have had a chance to use Copilot, we recommend running and reviewing the [Microsoft Copilot for Microsoft 365 usage report](/microsoft-365/admin/activity-reports/microsoft-365-copilot-usage) (which is in continuous enhancement) to get a summary of user adoption, retention, and engagement with Microsoft Copilot for Microsoft 365. The report can be found in the Microsoft 365 admin center under **Reports** > **Usage**.
