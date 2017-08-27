# Sublime text Build system
Custom C++11 and C++14 Build systems for sublime text. Supports input from user in a new terminal. 

To use it, Go to `Tools -> Build System -> New Build System...` in Sublime text. Paste the code there and save the build file with the name of your choice. Alternatively you can copy the file to `~/.config/sublime-text-3/Packages/User`.

You can build a file using a custom build system by pressing the key combination `Ctrl + Shift + B` and choosing the desired build system. 

Default terminal wrapper used is `gnome-terminal`, you can change it to `xterm` or `terminator` by changing the line `gnome-terminal -x` in `"cmd"` field of `"variants"` to either `xterm -e` or `terminator -x`. 
