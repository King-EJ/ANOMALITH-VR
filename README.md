# ANOMALITH-VR
VR mod for ANOMALITH

<img width="1024" height="1024" alt="ANOMALITH vr" src="https://github.com/user-attachments/assets/0cb7210b-59fe-4a88-b43f-9a5e108826e0" />


ANOMALITH VR  -  VR mod (Unity 6000.3, Mono x64, URP, BepInEx 5)
==================================================================
Version 0.2.2 (test build)

<img width="448" height="442" alt="Adobe" src="https://github.com/user-attachments/assets/e9a790b9-a52c-473c-81b5-149531cf32e4" />

INSTALL
-
  1. unzip to game folder, only tested with virtual desktop XR,
        to disable Mod rename winhttp.dll to winhttp.dll.bak
  2. Start your OpenXR runtime first (Virtual Desktop / SteamVR / Quest Link), then the game.
  
CONTROLS (the VR controllers are a GAMEPAD for the game - the game's own pad controls and button prompts)
-
  Left stick ............ left stick (move) 
  
  Right stick ......... right stick (camera)
                                                   
  A ..................... South (Cross / A)
  
  B ................... East (Circle / B)
  
  X tap ................. West (Square / X)
  
  Y ................... North (Triangle / Y)
  
  X hold ................ R3 (right stick press)
  
  X + Y together ........ Start (pause\hold skip)  
  Left grip + Y ....... Select
  
  Left grip + X ......... switch third person **Follow / GameCamera**
  
  Right grip ............ R1 / RB   (SwapRightGripAndLT: right grip and left trigger swapped)
  
  Left stick click ...... L3  
  
  Right stick click ... L1 / LB (short press)
  
  Hold right stick click  switch FIRST / THIRD PERSON (0.6 s)
  
  Both stick clicks ..... re-centre the view
  
  Hold both stick clicks 1.2 s ... VR SETTINGS MENU (stick up/down choose, left/right change, A toggle, B close;
                          saved straight away; no game buttons are sent while it is open)
                          
  Every button can be changed in the config ([Controls.Pad]: South, East, West, North, LeftShoulder,
  RightShoulder, LeftTrigger, RightTrigger, LeftStickPress, RightStickPress, Start, Select, DpadUp...).
  The game's controller rumble is sent to your controllers.

VIEW
-
  * Third person, Follow (default): you follow behind the player at a fixed height / distance (no orbiting, no up
    and down); the right stick turns you and the view stays behind the player.
  * Third person, GameCamera: you are where the game camera is; your view turns with it (right stick).
  * First person: you are the player's eyes (the head is hidden), the right stick turns you, the player's hands
    follow your controllers.
  * Both: the left stick moves you where you LOOK.
  * Menus / pause: the game's picture on a screen in front of you. In play the HUD floats in front of you (its black
    parts see-through). Cut-scenes: you see from the game camera.

AIM / INTERACT (6DoF)
-
  * Shots and the player's aim follow your RIGHT controller (in both views). A white dot shows where you aim;
    first person also shows a laser while aiming (Laser: WhenAiming / Always / Off). The game's crosshair is hidden.
  * Ammo / health float by your right controller, the objective by your left controller, interaction markers
    above the things in the world.
  * What you can interact with is picked from where your right controller points.
  * First person: the gun hand turns so the gun points where you aim.

Issues
  * Game 3rd person show in world interaction markers, the 1st person and follow 3rd person may not so just switch back to game 3rd person to see markers

