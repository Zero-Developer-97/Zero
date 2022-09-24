# Use Case:
Build a weather forecast application which can interact with the weather api and show a weather forecast
for a particular city. The application would allow the users to login, select a country and city from the list
and extract forecast information for a particular date range. It also allows the app maintainers to perform
analytics and display top n users who have access forecast service and most commonly queried city and
country.
Backend:
Enhance the API layer (existing app) to include the following functionalities:
1. Geo APIs (use data/country_data.json and perform lookup):
a. List all the countries
b. List all the cities of a country
2. Forecast APIs:
a. List forecasts for a city and number of future dates (3, 5, 7 etc)
3. Analytics APIs:
a. List top n users using forecast
b. List top n countries being queried for forecast
c. List top n cities being queried for forecast
Hint: For analytics APIs, ensure to audit the users and queries being fired into the DB.
Pre-requisites (What you need to implement this):
1. Since this development integrates with weather api, ensure to sign up against weather api and
generate an api key.
UI:
Create a simple user interface using React / Angular. Ensure to use any css framework like
Material, Ant, Bootstrap etc and make it more responsive. Use the following wireframe / design
to build an SPA
