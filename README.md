# gtlayout.library

This is the well known *gtlayout.library* for classic Amiga as used by *term*, refactored to build against NDK3.2

## [amigazen project](http://www.amigazen.com)

*The web, suddenly*

*Forty years meditation*

*Minds awaken, free*

**amigazen project** uses modern software development tools and methods to update and rerelease classic Amiga open source software. Our upcoming releases include a new AWeb, and a new Amiga Python 2.

Key to our approach is ensuring every project can be built with the same common set of development tools and configurations, so we created the ToolKit project to provide a standard configuration for Amiga development. All *amigazen project* releases will be guaranteed to build against the ToolKit standard so that anyone can download and begin contributing straightaway without having to tailor the toolchain for their own setup.

The original authors of the *gtlayout.library* software are not affiliated with the amigazen project. This software is redistributed on terms described in the documentation.

Our philosophy is based on openness:

*Open* to anyone and everyone	- *Open* source and free for all	- *Open* your mind and create!

PRs for all of our projects are gratefully received at [GitHub](https://github.com/amigazen/). While our focus now is on classic 68k software, we do intend that all amigazen project releases can be ported to other Amiga-like systems including AROS and MorphOS where feasible.

## About ToolKit

**ToolKit** exists to solve the problem that most Amiga software was written in the 1980s and 90s, by individuals working alone, each with their own preferred setup for where their dev tools are run from, where their include files, static libs and other toolchain artofacts could be found, which versions they used and which custom modifications they made. Open source collaboration did not exist as we know it in 2025. 

**ToolKit** from amigazen project is a work in progress to make a standardised installation of not just the Native Developer Kit, but the compilers, build tools and third party components needed to be able to consistently build projects in collaboration with others, without each contributor having to change build files to work with their particular toolchain configuration. 

All *amigazen project* releases will released in a ready to build configuration according to the ToolKit standard.

Each component of **ToolKit** is open source and like *gtlayout.library* here will have it's own github repo, while ToolKit itself will eventually be released as an easy to install package containing the redistributable components, as well as scripts to easily install the parts that are not freely redistributable from archive.

## Requirements

- Amiga or Amiga-compatible computer with latest operating system software
- SAS/C 6.58 setup according to ToolKit standard
- ctags for Amiga to generate Autodocs. This can be found at https://github.com/amigazen/ctags-amiga
- LibDescConverter for generating library headers. Can be obtained from https://gitlab.com/boemann/libdescconverter
- Autodoc for Amiga available in NDK3.2 as well as older developer CDs and NDKs
- NDK3.2R4

## Installation

- copy Libs/gtlayout.library to LIBS:
- copy the contents of the SDK folder to your SDK: assign setup by ToolKit

## To Do

- Refactor source code to modern LVO library standard
- Add VBCC build
- Add unittests - although since this requires a GUI app that may take some time
- Code review and hardening
- Remove CPU optimised builds and/or generate 5 CPU optimised versions!
- Remove unnecessary older files from project

## Contact 

- At GitHub https://github.com/amigazen/gtlayout.library
- on the web at http://www.amigazen.com/toolkit/ (Amiga browser compatible)
- or email toolkit@amigazen.com

## Aminet.readme
gtlayout.library V47.2 - GadTools layout toolkit

Changes done by Costel 'Cyborg' Mincea
Copyright stays with original author. Freely distributable.

Refactoring for NDK3.2 by amigazen project 2025

gtlayout.library V47.1 - GadTools layout toolkit

Copyright (c) 1993-1999 by Olaf `Olsen' Barthel
        Freely distributable.


This is the first complete stand-alone release of my "gtlayout.library" user
interface creation and management tool kit. I'm sad to say that the library
has not seen much development in recent years: other projects I attended to
took most of my time. Some of the code found in this library made its way into
the Workbench 3.5 and 3.9 updates, but I never quite found the time to merge
the bug fixes back. Well, another time, another place, I may eventually get my
act together and take care of that.

This is now the most current release, even though it is now almost two years
old. There are fewer bugs in it than in the previous versions, but there are
also still bugs lurking in it, especially the text edit gadget. Take care.


I'm grateful for any enhancement requests, bug reports and especially bug
fixes. My mail address is:

   Olaf Barthel
   Brabeckstr. 35
   30559 Hannover
   Federal Republic of Germany

My e-mail address is:

   olsen@sourcery.han.de

## Acknowledgements

*Amiga* is a trademark of **Amiga Inc**. 