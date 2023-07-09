- [Glitch](#glitch)
- [Claws](#claws)
- [TransHarmony](#transharmony)

# Glitch
<p align="center">
  <img id="logoGlitch" src="IMG/Glitch/Logo.png" height=256 width=height>
</p>

- Projet Unreal Engine 4 - C++ et Blueprint
- Équipe de 6 personnes
- Gameplay Programmer 3C et IA
- Octobre 2022 - Juin 2023

> Glitch est un tower defense - infiltration sur PC dans lequel le joueur incarne un personnage à la 3ᵉ personne qui évolue au sein de son monde médiéval corrompu par un vide étrange.
Le combat entre cette corruption et ce monde engendre des singularités affectant tout l’univers. Le joueur devra ainsi progresser en s'infiltrant au sein du territoire corrompu, pour identifier les infrastructures clés et les capturer. Lorsque le joueur décidera que son objectif est rempli, il devra survivre aux vagues ennemies qui lui seront opposées en générant ses propres défenses.

J'ai codé toutes les fonctionnalités de l'avatar et des IA du jeu.

La mécanique du Glitch Dash, une sorte de téléportation vers un point défini au préalable par le joueur.  
Il s'agit simplement d'une interpolation de positions. Tout ce que le joueur va traverser au cours de ce dash fera augmenter une jauge (nommée jauge de glitch) qui aura des impacts sur différents éléments comme les ennemis ou les tourelles.  
![GlitchDash](IMG/Glitch/GlitchDash.gif)

Dans Glitch pour se défendre contre les vagues ennemis, le joueur va devoir placer des pièges et des tourelles. Ces deux éléments héritent d'une même classe "PlacableObjects", et chaque Tourelle et piège ont leurs propre classe avec leurs propre comportement. Le placement des objets se fait sur des zones pré-définies.  
![TurretsPlacement](IMG/Glitch/TurretsPlacement.gif)

Les IA suivent un chemin principal en bleu qui les guident vers la structure que le joueur doit défendre. Mais elles peuvent se déplacer partout, notamment pour suivre le joueur si il entre dans leurs champs de vision. Si les IA se rapprochent trop du joueur, elles l'attaquent.  
![AIMovement](IMG/Glitch/AIMovement.gif)

- [Télécharger Glitch](https://github.com/MichenaudMelvin/Glitch/releases/latest)  
- [Repository de Glitch](https://github.com/MichenaudMelvin/Glitch)  

# Claws
<p align="center">
  <img id="logoClaws" src="IMG/Claws/Logo.png" height=256 width=height>
</p>

- Projet Unreal Engine 4 - Blueprint uniquement
- Équipe de 5 Personnes
- Gameplay Programmer 3C et IA
- Mars 2022 - Juin 2022

> Claws est un survival horror sur PC où l'on incarne un randonneur qui s'aventure dans une grotte non référencée dans laquelle il découvre des bâtiments scientifiques délabrés. Cependant, une entité monstrueuse habite les lieux et le traquera au moindre bruit. Il devra trouver un moyen de vous échapper vivant.

J'ai principalement codé l'IA du jeu, qui est une créature aveugle mais qui possède une ouïe surdéveloppée. L'IA devait donc réagir aux sons du jeu et du joueur. J'ai utilisé le composant natif AIPerception d'UE4.
![AIPerception](IMG/Claws/AIPerception.gif)

- [Télécharger Claws](https://github.com/MichenaudMelvin/Claws/releases/download/Beta/Claws.zip)  
- [Repository de Claws](https://github.com/MichenaudMelvin/Claws)  

# TransHarmony

<p align="center">
  <img id="logoTransHarmony" src="IMG/TransHarmony/Logo.png" height=256 width=height>
</p>

- Projet Unity - C#
- Équipe de 8 personnes
- Gameplay Programmer UI
- 2 Semaines

> TransHarmony est un jeu mobile de gestion réalisé en partenariat avec le festival des [TransMusicales](https://www.lestrans.com/). On y incarne les organisateurs du festival, leurs but est de répondre aux besoins des différents artistes pour que leurs concerts se déroulent au mieux. Le gameplay est simple, pour répondre à un besoin il suffit de faire glisser une icône sur le besoin de l'artiste.

![MainScene](IMG/TransHarmony/MainScene.png)

- [Télécharger TransHarmony](https://github.com/MichenaudMelvin/TransHarmony/releases/download/EdulabPresentation/TransHarmony_PC.zip)  
- [Repository de TransHarmony](https://github.com/MichenaudMelvin/TransHarmony)  
