Introduction:

Welcome to the GitHub repository for our immersive VR horror game project, incorporating biofeedback mechanisms to enhance player immersion and engagement. In this repository, you'll find all the necessary files, assets, and instructions to explore our prototype and contribute to its development.

Game Overview:

Our game is designed to provide players with a thrilling and immersive horror experience, leveraging virtual reality (VR) technology and biofeedback integration. Players will navigate through eerie environments, solve challenging puzzles, and evade terrifying adversaries, all while their physiological responses dynamically influence gameplay elements.

Hardware Requirements:

To run the game, you'll need the following hardware:
- Arduino Board (any)
- Arduino Heart Pulse Sensor

Software Requirements:

Ensure you have the following software installed:
- Oculus Quest Link (to connect the headset to the PC)
- Steam and SteamVR (OpenXR from the Oculus Quest also works)
- Unreal Engine 5.3 (Versions 5.1.1 - 5.4 are also compatible)
- Arduino IDE (to upload the heart pulse sensor library)

How to Use the Game:

As this is an early build of the game and cannot be exported, follow these steps to experience the game:
1. Open Oculus Quest Link and ensure your headset is connected.
2. Alternatively, use OpenXR for the Oculus or SteamVR (downloadable through Steam).
3. Open Unreal Engine with your preferred version (5.1.1 upwards).
4. locate BP_SerialCom_v4_UE510 in the assets and change the port based on the port of your Arduino board along with the highestBPM iin the Blueprint.
5. Next to the play button in Unreal Engine, click the three dots and select "VR Preview."
6. If VR Preview is greyed out, close Unreal Engine, SteamVR/OpenXR, and reopen them, ensuring SteamVR/OpenXR is opened first.

Note: Primarily, we use SteamVR, but you can find tutorials on how to use OpenXR if preferred.

Thank you for your interest in our project, and we hope you enjoy exploring our immersive horror experience! Feel free to contribute to the development or provide feedback through this GitHub repository.
