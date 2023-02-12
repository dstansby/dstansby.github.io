---
layout: page
title: Fundable projects
permalink: /fundable_projects/
nav: true
nav_order: 2
horizontal: false
---

This is a list of medium - large sized projects that I would like to work on, but don't currently have funding for.
If you know where I can get funding from to buy out my time for these, please let me know!
As long as the money can be sent to UCL, I should be able to work on them as part of my day job.

### How much CO2 does running continuous integration on open source projects emit?
Here's my best guess for one months GitHub actions activity on Matplotlib:

![Graph showing estimated CO2 emissions as a result of running continuous integration on the matplotlib/matplotlib repository.](/assets/img/mpl_co2.svg "Graph")

The headline answer seems to be "not much".
Every time I commute from Cambridge to London I'm responsible for ~ 8kg CO2e (see Our World in Data for [transport emissions in the UK](https://ourworldindata.org/travel-carbon-footprint)), so one person doing that eight times a month is already more than the entire CO2 emitted by Matplotlib's CI!

But I'd like to make this more systematic and refine it, and maybe publish a short paper on it.
For info on my approach so far, see the README at [dstansby/ci-impact](https://github.com/dstansby/ci-impact).

### Building accessibility into `matplotlib` windows
[Matplotlib](https://matplotlib.org/) has a number of interactive [backends](https://matplotlib.org/stable/users/explain/backends.html) that allow users to interact with plots.
So far no-one has done an accessibility audit on these backends - is it possible for users with accessibility requirements to use them, and if not what needs to happen?

This project would carry out an accessibility audit, and use the results to work on making interactive plotting in Matplotlib accessible.

Relevant issues:
- [MacOSX backend windows have no accessibility data](https://github.com/matplotlib/matplotlib/issues/24608)
