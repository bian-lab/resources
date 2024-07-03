# TDT Close Loop Tutorial

*2024-07-02*
*By: Xueqiang Wang*

---

This tutorial helps you to output TTL controls (e.g., shaker External TTL) with TDT stream signals.

### [Pre-record](#pre-record)
As the power of frequence bands (e.g., delta 0.5~4 Hz, theta 4~9 Hz) may be variant between different mice, and also the EMG baseline mean and standard deviation value. We suggest that you should record a short period of signals to get the parameters for close loop detection. 

You can record a 6-hour data before you officially start the close loop detection, this can be done when the mice are habituation with the cable connected to the bank. 

And when you get the data, annotate the data with Wake, NREM, REM state by using MiSleep, after annotation, export the power spectrum of each state, calculate the delta and theta band power with the power spectrum list, and get the ratio of delta/theta, which will be used to detect NREM and REM in the following close loop detection.


