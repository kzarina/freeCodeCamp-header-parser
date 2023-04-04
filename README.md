# Request Header Parser Microservice

This is a microservice project for freeCodeCamp that fulfills the following user stories:

1. I can get the IP address, preferred languages (from header Accept-Language) and system infos (from header User-Agent) for my device.

The project provides a `/api/whoami` endpoint that returns a JSON object with the user's IP address, preferred language, and system info based on the request headers.

## How to use

To use the project, you need to have [Node.js](https://nodejs.org/en) installed on your machine.

1. Clone this repository: `git clone https://github.com/kzarina/fcc-header-parser.git`
2. Install the dependencies: `npm install`
3. Start the server: `npm start`
4. Open your browser and navigate to http://localhost:3000/api/whoami. You should see a JSON object with your IP address, preferred language, and system info.

You can also use this microservice online by visiting the [live demo](https://boilerplate-project-headerparser.zarina-k.repl.co).
