---
title: "Understand how to view snapshots for a forecast in Dynamics 365 Sales Insights | MicrosoftDocs"
description: "Understand how to view snapshots for a forecast in Dynamics 365 Sales Insights"
ms.date: 08/01/2020
ms.service: crm-online
ms.custom: 
ms.topic: article
author: udaykirang
ms.author: udag
manager: shujoshi
---

# View snapshots

>[!NOTE]
>If you have opted in for early access, follow the process as specified in [View snapshot history in early access](#view-snapshot-history-in-early-access).

Viewing a snapshot allows you to see and understand the data of the forecast at the moment in time when it's taken including the underlying opportunities. Also, you can compare and understand the data between your current forecast and snapshot on how the forecast is doing. 


**To view snapshots**

1.	Sign in to the Sales Hub app and go to **Performance** > **Forecasts**.

2.	Select the forecast for which you want to view the snapshots.

3.	Select **Snapshot history**. 

    > [!div class="mx-imgBorder"]
    > ![Select snapshot history](media/predictive-forecasting-select-snapshot-history.png "Select snapshot history")

    A list of snapshot that is available for the selected forecast is displayed in the **Snapshot history** pane.
    
    > [!div class="mx-imgBorder"]
    > ![Snapshot history pane](media/predictive-forecasting-snapshot-history-pane.png "Snapshot history pane")

4.	Select a snapshot to view. In this example, we're selecting **Mar18-1** snapshot and displayed as shown in the following image:

    > [!div class="mx-imgBorder"]
    > ![View a snapshot](media/predictive-forecasting-select-snapshot-to-view.png "View a snapshot")

    >[!NOTE]
    >The data displayed in the snapshot is view only and can't be modified.

    You can select a column and see the underlying opportunities that are defining the value of the column at that point in time. For example, we're selecting Kenny Smith's Committed column and the underlying opportunities that are contributing the value in the **Committed** column at that point in time are displayed.
    
    > [!div class="mx-imgBorder"]
    > ![View underlying opportunities of a column](media/predictive-forecasting-snapshot-select-column-opportunities.png "View underlying opportunites of a column")

5.	To go back to the forecast, select **Back to forecast**.

## View snapshot history in early access

[!INCLUDE [cc-early-access](../includes/cc-early-access.md)]

You can view a snapshot to see and understand the data of the forecast at the moment in time when the snapshot was taken, including underlying opportunities. Also, you can compare the data between your current forecast and the snapshot to understand how the forecast is doing.

>[!NOTE]
>-	To view snapshot history, you must have at least one snapshot created for the forecast.
>-	The data displayed in the snapshot is view-only and can't be modified.

### Open and view snapshots

1.	Sign in to the **Sales Hub** app, and go to **Performance** > **Forecasts**.

2.	Select the forecast for which you want to view snapshots.

3.	Select **See forecast grid history**. 

    >[!NOTE]
    >The **See forecast grid history** option is inactive if there no snapshots available for the forecast.

    > [!div class="mx-imgBorder"]
    > ![Select See forecast grid history](media/predictive-forecasting-snapshot-select-forecast-grid-history.png "Select See forecast grid history")

    The latest snapshot for the forecast is displayed with information about forecast data at that point in time, along with name and date.

    The name of the snapshot is in the following format: *forecast name.recurrence name*. In this example, you can see that name of the snapshot is **FY2020 Quarterly Forecast (do not delete).FY2020 Q3**.

    > [!div class="mx-imgBorder"]
    > ![Forecast grid name and date](media/predictive-forecasting-snapshot-forecast-grid-name-date.png "Forecast grid name and date")

    The format for the date on which the snapshot is taken is displayed based on your personal settings. In this example, the date format is **MM/DD/YY** (**07/27/20**).
  
4.	To view a snapshot from a specific date, select the calendar icon and select the date.

    >[!NOTE]
    >If a date is inactive, there's no snapshot available for that date.

    > [!div class="mx-imgBorder"]
    > ![Select a date to view forecast history](media/predictive-forecasting-snapshot-select-date-forecast-history.png "Select a date to view forecast history")
 
### View underlying opportunities

For a snapshot, you can view the underlying opportunities of a column or the users who are influencing the displayed budget amount at that point in time. By viewing the opportunities, you can analyze and understand how they're trending.

1.	Open a snapshot.

2.	To see the underlying opportunities that are defining the value of a column at that point in time, select the column or user. In this example, Kenny Smith's **Committed** column is selected and the underlying opportunities that are contributing the value are displayed.

    > [!div class="mx-imgBorder"]
    > ![Select a column to view underlying opportunities](media/predictive-forecasting-snapshot-select-column-underlying-opportunities.png "Select a column to view underlying opportunities")

3.	To view the details of an underlying opportunity, under **Actions** column, select the navigate icon corresponding to the opportunity. 

    The opportunity is opened in a new tab. The latest information will be displayed in the opportunity, not the information as of the date of the snapshot.


### See also

[About premium forecasting](configure-premium-forecasting.md)<br>
[Manage snapshots for a forecast](manage-snapshots-forecast.md)<br>
[Analyze deals flow between snapshots](analyze-deals-flow-between-snapshots.md)
