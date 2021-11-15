# A Collection of Cool fMRI Tools

This site provides a landing page to summarize resources within the ME-ICA organization.

!!! note
    The ME-ICA organization was originally created specifically for the ``tedana`` library,
    which uses independent components analysis (ICA) on multi-echo (ME) fMRI data.
    However, since ME-ICA's inception, we have expanded our scope to include a range of
    denoising, visualization, and processing tools for fMRI.
    We know that the name "ME-ICA" may be somewhat confusing, given our new scope,
    but we have chosen to keep it for now because we're used to it.


## tedana

[tedana][] does multi-echo denoising.


## rica

[rica][] is a Javascript-based tool for visualizing and manually classifying fMRI-based components.


## mapca

[mapca][] is a Python package for moving average principal components analysis.


## aroma

[aroma][] is a fork of the ICA-AROMA tool, which we have been working to make work purely with Python, in a BIDS-compatible manner.


## godec

[godec][] is a Python package for Go Decomposition, specifically built to work with fMRI data.


## ddmra

[ddmra][] is a Python package for performing distance-dependent motion-related artifact analyses.


## Scientific Conferences

We have documented the progress of tedana at the Organization
For Human Brain Mapping annual meetings. For several years,
we have shared the tedana poster, an interactive demonstration of the results
and compiled other multi-echo posters and presentations at the conference.
- [OHBM 2021][]
- [OHBM 2020][]
- [OHBM 2019][]

<!-- links -->
[aroma]: https://github.com/ME-ICA/aroma
[ddmra]: http://ddmra.readthedocs.io
[godec]: https://github.com/ME-ICA/godec
[mapca]: https://github.com/ME-ICA/mapca
[rica]: https://github.com/ME-ICA/rica
[tedana]: https://tedana.readthedocs.io
[OHBM 2021]: https://github.com/ME-ICA/ohbm-2021-multiecho
[OHBM 2020]: https://github.com/ME-ICA/tedana-ohbm-2020
[OHBM 2019]: https://github.com/ME-ICA/tedana-ohbm-2019