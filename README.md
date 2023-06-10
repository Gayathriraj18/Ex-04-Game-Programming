# Ex-04-Game-Programming

# Aim:
To Attach Rifle with character mesh and implementation bullet spawn from Rifle.

# Procedure:
Step1:
Import the character mesh that you chose and the suitable gun mesh.Ensure all the files are imported correctly.

Step2:
Create action events to trigger them by pressing the respective key. image

Step3:
Open the SKELETAL MESH of the imported character and direct yourself to the skeleton tree. Here we have to create socket at the spinal and in right hand part of the skeleton tree.

Step4:
Attach the rifle model to the character's attachment point using the appropriate parenting or socketing mechanism provided by your game engine. This will ensure that the rifle follows the character's movements and animations correctly.

Step5:
After this we have to create a bullet actor, gunactor and specify the direction of the bullet to launch. In event graph make required connection so that the bullet launches correctly.

Step6:
In event graph create connection for the gun spawn so that when we click the triggering key and the gun gets spawned to hand. image

Step7:
Now create an event to trigger bullet fire and make appropriate connections so that when key is pressed, the bullet launches. Correct the initial and final velocity of the bullet before compiling. image

Step8:
Adjust the velocity of the bullet in ullet actor and make sure all the connections are correctly made.

Step9:
Additionally make sure that when the gun is spawned to spinalcord the bullet fire option should be disabled.

# Output:

![1](Screenshot%202023-06-10%20201158.png)

![2](Screenshot%202023-06-10%20201231.png)

![3](Screenshot%202023-06-10%20201302.png)

![4](Screenshot%202023-06-10%20201328.png)

# Gun in Hand :

![5](Screenshot%202023-06-10%20201346.png)