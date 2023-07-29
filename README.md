# HandGuestureControl-Project
 This code uses the MediaPipe library to detect hands in a video feed and control a media player. The code works by first initializing the MediaPipe library and the pyautogui library. Then, the code starts a video feed and begins detecting hands. The code then counts the number of fingers that are up and uses this information to control the media player.  For example, if the user holds up one finger, the code will play the next song in the playlist. If the user holds up two fingers, the code will rewind the current song. The code also uses the pyautogui library to control the mouse and keyboard. This allows the code to send keyboard presses to the media player, such as the spacebar to play/pause the music.  The code is a simple example of how you can use MediaPipe to detect hands and control a media player. You can modify the code to add more gestures or to control other applications.  Here are some of the key features of the code:  It uses the MediaPipe library to detect hands in a video feed. It counts the number of fingers that are up. It uses the number of fingers to control a media player. It can be modified to add more gestures or to control other applications.

# Do these steps to run properly...
Step 1: install python moduls (libraries).
	cv2
	import cv2
	mediapipe
	pyautogui
	time 
Step 2: before runing this project run any Video file in VLC or any recomended software.
Step 3: Run project and control media player using hand gestures.