---
title: Filter the View of DNS Resource Records
ms.custom: na
ms.prod: windows-server-threshold
ms.reviewer: na
ms.suite: na
ms.technology: 
  - techgroup-networking
ms.tgt_pltfrm: na
ms.topic: article
ms.assetid: 5b80294a-7325-476b-84eb-69f0d051e8b2
---
# Filter the View of DNS Resource Records
You can use this topic to filter the view of DNS resource records in the IPAM client console.

Membership in **Administrators**, or equivalent, is the minimum required to perform this procedure.

### To filter the view of DNS resource records

1.  In Server Manager, click  **IPAM**. The IPAM client console appears.

2.  In the navigation pane, in **MONITOR AND MANAGE**, click **DNS Zones**.  The navigation pane divides into an upper navigation pane and a lower navigation pane.

3.  In the lower navigation pane, click **Forward Lookup**. All IPAM\-managed DNS Forward Lookup zones are displayed in the display pane search results.

4.  Click on the zone whose records you want to view and filter.

5.  In the display pane, click **Current view**, and then click **Resource Records**. The resource records for the zone are shown in the display pane.

6.  In the display pane, click **Add criteria**.

    ![](media/ipam_FilterRR_01.jpg)

7.  Select a criteria from the drop\-down list. For example, if you want to view a specific record type, click **Record Type**.

    ![](media/ipam_FilterRR_02.jpg)

8.  Click **Add**.

    ![](media/ipam_FilterRR_03.jpg)

9. **Record Type** is added as a search parameter. Enter text for the type of record that you want to find. For example, if you want to view only SRV records, type **SRV**.

    ![](media/ipam_FilterRR_04.jpg)

10. Press ENTER. The DNS resource records are filtered according to the criteria and search phrase that you specified.

    ![](media/ipam_FilterRR_05.jpg)

## See Also
[DNS Resource Record Management](DNS-Resource-Record-Management.md)
[Manage IPAM](Manage-IPAM.md)

