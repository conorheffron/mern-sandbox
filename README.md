# mern-sandbox

#### Install MongoDB Community Version & Run Server
```
docker pull mongodb/mongodb-community-server:latest
docker run --name mongodb -p 27017:27017 -d mongodb/mongodb-community-server:latest
```

![docker-ps](./screenshots/docker-ps.png?raw=true "Docker Processes")

#### Use MongoDB Compass Client to verify DB & Data

![compass-client](./screenshots/compass.png?raw=true "Compass Client")

##### Start backend server in VS Code & see logs per CRUD operation
```
cd mern-sandbox/server
npm install
npm start
```

![run-server](./screenshots/run-server.png?raw=true "Run Backend")

##### Start Web/Client server in VS Code (new terminal tab)
```
cd mern-sandbox/client
npm install
npm run dev
```

![run-client](./screenshots/run-client.png?raw=true "Run Frontend")

#### View UI (use `chrome dev tools` to see client side logging)
```
http://localhost:5173/
```
![local-ui](./screenshots/local-ui-running.png?raw=true "Local UI")
