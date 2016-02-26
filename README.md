IDeATe@Hunt CAM Repository
=========================

This repository contains CAM configuration files for the CNC systems at the
IDeATe@Hunt facility at Carnegie Mellon University.  We currently maintain
post-processors and tool tables for sending files to our CNT Motion Systems 950
CNC Router using RhinoCAM, VisualCAM, or HSMWorks.

Eventually, these will be installed by default on IDeATe cluster computers along
with the Rhino and SolidWorks installations, but for now this can be installed
as needed by individual students.

RhinoCAM and VisualCAM share a common CAM platform, and so the actual
post-processor files may possibly be identical between the two products.

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