# DDRNoRotation
A mod for Desktop Dungeons Rewind that disables rotation of the camera when zooming in.

To apply you need xdelta3 from either your favorite package manager or from https://github.com/dan0v/xdelta3-cross-gui (I've not tested the GUI myself)

Apply the patch:
- run `xdelta3 -d -s Assembly-CSharp.dll patch_noRotation.xdelta modded.dll`
- copy the `modded.dll` to `Desktop Dungeons Rewind/Desktop Dungeons Rewind_Data/Managed`
- remove the original `Assembly-CSharp.dll`
- rename `modded.dll` to `Assembly-CSharp.dll`

or just use a GUI
