# Learning-Journal-2024
This documents my learning in Programming

2024-10-15

Created a repository (this one), and tried the github.dev edit opition, but had trouble opening the file. Tried learning how to create basic character movement in Unity and learned the basic componenets needed and how they work within Unity to create the code and the character movement in Unity.

2024-10-22

Had a lesson trying to make our own tutorial. Mainly investigated the different possiblities on how to make a dialouge system and how they differ from one another e.g. interactable, click and scroll (multiple options of dialouge). Quickly implemented character movement and got the character to interact with another object to print the phrase "Dialouge started!", which was successful, had small issue I resolved in which the Tag in the script differed from that for the playable character which led to the print command not applying and working. The other script I followed had a minor issue that while did not affect gameplay may be affected in the future, as it stated that it had trouble as it was unsure if there were hidden flies for the different strings, will finish this and see if applicable to fuse both options to create a more complete dialouge system. Warning seen bellow. Warning pops up when u load unity after altering/ editing the script.
![image](https://github.com/user-attachments/assets/da27edd2-72c0-42dc-b618-dafac877a279)
Also making notes within the scripts and making crappy simplified versions of the tutorial for me to redo and edit in the future on word before I create the tutoial in video , github and or proper docummentation formats, which will just show basic steps and order for the tutorial.
Also stayed after the lesson for 2 more hours to continue to add to my script. Faced problem of errors within script which is that the dialouge when instantiated does not show, as it is covered by the image UI, and the TextMeshPro that was added does not change to intended dialouge and just shows up blank. Also faced problem with the instatiate using the transform of the canvas and dialouge template for the tutorial. Will fix problem next week.

2024-10-29

Had a lesson. Fixed the problem of the dialouge not appearing due to being cover up by the image plane as well as showing up blank (can show the intended dialouge). This problem occured as I forgot to remove the original template in the Unity Scene which caused the template with the changed dialouge to be hidden by the original template that I had forgotten to delete from the Unity hierarchy. Change the tutorial so that it demonstartes the interacting system, as well as a single popup dialouge UI to show the basic functionality of the script and how it can be adjusted. To do this changed some areas of the script mainly the GetChild functio instead of the value being (1), which does not exist changed it to GetChild(0), which shows the first child of the canvas parent to be selected. Also removed a duplicate line in my scrpt that may ahve been causing issues when instantiating. Also made it so that when the character inteacts with the NPC the player is unable to move and is restarined in all axis using the rb (rigidbody). Started to write the tutorial for the Basic Single Interactable NPC Dialouge, which starts with the character movement of the capsule. Made a new unity project to show the results of the tutorial and if it was possible to reinact the tutorial and get the same results as I wanted from following the tutorial.

2024-11-05

Found an easy way to add videos and photos into github. I used word and cropped the photos in Word then copied and pasted to upload into github. For the videos I screenrecorded using Powerpoint and then right clicked the videos after editing and trimming the vids in Powerpoint and saved as which allowed me to upload videos easily onto Github. Had a problem with my project testing out my own tutorial, it was I missed a line of code which referenced he rb(Rigidbody in my code). Stayed after and compared my tutorial to one made by the teacher to see if my tutorial had enough detail as his.

2024-11-12

Watched video online on how to make clickable links embeded into the word for the tutorial in Github. I looked up keywords from my script and added links onto their descriptions into my Basic NPC intraction tutorial as links. Finished up the tutorial removed spelling errors within my tutorial. Finished my 2nd tutorial on Basic NPC interaction. This code however can be utilised so that they can do a multitude of actions such as opening doors or just creating interactable gameobjects by adjusting the code to fit the needs of the scene/ player.

2024-11-19

Learned how to use Github desktop and how to upload Unity Projects from computers. Learned the autonomy of a unity project and how the git ignore works and the basic files needed to upload a Unity Project with no problem re-opening it back up. Looked at videos on enemy ai and how it works. This is as the prototype game that I want to create will have interactable objects that might create events/actions to occur
