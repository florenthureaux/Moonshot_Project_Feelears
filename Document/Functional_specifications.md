<h1 style="text-align: center">Feelears - Functional Specification</h1>

<details>

<summary style="text-decoration: underline; font-size:150%">Table of contents:</summary>

- [1. Project Overview](#1-project-overview)
  - [1.1. Context](#11-context)
- [2. Hardware: Smart Eyewear](#2-hardware-smart-eyewear)
  - [2.1. Design and Sensors](#21-design-and-sensors)
  - [2.2. Data Processing](#22-data-processing)
  - [2.3. Communication](#23-communication)
- [3. Key Features](#3-key-features)
  - [3.1 Emotion-Based Sound Selection](#31-emotion-based-sound-selection)
  - [3.2 Real-time Emotional Sound Adjustment](#32-real-time-emotional-sound-adjustment)
  - [3.3 Surrounding Noise Adaptation](#33-surrounding-noise-adaptation)
  - [3.4 User Profiles and Preferences](#34-user-profiles-and-preferences)
  - [3.5 Notification and Alerts](#35-notification-and-alerts)
- [4. User Interface (UI) and User Experience (UX)](#4-user-interface-ui-and-user-experience-ux)
- [5. Technology Stack](#5-technology-stack)
  - [5.1 Mobile Application](#51-mobile-application)
  - [5.2 Hardware Integration](#52-hardware-integration)
  - [5.3 Emotion Analysis](#53-emotion-analysis)
- [6. Security and Privacy](#6-security-and-privacy)
- [7. Testing](#7-testing)
- [8. Deployment](#8-deployment)
- [9. Maintenance and Updates](#9-maintenance-and-updates)
- [10. Conclusion](#10-conclusion)
- [11. Glossary](#11-glossary)

</details>

## 1. Project Overview

The purpose of this functional specification is to outline the requirements and functionalities of a mobile application linked to a device that can play and adjust sounds based on the user's emotional state and the surrounding noise level. The application aims to provide an immersive and tailored sound experience, enhancing the user's emotional well-being and environment adaptability.

### 1.1. Context

The mobile application will be designed to interact with a compatible hardware device capable of monitoring the user's emotional state through biometric[^1] sensors[^2] (e.g., heart rate, facial expressions, etc.) and capturing surrounding noise levels through built-in microphones.

## 2. Hardware: Smart Eyewear

### 2.1. Design and Sensors

The smart eyewear[^3] will have a sleek and stylish design with embedded sensors for monitoring the user's emotional state and physiological signals.
Sensors may include a front-facing camera for facial expression analysis and a microphone for surrounding noise level detection.

### 2.2. Data Processing

The smart eyewear will have onboard processing capabilities to perform real-time analysis of collected data and send it to the mobile application.
The data processing unit will analyze facial expressions and other physiological signals to infer the user's emotional state.

### 2.3. Communication

The smart eyewear will communicate with the mobile application through a wireless connection (e.g., Bluetooth[^4]) to transmit emotional state data and receive sound selections and adjustments.

## 3. Key Features

### 3.1 Emotion-Based Sound Selection

The mobile app will analyze the user's emotional state using data from the connected hardware device.
Based on the user's emotional state, the application will select appropriate sounds from a predefined library categorized by emotions (e.g., calm, happy, sad).
Users can also manually select a sound of their choice from the library.

### 3.2 Real-time Emotional Sound Adjustment

The application will continually adjust the volume and characteristics of the selected sound based on the detected emotional changes.
For example, if the user becomes more stressed, the application will increase the sound volume and select sounds associated with relaxation or calmness.

### 3.3 Surrounding Noise Adaptation

The app will use the device's microphones to measure the noise level in the user's environment.
It will automatically adjust the sound volume based on the detected surrounding noise, ensuring the user's experience is not disrupted by external sounds.

### 3.4 User Profiles and Preferences

Users can create personalized profiles to store their sound preferences and emotional states history.
The application will learn from the user's behavior to provide more accurate and tailored sound selections over time.

### 3.5 Notification and Alerts

The app will allow users to set up notifications or alerts to prompt them to use the application during specific times or based on certain emotional triggers.

## 4. User Interface (UI) and User Experience (UX)

a. The UI will be intuitive and user-friendly, with a focus on simplicity and ease of use.
b. Visual elements will be designed to reflect the user's emotional state, creating a seamless and immersive experience.
c. Clear indicators will display the connected device status, the detected emotional state, and surrounding noise level.

## 5. Technology Stack

### 5.1 Mobile Application

The mobile application will be developed for both iOS and Android platforms

### 5.2 Hardware Integration

The application will integrate with the compatible device through Bluetooth or other appropriate communication protocols.

### 5.3 Emotion Analysis

The application will leverage machine learning[^5] or AI algorithms to analyze biometric sensor data and determine the user's emotional state.

## 6. Security and Privacy

User data, including emotional state analysis, will be stored and transmitted securely following industry-standard encryption protocols.
The application will request explicit user consent to access and use biometric sensor data, and users will have the option to opt-out at any time.
It will provide users with clear information about the limitations and potential risks of the application and encourage users to seek professional advice if they have concerns about their emotional well-being.

## 7. Testing

The application will undergo rigorous testing to ensure its stability, performance, and compatibility across various mobile devices and operating system versions.
User testing and feedback collection will be conducted to improve the application's user experience and functionalities.

## 8. Deployment

The application will be published on the respective app stores (Apple App Store and Google Play Store) following their submission guidelines and approval processes.

## 9. Maintenance and Updates

Regular maintenance and updates will be performed to address bugs, improve performance, and introduce new features based on user feedback and technological advancements.

## 10. Conclusion

The emotion-based sound manipulating mobile application aims to provide users with a personalized and dynamic audio experience based on their emotional state and surrounding noise level. Through seamless integration with compatible hardware and intelligent analysis of biometric data, the application seeks to enhance users' emotional well-being and environmental adaptability.

## 11. Glossary

[^1]: Biometric : Relating to or involving the application of statistical analysis to biological data.

[^2]: Sensors : a device which detects or measures a physical property and records, indicates, or otherwise responds to it.

[^3]: Smart Eyewear : Smartglasses or smart glasses are eye or head-worn wearable computers that offer useful capabilities to the user

[^4]: Bluetooth : a standard for the short-range wireless interconnection of mobile phones, computers, and other electronic devices.

[^5]: Machine Learning : the use and development of computer systems that are able to learn and adapt without following explicit instructions, by using algorithms and statistical models to analyse and draw inferences from patterns in data.
