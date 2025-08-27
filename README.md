Welcome to the Fake News Detector project! This project was created as part of my own work, and I'm excited to share it with the developer community. If you are interested in contributing to this project or using it as a basis for your own development, please read on.


# About FND

FND is a web-based application designed to detect fake news articles. It uses machine learning models to analyze news articles and predict whether they are real or fake. The goal of this project is to provide a tool that can help users identify unreliable news sources and combat the spread of misinformation.

# Feature

.Live News Monitoring: View real-time predictions for news articles. 

<img width="959" height="469" alt="image" src="https://github.com/user-attachments/assets/9abad39e-eb48-422b-bdd5-3948218fdeb5" />

.News Quiz: Test your fake news detection skills by taking our news quiz. 

<img width="679" height="340" alt="image" src="https://github.com/user-attachments/assets/b1fc60c3-7799-48f4-912a-fb4a70fcd9aa" />

.Check News by Title: Enter a news title to see if it's predicted as real or fake. 

<img width="815" height="258" alt="image" src="https://github.com/user-attachments/assets/02487454-7ae8-4bbb-9f13-d02b004bf238" />

.User Collaboration: I encourage other developers to collaborate and improve this project further.
# Getting Started
To get started with this project, follow these steps:

1.Cloning the repository
git clone https://github.com/Anandha-02/Fake-News-Detection.git

2.Install the required libraries for python
cd Fake-News-Detector/app/FakeNewsDetectorAPI/ && pip install -r requirements.txt

3.Install the required libraries for js
cd ../fake-news-detector-frontend && npm install

4.Deployment
Open terminal and cd to project root folder and run

cd app/FakeNewsDetectorAPI/ && python manage.py migrate && python manage.py runserver

To load quiz data,

python manage.py quiz_data_loader game_data/game_data.csv

Open another terminal and cd to project root folder and run

cd app/fake-news-detector-frontend/ && npm start

All set if everything running without errors. Now the deployed web application should open in a browser. If not, open a browser and navigate to http://localhost:3000

# Contributing
I welcome contributions from fellow developers. If you have ideas for new features, improvements, or bug fixes, please open an issue or submit a pull request. Your contributions will be greatly appreciated and will help make this project even better.

# Roadmap
.Enhanced Machine Learning Models: Improve the accuracy of the fake news detection models.
.User Profiles: Allow users to create profiles and track their quiz scores.



