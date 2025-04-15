# AR Business Card - Unity with Vuforia

## Overview
This project is an interactive Augmented Reality (AR) business card built with Unity and the Vuforia Engine. When users scan your physical business card with their smartphone, it displays your digital profile including your name and social media links in an engaging AR experience.

## Features
- **Marker-based AR recognition**: Uses Vuforia to detect your physical business card
- **Interactive digital profile**: Displays your information in 3D/AR space
- **Social media integration**: Quick links to your professional and coding profiles
- **Cross-platform**: Works on both iOS and Android devices

## Included Social Links
- LinkedIn
- Instagram
- LeetCode
- Discord
- GitHub

## Requirements
- Unity 2021.3 or later
- Vuforia Engine (installed via Unity Package Manager)
- Android/iOS device with AR capabilities

## Setup Instructions
1. Clone this repository
2. Open the project in Unity
3. Import Vuforia Engine via Package Manager if not already present
4. Replace the Vuforia target image with your own business card design
5. Update the social media links and personal information in the Unity scene
6. Build for your target platform (iOS/Android)

## How to Use
1. Print your business card (the one registered with Vuforia)
2. Install the app on your mobile device
3. Open the app and point your camera at the business card
4. View your digital profile appearing in AR space
5. Tap on social media icons to visit your profiles

## Customization
To personalize this project:
1. Replace `Assets/Images/TargetImage.jpg` with your business card design
2. Update personal info in `Assets/Scripts/ProfileController.cs`
3. Modify the 3D design in the Unity scene
4. Add/remove social media buttons as needed

## License
This project is open-source under the MIT License. Feel free to modify and use it for your personal or professional needs.

## Contact
For questions or support, please open an issue in this repository.

---

**Note**: Remember to register your business card image as a Vuforia target and download the database before building the application.
