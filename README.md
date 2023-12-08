# Epic GPULightmass Saving Bug Patch for 5.3.2

[Initial report of Saving problem in Epic GPULightmass thread](https://forums.unrealengine.com/t/epics-gpulightmass/139357/480)

The commit to fix this was in 5.4 code. This has been converted to 5.3.2

The binary for this fix has been compiled into UnrealEditor-Renderer.dll

Click on the green "Code" button to get a zip which you unload into root DRIVE:\Program Files\Epic Games\UE_5.3

check for  DRIVE:\Program Files\Epic Games\UE_5.3\Engine\Binaries\Win64\UnrealEditor-Renderer.dll to have an updated date/time

This patch is currently UNTESTED, one user says it works! please test it!. Report your findings in the thread

In the path Engine\Source\Runtime\Renderer\Private\PathTracing.cpp

LEGAL

NO WARRANTY and no responsibilty on behalf of any party is given for the patch. This makes you 5.3.2 binary no longer production version

If there is a problem and you want to remove the patch.

The best way is to go into the Epic Games Launcher where you installed 5.3.2

Right click on the yellow down arrow and select "Verify".

This will remove all the patches for Epic GPULightmass and Luoshuang’s GPULightmass patches


