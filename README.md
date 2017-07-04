# VR-Tracker v0.1 (experimental)
A setup (Python Server, Chrome Extension, Android App) that enables to send gyroscope/accelerometer data from Android device to Google Chrome browser on desktop.

## Instructions
1. Install Chrome Extension (enable developer mode)
2. Register the Python Script,
	For Windows: Run install_host.bat
	For MacOS/Linux : Run install_host.sh
3. Open a tab which wants to get tracking data
4. Open the extension using chrome://apps
5. Install VR Tracker App in your Android Phone, open it, toggle the stream switch.
6. Turn on tracking for that tab using the toggle switch & click 'CONNECT'
7. Once it says 'Connected.', 
    copy code of injectTracker.js and paste it into the web console of tab. 
    (the tab to which you want to enable tracking)
