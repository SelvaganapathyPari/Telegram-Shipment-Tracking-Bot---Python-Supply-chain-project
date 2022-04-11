## Real-Time Shipment Tracking Tool using  Telegram Bot
In this Python project we are designing a Telegram Bot that will interact with truck drivers and help supply chain professionals to track your shipments easily.

## Solving a problem which i have faced many times
As a supply chain professional you have to track lot metrics including critical items for production, placing new orders, managing past dues, rescheduling part numbers which are not currently required and more. Mostly important you should also track the incoming shipments from supplier and many times the scheduled items/ shipments needed much more attention as these items could be scheduled for next day production and it is very critical to track them in regular intervals.

As a supply chain professionals i have worked with both national and international suppliers, and tracking the critical shipments is one of the biggest challenges.

### Let me tell you a real situation which i have faced- During when i was working at EATON, there is one item (SKU) which was very critical for the next day production and every resources were planned based on that incoming item. And my job is to closely track and make sure it arrives ontime and move to the production. And, my manager asked to closely track the shipment for every 2 hours and make sure it arrives without any hassle. 

### so i need to constantly connect with truck driver and get shipment details on regular basis. but in reality it might not be as easy or practical thing to do, because though the arrival material is critical for us(company), we shouldn't force our thougts on others( truck drivers or any carriers), as it might impact their productivity. this is where the telegram bot could help supply chain professionals. 

### Benefits of this telegram bot
- simple, cheap and easy-to-implement solution to track your shipments 
- Does not require additional IT development for your carriers
- Easily integrates into the current transportation processes
- Does not impact drivers’ productivity
- Does not require additional equipment
- Easily Monitor whether the shipment is damaged at loading end or while in transit

### How does it work?
Scenario
Your shipment has been unloaded in your store. DRIVER wants to send delivery confirmation before leaving for his next destination.\
#### Step 1: DRIVER opens telegram and starts a discussion with BOT 
![This is an image](https://miro.medium.com/max/315/1*qnBHC99rd8J1Q5xmommMew.png) 
#### Step2: DRIVER shares it’s GPS Location (= Store Location) 
![This is an image](https://miro.medium.com/max/315/1*c1XgJWH7EH-Lcg5YPQiTWA.png)
#### Step 3: DRIVER shares a delivery number 
![This is an image](https://miro.medium.com/max/315/1*Vb3et27oNAnje5sSWgdh0w.png) 
#### Step 4: DRIVER shares a picture of the shipment 
![This is an image](https://miro.medium.com/max/315/1*7r7RHIWykG3zklrSl2DxPQ.png) 
#### Step 5: Your logistics teams receive a shipment confirmation
![This is an image](https://miro.medium.com/max/315/1*V1oEQcRAPxcgCPYN5ywZZA.png) 


## Code
This repository code is ready to be deployed on Heroku:
##### 1. Copy Github repository in your local folder and create a local python environment
##### 2. Download libraries listed in requirements.txt
```
  pip3 install -r requirements.txt
```
#### 1. Create your bot with another bot :)
@ BotFather is a Telegram bot that will help you create your own bot \
Search @ BotFather on Telegram and send him ‘/start’ \
Answer ‘/newbot’ message and follow instructions to set up a name and a username \
Your bot is now ready, with an API token created — please keep a copy of this token! 

![This is an image](https://miro.medium.com/max/875/1*FcjfAGjjYuQ_GG8s9dWQQg.png) 

#### 2. Take your token and Telegram API keys
```
TOKEN: shared by @ BotFather when you created your bot
APP_NAME: address of your Heroku application (see steps below)
```

#### 3. Deploy the code on the cloud
Heroku is a cloud-based service where you can host your web application; the free formula of hosting provides enough resources to run your app.
```
Procfile
requirements.txt
```

#### 4. Deployment
Open telegram app and search Trucktrack_12bot
