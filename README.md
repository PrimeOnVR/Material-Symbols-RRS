# MaterialSymbols RRS Compat
RRS Compatibility for Unity Material Symbols

## Installation

Step 1 :
Install [Unity Material Symbols](https://github.com/convalise/unity-material-symbols/releases/) by Convalise and import it into unity normally.
![image](https://github.com/user-attachments/assets/6f517b69-6078-4a61-a0d6-df63d2193154)

Step 2 :
Grab the latest version of this addon from [Releases](https://github.com/PrimeOnVR/Unity-Material-Symbols-RRS-Compatibility/releases/) and import it into unity normally.

Thats it for installation! Read Usage for info on using the addon.

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

### Why do i need to install Unity Material Symbols alongside this addon?

This RRS compatibility plugin simply takes UI and certain code from this unity package at this point, and will simply not work without it, as it links to references inside of it.

### Do you plan to make this a standalone package?

Maybe, but I am still quite new to writing Unity editor scripts so it might be a bit of time before this becomes its own standalone package.
