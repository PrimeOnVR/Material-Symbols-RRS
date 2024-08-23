# Material Symbols RRS
A modified version of Unity Material Symbols made for RRS development.

![image](https://github.com/user-attachments/assets/49d84b9a-75d7-43f3-abaa-30e3ce7e3b99)


## Installation

Step 1 :
Grab the latest version of this addon from [Releases](https://github.com/PrimeOnVR/Unity-Material-Symbols-RRS-Compatibility/releases/) and import it into unity normally.

Thats it for installation! Read Usage for info on using the addon.

*note: as of now, the original [Unity Material Symbols](https://github.com/convalise/unity-material-symbols/releases/) gets preinstalled when you install this package :)*

## Usage

If you would like to use the MaterialSymbols RRS Compat addon, just right click on your hierarchy while in a canvas prefab, and click:

`UI > Google > RRS Symbol`

![image](https://github.com/user-attachments/assets/b36f01a7-81fa-4c6f-8bd9-2c1c7daa0d5b)

*NOTE: Material Symbol is an option added by the original package, you can safely ignore it as it is for use with base unity.*

Once you have added a material symbol, you can use the script on the object to configure what icon you may want to use.

![image](https://github.com/user-attachments/assets/6f44c2a2-a7e1-4e88-a3cb-5dd285d0327a)

From my testing, after setting an icon, you can use this plugin normally in your RRS projects, and it should not complain about having a script, but if you are having issues, you can safely remove the Material Symbol Setter Util script from the object, as all the script does is input data into an existing Text component, and is not a standalone script (like the original Material Symbols package is)

## Uninstallation

well just delete the MaterialSymbols and MaterialSymbols RRS Compat folder, as they contain all of the scripts and various things that the package and addon utilize.

## FAQ

### How does this work with RRS? This uses scripts!

As mentioned in Usage, this just sets data to a default unity component, and doesnt act as its own standalone script.

### What is Material Symbol, and why is it an option in my hierarchy?

This is created by the original package, and since it uses a standalone script, will not function with Rec Room Studio properly.

### Why can't I set the fill on the icon?

Since this plugin takes stuff from MaterialSymbols, but doesnt have everything, if you would like to change between the filled and not filled variations of the font, please change the font on the text component.

### The fonts don't fit the style of my game. Do you have more styles?

Absolutely! Since both this project and Unity Material Symbols use [Google Icons](https://fonts.google.com/icons/), you can head over to there, download their font files, and replace the font on my RRS Prefab with a static font provided by Google.

### Why is there no TextMeshPro support?

Both me and the original package creator built the entire thing around legacy text, as it provides better performance and is easier to use for smaller, more lightweight solutions like this, and therefore, is what is used forthe

## Credits

Unity Material Symbols

https://github.com/convalise/unity-material-symbols
