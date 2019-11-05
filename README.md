# Security_HW3_Part2

## Purpose
In this assignmnt, we were tasked with creating an Android app to allow phone calls and texting. This was especially challenging because we did this as a first introduction to Android! 

## Phone Call Application
My APK for the first question is called Question1.apk. It is a simple phone call application, which asks the user for a phone number and calls that number if the user has granted the application permission via the CALL_PHONE functionality. If the user does not enter a phone number, the application will ask for one.

## Texting Application
My APK for the second question is called Question2.apk. In this application, I built upon Question1.apk by adding a button that allows the user to travel to a new page for texting. By clicking "TEXT" the user is presented with a new screen where they must fill out the phone number they wish to text as well as the message they wish to send. The application will prompt the user for content if either of these fields are empty. The application only sends a text if the SMS_SEND permission is granted by the user. I could not figure out how to show the message that was sent, but the application does succesfully send an SMS and alerts the user that it is sent.
