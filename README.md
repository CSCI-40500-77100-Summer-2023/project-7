# project-7
## Updated Prototype
project-7 created by GitHub Classroom

This is an android inventory management application. To run this prototype you need Android Studio. In the inventory management app we have three different functions. The dashboard shows the amount of stock you have for each product and alerts in red if product is running low, for example less than 50. The orders section show the current number of pending orders, current orders and upcoming orders. The scanner section brings up a scanner that will have the ability to scan inventory.

For the updated prototype, we added some features, including a recent activity button for every item, color-coded each item to indicate if they are moveable or non-moveable, a search bar in the dashboard to quickly find a specific item, the settings fragment that includes information about user privileges and button to request privileges. The prototype extension also includes an updated front-end UI.
 
## Software Architecture

The most important qualities of our software are **usability**, **availability** (non-functional product characteristics), and **product lifetime**. To optimize usability, our architecture requires only one layer of authentication where the user logins with their employee ID. To optimize availability our architecture includes a replica database, to ensure data availability if something goes wrong with the original database. Further, our architecture is simple and self-contained which will simplify any changes and adjustments made in the future.

![alt text](https://github.com/CSCI-40500-77100-Summer-2023/project-7/blob/master/ArchDiagram.png)


### Technologies 
Our software product will use a relational SQL database due to the structured nature of the data being used. We are keeping track of inventory including number of items, identification for items, item locations and comments. The platform will be a mobile app. We will use a cloud service to provide servers. Further, we will be using open source components to implement in the app such as the barcode scanner.
