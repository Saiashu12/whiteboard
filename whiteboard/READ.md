whiteboard/
├── client/         # React frontend
├── server/         # Node.js + Express backend
├── README.md

First clone the project 
cmd: git clone https://github.com/Saiashu12/whiteboard.git
cd whiteboard
create the server folder like this
server/
├── models/
│   └── Room.js
├── routes/
│   └── rooms.js
├── socket/
│   └── index.js
├── server.js
└── .env
To do this
cd server
then mkdir models routes socket
now transfer the files present in /whiteboard directory

Room.js into models
rooms.js into routes
index.js into socket
and server.js and .env files into /server folder

Then in bash cd server
npm install
npm start

Now you can see 
🚀 Server running on http://localhost:5000
✅ Connected to MongoDB
⚡ User connected: IXaP4YqJYf6QQfXCAAAC
⚡ User connected: LlJC1womlHC9nTizAAAD

******************************************************* 
now for frontend
cd frontend
npm install
npm start
then the web page should open
