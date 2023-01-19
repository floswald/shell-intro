---
title: Setup
---

You need to have a working Unix Shell (or something that mimicks it) installed for this lesson. We will be using a standard BASH shell.

## Data Sets

Download the [data zip file](data/data.zip) and unzip it to your Dektop.

## Software Setup

::::::::::::::::::::::::::::::::::::::: discussion

### Details

:::::::::::::::::::::::::::::::::::::::::::::::::::

:::::::::::::::: solution

### Windows

1. Install the [`GitForWindows](https://gitforwindows.org/) app. 
2. Make sure you have `R` installed before the next step! If not: [install it](https://www.r-project.org/)! 😀
2. Download the software carpentry setup script for windows from [here (`SWCarpentryInstaller.exe)](https://github.com/swcarpentry/windows-installer/releases/tag/v0.3), and execute it. It will setup some useful programs to work in the BASH console for you.

:::::::::::::::::::::::::

:::::::::::::::: solution

### MacOS

You should be all set. To make sure we have really everything we need, open `Terminal.app` (in &Applications > Utilities* or do `Cmd + Space` to get spotlight search and type *terminal*). Then paste this code and hit enter:

```
xcode-select --install
```

click on *install* (don’t click on *get Xcode*)

:::::::::::::::::::::::::


:::::::::::::::: solution

### Linux

All set. Maybe open a terminal and type

```
git --version
```

if that throws an error, install it with your package manager, e.g.

```
sudo apt install git-all
```

:::::::::::::::::::::::::

