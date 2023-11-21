# Jump-Pad-Tutorial

1. Create an object on the scene and name it JumpPad. Add a Sprite Renderer and a Box Collider 2D with 'No Friction' as the material. 
   ![image](https://github.com/MartTQ/Jump-Pad-Tutorial/assets/123513842/50c162be-a33b-43c1-a786-74551609d750)
   
   ![image](https://github.com/MartTQ/Jump-Pad-Tutorial/assets/123513842/1f95f33d-2d91-4122-bfd6-4a2bbc7932ea)

2. Create a new script within the Jump Pad object and name the script 'JumpPad'
   ![image](https://github.com/MartTQ/Jump-Pad-Tutorial/assets/123513842/c22bad98-d620-42ca-aae4-bafe2155152c)

3. Open the JumpPad Script. Set up a private float for our jump pad (the higher the value the higher our player accelerates upwards).
   ![image](https://github.com/MartTQ/Jump-Pad-Tutorial/assets/123513842/e6227bbd-aa12-481f-9789-426b665947da)

4. To check if the player has made contact with the jump pad, we will be using the 'OnCollisionEnter2D' method. We will need to check if the tag for our collided game object is 'Player'

   ![image](https://github.com/MartTQ/Jump-Pad-Tutorial/assets/123513842/e4be2984-0464-4cae-9d1e-625a1ecdc42e)

6. We then now how to access our 'player' rigidbody2D component and add a force to it; this determines the direction our player goes (which is 'up') when colliding with the jump pad. This is muiltiplied by our bounce value.

   ![image](https://github.com/MartTQ/Jump-Pad-Tutorial/assets/123513842/f2ca6972-0575-4acc-b237-a0e2ffbf3420)

7. Finally, we have to go to our 'player' object and set the tag to player. This should apply the tag from the jumppad script to our player.
   
   ![image](https://github.com/MartTQ/Jump-Pad-Tutorial/assets/123513842/5641c67a-40ff-4d04-b485-8eaf70b0e53e) ![image](https://github.com/MartTQ/Jump-Pad-Tutorial/assets/123513842/fc352104-5116-4e59-a365-36ec12dd7c86)

8. Final result should end up like this:
   
https://github.com/MartTQ/Jump-Pad-Tutorial/assets/123513842/00b63431-53ab-4ed1-863e-9d951f4e4a84


   
