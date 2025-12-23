# Unfold-Transition
Updated Unfold Transition Script to Work with Blender 5.0

# About & How-to
An addon that can make meshes "unfold" with an armature based on different methods.
For Blender 5.0 (and probably beyond), download "unfold_transition_5_0.py" and install from disk like a normal addon.
It will appear on the N-panel as " ||| ".

The original script/addon has been provided here for the sake of posterity (listed as "unfold_transition_279.py" and "unfold_transition_280.py") and for anyone that wants to tinker about with it.
The original code only works with Blender versions PRIOR to changes to how bones/armatures are organized in Blender, which made the script throw exceptions.
The original code has only been modified to remove the offending parts, and currently works with 5.0; other Blender versions unknown, but previous versions are probably fine, as well as future versions unless changes are once again made to how Blender handles bones and armatures.

# Examples:
YT: Default 3D Cursor Method

[![Default 3D Cursor Method](https://img.youtube.com/vi/nLqzqLx2naE/0.jpg)](https://www.youtube.com/watch?v=nLqzqLx2naE)

YT: Weight Map Method

[![Weight Map Method](https://img.youtube.com/vi/dzCg1h5h04E/0.jpg)](https://www.youtube.com/watch?v=dzCg1h5h04E)

Old 2.7x Example of what it does:

[![2.7x](https://img.youtube.com/vi/sUTPvUvZ-gI/0.jpg)](https://www.youtube.com/watch?v=sUTPvUvZ-gI)

# Further Info
The Original Unfold Transition
* https://blenderartists.org/t/unfold-transition/586992

This repo is to prevent the possibility/probability of link rot by providing a source of redundancy.

# License and A.I. Disclaimer

I have no idea what the license is for the original, as the code/script came without that information.
If *you* are the OG writer and can prove it, and want to be credited, or just want me to take this repo down, let me know.

*Lastly*, the original code was modified with Gemma to function with newer versions of Blender; however looking at it, they are functionally identical *except* where the code throws errors that Gemma fixed.
