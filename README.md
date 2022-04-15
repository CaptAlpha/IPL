# IPL OverFloww
>**Stack Overflow for IPL queries**

## Inspiration
AI and ML technologies are ruling the world, and is also being used in the world of sports. Data Science is ruling the world of Sports Analytics and Score Predictions in making Fantasy Teams. Our inspiration comes from Stack Overflow which gives you the solution to each and every coding solution you need. Our platform too aims to solve your team's problem.

## What it does

Our project is a consolidated one stop destination for cricket lovers, specifically IPL fans and teams to analyze detailed sport statistics and also answer various important questions using Machine Learning and Data Science.

We here answer some of the most asked questions asked in IPL.
1. Which teams would qualify for play-offs in the Tata IPL 2022
 2. Which team would win the trophy in the Tata IPL 2022? 
 3. Who will win the orange cap and purple cap? 
 4.  Who will be the critical player/players for winning team and why
 5. What strategies/tactics could help the team batting first to win? 
 6. What strategies/tactics could help the team bowling first to win?

We use advanced machine learning to help answer these questions.

We also give in-depth analysis of each team's playing 11, with the help of data visualization tools and techniques.  

## How are we building it?

#### Phase - 1 : Data Abstraction and Pre-processing:
We have collected the data from multiple sources across the internet and are also scraping several websites to get the best results for our outcome. 

The data collected needs to be cleaned and pre-processed according to our needs. We make use of several feature attributes to get the best results. The data is then scaled and encoded properly.

#### Phase - 2 :  Training and Testing our Machine Learning Model:

In order to train and test our models, we need to have a training set and a test set. As is common in machine learning techniques, the division of both datasets was made randomly, with the training set consisting on 75% of the full dataset.

The metrics which we used to evaluate the models’ performance on the test set were the Mean Squared Error (MSE) and the R-squared.

In our project, we have used several machine learning and deep learning models in order to get the best results.

#### Phase - 3 :  Building the API and WebApp:
 Once the machine learning model is ready, we dump it into a pickle file and save it for deployment of the model. The next task is to build the API for the project. 
 Our app will require API's which we will be called when we need to fetch the data regarding any question. The API will be built on flask.
 We will also need to get the frontend ready.

#### Phase - 4 :  Answering questions with help of Symbl.ai:
We will connect symbl.ai API with our project to get the maximum results from scrapped websites 

#### Phase - 5:  Integrating each phase:
 The final step of our project is to integrate all the components of our application in a consolidated manner. The frontend, backend and the machine learning models needs to be integrated in a smooth process.

## What's next for IPL - OverFloww
We also plan to make IPL - OverFloww, a open forum for sports discussion where the discussion will be used as data for model training and give outputs on the basis of the audience.

We also aim to extend IPL - OverFloww to other sports and various other domains, thus making it Sports - OverFloww.
