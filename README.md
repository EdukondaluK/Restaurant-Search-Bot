# Restaurant Search Bot
Restaurants Search Bot using Rasa Framework &amp; Zomato API

## Screens
![ScreenShot](./ui_1.PNG) ![ScreenShot](./ui_2.PNG) !

![ScreenShot](./Slack_1.PNG) ![ScreenShot](./Slack_2.PNG)

## Demo
Check out the demo @ https://youtu.be/j1BvTwNZKLY

## Features
- User can search top-rated restaurants
- User can search restaurants using location and cuisine
- Support for Interactive elements of Slack


## Rasa Components Used
- [Transformer Embedding Dialogue Policy (TEDP)](https://rasa.com/docs/rasa/core/policies/#ted-policy)
- [Retrieval Actions](https://rasa.com/docs/rasa/core/retrieval-actions/#retrieval-actions)
- [DIET Classifier](https://rasa.com/docs/rasa/nlu/components/#dietclassifier)

## Prerequisites
- Zomato API Key for searching the Restaurants, you can get it [here](https://developers.zomato.com/documentation#/)
- Rasa Framework, check the details [here](https://rasa.com/docs/rasa/user-guide/installation/)

## How to use
- Clone the repo
- add the Zomato API key to `zomatoApi.py` file
- open the terminal in the project directory and run the below commands
  - > rasa train
  - Once the bot has been trained, run the bot using the below commands
  - > rasa run actions
  - > rasa run -m models --enable-api --cors "*" --debug
  
  
  
  
 **Note**: *this bot was specifically designed to work with [Chatbot Widget](https://github.com/JiteshGaikwad/Chatbot-Widget)*
  
