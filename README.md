Plug n Play is a module launcher that allows you to install and run custom modules in Apple Shortcuts; all Plug n Play compatible modules are marked with a º symbol since Plug n Play checks if a shortcut has a º in its title.

## How do I use Plug n Play?

Plug n Play allows you to automatically run shortcuts from “Run Modules” and install from “Install Toggles”, you can also look at RoutineHub to see if there are any that you like. As of right now, the only 2 modules that are currently featured are ClipEdit and File Escape.   
If you have feedback or have a module that you want featured in “Install Modules”, use the “Feedback/Request” button.   

(**Left:** PnP Module Market | **Middle:** PnP Launch Screen | **Right:** Run Modules Menu)

<img width="4077" height="2736" alt="IMG_7204" src="https://github.com/user-attachments/assets/88a35da0-fbda-4b55-b121-54ddaad04c48" />

## How do I make a º?

**iOS:** Hold down 0 and then drag your finger to the º symbol  
**macOS:** Use Option (or Alt) + 0

## How do I make my installed shortcut compatible with PnP?

It is actually really simple, just add a º at the start in the Shortcut’s title, PnP will automatically detect it and show it in “Run Module”

## How do I integrate PnP into a shortcut?

This process is also very straight forward:


1. Add “Run Shortcut” action under a menu header and put Plug n Play into it
2. Add a “if” action underneath  
3. Make the if “If “run shortcut” does not have any value”  
4. Put under that a text saying PnP is not installed and direct the downloader to Plug n Play’s iCloud, GitHub or RoutineHub link  
5. Either delete the “otherwise” box or put a “nothing” action into the otherwise box  
**Note:** Do Not change Plug n Plays name at all (as in the shortcut title) because the modules may break.

**Below:** Visual version of Plug n Play compatability layer with Quick Menu v2.5.2

![IMG_6633](https://github.com/user-attachments/assets/562f2aac-79b1-4a3f-9f31-8d9d3889d3b2)

### Compatibility

-Plug n Play is designed for iOS 26  
-Runs smoothly on iOS 16 and iPhone X  
-Shortcuts must have º icon to be registered by Plug n Play
