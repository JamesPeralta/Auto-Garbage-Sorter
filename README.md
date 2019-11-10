# Auto-Garbage-Sorter
## Overview 
The algorithm developed in this repo can correctly classify the type of garbage from a picture. This ensures people don't put their garbage in the wrong bin ;). We developed this application in 12 hours for the Benevity Hackathon and won Peoples choice award.

## Tech Stack
- Frontend: An app that allows users to take a snapshot of their item.
  - React Native
- Backend: The backend serves our Deep learning model and processes all images being sent from the app. It then responds with the category of the item (ex. Recycling, Compost) 
  - AWS EC2
  - Docker
  - Flask
- Deep learning Model: The Deep learning model was written from scratch and is able to classify the category of the item
  - Keras
  - Google Colab

