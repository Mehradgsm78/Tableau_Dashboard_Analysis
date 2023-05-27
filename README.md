# Tableau_Dashboard_Analysis
The objective of this project is to use Tableau to analyze the Apartment Building Registration dataset and create dashboards that will provide important insights. 

I have used the ‘Apartment Building Registration’ dataset. This dataset has information on the buildings registered in the Apartment Building Standard (ABS) program. This dataset contains lots of important features, in our dashboards we have used some of them to create a visualization that can create actionable insights that would be significant to the ‘RentSafeTO’ program. Now, let’s dive into these two dashboards. 
  
  Figure 1 depicts a dashboard showcasing the general trends of Toronto rental apartments. The dashboard comprises three visualizations and two colors, with blue denoting buildings constructed during the peak period and orange denoting those that were not. The peak period refers to the period between the 1950s and 1970s, during which a large number of apartments were built in Toronto. The first visualization on the top left displays the number of buildings constructed each year from 1809 to 2020. The second visualization depicts the number of buildings with different numbers of storeys, ranging from three to twenty. The majority of buildings have three to four storeys and were constructed during the peak period, while taller buildings of thirty-one to fifty-one storeys were mostly built in recent times.The visualizations at the bottom illustrate the trends of unit density and average confirmed stories, where unit density represents the number of units per storey. In the beginning, the unit density is quite constant between ~5-10. As we get into the peak period, there’s a linear increase in unit density and almost doubling by the end of this period. The main insights here suggest that the population was growing, leading to a decrease in unit sizes and an increase in the number of units per storey. Subsequent to the peak period, there has been a diverging trend towards both high and low-density apartments. The bottom visualization indicates that the number of storeys per building grew during the peak period and has exponentially increased in recent years.


<img width="751" alt="Screenshot 2023-05-27 at 12 06 44 PM" src="https://github.com/Mehradgsm78/Tableau_Dashboard_Analysis/assets/132492356/5e53114e-f82a-4bc4-8512-7e603b33e419">

Figure 1. General Trends of Toronto Rental Apartments

The second dashboard, represented in Figure 2, offers more actionable insights, focusing on ‘Fire Risk Analysis of Toronto Rental Apartments’. The top-left visualization highlights the approved fire safety plan, fire alarm check percentage, and water pump testing. Hovering over the green, red, and grey segments displays the respective percentages. You can also click on each segment, and the information presented in the other visualizations would change accordingly. We can see that above 95% of apartments have an approved fire safety plan and have undergone fire alarm checks, while approximately 75% of apartments have undergone water pump testing. Now, let’s try clicking on the red part of water pump testing to get some insights. It’s observed that 23.75% of the apartments are not tested. The storey distribution visualization exhibits a significant skewness, with the majority of three to four-story buildings not having completed the test. Interestingly, we can notice that from the previous dashboard we saw that majority of 3-4 storeys were built in the peak period. 


We also have a ‘heating equipment age distribution’ visualization. On top left, the ‘Heating Type’ filter enables users to filter by heating equipment type. 
Red bars denote original equipment, while grey bars represent replaced equipment. We can observe that majority of old buildings, >50 years old, still have the original equipment. Now let’s focus on some insights that can be derived from this visualization. During winter the buildings use different types of heatings. Let’s focus on ‘Forced air gas’ type as an example. We can see that the buildings that have not completed the water pump testing, and have old heating equipments (not replaced) are more susceptible to significant danger. Hence, we should priotorize water pump testing on these types of buildings. Additionally, the majority of buildings that have not completed water pump testing are clustered in the bracket of 40- to 90-year-old buildings. 
The heating equipment age visualization also reveals that buildings between one and five years old use original heating equipment, which is not surprising. However, it is critical to prioritize replacing original heating equipment in older buildings.


<img width="760" alt="Screenshot 2023-05-27 at 12 08 51 PM" src="https://github.com/Mehradgsm78/Tableau_Dashboard_Analysis/assets/132492356/cd928721-dff1-4d57-aa36-46b0d311111b">

Figure 2. Fire Risk Analysis of Toronto Rented Apartments

What we have discussed above are just few examples of driven insights from the dashboards. These dashboards are very interactive and can provide many important information to the board of executives of city of Toronto and some of these insights would potentially prevent disasters in terms of fire system in the buildings. 






