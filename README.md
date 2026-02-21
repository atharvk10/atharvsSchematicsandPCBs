# atharvsSchematicsandPCBs
A repo that contains all of the PCBs and schematics I have created.

One Key Feature on Micromouse Designs:

    - 2025 Season: Vertical IMU Placement to Reduce Stack Height
        We reduced overall robot height by ~45 mm from 2024 Season to improve wall clearance and center-of-mass height. To enable this, we mounted the IMU vertically on the bottom-left edge of the PCB instead of flat. This saved board area and reduced stackup height without increasing PCB footprint.

    - 2026 Season: Transition to Full SMD + Integrated MCU 
        In 2026, we transitioned from breakout boards to a fully integrated SMD design using an STM32 MCU and TB6612FNG motor driver directly on the PCB. This reduced voltage line spikes, overall weight of the robot, stack height, and assembly complexity.
