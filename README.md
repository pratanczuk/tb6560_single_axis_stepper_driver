
# TB6560 Single Axis Stepper Driver PCB Design

This repository contains the PCB design files for a single-axis stepper motor driver based on the TB6560 IC. The design is suitable for controlling stepper motors in projects that require precise microstepping.

## Project Overview

The TB6560 is a highly reliable stepper motor driver chip, and this design aims to make it easier to integrate into custom CNC machines, robotics projects, and other applications requiring precise motor control. This PCB supports multiple microstepping resolutions and is designed for simple integration with other hardware.

## Repository Contents

-   **photo**: An image of the completed PCB for quick reference.
-   **$savepcb.000** & **$savepcb.brd**: Backup and board files for PCB design, useful for revision history.
-   **LICENSE**: The licensing file for this project.
-   **dip_switch_piano.mdc** & **dip_switch_piano.mod**: Model and module files for a piano-style DIP switch, used in configuration settings.
-   **ds_dp06.wrl**: 3D model file for visualizing the PCB design.
-   **microstep4axis.lib**: Library file defining various components used in the PCB design.
-   **tb6560_single_axis_stepper_driver**:
    -   **.000**, **.bak**, **.brd**, **.cmp**, **.dsn**, **.lst**, **.net**, **.pro**, **.sch**: Main design files for the TB6560-based single-axis stepper driver PCB. These include the schematic (`.sch`), board layout (`.brd`), project configuration (`.pro`), and various other files for design integrity and versioning.
    -   **-cache.bak** & **-cache.lib**: Cached files for library management in the design software.

## Getting Started

1.  Clone or download the repository.
2.  Open the `.sch` or `.brd` files in your preferred PCB design software to view the schematic and layout.
3.  Use the library files (`.lib`) and model files (`.mod`, `.mdc`, `.wrl`) as needed to modify or visualize the design.
