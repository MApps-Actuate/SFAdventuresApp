SFAdventuresApp
===============

The SFAdventures demo is an application that shows how Actuate products can enhance the sales operations experience. It can be used to show ANY company that has a sales force, regardless of the product they sell. It has a fully baked story that highlights functionaliy in crosstabs, third-party gadgets, data selectors with integration to Gmail and Twitter. This is a great overview demo to show product capabilities in a story that most audiences understand, even if they are not in sales.

Sales Operations, Can also be used as a good general demo showing product capabilities.

This demo should be run at 1440x900 resolution for the optimal gadget layout.

You must be connected to the internet for the google calendar on the Sales Rep Info Hub dashboard and the Twitter dashboard to work.

Executive Sales Insights Tab:
	Pipeline vs Goal  - Drills from Region -> District -> Individual Sales Rep.
	Forecast vs Quota - Drills from Region -> District -> Individual Sales Rep.
	
Sales Rep Info Hub Dashboard: 
    Commit this Qtr: 	Drills to report showing orders for selected customer. (already IV)
    Pipeline:			Drills to report showing top orders in pipeline
   
Analytica Insights Dashboard: 
The file SalesAnalysis.xls in Flatfiles is used to calculate the Total Cost needed for the crosstab.
 
    
Create the following bookmark to invoke in read-only mode:
    actuateone.localdomain:8700/iportal/dashboard?conf=%2fApplications%2fSFAdventuresApp%2fDashboards%2fExecutive Sales Insights%2edashboard%3b1&filetype=DASHBOARD&__vp=Default Volume&volume=Default Volume&showBanner=false&showBreadCrumb=false&locale=en_US

To learn how to use GitHub in Eclipse with this repository, check out the following link:
http://saleswiki.actuate.com/MApps%20Demo%20Deployment.ashx

To see more BIRT examples and get support from the BIRT community, go to:
http://developer.actuate.com 
