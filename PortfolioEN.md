- [Glitch](#glitch)
- [Claws](#claws)
- [TransHarmony](#transharmony)

# Glitch
<p align="center">
  <img id="logoGlitch" src="IMG/Glitch/Logo.png" height=256 width=height>
</p>

- Unreal Engine 4 Project - C++ and Blueprint
- Team of 6 person
- 3C and IA Programmer
- Octobrer 2022 - June 2023

> Glitch is a Tower Defense and Stealth game on PC where the player embodies a character to the 3rd person view. That character evolves within a medieval world corrupted by a strange void. Fighting this corruption generates singularities in the whole world. Players will have to progress quietly inside the corrupted world to identify key structures and capture them to bring back the world as it was. When the player finds his exploration is enough, he shall survive from multiple enemies incomming by creating his own defenses.

I coded every 3C and AI features of the game.

The Glitch Dash mechanic, a kind of teleportation towards a defined point in advance by the player.  
This is simply a linear interpolation of two locations. Everything the player will pass through during the dash will increase a gauge (named glitch gauge) which will impacts on differents elements such as enemies or turrets.  
![GlitchDash](IMG/Glitch/GlitchDash.gif)

In Glitch to defend against enemies waves, the player must place traps and turrets. Theses two elements inherit from the same base class named "PlacableObjects", and every turret and trap has their own class with their own behavior. The object placement is done in pre-defined areas.  
![TurretsPlacement](IMG/Glitch/TurretsPlacement.gif)

AI follow a main path (in blue) which guide them towards the structure the player must defend. But they can move everywhere, especially to follow the player if they enter in their sight. If the AI is close enough of the player, they attacked them.  
![AIMovement](IMG/Glitch/AIMovement.gif)

- [Trailer](https://youtu.be/VLsZSiRM8KA)  
- [Download Glitch](https://github.com/MichenaudMelvin/Glitch/releases/latest)  
- [Glitch repository](https://github.com/MichenaudMelvin/Glitch)  

# Claws
<p align="center">
  <img id="logoClaws" src="IMG/Claws/Logo.png" height=256 width=height>
</p>

- Unreal Engine 4 Project - Blueprint only
- Team of 5 person
- 3C and IA Programmer
- March 2022 - June 2022

> Claw is a survival horror on PC where we play as a hiker who ventures into an unreferenced cave in which he discovers dilapidated scientific buildings. However, a monstrous entity inhabits the place and will hunt him down at the slightest noise. He will have to find a way to escape you alive.

I mostly coded the AI of the game, who is a blind creature but own an overdeveloped hearing. The AI ​​therefore had to react to the sounds of the game and the player. I used the native AIPerception component from UE4.  
![AIPerception](IMG/Claws/AIPerception.gif)

- [Download Claws](https://github.com/MichenaudMelvin/Claws/releases/download/Beta/Claws.zip)  
- [Claws repository](https://github.com/MichenaudMelvin/Claws)  

# TransHarmony

<p align="center">
  <img id="logoTransHarmony" src="IMG/TransHarmony/Logo.png" height=256 width=height>
</p>

- Unity Project - C#
- Team of 8 person
- UI Programmer
- 2 Weeks

> TransHarmony is a management mobile game executed in partnership with the french festival of the [TransMusicales](https://www.lestrans.com/). We play the organizers of the festival, their goals is to meet the needs of different artists so that their concerts go as smoothly as possible. The gameplay is simple, to meet a need just drag and drop an icon on the need of the artist.

![MainScene](IMG/TransHarmony/MainScene.png)

- [Download TransHarmony](https://github.com/MichenaudMelvin/TransHarmony/releases/download/EdulabPresentation/TransHarmony_PC.zip)  
- [TransHarmony repository](https://github.com/MichenaudMelvin/TransHarmony)  
