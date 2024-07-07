These matlab codes correspond to manuscript " Spatial phasor analysis for optical sectioning nanoscopy".
Briefly, it is used to  decode information about the axial position in image scanning microscopy (ISM).

To extract the in-focus signal from the raw ISM data, first calculate the shift vector using calcShift.m 
and then perform pixel reassignment using pixelReassign.m. After that, the information about the 
axial position can be accurately decoded using spatialPhasor.m

In spatialPhasor.m, the sliding window radius should not exceed the resolution of the microscope.

The imageJ plugin is also available, but requires MCR 7.2 to be pre-installed.

If any bugs appear, please contact me at huangyr@zju.edu.cn.
