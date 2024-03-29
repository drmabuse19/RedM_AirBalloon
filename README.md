# Hot Air Balloon Spawn Script for RedM

This script enables players in a RedM server to spawn and delete a hot air balloon dynamically at specific locations on the map. It adds an immersive element to the gameplay, allowing players to explore the world from the skies in a leisurely manner. The script also provides basic controls for maneuvering the balloon in flight.

## Installation

1. **Clone the Repository:** Begin by cloning this repository to your local machine or directly into your server's resources directory.

    ```
    git clone https://your-repository-link.git
    ```

2. **Server Configuration:** Move the cloned project into your server's `resources` directory if you haven't already done so. Then, add the following line to your server's `server.cfg` file to ensure the resource is started with the server:

    ```
    start hot_air_balloon_spawn
    ```

3. **Script Dependencies:** Ensure you have the latest version of FiveM and all necessary dependencies installed on your server for this script to run smoothly. This script requires no external resources or libraries.

## Usage

- **Spawning the Balloon:** To spawn the hot air balloon, players must navigate to the coordinates `1423.25, -1309.64, 79.9`. Upon arrival, a prompt will appear instructing them to press `G` to spawn the balloon.
  
- **Deleting the Balloon:** To delete the balloon, players should be in a flying vehicle and navigate to the coordinates `1453.61, -1338.74, 83.84`. A prompt will appear, instructing them to press `G` to delete the balloon.

- **Maneuvering the Balloon:** Once in the air, players can control the balloon's movement using the `W`, `A`, `S`, and `D` keys to move forward, left, backward, and right, respectively.

## Acknowledgments



- **Contributors:**
- Neo Green - https://github.com/WolfPack-Gamin/wcrp_baloon
---

For any issues or contributions, please open an issue or a pull request on the repository. Enjoy exploring the skies!
