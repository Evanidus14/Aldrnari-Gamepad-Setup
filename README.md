# Aldrnari Gamepad Setup & Guide

![Logo](https://i.imgur.com/qOPBy7D.png)

## Foreword

Setting up Aldrnari with a gamepad can be a daunting task with all of it's extra features and possible keybinds. In addition to that, the main combat mod, Engarde, works in such a way that dodges and power attacks won't respond to your analog stick movements - effectively locking you out of most of your defensive and offensive options right from the start. There are some workarounds such as mapping your controller to keyboard keys for movement, but this is less than ideal and a pain to set up. Hopefully, with the help of this guide, you won't have to worry about *that*, anymore.

If you follow the instructions within this guide, you'll be able to play Aldrnari utilizing all of what it's systems have to offer, comfortably, with your gamepad while still enjoying all of what a controller brings to the table. Finally, you won't have to download any crazy software or tinker around with configurations - all of that has already been done for you and will be linked for easy access further into the guide.

... You *will* have to spend time and read this guide in its entirety though, otherwise you will be lost when trying to use your controller in game. You will also be told to RTFM if you ask any questions about controller support in the Aldrnari support channel that are answered within this guide. This guide has been prepared to help YOU help yourself. If you can't be bothered to read, well, no one else will be bothered to help. 

## First Steps & Setup

### Important Considerations

Make sure you follow this guide AFTER you finish the install guide and MCM settings in the main readme. If you do not, you will most likely run into keybinding issues as anything you set up in this guide could or will be overwritten by the main MCM keybindings or settings.

### Connecting Your Controller To Steam

This step can be somewhat difficult depending on your hardware and PC setup. Before we move on, Steam needs to be recognizing your controller for you to be able to apply the Aldrnari configurations. If you are having difficulty, make sure you go into Steam's settings, then controller settings, and then click on "GENERAL CONTROLLER SETTINGS" to ensure you have the right support boxes checked for the controller you're using. 

So, that will look like this...
![image](https://user-images.githubusercontent.com/89932487/133790433-f562b809-d170-487c-aa3a-2763e6bc7d79.png)

... and then this. Make sure you check the appropriate box or boxes for your specific controller situation!
![image](https://user-images.githubusercontent.com/89932487/133791623-28808010-9c55-426f-a998-a1d7f30edbb0.png)


Steam's controller support is very broad, so just about any controller will work. This guide, however, will be focusing on the PS4 controller and the Xbox controller, as those are the most widely known and used. If you still can't get your controller connected, you'll have to google solutions as the potential source of the problem could be a great many things and support/troubleshooting for it goes beyond the scope of this guide. Take solace in the fact that someone out there has most likely experienced your issue and has a solution for you, you just have to find it (yourself).

### Importing The Steam Controller Configurations

As was stated earlier, you don't need to mess around with any custom controls, software, or configurations yourself, that has ALL been done for you. This step is simply applying the configuration that has already been made to your specific controller. The configurations were made on a PS5 controller and an Xbox Elite controller, but they will still work with earlier generation models. That is to say, the PS5 controller configuration works with a PS4 controller and the Xbox Elite configuration works with any Xbox controller. If you're using some sort of wonky 3rd party controller, it *should* work with the Xbox configuration. So, depending on which controller you're using, Steam may give you a warning telling you the configuration you are trying to apply was made for a different controller, simply hit the "OK" option and the controls will map appropriately - SO LONG AS YOU APPLIED THE MATCHING CONFIGURATION THAT WAS JUST MENTIONED. 

Simply copy and paste the appropriate controller configuration from below into your browser and it will attempt to open Steam. Allow it to do so and then accept the configuration as was just mentioned.

The Steam controller configurations are here: 
  - [PS4/5 controller] (steam://controllerconfig/489830/2604084518)
  ![image](https://user-images.githubusercontent.com/89932487/133794142-8eb67c39-2dc2-4a31-9228-faeb6f06555f.png)

  - [Xbox and all 3rd party controllers] (steam://controllerconfig/489830/2604230895)
  ![image](https://user-images.githubusercontent.com/89932487/133794350-b206104c-76f7-443f-933b-8031bc13c566.png)

Feel free to browse through the various keybindings to get a visual of the controls. However, DO NOT CHANGE ANYTHING! That will completely mess up your controls. If you do accidentally change something, simply re-import the configuration from this guide. 

## Important Mods to Understand

### Engarde

Engarde is the combat mod being used by Alrnari. Go to the [Modified Gameplay.md](https://github.com/SovnSkyrim/Aldrnari/blob/main/Modified%20Gameplay.md) for details on the gameplay changes made. What you need to understand about Engarde when it comes to playing with your controller, is how it was designed and why it is notoriously hard to play with a controller. It was designed around keyboard directional keys for determining movement, so since we use an analog stick, Engarde can't read what our character is doing and therefore we can't use the dodges or power attacks correctly (without a custom solution). We have gotten around that issue by mapping key combos that, when pressed, press a directional keyboard key (W, A, S, and/or D) and the dodge or power attack key at the same time. This allows us to get past the limitations of Engarde when it comes to a controller, however...

### True Directional Movement

True Directional Movement (TDM) is the movement overhaul everyone wants to be using - and for good reason: it allows you to play Skyrim with a truly modern movement style. It also features a lock on feature (much like Dark Souls) that you will need to make extensive use of for this entire setup to really shine. 

### Engarde+True Directional Movement Together

So, with both mods put together, we have some issues. Firstly, because TDM changes how movement occurs, it messes with our Engarde setup. Since Engarde relies on strafing type movement to determine dodge and power attack direction and since TDM essentially puts your character into an "always moving forward" state, we won't be able to use our directional features from Engarde... UNLESS you are locked on! Once you lock on to enemies, all of the features of both mods come together and you can experience the full effect of both mods. So, when not locked on, it won't matter which directional dodge or power attack you try to use, you'll simply do the forward dodge or power attack. But that all changes when you lock on to your enemies. 

## Configuration In-Depth Explanation

These configurations were made possible by Steam's "shift modifier" and "action layer" options. What that means is this - While playing normally, you have the vanilla/default keybinds (for the most part). However, when you hold one of two modifiers, you get another set of new keybinds. I made both configurations virtually the same between PS4/5 and Xbox for ease of use. The two modifiers I make extensive use of are the LB & RB buttons on the Xbox controller and L1 & R1 for the PS4/5 controller. That means their vanilla/default functions have been remapped elswhere on the controller where it makes sense in order to free them up for modifier usage. These will be your main mode of switching your "focus."

With how many keybinds are necessary to fully utilize ultra-modded Skyrim, any gamepad setup can get quite complicated. With that being said, I have attempted to make this less daunting by having each modifier have a specific "focus." Here are the TWO main areas of "focus" that I built into the configurations:

#### Dodge Focus
-Holding L1/LB will bring up your directional dodges from engarde and your first set of 4 groups from SKYUI. The 4 groups are located on the directional buttons (left, right, up, and down) and the 4 dodges are located on your face buttons (PS4/5: Square, Circle, Triangle, and Cross) (Xbox: X, Y, B, and A). They were added to the controller in a way that maked sense to me - holding L1/LB and hitting Triangle/Y will give you a forward dodge. Holding L1/LB and hitting Square/X will give you your left dodge etc. 

#### Power Attack Focus
Holding R1/RB will bring up your directional power attacks from engarde and your last set of 4 groups from SKYUI. The groups are located on the directional buttons like before (left, right, down, and up) and the power attacks are located on the face buttons (PS4/5: Square, Circle, Triangle, and Cross) (Xbox: X, Y, B, and A). They were added to the controller in a way that maked sense to me - holding R1/RB and hitting Triangle/Y will give you a forward power attack. Holding R1/RB and hitting Square/X will give you your left power attack etc.

#### Gameplay & Controller Configuration Tutorial/Demo

I've created a video that may make it easier for you to understand how the controls work as you'll be able to see them in action. It is HIGHLY SUGGESTED you sit through the video to properly understand this control scheme. I know it's long, but it will help. (This video will be updated, for now consider it a work-in-progress.)

https://youtu.be/GMPVL1EfFv8


## Keybindings

This section will list out the keybinding setup for both controller configurations as a reference. For those of you that want to edit things - feel free to do so but know that you void any support in the Aldrnari support channel if you do. Also, keep in mind this setup was achieved with a combination of a custom controlmap.txt AND the steam configuration - that means you need to know how to edit both before you try and change things with any chance of success. Otherwise, this is probably all the official support you'll get for gamepads at all, so definitely pay attention.

### PS4/PS5:

I highly suggest you take a look at the configurations and familiarize yourself with the buttons. All have been labeled so you can easily see what button does what. They will also be listed for a comprehensive view of every keybind, but they will make more sense if you visualize them in the configuration. Make sure to switch between all three layers (Default, L1 Hotkeys and R1 Hotkeys). Keep in mind that while holding L1 or R1, any buttons that do not have a mapping listed here will perform the mapping from the default "layer" of the configuration.

![image](https://user-images.githubusercontent.com/89932487/133794142-8eb67c39-2dc2-4a31-9228-faeb6f06555f.png)

Default Keybinds (No Modifiers)                            
- L1 - Modifier Button & Left Shift 
- L2 - Left Hand
- R1 - Modifier Button
- R2 - Right Hand
- Dpad Left - Hotkey
- Dpad Down - Hotkey
- Dpad Right - Hotkey
- Dpad Up - Hotkey
- Square - Quick Heal
- Square (Long Hold) - Quick Magicka Potion
- Cross - Activate
- Circle - Sprint
- Triangle - Jump
- Left Stick Click - Ready/Sheath
- Right Stick Click - Lock On
- Right Stick Click (Hold for 0.25 seconds and then release) - Change POV
- Share (left side) - Wait 
- Start (right side) - System Menu
- Left Pad Click - Menu Sort Left
- Right Pad Click - Menu Sort Right

L1 Modifier Keybinds - This button must be held down for the following keybinds to work
- L1 + R1 - Shout/Power
- L1 + Dpad Left - Group 1
- L1 + Dpad Down - Group 2
- L1 + Dpad Right - Group 3
- L1 + Dpad Up - Group 4
- L1 + Square - Dodge Left
- L1 + Cross - Dodge Backwards
- L1 + Circle - Dodge Right
- L1 + Triangle - Dodge Forward
- L1 + Left Stick Click - Sneak
- L1 + Share (left side) - Immersive HUD Toggle 
- L1 + Start (right side) - Forceful Tongue Skill Menu (Shout Mod)
- L1 + Right Pad Click - Shoulder Cam Switch

R1 Modifier Keybinds - This button must be held down for the following keybinds to work
- R1 + R2 - Standing Power Attack
- R1 + Dpad Left - Group 5
- R1 + Dpad Down - Group 6
- R1 + Dpad Right - Group 7
- R1 + Dpad Up - Group 8
- R1 + Square - Left Power Attack
- R1 + Cross - Backwards Power Attack
- R1 + Circle - Right Power Attack
- R1 + Triangle - Forward Power Attack
- R1 + Select (left side) - ENB Lens Toggle
- R1 + Start (right Side) - ENB Screenshot
- R1 + Left Stick Click - Lichdom Mode Change

Campfire Actions (Hold Left Side Pad Button) - You must hold the Left Side Pad (LSP) Button for the following keybinds to work
- LSP + Square - Create Item
- LSP + Cross - Instincts
- LSP + Circle - Harvest Wood
- LSP + Triangle - Build Campfire

### Xbox:

I highly suggest you take a look at the configurations and familiarize yourself with the buttons. All have been labeled so you can easily see what button does what. They will also be listed for a comprehensive view of every keybind, but they will make more sense if you visualize them in the configuration. Make sure to switch between all three layers (Default, LB Hotkeys and RB Hotkeys). Keep in mind that while holding LB or RB, any buttons that do not have a mapping listed here will perform the mapping from the default "layer" of the configuration.

![image](https://user-images.githubusercontent.com/89932487/133794350-b206104c-76f7-443f-933b-8031bc13c566.png)

Default Keybinds (No Modifiers)                            
- LB - Modifier Button & Left Shift 
- Left Trigger - Left Hand
- RB - Modifier Button
- Right Trigger - Right Hand
- Dpad Left - Hotkey
- Dpad Down - Hotkey
- Dpad Right - Hotkey
- Dpad Up - Hotkey
- X - Quick Heal
- X (Long Hold) - Quick Magicka Potion
- A - Activate
- B - Sprint
- Y - Jump
- Left Stick Click - Ready/Sheath
- Right Stick Click - Lock On
- Right Stick Click (Hold for 0.25 seconds and then release) - Change POV
- Select (left side) - Wait 
- Start (right side) - System Menu

LB Modifier Keybinds - This button must be held down for the following keybinds to work
- LB + RB - Shout/Power
- LB + Dpad Left - Group 1
- LB + Dpad Down - Group 2
- LB + Dpad Right - Group 3
- LB + Dpad Up - Group 4
- LB + X - Dodge Left
- LB + A - Dodge Backwards
- LB + B - Dodge Right
- LB + Y - Dodge Forward
- LB + Left Stick Click - Sneak
- LB + Select (left side) - Immersive HUD Toggle 
- LB + Start - Forceful Tongue Skill Menu (Shout Mod)
- LB + Start (Long Hold) - Shoulder Cam Switch

RB Modifier Keybinds - This button must be held down for the following keybinds to work
- R1 + R2 - Standing Power Attack
- R1 + Dpad Left - Group 5
- R1 + Dpad Down - Group 6
- R1 + Dpad Right - Group 7
- R1 + Dpad Up - Group 8
- R1 + Square - Left Power Attack
- R1 + Cross - Backwards Power Attack
- R1 + Circle - Right Power Attack
- R1 + Triangle - Forward Power Attack
- R1 + Select (left side) - ENB Lens Toggle
- R1 + Start (right Side) - ENB Screenshot
- R1 + Left Stick Click - Lichdom Mode Change

Campfire Actions (Hold Left Side Pad Button) - You must hold the Left Side Pad (LSP) Button for the following keybinds to work
- LSP + Square - Create Item
- LSP + Cross - Instincts
- LSP + Circle - Harvest Wood
- LSP + Triangle - Build Campfire

## MCM & Control Settings

You're nearly there! We just need to change one vanilla keyboard control and setup the MCMs for our hotkeys to work correctly. 

### Vanilla Control Changes

You have but one key to change here, and that is to remap the command Run from "shift" to "Numpad."

### MCM Settings

It is imperative that you map all keys exactly as they are in this guide! The configurations were built around these specific keybinds, so if you change any of them, you'll have to change the Steam Controller Configurations as well. 

#### Campfire
- Gameplay
  - Hotkeys
    - Create Item - N
    - Build Campfire - B
    - Harvest Wood - H
    - Instincts - G

#### Engarde
- KeyButton
  - Power Attack Key - ]
  - Defensive Action Key - \

#### Follower Framework
- Activity
  - Catch Up (Teleport) 
    - Teleport Followers Hotkey - Numpad 7
  - Waiting
    - Followers Wait/Follow Key - Numpad 5
- System
  - Follower Action Keybinds
    - Command Followers - Numpad 1
    - Followers Attack - Numpad 4
    - Followers Retreat - Numpad 2
    - Calm Followers - Numpad 3
    - Followers Behind You - Numpad 6
    - Trade Items - Numpad 8

#### Forceful Tongue
  - Dragonborn Skill Menu Hotkey - ;

#### Immersive Hud
  - Activation
    - Compass Activation
      - iHUD Hotkey - X

#### Optimal Potion Hotkey
  - Hotkeys
    - Health Potion Hotkey - , (That is this key (<) for those unsure)
    - Magicka Potion Hotkey - . (That is this key (>) for those unsure)
    - I did not add in the stamina potion hotkey because I never use it and there is limited real-estate to work with as it is... If you want it you'll have to add it in yourself.

#### SkyUI
  - Controls
    - Favorite Groups
      - Group 1 - F1
      - Group 2 - F2
      - Group 3 - F3
      - Group 4 - F4
      - Group 5 - F6
      - Group 6 - F7
      - Group 7 - F8
      - Group 8 - F10
      - Be careful not to map F5 or F9 here, we want to keep those free as they are quick-save and quick-load. 

#### SmoothCam
  - Following
    - Misc
      - Shoulder Swap Key - V

#### True Directional Movement
  - Target Lock
    - Controls
      - Toggle Target Lock Key - Numpad /
      - Ensure that you do NOT have "Toggle Target Lock with Toggle POV Button" selected. 
      - I also personally go into the Target Lock Widget and make the lock on UI a simple dot and scale it down. That is, of course, up to you. 

### Remaining Free Keybinds

There are still quite a few keys on your keyboard left for possible hotkey use. You have the entire numbers line (not the numpad, most of those are being used) as well as the following keys: O, U, Y, K, and L. That should be more than enough. Unfortunately, if you want to use any hotkeys beyond what I've built into the configurations, you'll have to add them in yourself. Support for this endeavor will not be provided. Fortunately, it isn't very hard to figure out with a little time and effort.

## Final Tips

While this setup has worked well in my testing, there are a few quirks that can and will occur. During my testing they did not hamper or stop my gameplay. I will attempt to address them all as I have encountered them.

#### Engarde Spellsword Tips

If you love playing spellswords like I do, then this is vital for you to read through. I have mapped left shift to your L1/LB modifier button. That means it acts as both the modifier to change controls AND as your modifier in Engarde for using your left hand while wielding a sword in the right. All you have to do to cast your spells is hold L1/LB and start casting. You don't have to hold it the entire time, once you get the spell going, you can release L1/LB. If you want to free aim your spell, you'll need to let go of the L1/LB button after you get the spell going as for some reason, using the Engarde modifier stops you from being able to move your camera. However, if you want to rapid fire cast something (like Ice spike) it helps to lock on and then simply hold L1/LB and spam your left trigger to fire off spells until you need your right hand weapon. 

#### Dodging Quirks

If you never use lock on from True Directional Movement, you will never be able to use the directional dodging feature. When you press any of the dodge directions, you will simply dodge/slide/roll in the direction you are moving. This can be useful if you switch back and forth between locking on and not locking on. It is not a bug though, so don't ask in support as if it is. Also, I have found it unreliable to roll dodge by mashing the dodge key as you would in keyboard and mouse mode. As such, I do not rely on it. Feel free to explore it's usage more though. Perhaps you will have a different experience than me. 

#### Power Attack Quirks 

Power attacks work and function in much the same way as the dodge does - when not locked on, you will only ever get the forward power attack or the standing power attack depending on if you use the directional power attack hotkeys or the standing power attack hotkey (Duh). Also, I have found that, rarely, my character will get "stuck" doing the same power attack despite pressing different power attack hotkeys. This can be fixed by sprinting and/or using a standing power attack. It *seems* to me that this is a vanilla Skyrim foible, as such, please do not ask about it in support. 

#### SkyUI Favorites & Groups

If you're like me, you've never used the hotkeys provided by SkyUI. Well, if you want to really have fun, you need to change that up. I learned about them for the first time myself while I built these configurations. I have found them to be an amazing replacement for the somewhat script heavy Serio's Hotkeys that I use to use in every list. If you are unsure how the groups work, watch this [SkyUI Favorites & Groups Tutorial](https://youtu.be/FSrwmH4_dJM). Now that you understand how they work, you can fully utilize the 8 groups you have available from these configurations. You never have to pause during combat again, it really is amazing. 

Here are some tips I have for utilizing those groups on your 8 directional pad hotkeys. I tend to keep a theme on specific directional pad buttons. For example, the down directional pad button is easy to get to when you're in combat, so I tend to map healing spells there on the first layer (thats group 2 while just holding L1/LB) and then I use the second layer as buffs which is group 6 (while holding L1/LB + R1/RB). Then I keep offensive magic on the two left directional pad hotkeys I have and utility spells for the up directional pad hotkeys. That leaves me with two slots on my right directional pad keys for two different groups of whatever I want (perhaps swords, bows etc...). Additionally, you have two quick access hotkeys when not holding down ANY modifiers (as in, just playing normally) - the left direction key and right direction key. I use these for two quick access shouts or powers so I can... well, switch between them quickly. You have to map them in your favorites menu though. All you have to do is press either left or right on the item/spell/power/shout you want mapped and it'll map to that button. 

If you take the time to understand how these systems and features work, you will reap the benefit when you actually get around to playing the game.

#### Extended Hotkey System

While this mod provides a great amount of freedom, I am, in truth, not utilizing much of it in this guide. However, if you feel you need more hotkeys than I have provided, feel free to add as many as you want and add as many layers to your steam configuration as you would like. I feel 8 groups plus 2 quick access hotkeys is more than enough for most, including me. As I've stated before though, if you venture off beyond the scope of this guide, please do not ask for support in the support channel. Sovn has enough to manage as it is. 

#### You're Done! Have Fun!

#### Special Thanks
Thanks for making this awesome list Sovn!









