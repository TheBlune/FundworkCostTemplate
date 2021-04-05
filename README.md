# FundworkCostTemplate
 A template for managing your [FundWork-](https://github.com/TheBlune/FundWork)cost-file on Github.
 
 To get started, just fork this Repo and you will get: 
 - A public & transparent version-controlled file for your webistes/services-costs and capital income 
 - A way for users to suggest cost-optimizations via the issues-tab on this repo
 - No real-serverwork needed to get started using the [FundWork-Reports](https://github.com/TheBlune/FundWork)

File Structure: 
'''
- fdate: last date the finances have been updated 
- totalcosts: sum of all costs
- costsdate: the date since when the costs havn't changed
- currentcapital: startcapital-Months*(monthlyIncome-monthlycosts)
- startcapital: Capital on time when this cost-file has been started
- currency: Symbol of Currency you want to display
- costs: Array of every monthly cost
 - name: Name displayed
 - category: Costs are clustered to userdefined categories like hosting, content-creation,....be creative
 - amount:actual monthly cost as a float
 - info: Additional Info like tariffs to be shown on mouseover
- capitalsources: Array of all monthly Capital sources 
 - month: The month the capital has been received in
 - sources: The different sources
  - name = Name displayed
  - category = e.g. "Tier1" for direct donations, that do not have as much taxes and "Tier2" for things like patreon where 10% of the incoming pledge is taken away. Setting this category allows to emphasize that not every cash-flow is as welcomed as another, because e.g. in this example there may be middlemen cutting off money
  - amoutn actual monthly income
  - recurring: set "1" here, if this amount savely comes in every month. This uses to project your capital, if you forget to update the costs for a few months
  - info: Additional Info to be shown on mouseover
'''
