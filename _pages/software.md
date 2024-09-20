---
layout: page
title: Software
permalink: /software/
nav: true
nav_order: 3
horizontal: false
---
I have a long history of contributing to open source software, especially in the scientific Python ecosystem. Here are some of the large community packages I've worked on.

# Current projects

## [zarr-python](https://github.com/zarr-developers/zarr-python)
2023 -

I'm a core developer of zarr-python, and have taken the lead on user-facing improvements including adding typing to the library and adding complete API documentation.

## [napari](https://napari.org/stable/)
2022 -

I've worked on and off fixing bugs and adding typing to napari, to reduce technical debt and increase maintainability.

## [Matplotlib](https://matplotlib.org/)
2017 -

This is where I stated my adventure in open source.
I filed my first feature request [in April 2016](https://github.com/matplotlib/matplotlib/issues/6272), opened my first pull request [in May 2016](https://github.com/matplotlib/matplotlib/pull/6369), and became a maintainer in January 2017.
Since then I've done a wide range of fixing bugs, triaging issues, adding new features, and improving documentation.

# Past projects

## [pudl](https://catalyst.coop/pudl/)
2023

The Public Utility Data Liberation project, or `pudl` for short, is a project to make publicly available data publicly *usable*, by cleaning and standardising data from different sources in a single database.
I focused on improving the performance of the data pipelines by parallelising data ingestion from multiple sources.

## [sunpy](https://sunpy.org/)
2017 - 2023

I started contributing to `sunpy` in [Nov 2017](https://github.com/sunpy/sunpy/pull/2289), became a maintainer shortly after that, helping see sunpy through from the transition to the fist stable version (v1.0).
I've done a major re-write of the core Map class, added support for reading widely used file formats, made significant performance improvements across the library, and contributed many other bug fixes and issue reports.
I was also the release manager for two years.

## [pfsspy](https://pfsspy.readthedocs.io/en/stable/)
2019 - 2023

Potential field source surface (PFSS) modelling is the most popular way to model the magnetic field of the Sun.
Despite this there was no documented, open source tool to do this modelling, until I created `pfsspy`.
Since then it has been [used in almost 50 papers](https://ui.adsabs.harvard.edu/user/libraries/hfLAIo9DQw6yuNlLkn40GQ), including some of the key results from NASA's flagship [Parker Solar Probe](https://science.nasa.gov/mission/parker-solar-probe/) and ESA's flagship [Solar Orbiter](https://www.esa.int/Science_Exploration/Space_Science/Solar_Orbiter) missions.

## [HelioPy](https://github.com/heliopython/heliopy)
2016 - 2022

This is the first package I built from the ground up myself, to fill a gap for  doing data science with Heliospheric datasets.
I eventually sunsetted `HelioPy`, and most of the features got subsumed into `sunpy`.
