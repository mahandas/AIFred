# AIFred

Assisted Restricted Access Intelligence - An AI based age restricted access to multilingual chatroom with personal chatbot assistance called Alfred.  
3rd Position in EMTech Hackathon'19

[![Everything Is AWESOME](https://github.com/mahandas/AIFred/blob/master/alfred.jpg)](https://www.youtube.com/watch?v=qIXZfg3VyG8&feature=emb_logo "Everything Is AWESOME")


## Inspiration
  
Protecting young minds from age restricted activity.  
Adding an AI friend in a conversation who can help with the mood of the conversation or assist the conversation.  
Helping people from Diverse community to collaborate without the hassle to learn new lingual and communicate more effectively.  
  
## What it does
  
The application uses Flask as the base framework having multiple segments to the process primarily:  

1) The login authentication uses webcam having the facial recognition system through Opencv and a model trained using Wide Residual network predicting a person's age and gender.  
2) The chatroom system which is entered when someone crosses the predicted age value or otherwise barred from entering. An user can choose his preferred language to chat as well.  
3) A multi-session chat system that can invoke a chatbot trained in chatterbox english corpus conversation only when triggered with @alfred command and is personal to each chat in parallel and visible to that user only.

## How I built it
  
The chatroom built using the flask framework, implemented on websockets and google translate api. Access control is using wide residual networks, to detect the age of the person. This is done using opencv to detect faces in video streamed via webcam. keras implementation for age classification. Chat bot is build on top of tensor flow  
  
## Challenges I ran into
  
1. latency with large datasets for more accurate responses for @alfred
2. predicting the round about age of a person with lot of background noise
3. streaming video data from page to server
  
## Accomplishments that I'm proud of
  
To have a multi level ai assisted system to one single pipleline for both detection and prediction of various models of regression and classification.

## What I learned
  
Team work. Community driven experience. (Multilingual corpus translation) AI implementation for a practical filter and check. assisted bots continuous coding for 16+ hrs

### References:
Devpost Link: https://devpost.com/software/ai-fred-6ubhoi
