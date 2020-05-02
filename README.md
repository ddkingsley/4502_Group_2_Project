# Chicago Crime
## An Analysis of Chicago Crime Trends

### Team Members
- Graham Dominick
- Isaac Hames
- Amanda Killeen
- Daniel Kingsley

### Description of the project
Our goal for this project was to use data mining techniques on a dataset of Chicago crime information in order to uncover novel trends about crime in the city such as crime waves, trends, and clusters, through patterns and correlations between crime, location, and time. We hoped that the trends we uncovered could potentially help understand the factors causing crime in Chicago, provide insight leading to possible solutions, and provide law enforcement with predictive tools.

In this data mining effort we attempted to answer a number of interesting questions about Chicago crime. One interesting question we set out to answer was “Is there a correlation between type of crime and location description or district?” We approached answering this question using a partial data cube and viewing a two dimensional cuboid. Our results showed a concentration of “Battery” has a higher frequency of occuring in districts 2 through 11. We also saw a concentration of “Theft” in districts 1, 18 and 19. These results could be used by law enforcement or researchers to address this crime. In addition to identifying districts with higher rates of battery and theft, we also sought to develop an arrest prediction model using classification techniques and we were able to create an arrest prediction model with using Logistic Regression and Naive Bayes ~85% accuracy  Finally through the application of the association rule, we were able to determine the frequent itemset {Residential, Not Domestic, Property Crime} was the least likely to result in arrest.

### Summary of questions and answers
In this project, we set out to answer the following questions:
- Is there a correlation between type of crime and location description or district?
  *Yes, we discovered through the use of visualization and a data cube, that crimes like homicide, battery and theft have a recurrent pattern in certain districts and locations.
- Do arrests occur more often in different locations for the same crime?
  *Property Crime had the lowest rate of arrests being made, with the highest likelihood of not being arrested being the item set {Residential, Not Domestic, Property Crime}
- What are the most common crimes for different areas?
  * “Battery” has a higher frequency of occuring in districts 2 through 11. We also saw a concentration of “Theft” in districts 1, 18 and 19.
- Can an accurate model be generated for “arrest made” based on other information about a crime? 
  * Using a Decision Tree Model, we can predict with ~85% accuracy whether an arrest will be made.

### Application of this knowledge
- Law enforcement can use results based on location to increase presence and/or implement neighborhood watch, in particular residential areas due to high rate of no arrest.
- Potential for researchers to investigate districts with higher rates of battery and theft to see if there is a correlation between these crimes and other factors (socioeconomic, education, gang presence)
- Use arrest prediction to see if there is bias in crime investigation. i.e. do some districts have higher arrest rates than others because of less police attention?

### [Link to Video Demonstration](https://github.com/ddkingsley/4502_Group_2_Project/blob/master/Group2_Chicago_Crime_Part6_Video.mp4)

### [Link to your final project paper](https://github.com/ddkingsley/4502_Group_2_Project/blob/master/02_AnalysisofChicagoCrimeTrends_Part4.pdf)
