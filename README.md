Node.js and MongoDB Boilerplate

# Node.js and MongoDB Boilerplate

This is a boilerplate for building RESTful APIs using Node.js, Express, and MongoDB.

## Getting Started

### Prerequisites

- Node.js and npm
- MongoDB

### Installation

1. Clone the repository:

   ```sh
   git clone https://github.com/akashpbhardwaj/nextjs-boiler-plate.git
   cd node-mongo-boilerplate
   Install the dependencies:
   ```

```sh
npm install
```

Create a .env file in the root of the project and add your MongoDB connection string:

env
Copy code
MONGO_URI=mongodb://localhost:27017/yourdbname
PORT=5000
Running the Application
Start the server in development mode:

```sh
Copy code
npm run dev
Start the server in production mode:
```

```sh
npm start
```

Project Structure

```sh
node-mongo-boilerplate
├── config
│ └── db.js
├── controllers
│ └── exampleController.js
├── models
│ └── exampleModel.js
├── routes
│ └── exampleRoutes.js
├── .env
├── .gitignore
├── package.json
├── server.js
├── app.js
└── README.md
```

API Endpoints
GET /api/examples - Get all examples
POST /api/examples - Create a new example

License
This project is licensed under the MIT License.
