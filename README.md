# Hand Gesture Interface

Using machine learning to power intuitive human computer interfaces.

## Getting Started

Hand Gesture Interface requires Python 3 to be installed and a working webcam. Currently, only MacOS is supported but support for Windows and Linux is coming soon.

After downloading, simply double click the ```run``` script. It will automatically set up the appropriate Python environment and install the correct pip packages. Note that everything is done in a Python virtual environment in the same directory as the ```run``` file so you don't need to worry about package conflicts.

(Note that you may have to right click on ```run``` and click open instead of just double clicking as MacOS may say that it's from an unidentified developer)
(Also, be sure to allow Terminal.app or whatever terminal you're using to access the camera in System Preferences)

If you wish to uninstall, simply delete the folder that the ```run``` script is in. There's no need to delete any other packages.

## How To Use
Once the run script displays "Started inference loop", you can begin using hand gestures.

### Supported Gestures
So far, only 12 gestures are supported.

Four of these are swiping with your whole hand left or right (for switching desktops) and up or down.
You may also swipe up/down/left/right with two or one finger for scrolling.

Zooming in and our with full hand will initiate a zoom in/zoom out on the application you're currently running.

Pushing hand in or away will either reveal desktop or show your installed apps.

## Contributing

Contributions are welcome! Feel free to fork/pull request any changes.
