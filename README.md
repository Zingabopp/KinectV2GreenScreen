# KinectV2GreenScreen
This is a fork of https://github.com/atrujano10/KinectV2GreenScreen/releases (which is a fork of https://github.com/GiantSox/KinectV2GreenScreen/) with added features. This is aimed primarily at users of Mixed reality tools, ala LIV.tv, etc. as used with OBS Studio (Open Broadcaster Software) & VirtualCam, etc.

This tool enables the use of the XBox Kinect V2 (aka Kinect for XBox One) as a "virtual green-screen."

## New features

* Simplified capture with OBS / similar tools
** Automatically "flips" (unflips) the image
** Lacks window borders, removing the need for cropping
* Scalable output
* Calibration mode (disables the greenscreen effect, presenting plain video)

## Usage
* Run the .EXE and capture in OBS using "Game Capture".
* There's a setting to change the resolution in the ATXsKinectV2GreenScreen.exe.config file. If set to 0, Height will be calculated for 16:9 automatically from the Width setting. Note: Changing the resolution will not reduce the processing time needed to turn the background green, it only scales the final output.

### Installation 

* Extract the contents of the ZIP into a directory
* Run the .EXE!

### Keys

* **`C`** - Calibration Mode Toggle - disables/enables the greenscreen effect; this is helpful when setting up camera calibration in LIV / similar tools
* **`S`** - Stats display - Shows how many milliseconds it takes to process a frame and the Kinect's FPS (The Kinect will switch to 15 FPS if it detects inadequate lighting)
* **`Alt-F4`** - Exit the application

## See Also

### Usage with LIV.tv Mixed Reality

See the semi-official LIV.tv "Kinect V2" at https://wiki.liv.tv/index.php/Kinect_v2_Manual_Setup
