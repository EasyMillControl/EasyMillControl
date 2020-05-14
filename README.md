[![GitHub license](https://img.shields.io/badge/license-Apache2-brightgreen)](https://github.com/EasyMillControl/EasyMillControl/blob/master/LICENSE)
[![Languages](https://img.shields.io/badge/languages-Python3/C++-blue)](https://img.shields.io)

# [EasyMillControl](https://github.com/EasyMillControl/EasyMillControl)
3D interface to control your CNC Mill or Lathe

## Description
Change your CNC programming experience with this 3D GUI controller. Program the operations using an intuitive interface, and forget gcode 😀.<br/>
See our videos on [our Youtube channel](https://www.youtube.com/channel/UCZ0cAFyQO54Unen8guWqejg) (videos to come...)

## Features
  * High level description of the operations to perform (avoid gcode)
  * Simulation of the machine and accessories
  * Collision avoiding through simulation of the operation
  * Easy measurements (e.g. center and radius with only 3 contact points from the touch probe, ...)
  * Easy insertion of a workpiece into the interface's model using geometric constraints (with optional touch probe for automatic location)
  * Easily add/remove vices or rotary tables by automatic position location (with touch probe)
  * Angle compensation (e.g. measure the angle of the vice with the touch probe, and recompute drilling holes coordinates in the reference frame of the skewed vice)
  * And more!
  
## Installation
```bash
git clone https://github.com/EasyMillControl/EasyMillControl
```

## Links
  * Main [project's page](http://www.easymillcontrol.com/) (currently pointing to this github repo)
  * [Our Youtube channel](https://www.youtube.com/channel/UCZ0cAFyQO54Unen8guWqejg)
  * [Our Facebook page](https://www.facebook.com/Easymillcontrol-100501448344151/)
  
## Runtime dependencies
(for licensing information, please refer to the documentation of each projet, the information given here may be incomplete or not fully accurate)
  * [Panda3D](https://github.com/panda3d/panda3d) python3 game engine (modified BSD license)
  * [g3log](https://github.com/KjellKod/g3log)  "crash safe" logger (Unlicense license)
  * [g3log bindings and python wrapper](https://github.com/JoelStienlet/g3logPython) (Unlicense license)
  * [NNG](https://github.com/nanomsg/nng)  nanomsg-next-generation (MIT license)
  * [python bindings for NNG](https://github.com/codypiersall/pynng.git)  (MIT license)
  * [wxwidgets](https://github.com/wxWidgets)  (wxWindows Library Licence (a modified LGPL to allow proprietary software))
  * [python bindings for wxwidgets](https://github.com/wxWidgets/Phoenix) 
  * [RNP](https://github.com/rnpgp/rnp)  openPGP library (combination of works under BSD 2-clause, BSD 3-clause and Apache 2 licenses)
  * [Bullet3](https://github.com/bulletphysics/bullet3) physics (zlib license)
  * [Pybind11](https://github.com/pybind/pybind11) expose C++ to python  (BSD 3-clause license)
  * [libarchive](https://github.com/libarchive/libarchive)  (BSD 2-clause, BSD 3-clause, Apache 2)
  * [KAITAI runtime library](https://github.com/kaitai-io/kaitai_struct)  binary descriptions (Runtime library: dual MIT or Apache 2 license)
  * [TOML](https://github.com/uiri/toml)  in python (MIT license)
  * [sympy](https://github.com/sympy/sympy)  (combination of works under the BSD 3-clause license)
  * [tinyobjloader](https://github.com/tinyobjloader/tinyobjloader) (MIT license)
  * [cpython](https://github.com/python/cpython) python3 runtime (Python software foundation license V2)
  
## Build dependencies
  * [Meson](https://github.com/mesonbuild/meson)  build system (Apache-2 license)
  * [KAITAI compiler](https://github.com/kaitai-io/kaitai_struct) binary descriptions (compiler: GPLv3+ license (code not linked))
  And of course a C++17 compiler.
  
## Other tools required
  * [FreeCAD](https://github.com/FreeCAD/FreeCAD) to create the models (LGPLv2 license)


  
