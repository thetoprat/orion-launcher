# Orion Launcher

![Orion Launcher Screenshot](https://github.com/user-attachments/assets/108edb8d-38c2-4861-bd04-708052100c12)

A custom mod launcher for **The Isle (Evrima)** designed to make finding, installing, managing, and playing with mods easier.

> # ⚠️ Disclamer
> This is designed for unofficial use. Easy Anti-Cheat is disabled. You will only be able to play on community servers that disable EAC or adjust settings accordingly.
> We are not responsible for any damages or harm that you cause. Nor are we responsible for any in-game actions taken for the use of this application.
> You are not likely to get banned, just don't find ways to use this to join an official server! 

## Features

* **Mod Discovery:** Browse and search for mods hosted on the official Orion Launcher GitHub repository.
* **Easy Installation:** Download and install mods directly from the launcher with a single click (supports both directory-based mods and direct `.orionmod` files).
* **Local Mod Support:** Install mods from local `.orionmod` files using the "Add Mod" button.
* **Mod Management:** Enable or disable installed mods individually using simple toggles.
* **Update Notifications:** See when installed mods have updates available (based on GitHub repository).
* **One-Click Launch:** Launches The Isle with your enabled mods correctly loaded and injected.
    * Handles necessary file placements (Paks, DLLs).
    * Manages EAC (Easy Anti-Cheat) configuration automatically during launch.
* **Live Game Console:** View filtered game output directly within the launcher while playing.
* **Developer Mode:**
    * Access tools for mod creation.
    * **Create Mod:** Package your own mod files (assets, paks, source DLLs) into the `.orionmod` format for easy distribution.

## Installation

1.  Go to the [**Releases**](https://github.com/thetoprat/orion-launcher/releases) page of the Orion Launcher GitHub repository.
2.  Download the latest `Orion-Launcher-Setup-X.Y.Z.exe` file (where X.Y.Z is the version number).
3.  Run the downloaded installer and follow the on-screen prompts.

## Usage

**1. Initial Setup (First Launch):**

* The launcher may try to automatically detect your The Isle installation path.
* If it cannot find it, or if the path is incorrect, the "PLAY" button will be replaced with a "Set Game Path" button. Click it, or go to **Settings** (gear icon top-right), click "Change", and navigate to your main The Isle game directory (e.g., `C:\Program Files (x86)\Steam\steamapps\common\The Isle`).
* Once the path is set correctly, the "PLAY" button will appear.

**2. Managing Mods (Mods Tab):**

* Click the **Mods** tab.
* Browse the list of available mods. You can use the search bar to filter by name, description, etc.
* **Download/Install:** Click the "Download" button on a mod you want to install. If an update is available for an installed mod, the button will show "Update".
* **Add Local Mod:** Click the "Add Mod" button (top-right of the Mods tab) to select an `.orionmod` file from your computer to install it.
* **Enable/Disable:** Use the toggle switch next to each installed mod to enable or disable it for the next launch. The count of currently enabled mods is shown below the "PLAY" button on the Play tab.
* **Options:** Click the vertical dots (...) button on an installed mod to "View Directory" (opens the folder containing the `.orionmod` file) or "Uninstall" the mod.

**3. Launching the Game (Play Tab):**

* Ensure the mods you want to use are enabled in the Mods tab.
* Go to the **Play** tab.
* Click the large **PLAY** button.
* The view will switch to the **Live Console**, showing launch progress, mod injection status, and game output.
* The Isle will launch.

**4. Stopping the Game:**

* While the game is running (and the console view is active), click the red **Stop Game** button in the top-right corner of the console view to forcefully close the game client.

**5. Developer Mode:**

* Click the **Settings** icon (gear).
* Toggle the **Developer Mode** switch on.
* A new **Developer** tab will appear in the main navigation.
* **Create Mod:** Click the "Create Mod" button on the Developer tab to open the packaging tool. Fill in the details, add your mod's assets, paks (.pak, .cas, .utoc), and source (.dll) files, then click "Generate .orionmod" to create the distributable file.

## License

ARR License
