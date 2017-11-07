---
title: Connect to SendGrid with Power BI
description: SendGrid for Power BI
services: powerbi
documentationcenter: ''
author: joeshoukry
manager: erikre
backup: maggiesMSFT
editor: ''
tags: ''
qualityfocus: no
qualitydate: ''

ms.service: powerbi
ms.devlang: NA
ms.topic: article
ms.tgt_pltfrm: NA
ms.workload: powerbi
ms.date: 10/16/2017
ms.author: yshoukry

---
# Connect to SendGrid with Power BI
The Power BI content pack for SendGrid allows you to extract insights and statistics from your SendGrid account. Using the SendGrid content pack you can visualize your SendGrid statistics in a dashboard.

Connect to the [SendGrid content pack](https://app.powerbi.com/getdata/services/sendgrid) for Power BI.

## How to connect
1. Select **Get Data** at the bottom of the left navigation pane.
   
   ![](media/powerbi-content-pack-sendgrid/PBI_GetData.png) 
2. In the **Services** box, select **Get**.
   
   ![](media/powerbi-content-pack-sendgrid/PBI_GetServices.png) 
3. Select the **SendGrid** content pack and click **Get**.
   
   ![](media/powerbi-content-pack-sendgrid/sendgrid.png) 
4. When prompted, provide your SendGrid user name and password. Select **Sign In**.
   
   ![](media/powerbi-content-pack-sendgrid/PBI_SendGridSignIn.png)
5. After Power BI imports the data, you see a new dashboard, report, and dataset in the left navigation pane, populated with your email statistics for the past 90 days. New items are marked with a yellow asterisk \*.
   
   ![](media/powerbi-content-pack-sendgrid/PBI_SendGridDash.png)

**What Now?**

* Try [asking a question in the Q&A box](powerbi-service-q-and-a.md) at the top of the dashboard
* [Change the tiles](powerbi-service-edit-a-tile-in-a-dashboard.md) in the dashboard.
* [Select a tile](powerbi-service-dashboard-tiles.md) to open the underlying report.
* While your dataset will be schedule to refreshed daily, you can change the refresh schedule or try refreshing it on demand using **Refresh Now**

## What's included
The following metrics are available in the SendGrid dashboard:

* Overall email statistics - Requests, Delivered, Bounced, Spam Blocked, Spam Report, etc.
* Email statistics by category
* Email statistics by geography
* Email statistics by ISP
* Email statistics by device, client, browser

### See also
[Get started with Power BI](powerbi-service-get-started.md)

[Get Data](powerbi-service-get-data.md)
