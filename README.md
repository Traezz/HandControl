# HandControl
A program to enable a user to control their media player with hand gestures

Instructions:
Use a blue glove, or modify the color settings on lines  17 and 18.
Point webcam at a blank wall or ceiling, preferably white.
Results may vary depending on lighting conditions, Camera, etc.
If far from Camera: Insert fingers in to the Region of Interest (ROI).
If close to Camera: Insert hand into ROI.
There may be minor lag when the hand enters the ROI.

Fist or 1 finger: Spacebar (Pause, unpause on Youtube).
2 fingers: Volume up on Windows. Insert fingers into ROI simultaneously. Do not stagger.
3 fingers: Volume down on Windows. Insert fingers into ROI simultaneously. Do not stagger.
4 fingers: Volume mute on Windows. Unmute with volume up or down. Insert fingers into ROI simultaneously. Do not stagger

Press Q while Python window is in foreground to stop the program.
Note: [Warn:0] is thrown on termination. It seems this particular warning is due to Environment Variables in Windows.

'''
