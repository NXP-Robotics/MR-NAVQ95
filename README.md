# MR-NAVQ95
This repository contains the MR-NAVQ95 hardware design items.
MR-NAVQ95 includes the following differentiating features:
- Wide input power up to 52(60V peak)
- SPE network switch module with 2x1000BaseT1 and 6x100BaseT1 (Two wire/single pair automotive ethernet)
- 2x PCIe. M.2 B and M to support accelerators, NVME and Radio modems/cellular.
- Modular IO including typical IMU components found in state of the art Drones.
- Linux Foundation Dronecode compliant interfaces and connectors.
- Low cost modular adapter boards for cameras or serdes.

See [MR-NAVQ95/Mr Solutions MR-MR-NAVQ95-RevB description slides (Public).pdf](<https://github.com/NXP-Robotics/MR-NAVQ95/blob/main/Mr Solutions MR-NavQ95-RevB description slides (Public).pdf>) also for a short overview presentation.

Please note: This is an open Proof of Concept (POC) deisign and is not officially supported by NXP.
The design is enabled with a Vanilla UbuntuPOC layered on top of existing NXP Yocto build.
This means ROS2 main installs via `apt install ros2`.

The unsupported software repo may be found here:
https://github.com/NXP-Robotics/imx-manifest-navq95-private
