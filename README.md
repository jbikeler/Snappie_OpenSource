# Snappie (Snap Pie) - A Smarter Snap Pie Menu for Blender  

Snappie is a rewrite of Blender’s default snap pie menu, designed to bring better organization and additional functionality to snapping workflows.  

## 🎯 Why Snappie?  
Over my time working with Blender, I found the default pie menu to be a bit unorganized (displaying all options at once in a radial layout). **Snappie organizes snap options into clear, structured containers** while also adding new functions that help with my Blender pipline.

## ✨ Features  
- **Organized Snap Menu** – Snap options are grouped into logical sections for easier navigation.  
- **Enhanced 3D Cursor Snapping:**  
  - Snap the 3D cursor to your selection.  
  - Rotate the 3D cursor to match your selection.  
  - Snap the selection to match the rotated 3D cursor.  
- **Target & Home Transform System:**  
  - Save a target and home location, rotation, and scale for an object.  
  - Quickly toggle between saved transforms.  
  - Inspired by the *Geometry Stager* feature in ZBrush.  

## 🔧 Installation  
1. Download the latest release from [GitHub Releases](#).  
2. In Blender, go to **Edit > Preferences > Add-ons > Install** and select the downloaded `.zip` file.  
3. Enable the add-on and start using Snappie!  

## 🛠 Editing & Customization  
Snappie was developed using [Serpens](https://blendermarket.com/products/serpens?search_id=38267490), a visual scripting add-on for Blender.  

- If you'd like to modify the Python code directly, you can edit the `__init__.py` file inside the release `.zip` folder.  
- If you have the **Serpens add-on**, you can download the latest `.blend` file from the `SerpensBlenderFiles` directory and edit the add-on visually within Blender.  

⚠ **Warning:** Editing Snappie using the `.blend` file requires Serpens. Without it, you won’t be able to modify the add-on inside Blender.  

## 🚀 Usage  
Once installed, Snappie replaces the default snap pie menu. Simply slap the snap hotkey (`Shift + S` by default but you can change this in the Preferences of the addon).  

## 💬 Feedback & Contributions  
If you have any feedback or suggestions, feel free to open an issue or contribute!  

---
