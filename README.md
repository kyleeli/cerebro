# Cerebro

# Table of contents

At the end of this lab you will be able to create a Slack Chatbot service which makes use of [Watson Conversation Services (WCS)](https://www.ibm.com/watson/services/conversation/) to direct user interaction.  In addition, you'll be able to add configurable services for connecting to Twillio for text/sms capabilities, and also the ability to connect to IBM's Event Central tool for enrolling in events.

* [Pre-Requisites]()
* [Creating a Slack Bot]()
* [Download and install Botkit middleware]()
* [Create a Watson Conversation Services workspace]()
* [Connect Slack to WCS]()
* [Create text capabilities]()
* [Create Event Central capabilities]()
* [Deploy to Bluemix]()

# Pre-Requisites
Here's what you need for starting this project:

````
- Bluemix Account
- Slack account
- Watson Conversation Services added to Bluemix
- (optional) Twillio Account
- (optional) Event Central event ID
````

**NOTE: The Botkit middleware package will be installed as part of the lab and is not considered a prequisite**

# Creating a Slack Bot
We will use Slack as our user interface for the chatbot, which means we won't have to build out a web interface for our chatbot to use to interact with users.  Follow these steps to create a slack bot:

1.
2.
3.


# Download and install Botkit middleware
The Botkit middleware is required in order to connect Slack to the WCS service.


# Create a Watson Conversation Services workspace
For interacting with your users, a WCS workspace will be needed.  We don’t need to create anything fancy, just something that allows us to demonstrate how to connect Slack to WCS and get the appropriate response.  For ease of this lab, we are including a pre-built workspace which you can download directly from this repo and import into your own WCS service.

To add the pre-built workspace to your bluemix account’s WCS:

1.
2.
3.

# Connect Slack to WCS
Now it’s time to start building the code that will connect Slack to WCS.  This is done by  making use of the Botkit we installed earlier.

There are sample files you can use to work from, and this is how you get started:  

1. In the code for your application, add the following:

````
code goes here
````

# Create text capabilities
Next we want to connect our Slack bot to Twillio so that we can receive SMS alerts from our bot!





# Create Event Central capabilities
In this section you will learn how to connect your bot to the Event Central web api so that you can retrieve content to display to your user.

1.
2.
3.



# Deploy to Bluemix
Now it’s time to package everything up and send it to bluemix so we can use it!

1.
2.
3.




