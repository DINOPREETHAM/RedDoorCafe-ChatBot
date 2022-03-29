# RedDoorCafe-ChatBot

# PROBLEM STATEMENT:
Customers have difficulties in getting their doubts cleared from a small scale businesses. So here I have developed a chatbot for Red Door Cafe, A sophisticated coffee shop. "RedDoorCafe-ChatBot" is a chatbot which will reply the queries from the customers to help them get a knowledge of the place.

# DESCRIPTION:
In our project we used many azure services for creating a chatbot for business to customer communication which gives information about the product, the way of business they do, Red Door Cafe give amazing coffee and snacks. Information about those are clarified by this chatbot. This chatbot is built using Azure AI/ML services. QnA Maker is a cloud based Natural Language Processing(NLP) service that allows you to create a natural conversational layer over your data. It is used to find the most appropriate answer for any input from your custom knowledge base (KB) of information. QnA Maker is commonly used to build conversational client applications which include social media applications, which include social media applications, chat bots, and speech-enabled desktop applications. With the help of Azure QnA maker we can prebuilt or upload the questionaries for our chatbot. Here, we've used Azure Bot Service to add chatbot to our google site. Azure Bot Service can be added to websites, apps, email, GroupMe, Facebook Messenger, KiK, Skype, Slack, Microsoft Teams, Telegram, SMS, Twilio, Cortana and Skype for Business. In App Service(Web Apps, API Apps, or Mobile Apps), an app always runs in an App Service plan. Azure Application Insight is use it to monitor your live applications. It will automatically detect performance anomalies, and includes powerful analytics tools to help you diagnose issues and to understand what users actually do with your app. It's designed to help you continuously improve performance and usability. Hence with the help of above technologies we have integrated our chatbot to the google site which we have created

# INTRODUCTION:
RedDoorCafe-ChatBot is simple chatbot answering all your questions related to the place and food. Infact this chatbot also guides you to order some bestselling dishes and food to your liking. Using Azure Cognitive Services provided by Microsoft Azure and website created using google sites, makes this amazing chatbot unique. All you have to do is simple ask our chatbot what you want to know.

# TECHNOLOGIES USED:
* Microsoft Azure In this project I have taken Microsoft Azure as primary technology. Azure is a cloud computing platform and an online portal that allows you to access and manage cloud services and resources provided by Microsoft. These services and resources include storing your data and transforming it, depending on your requirements. To get access to these resources and services, all you need to have is an active internet connection and the ability to connect to the Azure portal. It was launched on February 1, 2010, significantly later than its main competitor, AWS. It’s free to start and follows a pay-per-use model, which means you pay only for the services you opt for. Interestingly, 80 percent of the Fortune 500 companies use Azure services for their cloud computing needs.

In this project, I have tried to use these following Azure Cognitive Services into my project:

1. QnA Maker: QnA Maker is a cloud-based Natural Language Processing (NLP) service that allows you to create a natural conversational layer over your data. It is used to find the most appropriate answer for any input from your custom knowledge base (KB) of information. QnA Maker is commonly used to build conversational client applications, which include social media applications, chat bots, and speech-enabled desktop applications. QnA Maker doesn't store customer data. All customer data (question answers and chat logs) is stored in the region the customer deploys the dependent service instances in.

2. Knowledge Base: QnA Maker imports your content into a knowledge base of question and answer pairs. The import process extracts information about the relationship between the parts of your structured and semi-structured content to imply relationships between the question and answer pairs. You can edit these question and answer pairs or add new pairs.

3. App Service Plan: An App Service plan defines a set of compute resources for a web app to run. These compute resources are analogous to the server farm in conventional web hosting. One or more apps can be configured to run on the same computing resources (or in the same App Service plan).

4. App Service: Quickly build web apps and APIs in the cloud. Azure App Service is an HTTP-based service for hosting web applications, REST APIs, and mobile back ends. You can develop in your favorite language, be it . NET, . NET Core, Java, Ruby, Node.

5. Application Insights: Application Insights is a feature of Azure Monitor that provides extensible application performance management (APM) and monitoring for live web apps. Developers can use Application Insights to: Automatically detect performance anomalies. Help diagnose issues by using powerful analytics tools.

6. Search Service: Azure has a unique service offering aptly named “Azure Search”. This is a search-as-a-service cloud solution that lets you add a rich search service to your apps. The search service abstracts the complexities of document retrieval through both a REST API and a . NET SDK.

7. Web App Bot: The Azure Bot resource provides the infrastructure that allows a bot to access secured resources. It also allows the user to communicate with the bot via several channels such as Web Chat.

* Google Sites Lastly, for creating code free websites on the go, I've used google sites for creating my Red Door Cafe website, in which I have deployed my RedDoorCafe-ChatBot. Google sites is a free website builder from Google. You can create websites with collaborators by giving another Google user edit access. Google Sites are compatible with other Google services like Docs, Sheets, and Slides.

# BACKGROUND WORKING OF AZURE COGNITIVE SERVICES:
![159109741-de750081-c59c-4b93-bfda-357e6e6ef282](https://user-images.githubusercontent.com/102014196/160556687-64078b1d-0f85-41d5-80c0-a3d5851dd0e4.jpg)

Here, in the above diagram, explains how cognitive services work in background.

With the help of Azure QnA maker we have created an knowledge base, then this knowledge base is connected to our azure chatbot and this chat bot is then embedded to our google site RedDoorCafe --> Client Device sends input to the Bot --> Azure language understanding understands the client queries and automatically chooses an knowledge base and hence finds the similar answer and sends the output.

# SCREENSHOTS:
Step 1 : Create services for the chatbot in azure
![rd1](https://user-images.githubusercontent.com/102014196/160557230-0f45fab7-2e3a-47a0-b691-facd2c1e7eb3.png)

Step 2 : Create a knowledge base in QnA Maker
![rd2](https://user-images.githubusercontent.com/102014196/160558182-dc7c9e95-b1ea-4064-bbea-c41889a0468d.png)

Step 3 : Create Web App Bot:
![rddd](https://user-images.githubusercontent.com/102014196/160559499-0f55ae10-2617-4a03-bd28-6b27d01e3935.png)

Step 4 : Create site in Google sites and publish it
![rdd](https://user-images.githubusercontent.com/102014196/160558793-afca3274-cc80-4a25-9435-98e28ffe297a.png)

# PROJECT URL:
https://sites.google.com/view/redoorcafe/home





