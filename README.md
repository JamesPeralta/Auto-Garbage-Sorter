# Auto-Garbage-Sorter
## Overview 
The project in this repo can correctly classify the type of garbage from a picture taken from a smartphone. This ensures people don't put their garbage in the wrong bin ;). We developed this application in for the Code the Change Hackathon 2019 sponsored by Benevity and won the People's Choice award.

## Tech Stack
- Frontend: An app that allows users to take a snapshot of their item.
  - React Native
  - JavaScript
- Backend: The backend serves our Deep learning model and processes all images being sent from the app. It then responds with the category of the item (ex. Recycling, Compost) 
  - AWS EC2
  - Docker
  - Flask
  - Python
- Deep learning Model: The Deep learning model was written from scratch and is able to classify the category of the item
  - Keras
  - Google Colab

## Team
* James Peralta [github.com/JamesPeralta](https://github.com/JamesPeralta)
* Albert Choi [github.com/ac1214](https://github.com/ac1214)
* Christian Garrovillo [github.com/christianjpg](https://github.com/christianjpg)
* Nathaniel Habtegergesa [github.com/Natu09](https://github.com/Natu09)
* Justin Flores [github.com/justinf34](https://github.com/justinf34)
* Tony Wong