
## Clone of (now deprecated) Sublime Boxy theme

The author of the [theme](https://github.com/ihodev/sublime-boxy) (ihodev) deleted the original repository since I believe he wished to deprecate it. It is a great theme so hopefully he does not mind it being made available here again for anyone who still wishes to use it.

### To install

1. Ensure you have [package control](https://packagecontrol.io/installation) installed in ST.
2. Since the original theme is no longer available via the [Package Control central repository](https://packagecontrol.io/packages/Boxy%20Theme) you need to add this repository. In ST go to `Tools` > `Command Palette` > type *"Package Control"* and choose *"Package Control: Add Repository"* and paste this repo URL *https://github.com/jonjack/Boxy-Theme*
3. Now select *"Package Control: Install Package"* and type *"boxy"*.    
You should see the *"Boxy-Theme"* package, select it to install.
4. Without closing ST, go to the package installation directory.     
On OSX this is usually at `~/Library/Application Support/Sublime Text X`.     
Make the following changes:-
    - Rename ***Boxy-Theme.sublime-package*** (inside **Installed Packages** dir) to remove the hyphen so it becomes ***Boxy Theme.sublime-package***.
    - Edit the theme name in ***Package Control.sublime-settings*** (inside **Packages/User** dir) to remove the hyphen so it looks as below.   
    ```sh
      "installed_packages":
        [
          "Boxy Theme",
          "Package Control",
        ],
    ```
5. Restart ST.
6. In ST, go to `Preferences` > `Select Theme`. If all went well you should see the options for Boxy in the list. If not, re-check the above steps.
7. Install the ***"A File Icon"*** package using Package Control since Boxy has a dependency on this.


***

The author's original [README](README-original.md)


