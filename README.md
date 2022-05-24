# Walkpaper

## About:
Have a different wallpaper on each GNOME workspace.

# Note:
    If you wanna make it usable on gnome 42 dark try changing
    ```
        "picture-uri" to "picture-uri-dark"
    ```
    in two files every where on the repository.They are extension.js and prefs.js.

## Installation:
Compile the extension by running
```
    # make all
```
Install `walkpaper.zip` using Tweak Tool and restart GNOME Shell (alt+F2 + 'r').

At this point you have two options:

You can either open extension's preferences and set paths to each workspace's wallpaper by double clicking on a specific row or use the default wallpaper changing method in GNOME settings.

More about the second method:

To set the background image for a workspace, switch to that workspace and use any method to
change the background E.g. standard background chooser (e.g. secondary click on background, "Change Background"),
then close the backgrounds dialog (otherwise trying to set background on another workspace may trigger a workspace
change back to the WS with the dialog)

You can even use another extension or program that changes the backgrounds automatically.

Switch away from the workspace to trigger saving the current background.

Remember that you can always manage your extensions from https://extensions.gnome.org/local/

## License:
This project is licensed under the GNU License - see the [LICENSE.md](LICENSE.md) file for details
