# Hololens2-Finger-Joint-Tracking

So you are developing an application for Hololens 2, and you can’t figure out how to get access to the finger joint positions?  This is how.

Follow steps 1 and 2 of instructions here: 
https://docs.microsoft.com/en-gb/windows/mixed-reality/mrlearning-base

Then create a Unity GameObject in the Unity scene you have created and attach the script 'FollowTrackedFingers.cs'.

Now, make some prefab objects of what ever you want to place at the finger tips, and drag those into the public GameObject fields (“fingerObject” and “wristObject”) on this script in the Inspector in Unity.
