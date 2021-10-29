# Olympic Athletes Data Challange

## Background and Task
During the two-day Data Challenge, the goal was to predict who will win the Olympics. This was done using a historical dataset of the modern Olympic Games, covering all games from Athens 1896 to Rio 2016.
The provided data was scraped from www.sports-reference.com in May 2018 and contains 271’116 rows and 15 columns.

## Feature Discription
- ID: Unique number for each athlete
- Name: Athlete’s name
- Sex: M or F
- Age: Integer
- Height: In centimeters
- Weight: In kilograms
- Team: Team name
- NOC: National Olympic Committee 3-letter code
- Games: Year and season
- Year: Integer
- Season: Summer or Winter
- City: Host city
- Sport: Sport
- Event: Event
- Medal: Gold, Silver, Bronze, or NA

## Methodology
- Data Exploration
- Data Cleaning and Preparation
- Supervised Machine Learning
- Explore Predictions

## Results
It was possible to correctly predict most people who did not win a medal and almost 40% who won a gold medal. Moreover, the countries that won the most medals in the actual data were also the ones that were predicted to win medals most often.
However, many fewer medals were won in the predicted data and it was very difficult to correctly predict silver and bronze medals.

## Outlook
- Up / down sampling
- Use more data → Tokyo 2021
- Data cleaning 
  - delete no longer existing sport events
  - cut off some years
- Feature engineering
  - Using Name of the athletes → Bolt, Phelps
  - Categorize data 
