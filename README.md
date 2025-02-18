# Suraksha-Dial : Emergency Call App

Suraksha-Dial is an Android app that continuously listens for the keyword *"HELP"* using built-in speech recognition. When the keyword is detected, the app automatically dials a predefined emergency number. This project is *open-source*, does not rely on external APIs, and works online.

# Features
✅ Continuous voice recognition in the background  
✅ Calls a custom emergency contact when "HELP" is detected  
✅ Simple UI to set a personal emergency number  
✅ Works *online* using Android's built-in SpeechRecognizer  
✅ Runs as a *foreground service* for persistent listening  

# Usage Instructions
Launch the App
Set an Emergency Number in the UI
Tap "Start Voice Recognition"
Say "HELP" aloud → The app will automatically call the saved number

# Permissions Required
Microphone Access → To detect the word "HELP"
Call Phone → To dial the emergency number
Foreground Service → To keep the app running in the background

# Technologies Used
Java for Android development
Android SpeechRecognizer (Built-in)
SharedPreferences for storing emergency numbers


