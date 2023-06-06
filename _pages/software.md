---
layout: page
title: Software
permalink: /software/
nav: true
nav_order: 3
horizontal: false
---
I have a long history of contributing to open source software, especially in the scientific Python ecosystem.

# Current projects

## [napari](https://napari.org/stable/)
I'm currently working on adding typing to napari, to reduce technical debt and increase maintainability.
I've also contributed issue reports and pull requests for various packages within the plugin ecosystem.

## [sunpy](https://sunpy.org/)
I'm currently the release manager for major releases of sunpy every six months. I no longer contribute code or do much code review.

I started contributing to sunpy in [Nov 2017](https://github.com/sunpy/sunpy/pull/2289), became a maintainer shortly after that, helping see sunpy through from the transition to the fist stable version (v1.0).
I've done a major re-write of the core ``Map`` class, added support for reading widely used file formats, made significant performance improvements across the library, and contributed many other bug fixes and issue reports.

## [pfsspy](https://pfsspy.readthedocs.io/en/stable/)
Potential Field Source Surface modelling is the most popular way to model the magnetic field of the Sun.
Despite this there was no documented, open source tool to do this modelling, until I created pfsspy in 2019.
Since then it has been [used in almost 50 papers](https://ui.adsabs.harvard.edu/user/libraries/hfLAIo9DQw6yuNlLkn40GQ), including some of the key results from NASA's Parker Solar Probe and ESA's Solar Orbiter missions.
I no longer actively develop pfsspy, but keep it compatible with new versions of Python and other dependencies and fix any bugs that are reported.

# Past projects

## [Matplotlib](https://matplotlib.org/)
This is where I stated my adventure in open source. I filed my first feature request [in April 2016](https://github.com/matplotlib/matplotlib/issues/6272), opened my first pull request [in May 2016](https://github.com/matplotlib/matplotlib/pull/6369), and became a maintainer in January 2017. Since then I've done a wide range of fixing bugs, triaging issues, adding new features, and improving documentation. I am not currently an active maintainer.

## [HelioPy](https://github.com/heliopython/heliopy)
This is the first package I built from the ground up myself, to fill a gap for  doing data science with Heliospheric datasets.
I eventually sunsetted HelioPy, as I didn't do a very good job of building a contributor community around it.
Instead I focused my efforts on helping sunpy support heliospheric data analysis.
