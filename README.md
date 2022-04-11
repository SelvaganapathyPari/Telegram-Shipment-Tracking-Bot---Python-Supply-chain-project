## Real-Time Shipment Tracking Tool using  Telegram Bot
In this Python project we are designing a Telegram Bot that will interact with truck drivers and help supply chain professionals to track your shipments easily.

## Solving a problem which i have faced many times
As a supply chain professional you have to track lot metrics including critical items for production, placing new orders, managing past dues, rescheduling part numbers which are not currently required and more. Mostly important you should also track the incoming shipments from supplier and many times the scheduled items/ shipments needed much more attention as these items could be scheduled for next day production and it is very critical to track them in regular intervals.

As a supply chain professionals i have worked with both national and international suppliers, and tracking the critical shipments is one of the biggest challenges.

### Let me tell you about a real situation I encountered while working at EATON: 
There was one item (SKU) that was critical for the next day's production, and all resources were planned around it.
And it's my job to keep a watchful eye on it and make sure it arrives on time nd move to the production.
My manager also demanded that I track the shipment every two hours to ensure that it arrives without mishap. 

so i need to constantly connect with truck driver and get shipment details on regular basis. but in reality it might not be as easy or practical thing to do, because though the arrival material is critical for us(company), we shouldn't force our thougts on others( truck drivers or any carriers), as it might impact their productivity. this is where the telegram bot could help supply chain professionals. 

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

![telegram bot](https://user-images.githubusercontent.com/102349366/162716364-23d46905-b544-41dd-b9bb-2430ec96b60d.gif)

## Code
This project code is deployed on Heroku:
##### Copy Github repository in your local folder and create a local python environment
```
  pip3 install -r requirements.txt
```
#### 1. Create your bot with another bot :)
@ BotFather is a Telegram bot that will help you create your own bot \
Search @ BotFather on Telegram and send him ‘/start’ \
Answer ‘/newbot’ message and follow instructions to set up a name and a username \
Your bot is now ready, with an API token created — please keep a copy of this token! 

#### 2. Token and Telegram API keys
```
TOKEN: shared by @ BotFather when you created your bot
APP_NAME: Trucktrack_12bot
```

#### 4. Deployment
Open telegram app and search Trucktrack_12bot

#####= Credits to samirsaci for  inspiration
