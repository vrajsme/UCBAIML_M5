# UCBAIML_M5
Repository for UCB AI ML Module 5 Assignment - Coupon Accepted
This readme file provides some details on the different types of data explorations I did with the coupons data set and my observations
In order to make the data set usable I have filled null values of the following columns  ['Bar','RestaurantLessThan20','CarryAway','Restaurant20To50','CoffeeHouse'] with never.  The assumption I have made if the column value for the following is null that means the customer never visited them.  

Following are my observations based on the analysis and visualization of the dataset for coupons
1.  56% of the folks who received a coupon accepted it
2.  Coffee House is the highest accepted coupon followed by restuarant (< 20)
3.  College drop outs or some degree and bachelors degree are the highest that accepted coupons
4.  Folks in the age groups of 21, 26 and 31 were the most that accepted the coupons

Observations based on Coupon type "Bar": 
1. Number that got Bar Coupons = 2017
2. Number of Accepted Bar Coupons = 827
3. Only 48% of folks who received the coupon type bar accepted the coupon
4. Out of the total folks who accepted bar coupons,  31% went less than once to bar and 18% when more than once to a bar
5. Ratio of Drivers visiting more than once with passangers not kids and not in Farming, Fishing and Forestory to total accepted is 47%
6. Bar Accepted with No Kids and Windowed = 393
7. Ratio of bar accepted with no kids and widowed to total bar accepted = 0.4752116082224909
8. Bar Accepted with under the age of 30 = 249
9. Ratio of bar accepted with under 30 to total bar accepted = 0.3010882708585248
10. Bar couppn Accepted with cheap restuarant and income < 50k = 100
11. Ratio of bar accepted with cheap restuarant and income < 50k to total bar accepted  = 0.12091898428053205
12. Total bar acceped with No_kids_Widowed plus under 30 plus cheap restuarant with less 50k  = 742
13. Ratio total bar acceped with No_kids_Widowed plus under 30 plus cheap restuarant with less 50k to total bar accepted  = 0.8972188633615478  

In Summary - My observations is the largest group of drivers that accepted bar coupons do not have kids

My Own investigations about coupon - 
1. total records in data set 12684
2. total records coupon accepted 7210
3. Largest number of coupons that were accepted were for expiring in less than 1 day vs less than 2 hours,  this indicates that people wanted to get the coupon to be used at a later point then immediately while driving
4. Most coupons were accepted by people in age group of 21, 26 and 31

Investigations of Coffee House Coupon: 

From the investigation and observations:  most people who accepeted coffee shop coupons had visited coffee shop less than once and are single or married partner

Further investigations on declined coupons it was observed that interestingly the coupon that was highest declined is Coffee House and second heighest is Bar

Further investigations can be done to determine of coupon acceptance rate changes with the distance travelled

Recommendations: Based on the data it suggests that the younger age group accepts the most coupons. 


