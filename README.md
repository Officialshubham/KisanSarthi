# KisanSarthi

## Name of the team
- Shubham Sharma
- Yogesh Singh
- Shivam Thakur

## Number of Members in a Team
3

## College
Maharaja Surajmal Institute of Technology

## Theme of the Project
Open Innovation | Agriculture

## Discord Usernames of TEAM MEMBERS on Discord Server (Technothon 1.0)
- Shubham Sharma | Participant
- Yogesh Singh | Participant
- Shivam Thakur | Particiapant

## Detailed Explanation of the Idea
The core idea of The KisanSarthi is to aid farmers by providing them best suited information about their crop.KisanSarthi is a platform that is built for aiding farmers scientifically in their farming practices. We built three main things that farmers use on daily basis. The first utility is disease identification in which farmers have to upload the image of the leaves of the crop. The platform returns the suggested crop which farmers should grow on their farms. The second utility is crop suggestion in which the farmer has to give some basic information regarding soil nutrients and ph value. Based on this, the platform will suggest the crop which farmers should grow. The third utility is the macro-nutrients suggestion in which the farmer has to provide us with the N-P-K values along with the crop he wants to grow, the platform is able to give the suggestions of nutrients along with some additional information on the nutrients.

## Solution provided
Our app makes it easy for the farmer to get information about their crop based on the soil info and weather. Also, they can get info about the crops diseases and fertilizer for crops.

## Tech Stack used
### Backend 
- Python
- Machine Learning
- Flask
- Pytorch

### Frontend
- React

## Real time usage

### Intro

![intro](https://user-images.githubusercontent.com/42817026/124343030-1e2a9400-dbe6-11eb-80a1-8284a45537e0.gif)

### Disease Identification

![diseaseIdentifier](https://user-images.githubusercontent.com/42817026/124343043-339fbe00-dbe6-11eb-8e2b-b3fabd72e041.gif)

### Crop Suggestion

![cropSuggestor](https://user-images.githubusercontent.com/42817026/124343058-4a461500-dbe6-11eb-8aed-5eb3c401f27c.gif)

### Macro Nutrients Suggestion

![macroNutrientsSuggestor](https://user-images.githubusercontent.com/42817026/124343066-5d58e500-dbe6-11eb-8e69-1764b6e16e60.gif)


## How to run locally
- Register for [OpenWeather](https://openweathermap.org/api) to get APPID which is important to run backend of the app
- Export APPID as environmenet variable then
1. Open terminal in root folder then
```bash
cd backend
pip install -r requirements.txt
flask run*
```
2. Open a new terminal in root folder then
```bash
cd frontend
npm install
npm start
```
3. Visit [localhost:3000](http://localhost:3000/).

##### *Note: Make sure flask server is being run on port 5000
