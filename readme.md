Complex-Animal-Movement-Capture-and-Live-Transmission-CAMCALT-

The main python file is "errorda.py" which branches into and calls other python files and the whole program files are packaged into a clickable shell file named "Camcal1t.sh"

Please feel free to contact me through linkedin if you have any doubts regarding the project: https://linkedin.com/in/shreyas-ramachandran-srinivasan-565638117/

To see photos and videos from presentation/demo, visit: https://ssr1996.wixsite.com/shreyas-ssr/projects-patents

User manual for said CAMCALT device: https://www.slideshare.net/slideshow/embed_code/key/t1MtqZh74rUYSy

INTRODUCTION

Our project Complex Animal Movement Capture And Live Transmission (CAMCALT) is a device specifically tailored to the need of a forest surveillance and monitoring system. The objective of the project is to eradicate the existing disadvantages of the Forest Trap Camera’s and integrate the latest technologically developed “Internet of Things” (IoT) into the device for Live feed wirelessly from any part of the world. The user-friendly UI is via an application that runs on a Raspberry Pi 3 Model B microcomputer. It is used to monitor the forests, animal movements and Poacher Detection. By this, 24 hours surveillance has been made possible that hunting and poaching can be prevented. Prevention of poaching of any animal by illegal poachers cabe done in forest areas. Forests can be more secure like a military restricted area. CAMCALT is an intelligent over watch for the forest landscape. In large numbers, you can have the whole forest under your control. 

LITERATURE REVIEW

In the existing trap camera system, the forest ranger
usually manually retrieves memory cards in the trap cameras
each 30 days and replaces them with new memory cards.
Then, the photographs stored in old memory card are
reviewed. By then, if any crime, poaching has occurred, forest
officers are not in a position to do anything about this
situation. But in our proposed concept, we are integrating the
latest technologically developed “Internet of Things” (IoT)
into the device for Live video feed which is done wirelessly
from any part of the world. This makes our proposed system
much better than the disadvantageous trap camera system. the
cost down for the home automation system. The global trap
cameras market is valued at 64 million US$ in 2017 and will
reach 77 million US$ by the end of 2025, growing at a CAGR
of 2.7% during 2018-2025.
Years considered for this report Base year: 2017
Estimated year: 2018 Forecast period: 2018–2025.

 COMPONENTS EXPLANATION
 
CAMCALT is abbreviated as Complex Animal
Movement Capture and Live Transmission. As the
abbreviated tag elucidates us clearly that it helps in capturing
the complex animal movement under intense period of time
providing a live feed of the situation. The prototype consists
of the following components to carry out the operation:

A. Central Microcontroller – Raspberry Pi 3 Model B
The prototype is designed with a Central Microcontroller
– Raspberry Pi 3 Model B which has a Broadcom BCM2837
64bit ARMv7 Quad Core Processor powered Single Board
Computer running at 1.2GHz, 1 GB RAM, BCM43143 Wi-Fi
on board, Bluetooth Low Energy (BLE) on board, 40pin
extended GPIO, 4 x USB 2 ports, 4 pole Stereo output and
Composite video port, Full size HDMI, CSI camera port for
connecting the Raspberry Pi camera, DSI display port for
connecting the Raspberry Pi touch screen display, Micro SD
port for loading your operating system and storing data. The
controller is interfaced with a Passive Infra-red sensor, Global
Positioning Sensor, Raspberry Pi Camera.

B. Pi Camera Module
PI camera module captures 2592 * 1944 pixel static
images and also supports 1080p at 30fps @ 60fps and 540 *
480p 60/90 video recording. Camera module is interfaced
with the central microcontroller Raspberry Pi 3.

C. GPS Module
This module named Neo 6M-0-00-1 U-Blox operating at
5V DC. Global Positioning System is used for tracking the
location of each Device placed in various parts. The Global
Positioning System is connected up with satellites, ground
stations, and receivers. Once the receiver calculates its
distance from four or more satellites, it knows exactly where
you are. GPS locks the exact position of that particular Device
if Motion Detected.

D. Motion Sensor
The A passive infrared sensor (PIR sensor) [1] is an
electronic sensor that measures infrared (IR) radiation being
emitted from objects in its field of view. They are most often
used in PIR-based motion detectors. When the sensor is idle,
both slots detect the same amount of IR, the ambient amount
radiated from the room or walls or outdoors. When a warm
body like a human or animal passes by, it first intercepts one
half of the PIR sensor, which causes a positive differential
change between the two halves. Thus automatically the PIR
sensor is trigger when any animal is caught within its radius.

E. USB Power In
Rechargepower bank of any capacity, here, 2800 mAH
is used (operating voltage of 5V DC), can be used to provide
supply to central microcontroller. The microcontroller used
will separate and supply the required amount of power to
each hardware component. This battery power pack is
rechargeable and can get charged and used again and again.

IV. CONNECTING TO THE INTERNET
The forest officials or the rangers at the control center
can continuously control and monitor the device in real time.
The device helps them to have a complete control of the
forest bed remotely. From their computer they can achieve a
graphical desktop based sharing system which uses Remote
frame buffer protocol (RFBP) through which the interace is
transmitted in real time from the device to the control centre.

GRAPHICAL USER INTERFACE

The application on the Raspberry Pi microcomputer is
developed using python language and made into an
executable shell file. When the file is double clicked, it
automatically opens the execution terminal.

 CASE 1: If any warm blooded animal or human
interferes the zone of IR rays it automatically
displays “Motion detected” and turns on the Camera
and GPS and sends a default notification is sent as a
message to the in charge security’s personal phone
[2].
 CASE 2: If no warm blooded animal or human
interferes the zone of IR rays it displays no Animal
is detected and set the camera and GPS to rest mode.
CAMCALT is designed in such a way that every
processing and monitoring is user friendly and can be
operated by everyone easily. As mentioned earlier once a Pop
up frame appears, a wide ray of options can be selected
according to the in-charge person’s requirement.
The GUI frame is user friendly and the following
processes can be done:
 Quit – Quits the program.
 Take Picture – We can immediately take a series
of photos in a burst, this is automatically saved to
a default location.
 Live Feed – We can get live feed of what the
current situation is from our device camera.
 Record Video – The live feed can be recorded
and the video files can be automatically saved to
a default location.
 Poacher Detection – Pre-trained Poachers can be
easily recognized by our Image Processing
Algorithms.
 Train Poacher to Camcalt – Repeated Poachers
can be trained to the device to be recognized in
the future by our Image Processing Algorithms
 GPS Location – The location of the device can
also be found.

A. Take picture, record video and live video feed
As the user-friendly UI pops up like that of Fig 5 when
motion is detected, the user–in-charge has the following
options here:
 “Take Photo”: This option gives the user - in -
charge an option to take a high quality
photograph/image (5 Mega - Pixels) of what is in
the field of view of the camera when the motion is
detected.
 “Record Video”: This option gives the user-in -
charge an option to record a high quality 10 second
video (1080p 24 fps) of whatever is in the field of
view of the camera when pressed.
 “Live Feed”: This option gives the user - in -
charge a high quality video feed (1080p 24
fps) of whatever is in the field of view of the
camera when the motion is detected.

B. Getting GPS Location
As the user-friendly UI pops up like that of Fig 5 when
motion is detected and the “GPS Location” button from this
UI gives the user-in -charge an option to get the current GPS
location coordinates of the CAMCALT device when pressed,
this will be useful when we use an array of CAMCALT
devices in the forest so as to identify from which device/
location of the forest the motion got detected.

C. Train Poacher to CAMCALT and poacher detection
The most special and powerful feature of CAMCALT is
Poacher Detection. This Feature uses the Image Processing
techniques to detect the Poacher using the 4 cores of the
powerful BCM2837 Processor powered by 1 GB RAM. By
using HSV to split-analyze the images and Haar Cascade
Detection to match the existing samples with the testing
image. The process of Poacher Detection is to first Train the
Poacher to the Device then followed by Poacher Detection.
Figure 6. Train Poacher to CAMCALT
Here, as the user-friendly UI pops up like that of Fig 5
when motion is detected and the “Train Poacher to
CAMCALT” button is pressed [3], one will get an option to
key in the name or identity of that Poacher. Then, show the
face of the poacher to the camera with good brightness. If
there is a face, the application will detect the face with a
green box. By default, the application is set to capture 20
samples. But it can be modified to one’s wish. As soon as the
application captures the necessary images, the camera
preview window closes automatically.
Now, the device is trained to that particular poacher, and
whenever or wherever (i.e. from any device placed) that
poacher is read in any device’s camera, he will be
automatically detected. That is because that poacher’s facial
features will be regularly compared and matched with the live
person’s face to check for a match. If it matches, he will be
immediately detected. Everything happens in real-time. There
is never a time delay between detections. The program
executes in micro-seconds, so the time lapse is negligible.
Here, as the user-friendly UI pops up like that of Fig 5
when motion is detected and the “Poacher Detection” button
is pressed, the “Face Recognition Window” pops up. Now
whenever a face is shown in front of the camera, it
immediately tries to find a match. If there is, then it shows
with a green box around the face with a name and identity of
the poacher. Else, it displays “Unknown” (See Fig 6) .
