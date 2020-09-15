# CS3219-OTOT-assignment-D

## Set up
1. Install node js
2. Install docker and docker-compose
3. git clone project

## To start Kafka cluster
1. Use terminal and go to project directory
2. Run `docker-compose up -d`
3. Run `npm install`
4. Run `npm run build && npm run bundle`
5. Run `npm start`
6. Open browser go and go to `localhost:3210`
7. Send messages by running `kafka-publish -t test "message"` to see message appear on the browser



References: https://hmh.engineering/experimenting-with-apache-kafka-and-nodejs-5c0604211196