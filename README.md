# pavan ganesh bhagathi-YoYoPizza-ChatBot-YellowMessenger

<h4>PROBLEM STATEMENT</h4>

Build a pizza ordering bot for YoYo Pizza! 
We want you to build a chatbot using any platform/API which can help users with the Pizza Ordering. 
Imagine what the user flow would look like in an actual store; 
All the orders generated on the Bot should get stored in a database (The choice of DB is left to you). 
URL Shortener is an application which will convert long URLs to short URLs. 
There are popular services like bit.ly which does this job. 

Application requirements: 
The bot should support the following use-cases: 
1. Order a pizza 
2. Take user details 
3. Check Pizza Status by Order ID 
4. UI to chat with the chatbot App should be deployed on a server, and should be accessible. 

Please give instructions to use the app. 
Add-on features: 

● NLP 

● Context processing 

Things to be submitted: 
1. Link for the app 
2. Code Repository link 
3. Application Architecture 
4. Product Documentation- Steps to use the app - optional 
5. Developer Documentation(APIs/Modules) - optional

============================================================================

<h1>YoYoPizza</h1>

<h2>About the YoYoPizza ChatBot</h2>
Pizza Ordering ChatBot using Dialogflow and Firebase. Using YoYoPizza ChatBot we can order the pizza.

<h2>Link for the YoYoPizza ChatBot</h2>
https://bot.dialogflow.com/bca4bf91-e57d-4af7-be6d-f0739d77c01d

<H1>ARCHITECTURE</H1>
<img src="https://github.com/pavanganeshbhagathi/YoYoPizza-ChatBot-YellowMessenger/blob/master/Document%20Images/Entity/final/Architecture.png">

<h1>Steps to use YoYoPizza ChatBot</h1>

<h4>STEP 1: Start our bot saying Hi or Helloo..</h4>
<img src="https://github.com/pavanganeshbhagathi/YoYoPizza-ChatBot-YellowMessenger/blob/master/Document%20Images/Entity/chatboxflow/chat1.png" height=210 width=380>

<h4>STEP 2: You can choose the type your favourite Pizza (Veg or Non-Veg)</h4>

<img src="https://github.com/YashasreeTummala/YashasreeTummala-YoYoPizza-ChatBot-YellowMessenger/blob/master/Document%20Images/Entity/chatboxflow/chat2.jpg" height=340 width=380>

<h4>STEP 3: You can pick now based on your favourite Pizza (Paneer Pizza/ Chicken Pizza/ Corn Pizza/ BBQ Chicken Pizza..)</h4>
<img src="https://github.com/pavanganeshbhagathi/YoYoPizza-ChatBot-YellowMessenger/blob/master/Document%20Images/Entity/chatboxflow/chat3.png" height=340 width=380>

<h4>STEP 4: Choose the size based on your hunger (Small, Medium, Large, Extra Large..)</h4>
<img src="https://github.com/pavanganeshbhagathi/YoYoPizza-ChatBot-YellowMessenger/blob/master/Document%20Images/Entity/chatboxflow/chat4.png" height=340 width=380>

<h4>STEP 5: Choose your favourite Toppings (Cheese, Baby Corn, Pepperoni, Mushroom, Tomato... )</h4>
<img src="https://github.com/pavanganeshbhagathi/YoYoPizza-ChatBot-YellowMessenger/blob/master/Document%20Images/Entity/chatboxflow/chat5.png" height=340 width=380>

<h4>STEP 6: Type OK to place your order.</h4>
<img src="https://github.com/pavanganeshbhagathi/YoYoPizza-ChatBot-YellowMessenger/blob/master/Document%20Images/Entity/chatboxflow/chat6.png" height=340 width=380>

<h4>STEP 7: Enter your Contact details for further information (Name) </h4>
<img src="https://github.com/pavanganeshbhagathi/YoYoPizza-ChatBot-YellowMessenger/blob/master/Document%20Images/Entity/chatboxflow/chat7.png" height=340 width=380>

<h4>STEP 8: Enter your valid Contact details for further information (Mobile) </h4>
<img src="https://github.com/pavanganeshbhagathi/YoYoPizza-ChatBot-YellowMessenger/blob/master/Document%20Images/Entity/chatboxflow/chat8.png" height=340 width=380>

<h4>STEP 9: Enter Address details for delivery & also make a note of your Order Number displayed to check the Order Status.</h4>
<img src="https://github.com/pavanganeshbhagathi/YoYoPizza-ChatBot-YellowMessenger/blob/master/Document%20Images/Entity/chatboxflow/chat9.png" height=340 width=380>

<h4>STEP 10: Type "Status or Order Status" to track your order. </h4>
<img src="https://github.com/pavanganeshbhagathi/YoYoPizza-ChatBot-YellowMessenger/blob/master/Document%20Images/Entity/chatboxflow/chat10.png" height=340 width=380>

<h4>STEP 11: Enter the correct Order Number to check the status (if entered wrong, try again).</h4>
<img src="https://github.com/pavanganeshbhagathi/YoYoPizza-ChatBot-YellowMessenger/blob/master/Document%20Images/Entity/chatboxflow/chat11fails.png" height=340 width=380>

<h4>STEP 12: Enter the correct Order Number to check the status.</h4>
<img src="https://github.com/pavanganeshbhagathi/YoYoPizza-ChatBot-YellowMessenger/blob/master/Document%20Images/Entity/chatboxflow/chat12.png" height=340 width=380>


============================================================================

<H1>FIREBASE REALTIME DATABASE</H1>
<h2>
The Firebase Realtime Database is a cloud-hosted database. 
All the orders of YoYo Pizza are sent to Firebase.
Data is stored as JSON and synchronized in realtime to every connected client. 
</h2>
<img src="https://github.com/pavanganeshbhagathi/YoYoPizza-ChatBot-YellowMessenger/blob/master/Document%20Images/Entity/final/firebase.png">



============================================================================

<h1>Documentations<h1>
	
<h2>
how to train agent using dialogflow(google cloud)
</h2>
	
<h3>Firebase</h3>
<p>

Firebase is a Backend-as-a-Service (Baas). It provides developers with a variety of tools and services to help them develop quality apps, grow their user base, and earn profit. It is built on Google’s infrastructure.

Firebase is categorized as a NoSQL database program, which stores data in JSON-like documents.

Firebase Key Features : 
1. Authentication
2. Real Time Database
3. Hosting
4. Test Lab
5. Notifications 
Note : ( In this project we use Firebase only for Real Time Database )

</p>
	
<h3>Dialogflow</h3>

<p>Dialogflow is a natural language understanding platform that makes it easy to design and integrate a conversational user interface into your mobile app, web application, device, bot, interactive voice response system, and so on. Using Dialogflow, you can provide new and engaging ways for users to interact with your product.

Dialogflow can analyze multiple types of input from your customers, including text or audio inputs (like from a phone or voice recording). It can also respond to your customers in a couple of ways, either through text or with synthetic speech.

Please refer this documentation : https://cloud.google.com/dialogflow/docs<p>
	
<h4><strong>Agent</strong></h4>

<p>
	A Dialogflow agent is a virtual agent that handles conversations with your end-users. It is a natural language understanding module that understands the nuances of human language. Dialogflow translates end-user text or audio during a conversation to structured data that your apps and services can understand. You design and build a Dialogflow agent to handle the types of conversations required for your system.

A Dialogflow agent is similar to a human call center agent. You train them both to handle expected conversation scenarios, and your training does not need to be overly explicit.

Please refer this article to understand what is an agent : https://cloud.google.com/dialogflow/es/docs/agents-overview
</p>

<h4><strong>Intent</strong></h4>
<p>
	An intent categorizes an end-user's intention for one conversation turn. For each agent, you define many intents, where your combined intents can handle a complete conversation. When an end-user writes or says something, referred to as an end-user expression, Dialogflow matches the end-user expression to the best intent in your agent. Matching an intent is also known as intent classification.
	
please refer this documentation to understand more about intents : https://cloud.google.com/dialogflow/es/docs/intents-overview
</p>


<h4><strong>Entity</strong></h4>
<p>
Each intent parameter has a type, called the entity type, which dictates exactly how data from an end-user expression is extracted.

Dialogflow provides predefined system entities that can match many common types of data. For example, there are system entities for matching dates, times, colors, email addresses, and so on. You can also create your own custom entities for matching custom data. For example, you could define a vegetable entity that can match the types of vegetables available for purchase with a grocery store agent.


please refer this documentation to understand more about Entities : https://cloud.google.com/dialogflow/es/docs/entities-overview

</p>

<h4><strong>Fulfillment</strong></h4>

<p>
	By default, your agent responds to a matched intent with a static response. If you're using one of the integration options, you can provide a more dynamic response by using fulfillment. When you enable fulfillment for an intent, Dialogflow responds to that intent by calling a service that you define. For example, if an end-user wants to schedule a haircut on Friday, your service can check your database and respond to the end-user with availability information for Friday.

Each intent has a setting to enable fulfillment. If an intent requires some action by your system or a dynamic response, you should enable fulfillment for the intent. If an intent without fulfillment enabled is matched, Dialogflow uses the static response you defined for the intent.

please refer this documentation to understand more about Fulfillment : https://cloud.google.com/dialogflow/es/docs/fulfillment-overview
</p>
	          
	
	

        :Entity

<h4>Entities</h4>
<img src="https://github.com/pavanganeshbhagathi/YoYoPizza-ChatBot-YellowMessenger/blob/master/Document%20Images/Entity/final/ENTITIES.png">
<h4>Description</h4>
<h5>step 1 : </h5> First we must create a list of Entities as show in this picture we have created 4 entities
<h5>step 2 : </h5> Each entity contains a list of responses
<h5>step 3 : </h5> For example , the user enters cheese toppings in chatbot then this cheese keyword will be checked if it contains in our Entity
<h5>step 4 : </h5> if cheese keyword is not present in our entity list then defaultFallback function gets called else we get the response related to this cheese toppings


            :Intents

<h4>yoyo welcome</h4>
<img src="https://github.com/pavanganeshbhagathi/YoYoPizza-ChatBot-YellowMessenger/blob/master/Document%20Images/Entity/final/yoyowelcome.png">
<h4>Description</h4>
<h5>step 1 :</h5> Just like execution starts from main method in java , here the chatbot responses start from here ! 
<h5>step 2 :</h5> This is a 1st training phase i.e., we must train the chatbot with questions and responses
<h5>step 3 :</h5> The input gathered from user will act as response to the next intent ( yoyo-start )


<h4>yoyo start</h4>
<img src="https://github.com/pavanganeshbhagathi/YoYoPizza-ChatBot-YellowMessenger/blob/master/Document%20Images/Entity/final/yoyostart.png">
<h4>Description</h4>
<h5>step 1 :</h5> The input gathered in yoyo-welcome will be input here !
<h5>step 2 :</h5> This is a 2nd training phase i.e., we must train the chatbot with questions and responses ( here in this intent we train the bot to ask a question like if the user wants veg pizza or non veg pizza )
<h5>step 3 :</h5> The input gathered from user will act as response to the next intent ( yoyo-pizzaname )
<h5>step 4 :</h5> The input gathered from user will be checked if the response contains any of options listed in entities ( for eg : @pizzatype contains veg and non veg , the user must select either one of them else defaultFallback will be trigerred )





<h4>yoyo pizzaname</h4>
<img src="https://github.com/pavanganeshbhagathi/YoYoPizza-ChatBot-YellowMessenger/blob/master/Document%20Images/Entity/final/yoyopizzaname.png">
<h4>Description</h4>
<h5>step 1 :</h5> we get response from the input gathered i.e., if the user enters "veg" we get only veg pizzas
<h5>step 2 :</h5> This is a 3rd training phase i.e., we must train chatbot what questions to ask at this stage
<h5>step 3 :</h5> The input gathered from user will be checked if the response contains any of options listed in entities ( for eg : @pizzaname contains different pizzas and the user must select either one of them else defaultFallback will be trigerred )
<h5>step 4 :</h5> The input gathered from user will act as response to the next intent ( yoyo-pizzasize )


<h4>yoyo pizzasize</h4>
<img src="https://github.com/pavanganeshbhagathi/YoYoPizza-ChatBot-YellowMessenger/blob/master/Document%20Images/Entity/final/pizzasize.png">
<h4>Description</h4>
<h5>step 1 :</h5> we have 4 different sizes created in our entity ( pizza-size )
<h5>step 2 :</h5> the chatbot must be trained with these sizes i.e., we are in 4th training phase
<h5>step 3 :</h5> Here we will get the response from the user  will be checked if the response contains any of options listed in entities ( for eg : @pizzasize contains different pizza sizes and the user must select either one of them else defaultFallback will be trigerred )
<h5>step 4 :</h5> The input gathered from user will act as response to the next intent ( yoyo-pizzatopping )




<h4>yoyo pizzatopping</h4>
<img src="https://github.com/pavanganeshbhagathi/YoYoPizza-ChatBot-YellowMessenger/blob/master/Document%20Images/Entity/final/yoyopizzatopping.png">
<h4>Description</h4>
<h5>step 1 :</h5>  we have 5 different toppings created in our entity ( pizza-crust )
<h5>step 2 :</h5> the chatbot must be trained with these toppings i.e., we are in 5th training phase
<h5>step 3 :</h5> Here we will get the response from the user  will be checked if the response contains any of options listed in entities ( for eg : @pizzacrust contains different pizza toppings and the user must select either one of them else defaultFallback will be triggered )
<h5>step 4 :</h5> The input gathered from user will act as response to the next intent ( yoyo-customerdetails )


<h4>yoyo customerdetails</h4>
<img src="https://github.com/pavanganeshbhagathi/YoYoPizza-ChatBot-YellowMessenger/blob/master/Document%20Images/Entity/final/customerdeatils.png">
<h4>Description</h4>
<h5>step 1 :</h5> We must enable web hooks i.e., we get callbacks from index.js
<h5>step 2 :</h5> This is a final training phase i.e., we train the bot with few questions
<h5>step 3 :</h5> Here we question the user with his details like name , mobile number , address and other details ! All these details will be sent to index.js through webhook
<h5>step 4 :</h5> All these details sent to index.js will be sent to database !
       
                        :Default Intents
			
<h4>Default Welcome</h4>

<img src="https://github.com/pavanganeshbhagathi/YoYoPizza-ChatBot-YellowMessenger/blob/master/Document%20Images/Entity/final/defaultwelocme.png">
<h4>Description</h4>
<h5>step 1 :</h5> This is the welcome Intent i.e., here we put the greeting messages like "hello i am pavan from yoyo-pizza how can i help you ?"
<h5>step 2 :</h5> This a default training phase provided by dialogflow i.e., the greeting messages will be trained here !
<h5>step 3 :</h5> Response from user will trigger necessary intent !
<h5>step 4 :</h5> If the response is not appropraite or not trained then it will trigger defaultFallback




<h4>Default fallback</h4>
<img src="https://github.com/pavanganeshbhagathi/YoYoPizza-ChatBot-YellowMessenger/blob/master/Document%20Images/Entity/defaultfallback/defaultfallback.png">
<h4>Description</h4>
<h5>step 1 :</h5> This will be called when the chatbot cant understand user query !
<h5>step 2 :</h5> This will be called from index.js file !


<h3>index.js</h3>
<p>
	
'use strict';
 
<p>const functions = require('firebase-functions');</p>
<p>const admin = require('firebase-admin');</p>
<p>const {WebhookClient} = require('dialogflow-fulfillment');</p>
<p>const {Card, Suggestion} = require('dialogflow-fulfillment');</p>
<p><h5>//yoyo-pizza-hbfk.firebaseio.com --> database url ! we can use "https" for accessing our DB but here we use "ws"</h5> </p>
<p>admin.initializeApp({</p>
<p>	credential: admin.credential.applicationDefault(),</p>
 <p> 	databaseURL: 'ws://yoyo-pizza-hbfk.firebaseio.com/'</p>
<p>});</p>
 
<p>process.env.DEBUG = 'dialogflow:debug';  </p>
<p>exports.dialogflowFirebaseFulfillment = functions.https.onRequest((request, response) => {</p>
<p>  const agent = new WebhookClient({ request, response });</p>
<p>  console.log('Dialogflow Request headers: ' + JSON.stringify(request.headers));</p>
 <p> console.log('Dialogflow Request body: ' + JSON.stringify(request.body));</p>
<p>  //var db = admin.database();</p>
<p> //var ref = db.ref("server/saving-data/fireblog");</p>
  
<p>  function welcomeMsg(agent) {</p>
 <p>   agent.add(`Welcome to Yoyo Pizza!`);</p>
<p>  }</p>
 
  <p><h5>//this method is called when the chatbot doesnt understand our response</h5></p>
  <p>function defaultFallback(agent) {</p>
    <p>agent.add(`Sorry , I didn't understand ðŸ¤·ðŸ¼â€â™‚ï¸`);</p>
    <p>agent.add(`Something wrong with your query , can you please try again? ðŸ¤·ðŸ¼â€â™‚ï¸`);</p>
  <p>}</p>
  
<p> <h5> //details gathered from chatbot will be updated into database</h5></p>
 <p> function checkoutorder(agent){</p>
   <p> const yoyotype = agent.parameters.yoyotype;</p>
   <p> const yoyosize = agent.parameters.yoyosize;</p>
   <p> const yoyotoppings = agent.parameters.yoyotoppings;</p>
   <p> const yoyopizzaname = agent.parameters.yoyopizzaname;</p>
    
   <p> <h5>//generating a random 4 digit number that is used as order id</h5></p>
   <p> const orderid = Math.floor((Math.random() * 9999) + 1000);</p>
   
   <p> const yoyocustomername = agent.parameters.name;</p>
   <p> const yoyocustomerphone = agent.parameters.phoneno;</p>
   <p> const yoyocustomeraddress = agent.parameters.address;</p>
       
  <p>  agent.add(`${yoyocustomername} Here's Your order id ${orderid}. Inorder to check your order ðŸšš please enter "Order Status"`);  </p>
   <p><h5> //updating data into database</h5></p>
   <p> return admin.database().ref('data').set({</p>
   <p>   //the left fields must match database fields !</p>
    <p>  yoyo_type: yoyotype,</p>
    <p>  yoyo_size: yoyosize,</p>
    <p>  yoyo_toppings: yoyotoppings,</p>
     <p> yoyo_pizzaname:yoyopizzaname,</p>
    <p>  orderid: orderid,</p>
     <p> name: yoyocustomername,</p>
     <p> mobilenumber : yoyocustomerphone,</p>
    <p>  address: yoyocustomeraddress</p>
  <p>  });</p>
    
<p>  }</p>
<p> <h5> //using order id we will track the order details from DB in this method !</h5></p>
<p>  function trackorderbyid(agent){</p>
 <p>   //getting order id from chatbot input i.e., input from user</p>
 <p>   const orderid = agent.parameters.orderid;</p>
  <p>  return admin.database().ref('data').once('value').then((snapshot)=>{</p>
   <p>   //getting required or necessary details from database</p>
  <p>  const dbOrderid = snapshot.child('orderid').val();</p>
    <p>const pizza_name = snapshot.child('yoyo_pizzaname').val();</p>
  <p>  const pizza_type = snapshot.child('yoyo_type').val();</p>
  <p>  const customer_name = snapshot.child('name').val();</p>
   <p>   //checking if the order id obtained from user exists in the database , if yes we will print the details else we will print a msg to try again</p>
   <p>   if(dbOrderid==orderid){</p>
    <p>   agent.add(`Here's your Order Details , Your ${pizza_type} ${pizza_name} Pizza is almost ready!! Thank you ${customer_name} for ordering with yoyo pizza! ðŸš›ðŸ•`);</p>
    <p>  }</p>
   <p>   else </p>
   <p>     agent.add(`please check your order id and try again :) !`);</p>
        
  <p>  });</p>
  }</p>
<p><h5>  //mapping fulfillment with intents</h5></p>
 <p> let intent = new Map();</p>
 <p> intent.set('Default Fallback Intent', defaultFallback);</p>
 <p> intent.set('yoyo-customerdetails', checkoutorder);</p>
 <p> intent.set('yoyo-orderstatus', trackorderbyid);</p>
 <p> agent.handleRequest(intent);</p>
<p>});</p>


</p>

<h3>package.json</h3>

<p>{</p>
  <p>"name": "dialogflowFirebaseFulfillment",</p>
 <p> "description": "This is the default fulfillment for a Dialogflow agents using Cloud Functions for Firebase",</p>
 <p> "version": "0.0.1",</p>
 <p> "private": true,</p>
 <p> "license": "Apache Version 2.0",</p>
 <p> "author": "Google Inc.",</p>
 <p> "engines": {</p>
 <p>   "node": "10"</p>
 <p> },</p>
 <p> "scripts": {</p>
  <p>  "start": "firebase serve --only functions:dialogflowFirebaseFulfillment",</p>
  <p>  "deploy": "firebase deploy --only functions:dialogflowFirebaseFulfillment"</p>
 <p> },</p>
  <p>"dependencies": {</p>
  <p>  "actions-on-google": "^2.2.0",</p>
   <p> "firebase-admin": "^5.13.1",</p>
   <p>"firebase-functions": "^2.0.2",</p>
   <p> "dialogflow": "^0.6.0",</p>
   <p> "dialogflow-fulfillment": "^0.5.0"</p>
  <p>  }</p>
 <p> }</p>




<br>



<p><h4>Thanks & Regards</h4></p>
<p>pavan ganesh bhagathi,</p>
<p>mail:pavanbhagathi@gmail.com</p>
<p>+91 9848850889.</p>

