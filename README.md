# mern-sandbox

## Install MongoDB Community Version & Run Server
```
docker pull mongodb/mongodb-community-server:latest
docker run --name mongodb -p 27017:27017 -d mongodb/mongodb-community-server:latest
```

## Use MongoDB Compass Client to verify DB & Data

### Start server:
```
cd mern/server
npm install
npm start
```

### Start Web server
```
cd mern/client
npm install
npm run dev
```

### View UI
