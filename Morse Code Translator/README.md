# Morse Code Translator 🔤➡️📻

A desktop application built in **Java** that translates text into **Morse code**, displays the translated output in real-time, and optionally plays the Morse code as **audible tones**.

📁 Summary of Each File

App.java:
Launches the GUI on the Event Dispatch Thread (EDT) for thread-safe UI creation.

MorseCodeController.java:
Contains the translation logic.
Handles Morse code sound playback using tone generation.

MorseCodeTranslatorGUI.java:
Builds the interface for text input and Morse code output.
Integrates the controller for live translation and sound playback.
