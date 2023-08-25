# Profitbase Gantt for Power BI [![github releace](https://img.shields.io/github/release/Profitbase/PowerBI-visuals-Gantt.svg)]

#### An improved Gantt visual with advanced formatting

Hope you enjoy this highly customizable gantt chart for Power BI.

![image](https://github.com/Profitbase/PowerBI-visuals-Gantt/assets/82056309/4a774b3a-e3a8-454d-a275-f68c7d7a48da)

![image](https://github.com/Profitbase/PowerBI-visuals-Gantt/assets/82056309/0667543a-4a2c-49bb-9888-6f7706099035)


![Income Statement](assets/Demo_Screenshot.PNG)

## Have questions or need help?

- To get started and explore features, please visit our [Wiki](https://github.com/Profitbase/PowerBI-visuals-Gantt/wiki).  
- If if you have found a bug, please submit an [issue](https://github.com/Profitbase/PowerBI-visuals-Gantt/issues), and we'll answer you as quickly as we can. 
- If you have a feature request or any other type of inquery regading this visual, please let us know at our [discussion](https://github.com/Profitbase/PowerBI-visuals-Gantt/discussions), and we'll follow your post there.


## Features

- Multiple level hierarchy
- Ragged hierarchy
- Expand/Collapse all rows using buttons, or individually by clicking on one row.
- Add unique formatting per level
- Cross-highlighting / Cross-filtering
- Change header on timeline (Years/Months/Weeks/Days/Hours/Minutes)
- Add Today-line always showing todays date
- Conditional formatting
- Milestones
- Static events with no connection to a specific task
- Event ranges, showing as curtains across all tasks for information about shutdown periods/maintenance windows/holidays or anything else that will affect all tasks.
- Additional columns, showing relevant information for each task

For any questions about this visual, please submit a post in [discussions](https://github.com/Profitbase/PowerBI-visuals-Gantt/discussions).

## Getting started

### Get it from Marketplace

Download the visual from AppSource directly in Power BI Desktop. Search for "Profitbase"
[Purchase the visual on AppSource](https://appsource.microsoft.com/en-us/product/power-bi-visuals/profitbase.profitbasegantt?exp=ubp8&tab=Overview)  

### Video tutorial

[Getting started](https://www.youtube.com/watch?v=TVbvs5DW8b8&list=PLIKjDnkaTRYxmEMX0kb_zRcfVMYRTruD0&index=11&t=89s&ab_channel=Profitbase)

### Step-by-step guide

1. Install Profitbase Gantt Chart from AppSource.
2. Add your data source
3. Add the visual to the dashboard
4. Configure the bucket fields
   - Rows - Drag-drop the column(s) that represents the tasks and task hierarchy
   - Start date - Drag the field that represent the start date of each task
   - End date or Duration - drag a field to either End date or Duration to create the task bars.
   - If you use Duration, the field needs to contain a number (whole or decimal). That number can represent days/weeks/months/years. Set the correct type in the format pane under the option "Duration" to get the correct end date of the task bars.
   - All other fields are optional.

#### Add event markers and event ranges

1. Click the edit link in the upper right menu of the visual.
2. Click on "Create new event" to get started.
3. Provide a name, and select either a date or a date range.
4. Click apply to add the event to the visual.
5. Repeat to add more events, or click "Back to report" when you are done

Event dates will appear as a single line on the selected date, with a label showing the event name.
Event ranges will appear as colored areas from the first day of the range, until the last day selected. 

Both event dates and event ranges can be formatted in the format pane.

#### Add conditional formatting

1. Click the edit link in the upper right menu of the visual.
2. Click on "Conditional formatting" to get started.
3. Click "Create new rule" and give it a name
4. Specify the condition(s)
5. Click "Apply" to activate the conditional formatting rule.
6. Repeate to apply more conditional formatting, or click "Back to report" when you are done.


