

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

Learned how to use Github desktop and how to upload Unity Projects from computers. Learned the autonomy of a unity project and how the git ignore works and the basic files needed to upload a Unity Project with no problem re-opening it back up. Looked at videos on enemy ai and how it works. This is as the prototype game that I want to create will have interactable objects that might create events/actions to occur.

2024-11-26

Researched how to use AI pathfinding in Unity. Had trouble following tutporial realised that it was because Unity has 2 different navigation windows, and the one shown in the video cannot be accessed in the same way, as Unity updated, meaning that it can only be accessed in the Windows tab in the AI tab. This update seemed to have occurred in the 2021 versions onwards based on a Unity thread posting about this same issue. The difference in the AI Navigation Windows can be seen bellow.
![image](https://github.com/user-attachments/assets/825eb714-f4ae-44f2-a89b-ef3a3c538c95)
This meant that I was unable to bake the NavMeshAgent or the floor (on which the agent has to walk onto and navigate) for it to work which led to an error to pop-up that the NavMeshAgent could not be called onto which was harder to solve.
Got another error regarding the OnDrawGizmos and Gizmos that was used in the Debug part of the script. After reseaching it may have also been done from an update from 2021 Unity ver onwards of it not being visble. The error that showed up is non invocable member cannot be used as method which I could not fix. I realised after asking for help that there were brackets in my script that were not in the tutorial due to the automatic "autocorrect" in visual studio which added a lot of other parts which were in the original script.
Got another error. Realised that this was beacuse I wrote Drawline and not DrawLine with a capital "L" which cause my problems to occur when doing the script. When I fixed this problem I got more problems when Unity loaded up I got 282 problems that said the same thing, which multipied whenever i clicked in Unity. Besides the constant notifications, the scene could still be played and would show the path of the AI its turns and how it changed depending on where the player was.
I realised that the objects in the scene could be changed so that they could be jumped, walked on etc.. as well as avoided by the AI. The main issue I had was with the character's gravity which even when change (including mass and drag), still fell too slow than what it should have. Had issues with some of the jumpable and walkable objects with the pathfinding. will fix next week.

2024-12-03

I realized that the multitude of errors that pop-up are just as the the scene is not playing. This means that the errors will not pop up and occur, if the scene is playing no errors will occur, and the previous errors go away, but when you stop playing, the errors pop back up. The AIs also had trouble going up diagonal slopes, as even if they baked they did not work, but if they were not baked also had problems with it, as they just went through the slopes. I thought that the reason that this occurred was due to the angle of the slope which was in the bake was too low, which meant that this slopw which was too high was not calculate and included in the walkable paths for the AI. I tried to fix this, but the fixes of this problem did not work on my project but I tested the solution of changing the angles in the bakable objects as well as the tag of the bakes from walkable to jump as an example to see how the bake would react. I stopped, as the bake started to rotate weirdly as an object.

https://github.com/user-attachments/assets/aa072ba5-3e54-4fb6-9c5c-3ba8d008c403

The problems with the playable character's gravity/mass (as well as other problems that I had last week) can also be seen here.

2024-12-10

Finishing tutorial. Finished the tutorial, however the page reloaded and lost 2 hours and 17 minutes worth of work currently 16:17. realised that I should save more often. On the good side I understood my code and tutorial more. Finished most of the tutorial by 18:01 I will add in more videos on how to switch the Gizmos on and off. I learnt that the solution to prvent these things from occuring is to save the work incrementally as you progress. Next week I aim to do my last tutorial which would be based of either killing the AI, being able to hide from the AI in certain areas which will then cause the AI to do a "normal routine" and or creating gameplay in which if you find a key the door might open if possible but I am not sure if that is feasible.

2024-17-10

computer crashed lost my work form earlier (4 hours) should save more often. Tried different tutorial on a key and door system for my game but one didn't work due tpo the set up and for it being more applicable in a 2d game rather than 3d game, while the other one was outdated which means that I could not use the tutorial. Started working on a rtimer when my stuff closed. Timer works. Had an issue woth the script not working due to a 

int string was not in the correct format

error which was beacuase I used the wrong puncuation in the script.


https://github.com/user-attachments/assets/e9de04c8-a4e1-4eca-9012-222183d36ced


The other error I had which was fixed can be seen on the video above .


https://github.com/user-attachments/assets/623d5d84-794e-48aa-bc32-d292f1aae6e0


I talked to Paul who said my script looked right, but after deleting a section of the script and copying it back in the issue was fixed not sure why seen in the video above.


https://github.com/user-attachments/assets/15471615-12e9-4b34-8232-0bd2ba1f00bd


Realised that I had an issue once the Timer goes past 0:00 displayed in the video above of what could occur in the nity scene if the scene does not stop playing after 0:00.

![image](https://github.com/user-attachments/assets/a73df10c-eb50-4a8b-b2c4-d66a629a5f9d)![image](https://github.com/user-attachments/assets/678b4f72-338a-4bc2-a14f-7188ccace275)

these are the changes I made onto the script.


https://github.com/user-attachments/assets/e07a5af7-efe7-4fbc-ace6-8ea30d0a9c2f

This just shows that the Time will just stay at 0 instead of counting down further.

Made some adjustments onto the script that just means that when it reaches 0, that the scene will reset using Unity's Scene Management system which was not in the original script. Using the Unity Management System just means that i dont have to create another script and or add more processes that could make the process take longer than needed.

2024-12-29
Made some changes onto my Timer Restart Scene tutorial. 

2025-01-07
Finished the Tutorial for the Timer which was my last tutorial, and made some changes onto my Basic Character Interaction tutorial. Realised that tutorials could have more detail so added more commitments onto all of them.

Forgot how to upload my game onto GitHub realised that the folder I selected was within another folder which was causing the issue, this happened when I moved my game from one PC to another, as it created anothe folder withthe same name which is why I was originally confused, selecting the correct folder fixed this issue. I also learnt how to export a Unity Project and how to open it onto another PC (creating a New Unity project and importing the assets and stuff back in). Also learned how to zip a Unity file, understood which files were necessary to recreate the project onto another computer as well as what folders were not needed (e.g. Library folder) and would appear when I opened the zipped Unity Project onto the new computer e.g. Library folder etc...

Handed in the coursework, however I had an issue uploading the video of my prototype onto the Vle and so instead added it onto my Read.me in the Prototype game repository in GitHub. This was as my videos were too lage to upload onto the Vle,and adding another link to the video in onedrive can cause complications so added it onto gitHub so that it was together with the prototype game itself. Imported the screen recodiings into Premiere pro and added in captions to describe what was happening in the videos. Also added in a secreen recording of the scene view in Unity, as one of my tutorials had features that could only be seen in the Scene view and not in the Game view/ window.

