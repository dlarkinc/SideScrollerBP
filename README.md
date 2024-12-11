# SideScrollerBP
UE5 Side Scroller template (Blueprint) for SOFT8009 Game Development.

This template is a modification of the Third Person Template that ships with Unreal Engine 5. It is inspired by the "How to make a 2.5D Platformer in Unreal Engine 5 - Beginner Tutorial" video on YouTube by "Cobra Code". See https://www.youtube.com/watch?v=ZGQoo9frBUA. Some modifications have been made, such as using the newer Enhanced Input feature of UE5 and modifying some values.

This template is a good starting point for 2.5D games with a fixed x-axis. Modify variables such as walk speed, gravity, camera offset and more to get it exactly how you want. Depending on the verticality of your level design, you may want to set the LockHeight boolean (in the camera manager blueprint) to true when there is no verticality or false to allow the camera to follow the player character as it ascends or descends. You may also consider moving the camara manager blueprint along a spline if you want more precise control over camera height.
