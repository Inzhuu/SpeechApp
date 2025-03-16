# SpeechApp
SpeechApp is a web-based application designed to convert audio files into text using the AssemblyAI API. The application enables users to register, log in, and submit audio file links for transcription.
 The main features of the application include:

User Registration and Login: Users can create an account and log in securely using their credentials. Registration is straightforward, requiring basic information such as name, email, and password.

Audio Transcription: Once logged in, users can submit a link to an audio file (e.g., MP3 or WAV). The application uses the AssemblyAI API to transcribe the audio into text and displays the transcribed content on the user’s dashboard.

Responsive User Interface: The application features a clean and simple interface built with HTML templates, ensuring that users can easily navigate the transcription process. It includes clear instructions for submitting audio files and viewing transcriptions.

Security Features: The application integrates Spring Security for user authentication and authorization, ensuring that only registered users can access the transcription service.

Spring Boot Architecture: The application follows a modular structure using the Spring Boot framework, including components such as controllers, models, repositories, services, and security configurations. This architecture allows for easy expansion and maintenance.
