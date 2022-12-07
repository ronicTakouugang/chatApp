This is a [React.js](https://Reacts.org/) project bootstrapped with [`create-react-app`](

## Getting Started
Using your terminal and the command cd, enter the project's root which in this case is "chatApp"

  - Use the command npm install --legacy-peer-deps to install all the dependencies necessary for this eCommerceProject

## Creating Stream Account
This projects includes stream(https://www.getStream.io/).

  - Sign up into stream and open the dashboard, replace the following values:
  
  -> STREAM_APP_ID = '' (App ID)
  -> STREAM_API_KEY = '' (Key)
  ->STREAM_API_SECRET = '' (Secret)
  
##Creating Twilio account
This projects includes stream(https://www.twilio.com/).

Create a Twilio account, open the Messaging tab and then Send an SMS, the procedure here is to obtain our keys. Click on the sub menu tab Node js where we will find our keys

-> TWILIO_ACCOUNT_SID = '' (accountSid)
-> TWILIO_AUTH_TOKEN = '' (authToken)
->TWILIO_MESSAGING_SERVICE_SID = '' ( messagingServiceSid)

cd into the Client folder then -> npm start
cd into the Server folder then -> npm run dev


Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.
Open [http://localhost:5000](http://localhost:5000) with your browser to see the result on the Server side.


You can start editing the page by modifying `pages/index.js`. The page auto-updates as you edit the file.


