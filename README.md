# Wireless Sound Control using OpenCV: Hand Gesture Recognition and Volume Control

This project uses OpenCV and hand gesture recognition to create a wireless sound control system. The program captures video input to detect hand gestures, utilizing techniques like background subtraction and skin color segmentation to isolate the hand. MediaPipe assists in tracking hand landmarks, such as fingertips, enabling specific gestures for controlling volume. For example, the distance between the thumb and index finger can adjust volume levels, while closing fingers completely mutes the sound.

For wireless communication, the program can connect to the sound source via Bluetooth or network. A Bluetooth module can send commands to a Bluetooth speaker, or a network connection can allow remote volume adjustments on devices within the same network. This provides a hands-free and intuitive way to control audio levels from a distance.


**Hand Gesture Recognition:** You'll use OpenCV for video capture and hand detection. Techniques like background subtraction and skin color segmentation can help isolate the hand in the frame. Then, libraries like MediaPipe can be leveraged to track specific hand landmarks (fingertips).

**Gesture-to-Volume Mapping:** Based on the positions of identified landmarks (e.g., distance between thumb and index finger), you can define gestures for volume control. Closing the fingers completely might signify mute, while increasing the distance could correspond to volume increase.

**Wireless Communication** (Optional): To make it truly wireless, you'll need to establish communication between your program and the sound source (speaker/PC). This could involve:

Bluetooth: By connecting a Bluetooth module to your device running OpenCV, you can send volume control commands to a Bluetooth speaker.

Network: Setting up a network connection allows your program to communicate with the sound source on the same network and adjust volume remotely.

# REQUIREMENTS
opencv-python
mediapipe
comtypes
numpy
pycaw


![image](https://github.com/KaziAfrozAlam/Wireless_Sound_Control_using_OpenCV_main/assets/80971832/421034bc-3314-4c3a-adcd-fe14874440e4)



![image](https://github.com/KaziAfrozAlam/Wireless_Sound_Control_using_OpenCV_main/assets/80971832/5fc1f9db-e4d3-4d27-b836-30d062a08f92)

