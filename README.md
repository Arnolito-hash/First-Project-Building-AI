# Best Coffee in the City

Final project for the Building AI course: Create best recommendations to find the best coffee in the city

## Summary

Development of a system that displays personalized recommendations tailored to each customer’s preferences in the city, based on their historical data and location history. The recommendations will be displayed to customers in the coffee shop search app and on the relevant website.

## Background

In recent years, the number of coffee shops in the city has changed compared to the past, and coffee consumption has declined as customers have turned to other options, such as bars. By using a recommendation system, each customer will be shown the highest-rated bars, which should have a positive impact on sales and also appeal to customers looking for a good cup of coffee.

We help people find the best coffee shops in every city. 
Our reviews are written by customers who are experts in the specialty coffee industry.
Only expert reviews, written by our customers.
We rate places on a scale of 1 to 5 stars based solely on the quality of the coffee. We also highlight other aspects such as the atmosphere, pastries, customer service, and much more.

## How is it used?

The first step is to identify the specific customer looking for a good coffee shop in the city. To do this, the following methods will be used:

within the city: for example, people who lack the time or mobility to travel;
outside the city: for people who have the time and mobility to travel;

Once the customer has been identified, the backend system must present the options—within a short timeframe and distance—create recommendations, and display them. The recommendations could be displayed, for example:

a) within the city: as part of the app’s or website’s graphical user interface
b) outside the city: as part of the app’s or website’s graphical user interface

“Coffee Stars” are awarded based on the quality of the coffee, as well as the customer service and price. This is a new rating that a coffee shop can earn in our rating system. 

Coffee shops are evaluated based on:

-Quality of preparation
-Quality of the coffee
-Consistency over time and across the menu
-Customer service
-Price

Below are the star categories:

5 Five Coffee Stars
This is the kind of café you rarely come across—a true gem of the city, offering personalized service where they not only know you by name but also know your preferences. And if you bring your dogs along, they always have a bowl of water waiting to cool them off. The atmosphere is the best; the music and seating let you relax while you enjoy your well-deserved elixir. It’s one of those sacred places known only to true coffee connoisseurs—the price doesn’t matter, only the great experience.

4 Four Coffee Stars
A top-tier café with personalized service and a high-class atmosphere where everything is top-notch, just like the price.

3 Three Coffee Stars
High-quality coffee, personalized service, reasonable prices, and an exquisite atmosphere—a destination in itself

2 Two Coffee Stars
Superior coffee, superior service, and a fair price—it’s worth visiting at least three times.

1 One Coffee Star
Good coffee, good service, and a fair price.

0 New Coffee Shop (No Stars)
It doesn’t have any stars yet, but it’s still worth a visit for an initial evaluation.

## Data sources and AI methods

The system would require the following data sources:

a) information needed to identify customers—for example, through the app or website to access the service and locate the customer in the city
b) customer information—for example, details about the customer’s age and preferences;
c) information on the customer’s previous search history—this information should be available in the company’s internal database—
d) Other relevant information: for example, current weather conditions to create weather-based recommendations (e.g., places with outdoor seating or parks for drinking in the summer, or with warm interiors in the winter) using publicly available weather services (e.g., the Weather API or traffic city API), information on ongoing marketing campaigns (e.g., giving preference to Coffee that want to advertise and be ranked higher or that are currently on sale, etc.). Once the customer has been identified, the information will be provided to the recommendation system. The recommendation system will be based on a neural network. Since it is anticipated that a large amount of data will need to be processed in a short period of time, the task will be broadly divided into two subtasks:

1- select the top 10 best coffee in the city

2- rank them based on the “Coffee Stars”

The recommendation system will return one or more Coffees, which will be displayed to the customer during the search process.

## Challenges

To objectively assess the quality of the model, it will be necessary to define appropriate quality indicators, particularly for recommendation systems.
Since the system requires the collection of a certain amount of personal data, this must be done with the customer’s consent and in accordance with local data protection and privacy laws, particularly in Europe under the relevant GDPR regulations.

## What next?

The next step would be to create a data model for the customer, city, and café data sources, and then begin developing the recommendation system model. I would have to go even more into learning AI and maybe using one of the best AI creators of the moment like Claude, Emergent, Replit or Base44. After that we can look into some city database that include bares for testing sets and experimenting with that before we create the first recommendations. Anyone interested in collaborating is welcome to join!!!

## Acknowledgments

* Reaktor, MinnaLearn team and University of Helsinki for creating Elements of AI https://www.elementsofai.com/ with the 2 trainings Introduction to AI and Building AI	 
* when you have permission to use other people's materials, always mention the original creator and the open source / Creative Commons licence they've used For example: [Sleeping Cat on Her Back by Umberto Salvagnin](https://commons.wikimedia.org/wiki/File:Sleeping_cat_on_her_back.jpg#filelinks) / [CC BY 2.0](https://creativecommons.org/licenses/by/2.0)
