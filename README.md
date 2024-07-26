# Group F's Agricultural Drone for CSC 414 - Software Design - University of Southern Mississippi

*You MUST use Unity version 2021.3.8f1 and it is highly recommended to use Unity Hub to manage your installation.*

### How to download project:

[Install git](https://git-scm.com/downloads)

Open git bash and navigate to your Unity Projects folder. If you haven't made one, feel free to make it wherever you would like. I keep mine in my documents folder, i.e. ~/Documents/Unity_Projects
You can navigate by using the cd & ls command like bash on linux. cd whill change the directory and ls will list the contents of the directory.
<details>
   <summary>
      Example
   </summary>
   
```bash
cd Documents/Unity_Projects && ls
```
**Note:** To navigate to a folder which contains spaces, put a backslash before the space
```bash
cd Documents/Unity\ Projects
```
</details>

Once you have navigated to the folder you want your Unity project to be in, clone the repository with this command:

```bash
git clone https://github.com/gibbyb/AgriculturalDrone
```

Open Unity Hub, click open, navigate to your recently created Unity Projects folder & select the AgriculturalDrone folder and click open. 

In the assets folder, click on the LowPolyFarmLite/Scenes/LowPolyFarmLite_Demo.unity scene. 

Once the scene is opened, just press play and you can then fly the drone.

Drone Controls:
-  Forward:          W	 
-  Backward:         S
-  Left:             A
-  Right:            D
-  Fly up:           Spacebar
-  Fly down:         Shift
-  First-Person:     3
-  Third-Person:     1
-  Top-down:         2
-  Take picture:     G
   - uses top-down camera  
-  Head to waypoint: P

<details>
   <summary>
      <h4>If the camera does not change perspectives, follow these steps:</h4>
   </summary>
   <ol>
      <li>
         Open the project in unity and click on "Edit" in the top left corner
      </li>
      <br/>
      <li>
         Click on "Project Settings" [Should be sixth from the bottom]
      </li>
      <br/>
      <li>
         On the left-hand side of the project settings window, locate the "Input Manager" tab
      </li>
      <br/>
      <li>
         Once there, look under axes to see if "1Key", "2Key", and or "3Key" are missing [make note of the last dropdown].
      </li>
      <br/>
      <li>
         If they are missing, scroll up to the "Size" box [just under the axes dropdown], and add 3 to that current number.
      </li>
      <br/>
      <li>
         Scroll back down, and you will notice that the last dropdown was duplicated 3 times. Click on the first duplicated dropdown, and modify the values so that it is the same as the image that I posted above. Do this step 2 more times for the remaining duplicates naming and changing the "Positive" value for "2Key" and "3Key" respectively.
      </li>
   </ol>
</details>
