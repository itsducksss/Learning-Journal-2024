# Learning-Journal-2024
This documents my learning in Programming

2024-10-15

Created a repository (this one), and tried the github.dev edit opition, but had trouble opening the file.

2024-10-22

Had a lesson trying to make our own tutorial. Mainly investigated the different possiblities on how to make a dialouge system and how they differ from one another e.g. interactable, click and scroll (multiple options of dialouge). Quickly implemented character movement and got the character to interact with another object to print the phrase "Dialouge started!", which was successful, had small issue I resolved in which the Tag in the script differed from that for the playable character which led to the print command not applying and working. The other script I followed had a minor issue that while did not affect gameplay may be affected in the future, as it stated that it had trouble as it was unsure if there were hidden flies for the different strings, will finish this and see if applicable to fuse both options to create a more complete dialouge system. Warning seen bellow. Warning pops up when u load unity after altering/ editing the script.
![image](https://github.com/user-attachments/assets/da27edd2-72c0-42dc-b618-dafac877a279)
Also making notes within the scripts and making crappy simplified versions of the tutorial for me to redo and edit in the future on word before I create the tutoial in video , github and or proper docummentation formats, which will just show basic steps and order for the tutorial.
Also stayed after the lesson for 2 more hours to continue to add to my script. Faced problem of errors within script which is that the dialouge when instantiated does not show, as it is covered by the image UI, and the TextMeshPro that was added does not change to intended dialouge and just shows up blank. Also faced problem with the instatiate using the transform of the canvas and dialouge template for the tutorial. Will fix problem next week.

2024-10-29

Had a lesson. Fixed the problem of the dialouge not appearing due to being cover up by the image plane as well as showing up blank (can show the intended dialouge). Change the tutoriakl so that it demonstartes the interacting system, as well as a single popup dialouge UI to show the basic functionality of the script and how it can be adjusted. To do this changed some areas of the script mainly the GetChild functio instead of the value being (1), which does not exist changed it to GetChild(0), which shows the first child of the canvas parent to be selected. Also removed a duplicate line in my scrpt that may ahve been causing issues when instantiating. Also made it so that when the character inteacts with the NPC the player is unable to move and is restarined in all axis using the rb (rigidbody). Started to write the tutorial for the Basic Single Interactable NPC Dialouge, which starts with the character movement of the capsule. Made a new unity project to show the results of the tutorial and if it was possible to reinact the tutorial and get the same results as I wanted from following the tutorial.
