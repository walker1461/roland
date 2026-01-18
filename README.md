# Roland TR-808 Web App

This project initially began as my final project for Sounth Synthesis & Signal Processing, where I recreated a functioning Roland TR-808 in MaxMSP.  As I began to learn more about web development, I decided that I wanted to challenge myself by creating a similar application that could run in a browser.  My research led me to p5.js, a JavaScript library that focuses 
on creating audio and visual art with code.  I fell in love with this creative form of coding and used p5 in order to build this page, along with some vanilla CSS for styling.

> [!NOTE]
> This page is not mobile friendly, use desktop to view.

## Usage
<img width="333" height="137" alt="Roland web app pattern grid" src="https://github.com/user-attachments/assets/b6713d54-bfe0-4f95-bb4a-31249ec3c401" />\
The drum machine is organized into a grid where each button in a row represents a quarter note, with 16 columns making a full measure. Each row is associated with playing a particular sound on each pass over a button. Clicking on a button toggles it both on and off.


<img width="179" height="53" alt="Roland web app controls" src="https://github.com/user-attachments/assets/894c9826-5dc4-4f53-835c-5fac26853a75" />\
Click the play button to play your created pattern and click again to stop it. The reset button will clear the current pattern, and the save button will save the current pattern to the pattern bank in your browsers local memory.


<img width="286" height="56" alt="Roland web app pattern bank" src="https://github.com/user-attachments/assets/239312a8-2f46-4b34-bf64-afa182c08dee" />\
The pattern bank will let you save and load up to six different patterns. Click on any numbered pattern button to switch to it.


<img width="451" height="46" alt="Roland web app BPM slider" src="https://github.com/user-attachments/assets/9c0a93a5-9564-47ed-9e42-caea3349da78" />\
Use the BPM slider to choose the tempo that your pattern will be played back at. BPM ranges between 60 and 180.
