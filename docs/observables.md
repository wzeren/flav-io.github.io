---
layout: default
title: Observables
---

# List of all observables

To display automatically generated tables with lists of all observables
currently implemented in flavio, select a category below. See also the
[notes on conventions](#some-general-notes-on-conventions) at the bottom
of this page.

## Categories



### $W^\pm$ decays


- [Leptonic decays](obs/wpmdecays-leptonicdecays.html) (6 observables)


### $Z^0$ decays


- [FCNC decays](obs/zdecays-fcncdecays.html) (3 observables)

- [Flavour conserving decays](obs/zdecays-flavourconservingdecays.html) (49 observables)


### $\tau$ lepton decays


- [Hadronic tree-level decays](obs/tauleptondecays-hadronictreeleveldecays.html) (2 observables)

- [LFV decays](obs/tauleptondecays-lfvdecays.html) (8 observables)

- [Leptonic tree-level decays](obs/tauleptondecays-leptonictreeleveldecays.html) (2 observables)


### $b$ hadron decays


- [FCNC decays](obs/bhadrondecays-fcncdecays.html) (620 observables)

- [Leptonic tree-level decays](obs/bhadrondecays-leptonictreeleveldecays.html) (6 observables)

- [Non-leptonic decays](obs/bhadrondecays-nonleptonicdecays.html) (2 observables)

- [Semi-leptonic tree-level decays](obs/bhadrondecays-semileptonictreeleveldecays.html) (614 observables)


### $c$ hadron decays


- [Leptonic tree-level decays](obs/chadrondecays-leptonictreeleveldecays.html) (6 observables)


### $s$ hadron decays


- [FCNC decays](obs/shadrondecays-fcncdecays.html) (2 observables)

- [Leptonic tree-level decays](obs/shadrondecays-leptonictreeleveldecays.html) (4 observables)

- [Non-leptonic decays](obs/shadrondecays-nonleptonicdecays.html) (1 observable)

- [Semi-leptonic tree-level decays](obs/shadrondecays-semileptonictreeleveldecays.html) (6 observables)


### Dipole moments


- [Lepton anomalous magnetic moments](obs/dipolemoments-leptonanomalousmagneticmoments.html) (3 observables)

- [Nucleon electric dipole moments](obs/dipolemoments-nucleonelectricdipolemoments.html) (1 observable)


### Meson-antimeson mixing


- [ $B^0$-$\bar B^0$ mixing](obs/mesonantimesonmixing-bbarbmixing.html) (4 observables)

- [ $B_s$-$\bar B_s$ mixing](obs/mesonantimesonmixing-bsbarbsmixing.html) (4 observables)

- [ $D^0$-$\bar D^0$ mixing](obs/mesonantimesonmixing-dbardmixing.html) (8 observables)

- [ $K^0$-$\bar K^0$ mixing](obs/mesonantimesonmixing-kbarkmixing.html) (1 observable)


### Unflavoured meson decays


- [Leptonic tree-level decays](obs/unflavouredmesondecays-leptonictreeleveldecays.html) (1 observable)


### muon decays


- [LFV decays](obs/muondecays-lfvdecays.html) (2 observables)


### neutrino physics


- [scattering cross sections](obs/neutrinophysics-scatteringcrosssections.html) (1 observable)

## Some general notes on conventions

- Unless noted explicitly, branching ratios and angular observables always
imply a *CP-average*. For instance, charged $B$ decay modes are always written as
$B^+ \to \ldots$, but what is meant is the average of the $B^+$ and the $B^-$
decay.
- For lepton flavour violating $B$ decays, no CP-average is made; e.g. the
decay $B^-\to e^+\mu^-$ (`B+->emu`, *sic*) is distinct from
$B^-\to\mu^+e^-$ (`B+->mue`) but its rate is equal to $B^+\to \mu^+e^-$
by CPT.
- *"Binned branching ratio"* refers to the $q^2$-integral of the differential branching
ratio, which is a dimensionless number and which coincides with the total branching
ratio if the bin spans the whole kinematic domain. *"Binned differential branching ratio"*
refers instead to the binned branching ratio divided by the bin width, which
has units of GeV$^{-2}$. This definition is frequently used by LHCb and has the
advantage that it is easier  to  compare results in the same kinematic region
but with different bin sizes.
- The conventions for $B\to V\ell^+\ell^-$ angular observables follow the ones
used by LHCb, which differ from the ones used in many theory papers,
e.g. for $A_\text{FB}$, $S_4$, $P_4^\prime$, $A_7$, $A_9$
(see e.g. [arXiv:1506.03970](http://www.arxiv.org/abs/1506.03970)).
- Lepton flavour $\ell$ always refers to an average of electron and muon modes.

