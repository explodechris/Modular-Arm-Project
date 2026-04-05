# Modular-Arm-Project
Modular 3-DOF modules using a parallel kinematic mechanism (pitch, yaw, and extension).

--- Design ---\
• Designed limits: 220˚ sweep/axis, 2.4× body height extension stroke per module.\
• Materials: SLS nylon (structural), SLA resin (precision interfaces).

--- Progress ---\
• Proof-of-concept prototype built.\
• Designed for manufacturing around SLS and SLA-specific constraints: thermal bleed, over-sintering on unsupported geometry, and fluid-wash tolerances.\
• Traded off over-constrained PKM design for structural stability and manufacturability.\
• Custom motor driver PCB: 10×15mm, DRV8871 IC, distributed power architecture, stacked board design. Trace widths calculated for peak stall current, thermal dissipation through thermal vias, and bulk capacitance engineered within 1/2 the size of the commercially available equivalent. Full PCB design and PCBA.\
• Interfaces with ESP32 and MPU6050 IMU for closed-loop position control (firmware in progress).
