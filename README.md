# Oil-Knight
Mini Jam 159: Ocean

[Play now on itch.io](https://sourcecodesorcerer.itch.io/oil-knight)

Author: Timothy Johnson <br>
Date: May 23, 2024 to May 26, 2024

Explore the depths of a polluted sea as a cybernetic knight equipped with an oil-blasting laser.
Clean up environmental disasters, navigate platforming challenges, and restore life to the ocean—one blast at a time.

## Overview

&nbsp;&nbsp;&nbsp;&nbsp;Oil Knight is a 2D platformer created in Godot 4 for Mini Game Jam under the theme “Ocean.”
You play as a deep-sea knight tasked with restoring the ocean from deadly oil spills.
Armed with a pressurized oil laser, you explore underwater caverns, dodge sea creatures, and purify contaminated areas in this pixel-art platformer.

🌊 Game Jam Theme Integration

The Ocean theme is central to the game’s setting and mechanics:

    The player swims through underwater caverns and coral reefs

    Oil spills and sludge clouds pollute the environment

    Using your oil laser blaster, you “clean” areas to progress

    Oceanic wildlife and wreckage form the primary hazards and platforming elements

🧩 Features

    🧜‍♂️ Fluid underwater platforming movement with swimming mechanics

    🔫 Oil Blaster mechanic to clean up pollution and interact with the environment

    🧱 Level progression tied to environmental cleanup

    🐠 Ambient underwater zones with parallax and pixel-art visuals

    🎮 Full controller and keyboard support

    🌌 Pixel-art HUD showing oxygen, oil meter, and cleanup progress

🎮 Gameplay

You dive into the ocean depths, navigating caverns while cleaning toxic spills using your oil laser.
Each level contains polluted zones that must be fully cleaned to unlock the path forward. You’ll balance exploration, platforming precision, and shooting accuracy—all while keeping your oxygen and oil levels in check.

### Controls:

| Key        | Action      |
| ---------- | ----------- |
| ← / A      | Turn Left   |
| → / D      | Turn Right  |
| Space      | Jump / Swim |
| Mouse      | Aim         |
| Left Mouse | Aim         |
| Esc        | Quit        |

📁 Code Structure

. <br>
├── main.tscn &nbsp;&nbsp;&nbsp;---&nbsp;&nbsp;&nbsp; Main scene with game loop and HUD <br>
├── player.gd &nbsp;&nbsp;&nbsp;---&nbsp;&nbsp;&nbsp; Player movement, swimming, and oil laser code <br>
├── oil_area.gd &nbsp;&nbsp;&nbsp;---&nbsp;&nbsp;&nbsp; Pollution cleanup zone logic <br>
├── laser_beam.gd &nbsp;&nbsp;&nbsp;---&nbsp;&nbsp;&nbsp; Oil blaster laser behavior <br>
├── ui/ &nbsp;&nbsp;&nbsp;---&nbsp;&nbsp;&nbsp; Oxygen + cleanup progress bars <br>
├── levels/ &nbsp;&nbsp;&nbsp;---&nbsp;&nbsp;&nbsp; Tilemaps and level scenes <br>
├── res/ &nbsp;&nbsp;&nbsp;---&nbsp;&nbsp;&nbsp; Sprites, audio, and background assets <br>
│   ├── knight.png <br>
│   ├── oil_splash.png <br>
│   ├── background_layers/ <br>
│   └── pollution_zones/ <br>


⚙️ How It Works

    Player Movement: Uses custom swimming physics in water with jump/dive support

    Oil Cleanup: The player aims and fires a laser beam that cleans toxic tiles or areas on contact

    Level Progression: Once a cleanup threshold is met, a gate or exit becomes available

    HUD: Tracks oxygen (air supply), oil energy, and cleanup progress

    Enemies (optional): Creatures react to pollution zones, adding challenge in late levels
    
🖼️ Screenshots / Visuals

![oilknightbanner](https://github.com/user-attachments/assets/a7eb4dea-8ac6-4539-8cf4-479c2202053f)

🧰 Technologies Used

    🧠 Godot

    🎨 Custom 2D pixel-art assets

    🕹️ Controller and keyboard support

    🎧 Environmental SFX using built-in AudioStreamPlayer nodes

    🔥 Laser raycasting for interactive cleanup zones

🚀 Getting Started

    To play locally:

    1. Clone this repository

        git clone https://github.com/MrTimmyJ/oil-knight.git
        cd oil-knight

    2. Open in Godot :

       Launch the Godot editor and open the project folder.

    3. Run the game
    
       Click "Play Scene" to start the game.

🌱 Future Improvements

    🧭 Minimap or sonar system for level layout

    🐋 Marine wildlife NPCs you can help rescue

    🧪 Hazardous enemies like oil-mutated eels

    💾 Save/load progress between levels

    🎬 Animated intro + ending cutscene

🪪 License

This open-source project is available under the [MIT License](https://opensource.org/license/mit).

