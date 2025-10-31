[README.md]

# Dafx-Tape

<p align="center">
  <a href="https://github.com/whisprer/dafx-tape/releases"> 
    <img src="https://img.shields.io/github/v/release/whisprer/dafx-tape?color=4CAF50&label=release" alt="Release Version"> 
  </a>
  <a href="https://github.com/whisprer/dafx-tape/actions"> 
    <img src="https://img.shields.io/github/actions/workflow/status/whisprer/dafx-tape/lint-and-plot.yml?label=build" alt="Build Status"> 
  </a>
</p>

![Commits](https://img.shields.io/github/commit-activity/m/whisprer/dafx-tape?label=commits) 
![Last Commit](https://img.shields.io/github/last-commit/whisprer/dafx-tape) 
![Issues](https://img.shields.io/github/issues/whisprer/dafx-tape) 
[![Version](https://img.shields.io/badge/version-3.1.1-blue.svg)](https://github.com/whisprer/dafx-tape) 
[![Platform](https://img.shields.io/badge/platform-Windows%2010%2F11-lightgrey.svg)](https://www.microsoft.com/windows)
[![Python](https://img.shields.io/badge/python-3.8%2B-blue.svg)](https://www.python.org)
[![License](https://img.shields.io/badge/license-MIT-green.svg)](LICENSE)

<p align="center">
  <img src="dafx-tape-banner.png" width="850" alt="Dafx-Tape Banner">

# DAFX-Tape
Supplementary material for the paper 'Efficient emulation of tape-like delay modulation behavior'

The 4 wavefiles __dly\_test\_vl.wav ... dly\_test\_p.wav__ contain the recordings of the output of a feedback delay with the delay core being implemented with algorithms __(vl) ... (p)__, as introduced in the __Results__ section of the paper. The recordings are done for a short piece of a lowpass-filtered sawtooth appearing at the delay input and then modulating the equivalent tape speed according to the automation curve below (which plots the steady-state delay time `L/v` against time `t`).

![Alt text](pics/curve1a.png "Modulation curve")

The curve demonstrates speedup/slowdown jumps in tape speed as well as a gradual change of the tape speed.
