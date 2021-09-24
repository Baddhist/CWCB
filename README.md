# Cold Waters Control Boxes

**Step 1. Copy the "override" folder.**
\
\
**Step 2. Paste "override" folder to:**

STEAM\steamapps\common\Cold Waters\ColdWaters_Data\StreamingAssets\
\
\
\
\
\
(To disable lines of code add "//" at start of line to disable it or remove "//" to enable.)

*Config to enable the horizontal panels:*

[HUD LAYOUT]
//All positions in screen pixels

//From element's default anchored screen corner/position

BottomLeftPanelPos=0,0

//Toolbar position 0,0, (1 to anchor to minimap or 0 for no anchor)
//Default toolbars overlap and enabled via tabs/keys
//ToolbarsPos=0,0,0
//ForceAllToolbarsOn=FALSE
//HelmToolbarOffset=0,0
//DiveToolbarOffset=0,0
//SensorToolbarOffset=0,0

//Force all toolbars on in bottom horizontal row
ToolbarsPos=0,0,0
ForceAllToolbarsOn=TRUE
HelmToolbarOffset=391,-346
DiveToolbarOffset=700,-346
SensorToolbarOffset=1013,-346

//Force all toolbars on in right vertical stack, anchored to mini-map
//ToolbarsPos=0,0,1
//ForceAllToolbarsOn=TRUE
//HelmToolbarOffset=0,0
//DiveToolbarOffset=0,71
//SensorToolbarOffset=0,142

BottomRightPanelPos=0,0
UpperRightStatusIcons=0,-3
UpperCentreBearingTapePos=0,-2
BottomCentreWaypointInfoPos=0,153
UpperRightTacMapZoomReadoutPos=0,-45
UpperRightPeriscopeZoomReadoutPos=0,-45
UpperRightRecognitionManual=0,0
UpperLeftPeriscopeESMPos=0,0
MainCameraFieldOfView=30
