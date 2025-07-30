# Paper-Mario-The-Thousand-Year-Door-Texture-Mod-Bow-Over-Flurrie
This is an easy texture mod for the dolphin emulator that replaces the provocative Flurrie with a family friendly cute boo named Bow! I know of this one:

https://gamebanana.com/mods/518748

But I couldn't actually get the pngs from the download. So I made my own that's much easier to install.

(This project is unfinished)

# How I Extracted the Textures Using Dolphin Emulator
Open Dolphin Emulator and load your Paper Mario: The Thousand-Year Door ISO.

Go to Options → Configuration → Graphics.

In the Advanced tab, enable the option "Dump Textures". and load custom textures.

This tells Dolphin to save all textures the game uses as PNG files on your computer.

Launch the game and play until you see the character (Flurrie) whose textures you want to extract.

While playing, Dolphin will automatically save textures as .png files in this folder on your computer:

swift
Copy
Edit
~/.local/share/dolphin-emu/Dump/Textures/G8ME01/
(Here, G8ME01 is the Game ID for Paper Mario: The Thousand-Year Door.)

Go to that folder and look through the PNG files — these are the raw textures the game uses.

Edit the textures you want (for example, Flurrie’s textures) in your favorite image editor.

Place the edited PNGs here:

~/.local/share/dolphin-emu/Load/Textures/G8ME01/

to have Dolphin load your custom textures when you run the game.

