# Alexa-Voice-Service

It is implementation of alexa voice service in android app. The app also includes the ability to set an alarm or a timer. 

## Compile and run this application

   1. Follow the process for creating a connected device detailed at this Amazon link  https://developer.amazon.com/appsandservices/solutions/alexa/alexa-voice-service/getting-started-with-the-alexa-voice-service.
   2. Also see this github link for better understanding https://github.com/alexa/alexa-avs-sample-app. Don't forget to enable your
   security profile for Login with Amazon!
   3. Add your api_key.txt file (part of the Amazon process) to the app/src/main/assets folder
   4. Enter the PRODUCT_ID in the MainActivity that you configured for "Application Type Id" above.
   5. Build and run the sample app using Gradle from the command line or Android Studio!
   
   After installing the app in your android mobile. Press the Login button of the first screen it will take you to your web browser
   to login in your account through your security profile and to get access token for communicating with Alexa. After that you will
   be directed to second screen where you can ask your questions to Alexa. Just keep your finger down on the button and ask your 
   question and release it when you are finished. You can set an alarm by asking "Set an alarm" and wait for the response as it is 
   a continuous session. Now don't press the button as Alexa will ask you the time for the alarm. After setting the alarm you can  
   continue as before.
   
   See below screeshots
   
   <p align="center">
<img src="Screenshots/s1.png" height = "480" width="270"> <img src="Screenshots/s3.png" height = "480" width="270"> <img src="Screenshots/s4.png" height = "480" width="270">
</p>

<p align="left">
<img src="Screenshots/s2.png" height = "480" width="270"> <img src="Screenshots/s5.png" height = "480" width="270">
</p>   
   
  You can delete the alarm from the list by long pressing the desired alarm.
   
 
