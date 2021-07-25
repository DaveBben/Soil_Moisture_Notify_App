# Soil Moisture Notification App
As part of my [Arduino Soil Moisture Transmitter and Receiver project]([https://github.com/DaveBben/Soil_Moisture_Transmitter_Reciver) this is the Android app which listens to the *plants* topic from Google Firebase and triggers an alert when an item on the topic is received.

This is a bare bones simple app with a horrible UI and no other features. It's simply meant to trigger a notification to myself when I receive an event from FCM. I might improve upon it in the future.

### Related Repos
Soil Moisture Sensor Transmitter and Receiver: [https://github.com/DaveBben/Soil_Moisture_Transmitter_Reciver](https://github.com/DaveBben/Soil_Moisture_Transmitter_Reciver)
Google Cloud Function: [https://github.com/DaveBben/fcm_soil_notification_function](https://github.com/DaveBben/fcm_soil_notification_function)