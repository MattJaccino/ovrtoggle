# Rainmeter - OVRtoggle
Rainmeter skin to start and stop Oculus VR services to avoid having them run all the time. 

To do that, in Task Manager, click the "Services" tab at the top, then the "Open Services" text at the bottom.  In there, scroll down to "Oculus VR Runtime Service", right click it and pick "Properties".  From that window, you can select the "Startup Type".  Repeat for "Oculus VR Library Service".  I recommend making the startup types for both "Oculus VR Runtime Service" **and** "Oculus VR Library Service" the same, either 'Manual' (my recommendation) or leave it as 'Automatic'.

Download the two files (.ini and .png) into a zip, extract them into a folder (say "OVRtoggle") in your C:\Users\[user]\Documents\Rainmeter\Skins folder (or wherever you save your skins).  Then just load the skin in Rainmeter.
