# TrackingBot Android App

The MySampleApp folder contains a sample Android App originally generated using MobileHub.

The example Android application has two main areas of user interaction: 
Dashboard and Record.

## Dashboard

The Dashboard displays results for each category defined in the model. It breaks
the results up into daily, weekly, and monthly pages. It is different in this
regard from the dashboard-app component. The dashboard-app provides a radial pie chart with three arcs. In
contrast the Android sample provides a radial pie chart with one arc and buttons to navigate between
daily, past 7 days (weekly), and past 30 days (monthly) views. 

## Record

The Record fragment (YourHistory.java) allows the user to input new information via voice input. Just click
on the record button and tell the App what you've accomplished. 

## Development approach

The Android app was initially generated using MobileHub and then heavily customized to implement
the two features above. You will see the framework to construct the demo application largely intact from
that generated by MobileHub. 

The Android app uses the same cognito user pool created by the LexAppBuilder. It operates in unauthenticated mode to 
gain access using AWS credentials to Lex/Polly and DynamoDB.

 
 