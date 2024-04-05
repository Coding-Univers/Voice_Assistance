# Voice Assistance
This Python script implements a voice-controlled assistant that utilizes speech recognition to understand user commands and text-to-speech synthesis to respond. It can greet the user, provide the current time, open Chrome or YouTube, express gratitude, and gracefully exit upon command.

Key Features:-

1.Voice Recognition and Speech Synthesis: The code utilizes the speech_recognition library for recognizing speech input from the user through a microphone and the pyttsx3 library for converting text to speech.

2.Greetings Based on Time: The assistant greets the user based on the current time of the day (morning, afternoon, or evening).

3.Listening for User Queries: The assistant continuously listens for user queries after initial greetings.

4.Handling User Queries: It handles various user queries such as greeting, asking for the current time, opening Chrome browser, opening YouTube, expressing gratitude, and exiting the program.

5.Response Generation: It generates appropriate responses based on the user's input and executes corresponding actions like opening applications or playing a YouTube video.

6.Continuous Execution: The assistant runs in a continuous loop, listening for user input until the user decides to exit the program.

7.Error Handling: The code includes basic error handling to catch exceptions during speech recognition.

8.Modularization: The code is modularized into functions for better organization and readability.
