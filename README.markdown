# Framecurve Maya MEL script

First of all, you will need our MEL file that you will need to source.
[Download the .mel](scripts/framecurveApplyTimewarp.mel)

Select an object in Maya, execute the script function **framecurve.timewarpDialog()**.
A dialog will pop out prompting you to select your framecurve file and the object to timewarp.
Select a file and then hit the **Get** button to select the object you are going to timewarp.

![Pick objects](framecurve_maya/raw/master/images/fc_maya_pick.png)

Activate the dialog, and your Hypergraph hierarchy will transform from this:

![Standard hypergraph without timewarp](framecurve_maya/raw/master/images/fc_maya_hyper.png)

to this:

![Timewarped graph](framecurve_maya/raw/master/images/fc_maya_modified_hyper.png)

The main curve that now feeds the other curves will contain the Framecurve animation.