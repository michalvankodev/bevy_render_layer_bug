While using setup of 2 different cameras with `RenderLayers`. Both cameras are using different `ScalingMode`. Observers for `Trigger` events are only fired for One of the cameras. Making it unusable for an *Overlay camera* for a game.


See the pointer in the image. That's where the **Hexagon** is located for the 2nd camera that scales with the width of the window. And only at that position the `Trigger` event is triggered.

![image](https://github.com/user-attachments/assets/12ef43b5-3ac1-4f3b-afb9-0c470bfce68f)
