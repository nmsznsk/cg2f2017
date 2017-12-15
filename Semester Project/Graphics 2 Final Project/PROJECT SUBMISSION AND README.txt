Nicholas Muszynski
Graphics 2 Semester Project



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
Hardware requirements - The phone which I had made an osig file out of. This is the phone that I had borrowed for a brief time during our final class day (12/13), and is also the same phone which had the step tracker motion detection app used to walk-in-place to move within virtual reality. Also please note, I gave the same osig file to the other student who was also developing on Gear VR so you will need this phone for his meditation project as well, as I found out that unless you have your app published to the store, each phone that will use the application needs their own osig file generated and compiled with the project.
You will also need a Gear VR headset.



THIS IS STILL BEING UPDATED, PLEASE WAIT...