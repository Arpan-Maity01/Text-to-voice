# Text-to-voice
The given code uses the Google Speech Recognition API and PyTTSX3, a text-to-speech conversion library, to create a simple voice-activated personal assistant. It follows a while loop that listens for user input using a microphone and processes the speech recognition.

First, the code imports the necessary libraries, speech_recognition for speech recognition, and pyttsx3 for text-to-speech conversion. Then, it initializes the recognizer using sr.Recognizer().

The SpeakText function takes a command as input, initializes the text-to-speech engine using pyttsx3.init(), and uses the engine to convert the command into speech.

Inside the while loop, the code listens for the user's input using the microphone as the source for input. The adjust_for_ambient_noise function adjusts the energy threshold based on the surrounding noise level. Then, the code listens for the user's input using the listen function.

After listening for the user's input, the code recognizes the speech using the Google Speech Recognition API and converts it into text using the recognize_google function. The recognized text is then converted to lowercase using the lower function and printed out.

Finally, the code uses the SpeakText function to convert the recognized text into speech and speaks it out loud. The while loop keeps running indefinitely, allowing the user to continuously interact with the voice-activated personal assistant.



