# Seminar Health Economics R Assignment 0

Calculation on costs of an EU wide Health plan.

Scenario 1:
All member states will spend per capita as much (or more) as the Netherlands on their Health sector.

Scenario 2:
All member states will have the same (or higher) life expectancy as the Netherlands. 
This is calculated using a linear regression run on life expectency and health expenditure per capita. 
This coefficient is then used to calculate the extra expenditure needed to match the life expectancy of the Netherlands.


The allocation of this extra expenditure is then calculated for all member states using the following equation:
Extra Expenditure of member i = (GDPi/SUM(GDP))*TotalExtraExpenditure

This calcualtion then shows how much each member state will have to spend for an EU wide Health plan.


