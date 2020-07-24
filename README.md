# OpenFabric
[![MIT License](https://img.shields.io/apm/l/atomic-design-ui.svg?)](https://github.com/tterb/atomic-design-ui/blob/master/LICENSEs)
![GitHub contributors](https://img.shields.io/github/contributors/merledu/OpenFabric)
![GitHub issues](https://img.shields.io/github/issues/merledu/OpenFabric)
![GitHub contribution](https://img.shields.io/badge/contribution-open%20for%20everyone-blueviolet)
![GitHub status](https://img.shields.io/badge/status-initial%20stage-blue)

Open source generator for creating customisable bus fabrics (Point-to-point, Shared Bus, CrossBar Switch) according to the user's requirements and the protocol (TileLink, AMBA, Wishbone) provided by the user.

## What this project is about?
OpenFabric helps users create configurable bus fabrics according to the interfaces required. For e.g a user can specify AHB based protocol with 3 master and 4 slaves and a topology of Crossbar switch. The generator can then generate the appropriate RTL providing the interface and the document to the user on how to interface the fabric with their own custom SoC.


