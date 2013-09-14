X32-Scribbler 
============= 
 
Realtime Editing and Viewing Of Behringer X32 Scribble Strips 
 
##About 
The scribble strips on the Behringer X32 are an amazing feature.  Unfortunately, editing their contents on the device is not easy without a keyboard.  Furthermore, the various *layers* restrict the user from seeing all settings at a glance. 
 
The X32 will allow up to 4 clients to subscribe to realtime control changes.  This application will register as one of them.  Changes on either the X32, the X32-Scribbler, or another controller will be synchronized. 
 
You can currently set the following parameters 
- Configuration
  - text 
  - color 
  - icon 
  - source
- Mixer
  - level 
  - mute 
 
##Usage 
- You must have Java 7 or later installed. 
- Unzip the application folder
- Run the application, type your X32 network address in the toolbar, then press enter. 
- There are currently issues with the X32 when requesting many values at once, so if a '?' still appears in a field, press *refresh* on the toolbar. 
- The application is written using the Eclipse e4 application framework.  You can drag any view to any postion in the window, stack them, or even drag them out of the main window.  Each view can be minimized or maximized by pressing the icon or double clicking the title. 
- The mixer level should be set as an integer between 0 and 100.  Mute is 0 or 1 (0 means muted...).  Entering text other than these values will result in unexpected behavior.
 
##Source Code 
I am unable to release the source for this project until I separate the X32 code from my company's non-open source libraries, so until that time, please enjoy one of the platform builds I am posting. 
 
