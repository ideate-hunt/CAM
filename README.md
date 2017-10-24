IDeATe@Hunt CAM Repository
=========================

This repository contains CAM configuration files for the CNC systems at the
IDeATe@Hunt facility at Carnegie Mellon University.  We currently maintain
post-processors and tool tables for sending files to our CNT Motion Systems 950
CNC Router using RhinoCAM, VisualCAM, or HSMWorks.

Eventually, these will be installed by default on IDeATe cluster computers along
with the Rhino and SolidWorks installations, but for now this can be installed
as needed by individual students.

RhinoCAM and VisualCAM share a common CAM platform from
[MecSoft](https://mecsoft.com/), and so the post-processor and tool files are
shared between the two.

notes on file types
-------------------

**.spm** files are RhinoCAM or VisualCAM post-processor configurations.  Millimeter
and inch output are handled with separate files.

**.vkb** files contain RhinoCAM or VisualCAM tool tables ("knowledge base"
files). Millimeter and inch output are handled with separate files.

**.cps** files contain HSMWorks post-processor scripts.  The same script supports
millimeters or inches.

**.hsmlib** files contain HSMWorks tool tables.  The same tables work with either
millimeters or inches.

**.hsmworks-template** files contain HSMWorks operation templates.  Each
specifies all parameters (including tool) for a given operation type.  The same
templates work with either millimeters or inches.

CNT Router Tooling
------------------

The router tool changer has nine installed tool holder nests, of which the first
eight of which are generally a standard set of tools.  Tool 1 is near the edge
of the machine, i.e. on the left when viewed from the operator console.

The standard set includes:

1. engraving tool
2. 1/4" tapered mill, R0.125", 5 degree taper
3. 1/4" flat mill
4. 3/8" ball mill
5. 3/8" flat mill
6. 1/2" ball mill
7. 1/2" flat mill
8. 1/2" flat mill for foam only
9. drill chuck

This listing is intended for design guidance only and does not supersede the CAM
tool tables.

References
----------

  * [IDeATe CNC Router Procedures and Policies](https://resources.ideate.cmu.edu/equipment/cnc-router/)
