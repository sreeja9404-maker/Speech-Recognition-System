# Speech-Recognition-System

*COMPANY*: CODTECH IT SOLUTIONS
*NAME*: SREEJA R
*INTERN ID*: CT06DR3163
*DOMAIN*: ARTIFICIAL INTELLIGENCE
*DURATION*: 6 WEEKS
*MENTOR*: NEELA SANTHOSH

**DESCRIPTION OF THE PROJECT**:

This project implements a simple *speech recognition system* using Python, which converts spoken words into written text. The main goal of the project is to allow a computer to listen to human speech through a microphone and accurately recognize what is being said. This type of system is widely used in real-world applications such as voice assistants, speech-to-text tools, customer support automation, accessibility tools for people with disabilities, and smart devices. The project is built using the *SpeechRecognition* library, which is a popular Python library for performing automatic speech recognition tasks. It provides an easy-to-use interface for capturing audio input and sending it to different speech recognition engines. In this project, the *Google Web Speech API* is used as the backend service to recognize speech because it is reliable and supports multiple languages with good accuracy. To capture live audio input, the project uses *PyAudio*, which is a Python library that allows access to the system’s microphone. PyAudio acts as a bridge between the microphone hardware and the Python program, enabling real-time audio recording. The program begins by installing the required libraries, namely SpeechRecognition and PyAudio. Once installed, a recognizer object is created using the SpeechRecognition library. This recognizer object is responsible for processing the audio and converting it into text. The system then accesses the default microphone using the Microphone class and prompts the user to speak. Before listening to the speech, the program adjusts for ambient noise for a short duration. This step is very important because it helps the system reduce background noise and improve recognition accuracy, especially in noisy environments. After adjusting for noise, the system listens to the user’s speech and captures the audio data. The captured audio is then processed and sent to the Google Web Speech API through an internet connection. The API analyzes the audio signal, identifies spoken words, and converts them into text. The recognized text is then displayed on the screen. The project also includes proper exception handling to manage possible errors. If the speech is unclear or cannot be understood, the program displays a message indicating that the audio could not be recognized. If there is a problem with the internet connection or the API request, an appropriate error message is shown. This makes the system more user-friendly and robust. Overall, this project demonstrates the basic working of a speech recognition system using Python. It highlights important technologies such as Python programming, SpeechRecognition library, PyAudio for audio input, and cloud-based speech processing using the Google Web Speech API. The project is simple, easy to understand, and serves as a strong foundation for building more advanced voice-based applications in the future.

**OUTPUT**:

<img width="384" height="55" alt="Image" src="https://github.com/user-attachments/assets/4a9ef02f-a7bb-477d-9fb0-d05ce94de823" />

<img width="311" height="44" alt="Image" src="https://github.com/user-attachments/assets/b0601315-41dc-4f6a-a9a7-e40c909c009b" />

                        
