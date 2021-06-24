# Visiview - Change Timepoint Interval [![DOI](https://zenodo.org/badge/373520807.svg)](https://zenodo.org/badge/latestdoi/373520807)

Script wrote in Python using Visiview API to control the Visiview acquisition software for microscope.
The script allow to change the time interval between timepoints after a given time.

Initially made for FURA-2 recording when the thapsigargin-dependent calcium elevation is a slow mechanism that does not require high temporal resolution.
But the same experiment is followed by a calcium re-addition which is a much faster process that needs a faster recording rate.

For each channel, you can change the timepoint interval, the exposure time and so on.
