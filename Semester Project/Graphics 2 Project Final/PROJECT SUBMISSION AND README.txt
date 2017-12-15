
~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~

Graphics 2 Semester Project
Nicholas Muszynski
nmsznsk@gmail.com



----------------
Directory Contents:

Game Assets  ->  Meshes, textures and normal map used to create all the objects in the game (other than the mannequin). Files with the .fbx extension can be opened by most engines and modelling software, but Blender is free and open-source if one is needed.

Unreal Engine Files.zip  ->  This zip file contains all the files necessary to open and review within Unreal Engine 4. You will need to download version 4.18 if you want to open these files, shouldn't be necessary unless you wanted to see how the game was built inside the editor.

Logic Pictures  ->  Pictures of the various scripts I compiled within the game to perform the animations and check the player's head position. I realize that the comment boxes used white text on white background; in my defense, I couldn't change the colors of the background or text for the comment boxes.

Project Installer  ->  Contains the .apk file which is the installer for the application, installation details below.

Muszynski-Nicholas_comp4280f2017-final-project.zip  ->  Complete archive of all of the files within this GitHub directory. The file on its own is too large for GitHub (141 MB) so it is broken into two volumes. Simply select both together, right click -> extract, and pick a desired location, or alternatively any other method you may prefer for extracting files that are broken into multiple volumes.
----------------



- What does the project do?

	This project attempts to utilize head motion as a naturally intuitive control for users to interact with the application. This is approached as a proof-of-concept implementation, where a mannequin will guide the user to tilt their head to the left or right based on which hand is held up. The desired outcome of this design is to be simple to understand and utilize due to the context of the scenario that the user is experiencing within VR, while attempting to avoid being a burdensome task to carry out from the added weight of wearing a VR headset along with the required head movement instead of traditionally pressing a button on a controller. By achieving both of these specifications, a user's VR experience can be enhanced in a subtle fashion by implementing this mode of input. Since this concept of user input is heavily focused on physical manipulation, it can be expanded by using advanced motion tracking systems such as cameras, wand controllers, and sensors within the headset itself. Because of this, it was a desire of mine to utilize the Oculus Rift, but unfortunately this system wasn't compatible with my computer so I settled for the Gear VR instead. While this resulted in a simpler motion tracking system of only the VR headset sensors, this is still enough to incorporate some basic degree of physical movement as a method of control and enabled me to achieve the proof-of-concept functionality that the project offers.



- List of the parts of the project:

All meshes except for the mannequin were developed by myself.
All textures were developed by myself.
Normal map was created by converting the grass texture I had made, via this website:  http://cpetry.github.io/NormalMap-Online/
Mannequin and its components (meshes, normal maps, textures, etc.) were provided by the engine.
The terrain was made by myself using a basic landscape editor within the engine.
Animations were mostly done by myself, details below:
Took a default idle animation provided by engine which has the user holding a rifle at their hip
Modified this animation by deleting any frame data for the arms, and manipulating the arms to rest at the mannequin's sides in a neutral posture (the rest of the frame data for the rigging was left alone, as the mannequin would show slight movements which felt more natural than standing completely still, and didn't cause any issues with the new animations I created).
Used this newly modified idle animation as a starting foundation for the rest of the animations, which were developed by myself.



- User Manual:

Software requirements - N/A
Hardware requirements - The phone which I had made an osig file out of. This is the phone that I had borrowed for a brief time during our final class day (12/13), and is also the same phone which had the step tracker motion detection app used to walk-in-place to move within virtual reality in one student's project (I believe his name was Seth?). Also please note, I gave the same osig file to the other student who was also developing on Gear VR so you will need this phone for his meditation project as well, as I found out that unless you have your app published to the store, each phone that will use the application needs their own osig file generated and compiled with the project.
You will also need a Gear VR headset.

Installation:
1.  Download the .apk file from the Project Installer directory on GitHub to a local directory.
	Download link:  https://github.com/nmsznsk/cg2f2017/tree/master/Semester%20Project/Graphics%202%20Final%20Project/Project%20Installer
2.  Connect your computer to your phone, and upload the .apk file to your phone's storage (can be anywhere on the phone).
3.  Use a file manager app to navigate to the file (you should have one by default, look for one called "My Files" or something similar).
4.  Select the app. The phone will likely tell you that the app is blocked unless you allow unknown sources, so select the "Settings" option it provides. If you don't get this message, go to:  Settings -> Lock Screen and Security -> Lock Screen and Security -> Unknown Sources, enable.
5. once this is allowed (select the file again if you had to navigate through Settings above), the application will install to your phone.
6. Once the installation is done, you will have a new application available to select called "graphics2project".
7. Select this app, then plug into the Gear VR headset to begin playing.

How to play:
The game will automatically begin upon starting the application.
The game is played by tilting your head either to the left or right, as if to touch your head to your shoulder.
The mannequin will lift either its left or right arm above its head.
Tilt your head in the direction that the mannequin's arm is raised.
If your head isn't tilted enough, or if it isn't done fast enough in response to the mannequin raising their arm, it shakes its head in profuse disagreement.
There are no limits to how many times you are allowed to fail or succeed, so attempt as many times as desired.

~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~*~
