Machine Learning Case Study: Fraud Detection
Design a model to flag potential fraud events for an online event company.
A fraud event is a fake event and tickets are purchased using stolen
credit cards.

Data Science Requirements
Exploratory Data analysis

Feature Engineering

Build a model

Build a Web Application


Exploratory Data analysis and Feature Engineering
14,337 Labeled events (Fraud not Fraud).

Important Object type (Text - ex. account type) converted into integers.

Created a "cleaning pipeline" for future incoming data (json file).

Build a Model:
Built a Random Forest using sci-kit Learn.

Model accuracy on Test data is 93.8%.

Pickled the model for future data to be analyzed.

Build a Web Application
Created a Web Application using Flask.

Click "Submit" to generate a 'new' event, the model then determines
if the event is a fraud and displays the results.

![Web Application](/Screen Shot 2017-03-01 at 11.22.07 AM.png?raw=true "WebApplication")

