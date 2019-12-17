# BackFacingStep
OpenFOAM Steady Flow over a 2D Backward Facing Step

Modified from https://www.openfoam.com/documentation/guides/latest/doc/verification-validation-turbulent-backward-facing-step.html

## Background

The backward facing step is a classic geometry used to test CFD turbulence models.  The blunt step creates flow separation and reattachment downstream.  It has been experimentally measured and reported extensively beginning with the 1981 Stanford Conference

> Kline, S. J., and Lilley, G. M. (June 1, 1981). "Correspondent Report on the Initial Meeting, Held September 3–6, 1980, of the 1980–1981 AFOSR-HTTM-Stanford Conference on Complex Turbulent Flows: Comparison of Computation and Experiment." ASME. J. Fluids Eng. June 1981; 103(2): 184–188. https://doi.org/10.1115/1.3241724

Data for this test case has been published specifically as

> Driver, David M., and H. Lee Seegmiller. "Features of a reattaching turbulent shear layer in divergent channelflow." AIAA journal 23.2 (1985): 163-171.  https://doi.org/10.2514/3.8890

## Setup

Geometry, meshing, and comparison data can be found at the Langley Research Center urbulence Modeling Resource website  https://turbmodels.larc.nasa.gov/backstep_val.html

The Allrun script will run the case and generate graphs showing the wall hear stress and velocity profiles at various cross-sections.  To run correctly, the following software is needed:

 * OpenFOAM 6
 * PyFoam
 * Gnuplot
 * Mirage
