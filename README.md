# Unfold-Transition
Updated Unfold Transition Script to Work with Blender 5.0

An addon that can make meshes "unfold" with an armature based on different methods.
For Blender 5.0 (and probably beyond), download "unfold_transition_5_0.py" and install from disk like a normal addon.
It will appears on the N-panel as " ||| ".

# Examples:
YT: Default 3D Cursor Method

[![Default 3D Cursor Method](https://img.youtube.com/vi/nLqzqLx2naE/0.jpg)](https://www.youtube.com/watch?v=nLqzqLx2naE)

YT: Weight Map Method

[![Weight Map Method](https://img.youtube.com/vi/dzCg1h5h04E/0.jpg)](https://www.youtube.com/watch?v=dzCg1h5h04E)

As the original script/addon has been effectively lost, it is provided here for the sake of posterity (listed as "unfold_transition_280.py") and for anyone that wants to tinker about with it.
The original code only works with Blender versions PRIOR to changes to how bones/armatures are organized in Blender, which made the script throw exceptions.
The original code has only been modified to remove the offending parts, and currently works with 5.0; other Blender versions unknown, but previous versions are probably fine, as well as future versions unless changes are once again made to how Blender handles bones and armatures.

Old 2.7x Example of what it does:
[![2.7x](https://img.youtube.com/vi/sUTPvUvZ-gI/0.jpg)](https://www.youtube.com/watch?v=sUTPvUvZ-gI)

The Original Unfold Transition has, effectively, fallen to link rot; here remains what can be reasonably googled:
* https://blenderartists.org/t/unfold-transition/586992
* https://www.reddit.com/r/blenderhelp/comments/60apzm/help_getting_a_copy_of_the_unfold_transition_addon/

I have no idea what the license is for the original, as the code/script came without that information.

DISCLAIMER
The code was modified with Gemma to function with newer versions of Blender, however looking at it, they are functionally identical *except* where the code throws errors.
