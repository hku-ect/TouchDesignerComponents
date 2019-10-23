# TouchDesignerComponents
This is a collection of commonly used TouchDesigner components

**ActivityMon**
Allows for CHOP data to be registered as activity over time. This could be movement, audio, etc.

**DMX_Out_Artnet**
This sends out data to Artnet. You can define the IP of the artnet controller and the universe.
If you have multiple fixtures, please add a "merge" CHOP to merge the channels to a single stream.

**Elation_DLED_Zoom**
Enables you to control the parameters of the Elation Zoom Par and gives visual feedback of the current color.
set the DMX adress and feed the resulting channel data to a DMX output.
this has 6 CHOP inputs (Int,R,G,B,Strobe,Zoom)

**ETC_Colorsource_Par**
Enables you to control the parameters of the ETC Colorsource PAR and gives visual feedback of the current color.
set the DMX adress and feed the resulting channel data to a DMX output.
this has 6 CHOP inputs (Int,R,G,B,Strobe)

**RadiusCheck**
Creates a virtual point in 3D space and checks the relation between input XYZ.
Set the radius in metres
Set the XYZ location
feed it a live location (XYZ)
Outputs Percentage within the radius
Outputs InsideBounds
Outputs Distance in Metres

**RigidBodyOsc Receiver**
Restructures the incoming OSC data coming from the OSCNatnetBridge / Optitrack system
input the OSC port number
input the RigidBody Name
outputs the osc data in an understandable format.

**SkeletonOsc Receiver**
Restructures the incoming OSC data coming from the OSCNatnetBridge / Optitrack system
input the OSC port number
input the Skeleton Name
optional: select Joint
outputs the osc data in an understandable format.
**note:**
Can be used to target FBX rigged models from mixamo. Make sure you enter the correct mixamo base name, joint names and make sure the joints are unlinked (moving in world space not relative space)

**V_1HD_Control**
communicates with the Roland V-1HD video mixer over MIDI/USB
you can manipulate most functions.
