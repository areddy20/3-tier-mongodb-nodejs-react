# 3-tier-mongodb-nodejs-react
Dockerized a 3-tier application using the mongodb database, nodejs code in the backend, and react for the frontend.

NOTE: make changes in the the App.js as shown below.

.
├── backend
│   ├── app.js
│   ├── Dockerfile
│   ├── logs
│   │   └── access.log
│   ├── models
│   │   └── goal.js
│   ├── node_modules
│   └── package.json
├── docker-commands.txt
├── docker-compose.yaml
├── env
│   ├── backend.env
│   └── mongo.env
├── frontend
│   ├── Dockerfile
│   ├── package.json
│   ├── package-lock.json
│   ├── public
│   │   ├── favicon.ico
│   │   ├── index.html
│   │   ├── logo192.png
│   │   ├── logo512.png
│   │   ├── manifest.json
│   │   └── robots.txt
│   ├── README.md
│   └── src
│       ├── App.js <<<<<<<<<<<<<<<<<<<replace the API call to the backend with host IP, for example await fetch('http://<host IP where this app is running>/goals')>>>>>>>>>>>>>>>
│       ├── components
│       │   ├── goals
│       │   │   ├── CourseGoals.css
│       │   │   ├── CourseGoals.js
│       │   │   ├── GoalInput.css
│       │   │   ├── GoalInput.js
│       │   │   ├── GoalItem.css
│       │   │   └── GoalItem.js
│       │   └── UI
│       │       ├── Card.css
│       │       ├── Card.js
│       │       ├── ErrorAlert.css
│       │       ├── ErrorAlert.js
│       │       ├── LoadingSpinner.css
│       │       └── LoadingSpinner.js
│       ├── index.css
│       └── index.js
└── README.md

