# MirrorSystem

This is a Mirror System that once setup, controls all the mirrors in your world so only 1 can be active at a time.

![](/Basics/MirrorSystem/MirrorSystem.gif)

## ***THIS SCRIPT HAS TO BE A COMPONENT IN AN INPUT FEILD***

*The prefab has the debugger removed for it to cut down on un-needed checks. If you want the debugger use the script on this github.*

### Setting the script up from scratch

1. add an Udon Behaviour to an InputFeild
2. set "On Value Changed" to the InputFeild
3. select "UdonBehaviour.Interact" in the dropdown menu
4. make the Mirrors Size the number of the mirrors in your world in the Udon Behaviour Component
   * This can be changed at any time even after setup
5. add all your mirrors to the script
6. Make a UI button
   * if you never used UI in VRC before, make sure you attach the Component "VRC Ui Shape" to the parented Canvas of the button or else it will not work in game
7. set OnClick to use the InputFeild that the script is attched to
8. set the Button to "InputFeild.text"
9. set the string to the Element value to the mirror
* Done

### Using the Prefabs

1. make the Mirrors Size the number of the mirrors in your world in the Udon Behaviour Component
   * This can be changed at any time even after setup
2. add all your mirrors to the script
3. Use the UI_Button Prefab
4. set OnClick to use the InputFeild that the script is attched to
5. set the Button to "InputFeild.text"
6. set the string to the Element value to the mirror
* Done

---------------------

<p align="center">
  <a href="https://www.patreon.com/TakatoandBeast" target="_blank">
    <img src="/.github/Icon/Patreon Button.png" height="30"></a>
  <a href="http://discord.gg/dpuxmxr" target="_blank">
    <img src="/.github/Icon/Discord Button.png" height="30"></a>
  <a href="https://ko-fi.com/takatoandbeast" target="_blank">
    <img src="https://www.ko-fi.com/img/githubbutton_sm.svg" height="30"></a>
</p>

---------------------
