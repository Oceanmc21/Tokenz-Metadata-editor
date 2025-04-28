# Tokenz' Metadata-editor

## Overview
Tokenz' Metadata-editor is an advanced tool for modifying string data in Unity IL2CPP games. This tool allows you to edit the `global-metadata.dat` file found in Unity games, enabling various modding capabilities including text translations, UI modifications, and game behavior alterations.

## Key Features

### Core Functionality
- **String Editing**: Modify any text strings in the game's metadata
- **Search Capability**: Quickly find specific strings using the search function
- **Modern UI**: Clean, intuitive interface with customizable themes
- **Backup System**: Automatically creates backups before making changes

### Game Modding Features
- **Mod Menu Creator**: Generate in-game mod menus by modifying specific strings
- **Item Injection**: Add new items or modify existing ones in supported games
- **Text Replacement**: Change game text for translations or customization
- **UI Element Modification**: Alter UI text and potentially behavior

### Advanced Features
- **Discord Bot Integration**: Control game modifications remotely via Discord
- **Batch Processing**: Apply multiple string changes at once
- **Export/Import**: Save your modifications for sharing or future use

## Getting Started

### Basic Usage
1. Click **Load** to open a `global-metadata.dat` file
2. Browse and search for strings you want to modify
3. Double-click any string to edit it
4. Click **Save As** to save your changes to a new file
5. Replace the original file in your game with the modified version

### Creating Game Mods
To create a mod menu or inject items:
1. Search for strings related to UI elements or item names
2. Modify these strings to include your custom menu options or items
3. For more complex mods, identify and modify strings that control game behavior

### Discord Bot Integration
1. Go to **Settings > Discord Integration**
2. Enter your Discord bot token and server ID
3. Configure the commands you want to enable
4. Start the bot to enable remote control of the application

## Technical Information

The `global-metadata.dat` file in Unity IL2CPP games contains all the strings used in the game code. This tool allows you to modify these strings without needing to decompile or modify the game's core executable files.

The tool works by:
1. Reading the metadata file structure
2. Identifying string literals and their offsets
3. Allowing modification of these strings
4. Writing changes back to the file while maintaining proper structure

## Credits

- Based on research from [Il2CppDumper](https://github.com/Perfare/Il2CppDumper)
- Special thanks to the game modding community for testing and feedback
