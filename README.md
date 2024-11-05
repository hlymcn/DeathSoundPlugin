# DeathSoundPlugin
## Overview
DeathSoundPlugin is an innovative plugin designed for Counter-Strike 2 servers that enhances the gaming experience by playing a custom sound whenever a player dies. This plugin is currently in its early beta phase, offering a unique feature that adds an auditory dimension to the game, making it more immersive and engaging for players.

## Features
Customizable Death Sounds: The plugin allows server administrators to define a list of custom sounds that play upon a player's death, adding a new layer of realism and excitement to the game.
Random Sound Playback: Each time a player dies, the plugin randomly selects a sound from the configured list, ensuring variety and unpredictability.
Team Color Chat Messages: The plugin supports team-colored chat messages, making it easier for players to identify messages related to their team.
## Usage
To utilize the DeathSoundPlugin, follow these simple steps:

### Installation
Download the plugin from the GitHub repository and place it in the appropriate directory on your server.
### Configuration
Set up the plugin by configuring the DeathSounds list in the plugin's configuration file with the paths to your custom sound files.
### Activation
Once installed and configured, the plugin will automatically play a random death sound for each player death event.
## Requirements
[CounterStrikeSharp](https://github.com/roflmuffin/CounterStrikeSharp)

[MetaMod](https://www.metamodsource.net/downloads.php?branch=dev)

.NET 6.0 or higher
## Installation
Clone the repository or download the latest release from GitHub.
Copy the plugin files to your server's plugin directory.
Configure the plugin settings to match your server's requirements.
## Contribution
We welcome contributions from the community. If you have any ideas or find any issues, please submit a pull request or open an issue on the GitHub repository.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Developer Notes
The plugin is currently in its early beta phase, and we encourage users to provide feedback and report any issues they encounter. The plugin uses the IStringLocalizer interface for localization support, allowing for easy translation into different languages.
