## This project is currently in closed beta.  
A public playable version will be released once the essential features are added and the main bugs are fixed.

---

<p align="center">
<img width="2000" height="500" alt="Logo" src="https://github.com/user-attachments/assets/ffae82f7-5719-4c49-90e8-4d8ef3c31e49" />
</p>



**Road to Temehani** is a game I developed by following the paid course **[Formation Créateur de Jeux Vidéo Pro sur Unreal Engine 5](https://www.gamedevteacher.fr)** (French course), which guides students through the process of making this game.

I took creative liberties with the course content, adding and tweaking several elements, and plan to expand the game with around ten levels, mini-games, and new gameplay features.  

The game is currently only playable in French. However, this is not a big issue as only the menus contain text.

⚠️ Since this project originates from a paid course, I am **not allowed to share the source code**, as doing so could compromise the integrity of the course.

---

<p align="center">
  <img src="https://github.com/user-attachments/assets/91b78003-8534-405a-bd73-1336faa3e067" width="1000" alt="RoadToTemehani-Win64-Shipping_ohRcF0UZBV" />
</p>

| ![Screenshot 1](https://github.com/user-attachments/assets/ecd04e32-7aab-4e0f-866b-afa276ed1e0b) | ![Screenshot 2](https://github.com/user-attachments/assets/b854b641-bc26-45ed-aed3-582884142001) |
|---|---|
| ![Screenshot 3](https://github.com/user-attachments/assets/f9d5fa52-626d-4f5c-a477-6c0955f15612) | ![Screenshot 4](https://github.com/user-attachments/assets/4355ffca-c1c4-4f05-94fa-4077fb4402cc) |
| ![Screenshot 5](https://github.com/user-attachments/assets/c351643e-64b3-4469-9177-f1427b7ba799) | ![Screenshot 6](https://github.com/user-attachments/assets/2d598db7-424f-4806-8815-e204adc21567) |

<p align="center">
  <img src="https://github.com/user-attachments/assets/212a2524-8361-4db3-b913-5b26b4ac4d90" width="1000" alt="UnrealEditor_3pabmcjnsy" />
</p>

---

# To-do
- Add a button to show the HUD
- Add more particles, effects, sounds, and camera shakes to interactions
- Implement saving (+ level selection)
- Make entities be able to cast shadows
- Create adventure levels (new enemies + mini-games)
- Add ultra-wide support
- Add Discord integration
- Add multiple languages options
- More stuff I'll find down the road

# Known Issues

#### Gameplay / Player Mechanics
- Jumping just before landing and quickly switching between the glide and fall states causes the player to use the idle animation instead of the jump animation.
- Killing a stunned enemy does not stop the stun audio.
- Performing a ground pound can make the player invisible to damage from the side.
- Attacking a fast charging bird might still damage the player unexpectedly.
- Camera movement speed does not adjust according to the player's speed.

#### Enemy Behavior
- Enemies may change their next patrol point immediately after being hit.

#### UI / Menu
- Hovering near the edge of a button causes it to jitter.
- HUD animations continue to play even when the game is paused.
