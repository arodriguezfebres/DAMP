# DAMP Guide
Disaster App For Medical Preparedness Project

## Sections
1. [Project Introduction](https://github.com/JID-7155/DAMP#project-introduction)
2. [Install Guide](https://github.com/JID-7155/DAMP#installation-guide)
3. [Release Notes](https://github.com/JID-7155/DAMP#release-notes)
4. [Frequently Asked Questions (FAQ)](https://github.com/JID-7155/DAMP#faq)


## Project Introduction
Disaster App for Medical Preparedness, DAMP, is an Android project focused on providing a platform to host medical response plans for individuals concerned with their health/safety, so that in the case of a medical emergency they have immediate access to procedures of how to handle such an occurance. As part of our junior design Georgia Tech team, JID-7155 'Ad Revenue', we are composed of five members:
- <code>Aaron&nbsp;&nbsp;&nbsp;<strong>A</strong>ndrews</code>.
- <code>Elie&nbsp;&nbsp;&nbsp;&nbsp;<strong>D</strong>iaz</code>.
- <code>Adrian&nbsp;&nbsp;<strong>R</strong>odriguez-Febres</code>.
- <code>Melissa&nbsp;<strong>E</strong>ssue</code>.
- <code>Joshua&nbsp;&nbsp;<strong>V</strong>aldez</code>.

## Install Guide
* Pre-requesites:
  * Download and install Android Studio.
* Dependent Libraries:
  * None.
* Download Instructions:
  * Access the repository [here](https://github.com/JID-7155/DAMP).
  * Click 'Clone or download' at the top right.
* Build Instructions:
  * Open the project folder in Android Studio. It will automatically configure the application by the gradle settings.
* Run Instructions:
  * Run the application in an emulator or connected mobile device of your choice.
 
## Release Notes
1.00 (Current):
 - If utilizing on an emulator, please note that Maps functionality will assume the Google HQ as current location unless current coordinates are sent through the emulator toolkit. 
 - You <strong>MUST</strong> replace the Google Maps API key with your own. It is located in the Android Manifest file.
 
Fixes:
 - The step list on the plan screen now parses each step as a separate item in a listview.
 - All entry text fields are now more flexible and grow as neccessary.
 - Fixed exception that occured when accessing a patient who currently has no plans.
 - General UI improvements across the app, particularly the Maps Screen.
 - The edit/delete button on the view plans screen now changes color to reflect what mode the user is in.
 - Returning to the view plans screen now forces the user into Edit mode.
 
 Missing Features:
 - Currently there are no constraints on user input, allowing empty plan and patient names among other things.
 - Plan importing and exporting has yet to be implemented.
 - There is no way of bypassing a phone's locking system in the case of an emergency.

## FAQ
- Q. Who do I contact for more info?
  * A. Our team lead, Adrian Rodriguez, at aorf3@gatech.edu
- Q. Am I free to use and modify this project for whatever purposes I see, be it commercial or personal?
  * A. You are free to modify and utilize our code for any and all purposes, but all five original team members must be credited accordingly as contributors.
