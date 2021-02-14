# XMeme


## Local Run Backend

To run the Backend locally on Port `8080` and `8081`

```bash
cd Backend
npm install && npm run server
cd..
```

## Backend Deployment

* Create an EC-2 instance in Aws on Ubuntu 18.
* Associate it with an Elastic IP.
* Clone your App.
* Install Dependencies on Server.

### PM2 Server

```bash
cd Backend
sudo npm i pm2 -g
pm2 start server.js
pm2 startup ubuntu
```

## Local Run Frontend

To run the Frontend locally on Port `3000`

```bash
cd Frontend
yarn install && yarn start
cd ..
```



