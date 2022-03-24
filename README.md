# An introduction to scikit-rf, an Open Source Python Package for Microwave Network Creation, Analysis and Calibration  

The rapid proliferation of telecommunication and radio-frequency (RF) applications had led to a demand for efficient and convenient tools to design and characterize these devices. [scikit-rf](http://scikit-rf.org/) is a free and open-source Python package designed to make RF/Microwave engineering both robust and approachable. The package provides a modern library for RF network analysis, circuit building, calibration, and simulation.

Besides offering standard microwave network operations, such as reading/writing Touchstone files (.sNp files), connecting or de-embedding N-port networks, frequency/port slicing, concatenation or interpolations, it is also capable of advanced operations such as Vector Network Analyzer (VNA) offline calibrations, time-gating, vector fitting, interpolating between an individual set of networks, deriving network statistical properties and support of Virtual Instruments for direct communication to VNAs. The package also allows straightforward plotting of rectangular plots (dB, magnitude, phase, group delay, etc.), Smith Charts or automated uncertainty bounds.

This repository contains materials to:
* introduce scikit-rf during a 15-20 min talk, 
* give an interactive short course on scikit-rf, to explain and learn some of the capabilities of the package. 

The Jupyter notebooks in the directory `Short_Course` are intented to be use with the [RISE Jupyter extension](https://github.com/damianavila/RISE), which allows you to instantly turn your Jupyter Notebooks into a slideshow.
