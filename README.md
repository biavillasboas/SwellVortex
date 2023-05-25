# Source code for 
Wang, H ., Villas Bôas, A. B., Young, W. R. Young, and Vanneste, J. Scattering of swell by currents. *Submitted to Journal of Fluid Mechanics* 

Preprint available from [arXiv](https://arxiv.org/abs/2305.12163)

# Abstract
The refraction of surface gravity waves by currents leads to spatial modulations
in the wave field and, in particular, in the significant wave height. We examine
this phenomenon in the case of waves scattered by a localised current feature,
assuming (i) the smallness of the ratio between current velocity and wave group
speed, and (ii) a swell-like, highly directional wave spectrum.
We apply matched asymptotics to the equation governing the conservation of
wave action in the four-dimensional position–wavenumber space. The resulting
explicit formulas show that the modulations in wave action and significant wave
height past the localised current are controlled by the vorticity of the current
integrated along the primary direction of the swell.
We assess the asymptotic predictions against numerical simulations using
WAVEWATCH III for a Gaussian vortex. We also consider vortex dipoles to
demonstrate the possibility of ‘vortex cloaking’ whereby certain currents have
(asymptotically) no impact on the significant wave height. We discuss the role
of the ratio of the two small parameters characterising assumptions (i) and (ii)
above and show that caustics are only significant for unrealistically large values
of this ratio, corresponding to unrealistically narrow directional spectra

# Authors
* [Han Wang](https://hannnwang.github.io/)
* [Bia Villas Boas](https://biavillasboas.github.io/)
* [Bill Young](http://www-pord.ucsd.edu/wryoung/)
* [Jacques Vanneste](https://www.maths.ed.ac.uk/~vanneste/)



# Data
All data used in this work was obtained from numerical simulations. The configuration files to reproduce the WAVEWATCH III results are available in [ww3_experiments](https://github.com/biavillasboas/SwellVortex/tree/main/ww3_experiments) and are organized using the following convention.

- [s10](https://github.com/biavillasboas/SwellVortex/tree/main/ww3_experiments/s10): Experiments forced with directional spreading set by the parameter $s = 10$
  - [control](https://github.com/biavillasboas/SwellVortex/tree/main/ww3_experiments/s10/control): Run with no current forcing
  - [gauss_vmax40cms](https://github.com/biavillasboas/SwellVortex/tree/main/ww3_experiments/s10/gauss_vmax40cms): Experiment for the Gaussian vortex with maximum speed $U_m = 0.4$ m/s
  - - gauss_vmax80cms: Experiment for the Gaussian vortex with maximum speed $U_m = 0.8$ m/s   
- s40: Experiments forced with directional spreading set by the parameter $s = 40$
  - control: Run with no current forcing
  - gauss_vmax40cms: Experiment for the Gaussian vortex with maximum speed $U_m = 0.4$ m/s
  - - gauss_vmax80cms: Experiment for the Gaussian vortex with maximum speed $U_m = 0.8$ m/s

# Funding

