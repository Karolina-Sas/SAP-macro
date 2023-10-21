# SAP-macro <img src="https://github.com/Karolina-Sas/SAP-macro/assets/68974023/89404143-83cb-4980-abef-ae3f5d212ace" width=5% height=5%> <img src="https://github.com/Karolina-Sas/SAP-macro/assets/68974023/b0bc9210-d470-4eb1-a455-4eaa63da5e91" width=5% height=5%>


Macro for downloading customers portofolio linked with power BI dashboard 

## Project description

The macro was created to export data from SAP using SAP GUI Scripting API. In this project, customer data is downloaded from SAP and the detailed report about customer accounts is saved on a specific location on the hard drive. A special layout has been created in SAP, and after each download every day, the previous report is overwritten to get the most recent update and insight into accounts. Using this data, a dashboard was designed in Power BI. It includes customer details such as current arrears, percentage of invoices due, total account turnover splitted into two company codes.
This makes it easier to get the data we want, and visualization in the form of different types of charts is more engaging and allows to more quickly identify strategic points and accounts where immediate action is required. 

## Preparation before use:

:page_with_curl: `Microsoft Excel`: Enabling macros <br>
:page_with_curl: `Visual Basic`: Enabling SAP API -Navigate to **Tools/References** and enable **SAP GUI Scripting API**. If SAP API is not available, file with .ocx extension (sapfewse.ocx) from SAP GUI folder has to be opened. 

#### Software: Power BI,  ERP SAP R/3, Microsoft Excel, Visual Basic Editor 
