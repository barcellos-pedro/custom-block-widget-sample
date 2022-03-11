# Sample Salesforce Marketing Cloud Content Builder Block using the blocksdk.

- Chose one method below to deploy this project to later use the localhost url into [blocktester](https://blocktester.herokuapp.com/) block widget URL field.

- Or use any other [hosted app URL](https://custom-block-widget-sample.herokuapp.com/)

![blocktester url field to fill](https://i.imgur.com/OeCZx8c.png)

# Deploy via Live Server
Deploy through VS Code extension Live Server, clicking **Go Live**

![live server example](https://i.imgur.com/6HXGcgq.png)

# Deploy as a node app

```
npm install
npm start
```

# Building Docker image
Go to the directory that has Dockerfile and run the following command to build the Docker image.
```
docker build . -t <your username>/custom-block-widget-sample
docker run -p <some port>:8080 -d <your username>/custom-block-widget-sample
```