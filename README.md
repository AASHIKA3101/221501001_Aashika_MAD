# MAD-Experiments

Welcome to the **Mobile Application Development Experiments Lab!** This repository hosts various mobile application experiments aimed at enhancing user experience, security, and functionality in mobile apps.

## Table of Contents
- [Overview](#overview)
- [Features](#features)
  - [Secure Login System](#secure-login-system)
  - [Dynamic Font Change Functionality](#dynamic-font-change-functionality)
  - [Intuitive Calculator](#intuitive-calculator)
  - [Database Connectivity](#database-connectivity)
  - [Credential Verification System](#credential-verification-system)
  - [Text-to-Speech and Speech-to-Text](#text-to-speech-and-speech-to-text)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Overview
This project contains multiple experiments focused on different aspects of mobile application development. These experiments include implementations of a secure login system, dynamic font change functionality, a user-friendly calculator, and credential verification methods. Each experiment is designed to be modular, allowing you to easily integrate them into your projects.

## Features

### Secure Login System
**Description:**
The login system is designed with security in mind. It includes the following features:
- **Username and Password Validation:** Ensures that users enter valid credentials.
- **Error Handling:** Provides clear feedback for incorrect login attempts.
- **Session Management:** Maintains user sessions securely.

**Usage:**
Users can log in using their username and password. Upon successful login, they are redirected to the main application screen. If the credentials are incorrect, an informative error message will be displayed.

### Dynamic Font Change Functionality
**Description:**
This feature allows users to dynamically change the font style and size in the application.
- **Predefined Font Styles:** Includes a selection of popular and readable fonts.
- **Custom Font Sizes:** Users can adjust the font size to their preferred level of comfort.
- **Real-time Preview:** Users can see the changes immediately, enabling them to find the optimal settings.

**Usage:**
Navigate to the settings menu and choose the "Font Settings" option. From there, select a font style and size that suits your needs and preferences.

### Intuitive Calculator
**Description:**
A simple, yet functional calculator built into the application.
- **Basic Arithmetic Operations:** Supports addition, subtraction, multiplication, and division.
- **User-friendly Interface:** Designed with ease of use and accessibility in mind.

**Usage:**
Access the calculator from the main menu. Enter numbers using the on-screen keypad and select the desired operation to perform calculations.

### Database Connectivity
**Description:**
Establishing a connection to a database is the first step in enabling an application to perform database operations. This involves specifying connection parameters such as the database type, server address, database name, username, and password.

**Usage:**
To establish a connection, follow these steps:
1. **Choose a Database Driver:** Select the appropriate driver for the database system (e.g., MySQL, PostgreSQL, SQLite).
2. **Configure Connection Parameters:** Set up the necessary parameters, including:
   - **Database Type:** Specify the type of database (e.g., MySQL, Oracle).
   - **Server Address:** Provide the hostname or IP address of the database server.
   - **Database Name:** Indicate the specific database to connect to.

### Credential Verification System
**Description:**
Enhances the security of the login system by verifying user credentials.
- **Email Verification:** Sends a verification link to the user's email upon registration, ensuring the authenticity of the provided email address.
- **Two-Factor Authentication (2FA):** Offers an optional feature for additional security, requiring users to provide a one-time code sent to their registered device or email.
- **Password Strength Checker:** Ensures users create strong, secure passwords by enforcing specific requirements such as length, character diversity, and the absence of common passwords.

**Usage:**
Users are required to verify their email address during the registration process. For enhanced security, 2FA can be enabled from the security settings menu.

### Text-to-Speech and Speech-to-Text
Text-to-Speech (TTS) and Speech-to-Text (STT) are essential technologies that enhance user interaction within applications by converting text into spoken words and vice versa. These functionalities can significantly improve accessibility and user experience.

#### Text-to-Speech (TTS)
**Description:**
TTS technology transforms written text into audible speech, enabling applications to read content aloud. This is particularly beneficial for users who prefer auditory information or have reading difficulties.

**Key Features:**
- **Natural Voice Generation:** Modern TTS systems utilize advanced algorithms to produce human-like voices, enhancing the listening experience.
- **Wide Application:** TTS is used in virtual assistants, educational tools, and accessibility applications for visually impaired users.

**Usage in the Application:**
Incorporating TTS allows the application to provide auditory feedback, read notifications, or assist users in navigating through text-heavy content. This can be implemented using various TTS engines, such as Google TTS or Microsoft Azure TTS.

#### Speech-to-Text (STT)
**Description:**
STT technology converts spoken language into written text, facilitating transcription and enabling voice commands within applications. This technology is crucial for creating accessible interfaces and enhancing user interaction.

**Key Features:**
- **Real-time Transcription:** STT systems can transcribe spoken words into text almost instantaneously, which is beneficial for live captioning and note-taking.
- **Language Support:** Many STT systems support multiple languages, making them versatile for global applications.

**Usage in the Application:**
Integrating STT into the application can allow users to dictate messages, control app functions, or transcribe audio recordings. This enhances usability, particularly in scenarios where typing is impractical.

### Implementation Considerations
**Technical Setup:**
To implement TTS and STT in the application, developers should consider the following:
- **Choosing the Right API:** Select a TTS/STT API that fits the application's needs. Popular options include Google Cloud Speech-to-Text, Microsoft Azure Speech, and ElevenLabs for TTS.
- **Handling Errors and Edge Cases:** Implement robust error handling to manage issues like unrecognized speech or API failures.
- **User Experience Design:** Ensure that the integration of TTS and STT is seamless and intuitive for users, providing clear instructions and feedback.

## Installation
To get started with the MAD-Experiments project, follow these steps:

1. **Clone this repository:**
   ```bash
   git clone https://github.com/AASHIKA3101/221501001_Aashika_MAD
   ```

2. **Navigate to the project directory:**
   ```bash
   cd mobile-app-experiments-lab
   ```

3. **Install dependencies:**
   ```bash
   npm install
   ```

4. **Run the application:**
   ```bash
   npm start
   ```

## Usage
Once the application is running, you can explore the different experiments by navigating through the menu. Each feature is designed to be intuitive, with user guides available in the help section of the application.

## Contributing
Contributions are welcome! Please read the `CONTRIBUTING.md` file for more information on how to get involved.

## License
This project is licensed under the MIT License - see the `LICENSE` file for details.

Feel free to modify this template according to your specific project requirements. If you need additional sections or details, let me know!
