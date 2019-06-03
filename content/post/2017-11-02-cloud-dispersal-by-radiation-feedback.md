
+++
title = "Cloud Dispersal by Radiation Feedback"
date = "2017-11-02"
author = "Jeong-Gyu Kim"
categories = "research"
tags = ["giant molecular clouds", "radiation hydrodynamics", "star cluster formation", "HII regions"]
+++


Almost all stars in the present-day Universe are believed to form in clusters embedded in **giant molecular clouds (GMCs)**. It has long been known to observers that star formation in GMCs is a slow and inefficient process, in the sense that star formation rate is much more smaller than what would be expected from the free-fall (pure gravitational) collapse andthat clouds turn only a small fraction of gas mass into stars during their lifetime. On the theoretical side, the question of what physical processes are responsible for regulating star formation efficiency and lifetime of GMCs remains unanswered.

Although scarce in numbers, massive stars profoundly affect the evolution of their natal clouds by releasing a tremendous amount of energy and momentum in forms of radiation, winds, and supernova explosions, which are collectively known as **stellar feedback**. In particular, copious ultraviolet (UV) photons emitted by massive stars excite **HII regions**---bubbles of warm (\\(\\sim 10^4\\,{\\rm K}\\)) and ionized hydrogen gas marked by its telltable reddish glow---and drive expansion of them by producing extremly high internal pressure.

Using the Eulerian hydrodynamics code _Athena_
([<span style="color:grey">Stone et al. 2008</span>](http://adsabs.harvard.edu/abs/2008ApJS..178..137S)),
we performed a suite of radiation hydrodynamic simulations of star cluster formation in turbulent molecular clouds, focusing on how UV radiation feedback from massive stars controls the net star formation efficiency and the lifetime
of natal clouds. We study the effects of photoionization (conversion of neutral gas to ionzied gas by ionizing radiation) and radiation pressure on dust grains (which transfers the photon momentum to gas via mutual collisions) in controlling the cloud dynamics in a range of star-forming environments. The movie shows the volume-rendering of gas distribution taken from the fiducial model, which has an initial cloud mass of \\(10^5\\, M\_{\\odot}\\) and radius of \\(20\\,{\\rm pc}\\). The blue-white-red scale shows neutral gas while green-white scale shows ionized gas. The spheres show the position of Lagrangian sink particles that represent stellar subclusters. Our cluster particles not only accrete surrounding gas that had been gravitationally pulled in, but also emit intense UV radiation blowing out ambient gas. The cloud is completely destroyed within \\(\\sim 8\\,{\\rm Myr}\\) timescale after the onset of star formation. The remaining star cluster is loosely bound gravitationally and dissolves rapidly, which would be seen as a open cluster to an observer.

{{< figure src="/img/projects/Comparison-Simulation-HST.png" title="(left) Snapshot of emission measure of ionized gas. (right) A Hubble Space Telescope image of NGC 602, an open star cluster in the Small Magellanic Cloud." >}}

In our simulations, the star formation efficiency of a cloud rises to a final
value until the associated feedback is able to photoevaporate and dynamically
eject the remaining gas, completely halting further star formation. Figure 2
plots the net star formation efficiency as a function of the initial gas surface
density \\(\\Sigma\_{\\rm cl,0}\\) for runs including photoionization (PH-only, red
circles), radiation pressure (RP-only, blue squares), and both photoionization
and radiation pressure (PH+RP, black stars). The green triangle shows the net
SFE of the cloud without radiation feedback. The net SFE of the PH-only run is
smaller than that of the RP-only counterpart and closer to that of the PH+RP
run, indicating that the photoionization feedback is more important than the
radiation pressure in disrupting the parent clouds. The two exceptions are the
dense, massive clouds, for which radiation pressure plays a dominant role in
cloud disruption.

{{< figure src="/img/projects/fig-SFE.png" title="Net star formation efficiency as a function of initial gas surface density" width="600" >}}
