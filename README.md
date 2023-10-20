# SAP-macro
Macro for downloading customers portofolio linked with power BI dashboard 

## Project decription

The macro was created to export data from SAP using SAP GUI Scripting API. In this project, customer data is downloaded and the detailed report about customer accounts is saved to a specific location on the hard drive. A special layout has been created in SAP, and after each download each day, the previous report is overwritten to get the most recent update and insight on accounts. Using this data, a dashboard was designed in Power BI. It includes customer details such as current arrears, percentage of invoices due, total account turnover splitted into two company codes. This makes it easy to get the data you want, and the visualization in the form of a bar chart is more gripping and allows you to more quickly identify strategic points and accounts where immediate action is required. 

## Preparation before use:

Visual Basic: Enabling SAP API, Navigate to Tools/References and enable SAP GUI Scripting API. If API is not available file with .ocx extension (sapfewse.ocx) from SAP GUI folder has to be opened. 

#### Software: Power BI,  ERP SAP R/3., Microsoft Excel, Visual Basic Editor 
