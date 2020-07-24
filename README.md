# Project2RealTimeChat

## The Real Time Chat Application will allow users of the app to talk in real time to each other, see who is home/not-home.

## User Stories.

### Admin
  1) There is an admin that can view everything....


### User

1) Users should be able to set if they are Home/Not-Home;
2) Users should be able to see if other users are Home
3) Users should be able to send messages to other Users
4) Users should be able to recieve messages from Users
5) Users should recieve notification of new messages
6) Users should be able to mute themselves and disable notifications

### Stretch Goals
7) Users should be able to send things other than text (photos, emojis, videos)
8) Users should be able to see messsages with other than text objects from other users
9) Users can add other people to the chat
10) Users can edit messages after they are sent




### Database Tables

Name: Users
Fields: (Long PK) ID, (VarChar) Display Name : (Boolean) Is_Home?

Name: Conversation
Fields: (Long PK) ID, (text) Message, (Long FK) User_A,(Long FK) User_B, (Date) Date Sent, (Date) Date Recieved


### Front End Components
Using Material-UI CSS
User navigates to chat screen and sees who is home
User can click each person and send a message


## Current Blockers/Issues: None



