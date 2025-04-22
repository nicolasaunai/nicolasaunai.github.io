---
title: Jérémy Dargent
draft: false
tags:
  - student
---
 
## Context
- 2014 : Master 2 (Astronomy and Astrophysics) internship
- 2014-2017 : PhD Thesis

## Our work
Jérémy worked with Benoit Lavraud and I on modeling magnetic reconnection with numerical simulations. 

[Download Jeremy's thesis](https://theses.hal.science/tel-01795033/)

### Kinetic equilibria
The first work Jeremy did was to implement a kinetic equilibrium solution for the ion distribution in a fully kinetic PIC model. We were wondering to what extent not knowing the kinetic solution for electrons too would make the current sheet unstable. Jeremy showed the unsteadiness stays confined at the electron Larmor scale while the larger ion scale structure remains steady, provided enough scale separation exists in the model. He later showed (@2016JPlPh..82c9005D) that reconnection signatures in PIC simulations were only function of upstream conditions and did not depend on whether the initial current sheet was in an equilibrium state or not.

>[!Citations]
>[@2016JPlPh..82c9005D](https://ui.adsabs.harvard.edu/abs/2016JPlPh..82c9005D)
### Cold ions
Magnetic reconnection at the Earth's magnetopause mixes plasmas from the solar wind and the magnetosphere. In the latter region, several population coexist/ among which cold ions directly coming from the plasmasphere. These cold ions are rarely accounted for in numerical model despite their important contribution to the particle density.
Jeremy first compared two interesting setups sharing the exact same macroscopic state but where one has its magnetospheric plasma made of a mix of plasma sheet and cold ions while the other one only has a plasma sheet.
Having exactly the same macroscopic state, the two simulations showed the same overall dynamics of the reconnection process. However, details were different and in particular signatures expected to be characteristics of the X line region. We discovered that cold ions, frozen in the magnetic field at very small scale, are able to sustain a small scale electric field normal to the current sheet and that otherwise vanishes everywhere but around the X line where the current sheet thickness is small. 
Jeremy then continued analyzing the structure of cold ion velocity distribution functions in particular close to the magnetospheric separatrix and proposed a model explaining the crescent-shape distributions observed there. These results where a very interesting finding at a time where finding relevant signatures of the X line region was so important for preparing the future analysis of MMS data.
Jeremy finally made a massive fully-kinetic PIC simulation to investigate how reconnection at the magnetopause is impacted by the arrival of a plasmaspheric plume. In his setup, the plume density is even larger than that of the magnetosheath, reversing the typical asymmetry observed at the magnetopause. Jeremy's main finding from that model is that depsite the overall unsteadiness arising from the plume's arrival, the reconnection rate follows well predictions from MHD scaling laws, and is significantly reduced by the mass loading of the system.



> [!Citations]+
> [@2017JGRA..122.5290D](https://ui.adsabs.harvard.edu/abs/2017JGRA..122.5290D)
> [@2019JGRA..124.2497D](https://ui.adsabs.harvard.edu/abs/2019JGRA..124.2497D)
> [@2020GeoRL..4786546D](https://ui.adsabs.harvard.edu/abs/2020GeoRL..4786546D)

## After
After his PhD Jeremy continued research at Pisa University, Bochum University and LPP again.