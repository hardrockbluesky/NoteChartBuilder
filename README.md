# NoteChartBuilder

Unreal Engine 5 project to make note charts for my PS1 rhythm game.

Unreal is owned by Epic, but all of the code/scripting exclusive to this project is [licensed under MIT](License.txt).

Bambi.wav is available in the main BKBS repo and is not included in the MIT License.

# Dependencies
Unreal Engine 5 Editor

[Victory Plugin](https://github.com/EverNewJoy/VictoryPlugin) for writing the CSV.

# Usage
Open the project in the Unreal Editor and place your song in the Song slot on the BP_SongChart placed in the default level. Output file defaults to BambiCSV.txt.

# Controls
* Pressing preview in Editor starts the song playing.
* Arrow keys while the song is playing generate arrows [may not show up until next time you hit preview]
* Spacebar pauses and selects the nearest note line
* 1-2-3-4 on the main keyboard add or remove notes on the selected line
* While paused, Page Up and Page Down jump to nearest lines with notes on them
* Z and X fast forward and reverse

99% of the code and comments are in BP_SongChart, including the controls.

# Preview

https://github.com/hardrockbluesky/NoteChartBuilder/assets/38575131/4a941631-759c-4b15-8880-fe933ae7ad5a

