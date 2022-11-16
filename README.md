# GYST "Get Your Shit Together!"

Keeping up with college life is difficult. Students feel overwhelmed just thinking of their daily tasks, let alone keeping up with their favorite topics. Our application GYST tackles this problem in a simple, automated solution. All a user has to do it input their favorite news buzzwords, personal calendar, and phone number. From this, they will automatically receive a personalized text message from GYST containing their daily tasks, upcoming tests, news articles, and even have the option to receive a joke of the day!

We used React Bootstrap to make the UI, and many, many APIs to scrape data and complete tasks. We used a Google API client to authorize users and pickle to store their credentials. From this, we used the Calendar API to scrape user events and sort the data into appropriate categories based on dates and keywords to create the text message. We used the Twilio Conversational API to send and receive text messages between GYST and the user. Based on the user's interaction with the UI, we created a personalized news summary using a News Client API. In addition, the user has the option to send text messages and receive either the Joke of the Day using Twilio or the daily weather report using Weather API. This functionality was aggregated using Amazon Web Services, S3, Lambda, and API Gateway.
