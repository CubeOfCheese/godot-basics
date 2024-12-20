---
heroImage: /src/assets/images/macos.jpg
category: Tutorial
description: How to export your godot game to MacOS
pubDate: 2024-10-19T07:00:00.000Z
tags:
  - Exporting
  - macOS
  - mac
title: How to Export a Godot Game to MacOS
---

# Set up Exports

(You should only need to do this section once for your first game)

1. Go to the menu Editor > Manage Export Templates
2. If it says “Export templates are installed and ready to be used.” then you can skip the next two steps
3. Download from: Official Github Releases mirror
4. Click Download and Install
5. Once it is complete you can close that window
6. In Finder, create an exports folder (outside of your game project folder)

# Add a custom app icon

1. Go to Project > Project settings
   * Application > Config
2. Click the folder where it says Icon
3. Select the picture you want to have as your icon
4. Close Project Settings

# Exporting

1. Go to Project > Export
2. Click Add…
3. Click MacOS
4. Fill in the Bundle Identifier with this format: com.yourName.gameName
5. Click Export Project
6. Find and select your exports folder
7. Uncheck Export with Debug
8. Click save

Now we have a .dmg file in the exports folder.

1. Open Finder
2. Go to your exports folder
3. You should see a .dmg file there
4. Double click the dmg file
5. You can double click your game to open it. You can drag it to your desktop or dock to have easy access to it. To fully install it, you can drag it to your Applications folder in Finder

**Success!**
