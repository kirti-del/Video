## 🔰 MS Teams Clone 🔰
An attempt to make a clone of existing MS Teams for Micorsoft Engage 2021 Link: https://microsoft-teams-clone14.herokuapp.com/🔗.
It was a challenge given by Microsft to build a replica of MS Team with a mandatory feature where atleast 2 people can join a room and have video call. On my way of building this I used MERN stack for building its frontend and backend. I tried and added more featrues by myself to make it user-friendly

# Features 🔰
1) Create Teams/ Delete teams: Make teams for 2 or more people to connect
2) Send messages: Chat with others in the group
3) Share photos: Share photos with your team
4) Video Call: Have video call meetings
5) Manage Profile: Can Edit your profile 

# How to run in local system 💻
This project containns 2 folder 📁 "client" and "server"
Client conatins frontend part and server contains backend part for this website

# Prerequisites
‼️ You should have node version higher than 8
‼️ Get a free account of Chat Engine and note down your project ID and API key

In client's .env.local file

REACT_APP_CHAT_ENGINE_API_KEY=XXXXXXXXXXXXXXXXXXXXX
REACT_APP_PROJECT_ID=XXXXXXXXXXXXXXXXXXXXX
REACT_APP_BACKEND_URL=XXXXXXXXXXXXXXXXXXXXX
Deploy your backend on heroku and save the URL or write http://localhost:3000 if your are running it locally

In server's .env file

CHAT_ENGINE_API_KEY =XXXXXXXXXXXXXXXXXXXXX
CHAT_ENGINE_PROJECT_ID =XXXXXXXXXXXXXXXXXXXXX
MAIL_ID=XXXXXXXXXXXXXXXXXXXXX
MAIL_SECRET=XXXXXXXXXXXXXXXXXXXXX
Create a database in Mongo Atlas and note the secret and url of the cluster



✔️1. Clone this repository

 git clone https://github.com/AdityaKumar-01/MS-Teams-clone.git
✔️2. cd into client and then run

 cd client
 npm install
✔️3. cd into server and then run

 cd server
 npm install
This will install all the dependencies required and your are good to go 💯

# Working 🛠
Frontend

For frontend I used React to build components like form teams and other things. React is a go to option for projects like this where you have multiple repeating components and lot of rendering of components is required. Frontend was supported by lots of other NPM packages too to make the work easy and nice.


Here is a list of those NPM packages 📝
📍 Material UI core
📍 Material UI icons
📍 Axios
📍 React Avatar
📍 React Chat Engine
📍 React Scroll To Bottom
📍 Use Animations
📍 UUID

Backend

For backend I used NodeJS for creating servers and routes. I used node for backend because it has support from a big community for its packages and twilio and chat Engine is very easy to integrate. For database I used MongoDB Atlas which is cloud based data storage.


Here is a list of those NPM packages 📝
📍 Socket.io
📍 Peer.js
📍 UUID
📍 Express
📍 Nodemon

# Tools in Spotlight🔆
Chat engine
Chat Engine helps you to build chat app. You dont have to write all the componets from scratch and every part of it is customizable. In this project I reconfigured most of the components like created own form to send message, created own custom styled chat messages and added functionality like sending pictures and starting a video call with memebers of chat room and many more. It also has its REST API with which you can interact with teh database it has.


WebRTC
With WebRTC, you can add real-time communication capabilities to your application that works on top of an open standard. It supports video, voice, and generic data to be sent between peers, allowing developers to build powerful voice- and video-communication solutions. The technology is available on all modern browsers as well as on native clients for all major platforms. The technologies behind WebRTC are implemented as an open web standard and available as regular JavaScript APIs in all major browsers.

