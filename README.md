<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/5001c565-9f07-48e4-a331-bf17f92cb044" />


https://github.com/user-attachments/assets/202e4cdc-49b5-46fe-b89e-6022b0fb5c66

# BeamMP Dynamic Zone (Circle of Death)

A robust, synchronized multiplayer shrinking zone script for BeamMP. Designed for server hosts to run competitive events like Sumo, Derby, or Last Man Standing.

## 🚀 Features
* **Real-time 3D Visualization:** A semi-transparent red cylinder marks the safe zone for all players.
* **Network Synchronized:** Fully synchronized across all clients synchronization ensures the zone is in the exact same spot for everyone.
* **On-Screen UI:** Integrated notifications in the top-left corner keep players updated on zone status and warnings.
* **Smart Elimination:** Automatically triggers vehicle failures (engine, tires, structural damage) when players leave the boundary.
* **Players Friendly:** Easy to use commands without needing to restart the server or edit files mid-game.

---

## 🛠 Installation

1. Go to the **[Releases]** section on the right and download the latest `.zip` file.
2. Extract the contents.
3. Place the `Client` folder contents into your server's `Resources/Client` directory.
4. Place the `Server` folder contents into your server's `Resources/Server` directory.
5. Restart your server or use `/refresh` (if applicable).

---

## 🎮 Admin Commands

| Command | Description |
| :--- | :--- |
| `/setzone [radius]` | Spawns the zone at your position with the given radius. |
| `/setzonespeed [speed]` | Sets the shrinking speed (meters per second). |
| `/setzonelimit [radius]` | Sets the minimum radius where the zone stops shrinking. |
| `/stopzone` | Instantly removes the zone and stops all logic. |

---

## 💡 How to run an event
1. Drive to the center of the arena.
2. Type `/setzone 150` to create a large boundary.
3. Once everyone is ready, type `/setzonespeed 0.5` to start the shrink.
4. The script handles the rest!


https://github.com/user-attachments/assets/0172b626-bf0f-46bb-a790-dfe8b20c5c26


---

## License
Distributed under the **MIT License**. See `LICENSE` for more information.

## 🔮 Future Plans
- Custom zone shapes (square, polygon)
- Multiple zones
- UI improvements
  
## Support
If you enjoy this script, consider supporting my work on [Patreon](https://www.patreon.com/c/Kengar) Support is entirely optional!
