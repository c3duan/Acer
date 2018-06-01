# Acer
First Ever Unity Game build by following the online tutorial


# Task
1. Setting up the Scene
2. Game Logic

# Scene
- Canvas (UI Game Object)
  * Score (Text)
  * Restart (Text)
  * GameOver (Text)
- Background (Parent Empty Carrior Game Object)
  * Background (Mesh Render Game Object)
- Player (DIY Game Object)
  * Engines_player (Library Object)
  * Shot Spawn (Carrior Game Object for light bolts)
- StarField (Background Visual Game Object)
  * part_starField
  * part_starField_distant
- Game Controller (Game Logic Object)
- Main Camera (Build in Camer Setting)
- Lighting (Parent Empty Carrior Game Object)
  * Fill Light (filler)
  * Main Ligth (front)
  * Rim Light (around)
- Event System (Empty Build in Object)

# Scripts
- BGScroller.cs
- DestroyByBoundary.cs
- DestroyByContact.cs
- DestoryByTime.cs
- GameController.cs
- Mover.cs
- PlayerController.cs
- RandomRotator.cs
- WeaponController.cs

# Prefabs
- Asteroid 1
- Asteroid 2
- Asteroid 3
- Bolt_Player
- Bolt_Enemy
- Enemy_Vehicle
- Player_Vehicle

# Screenshots of GamePlay
- In Game Demo:
<img width="465" alt="screen shot 2018-06-01 at 1 10 29 pm" src="https://user-images.githubusercontent.com/33473131/40861854-661de16a-659f-11e8-83ea-66dd77352734.png">
- Game Over:
