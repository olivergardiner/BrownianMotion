# BrownianMotion
Open hardware guitar pedal that uses JFETs for a complete emulation of a valve amp, derived from the Infinite Improbability Drive but with only one gain stage and two tone controls to give an "amp in a box" feel to the distortion but with more rock than metal.

Note that there are two versions, the Mk I and the Mk II. The Mk I uses a Fetzer configuration, which behaves like a triode, for the preamp emulation while the Mk II uses a cascode/JFET combination which has more gain and behaves more like a pentode. In both cases, the output stage is the same as the Inifinite Improbability Drive. Note that the input buffer has the potential to be wired for some gain in case this is needed (particularly with the low gain Fetzer stage) to push the preamp properly.

The generated Gerber files are provided as a Release - the repository only contains the design files for DesignSpark PCB v10.

The Visio file provides the template for drilling and printing (e.g. with a waterslide or self-adhesive decal) a 1590BB enclosure.
