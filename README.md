# Supply-Chain-Optimization-Using-Python
A low capacity and high capacity plant across 5 countries are considered and a linear programming model is built to determine the total lowest costs for satisfying consumer demand across all countries, based on various constraints. Data visualization is done and interactive widgets are used to compare different scenarios.

## Assumptions made for additional data:
1. Storage Cost : If a country imports the product then it stores at port at some price , else if it produces it then stores in the    production facility.
2. The produce must be delivered to the end-user with 30 days of Production
3. CO2 is emmited while shipping. The destination country will not accept this after a certain limit.

## Reference Code: 
https://github.com/samirsaci/supply-chain-optimization

## Note : 

1. To evaluate different scenerios, change the values in file named 'factor.xlsx'.
2. The Output1 file contains the information about how the demand of a country is fullfilled
3. The Output2 file contains the information about how factory of which kind to open in which country.

## Special Note :

The data preprocessing here is a very crucial step. By getting the data in a form of a dictionary it provides us the flexibility to
manipulate our data as we wish too. In this code we can open N factory of any type in any country. This thing is not possible with
the reference code if change the cat value of 'y' decision variable to 'Integer' from 'Binary'. In my code 'y' decision is set to
'Integer' but if it is changed to 'Binary' then it will also give the same output as the reference code.
