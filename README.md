6-axis arm for proof of concept. The robot is an enabler to develop competencies in mechatronics and programming. 
Very small with low payload; the model will be scalable once software is ready.

Mk2 frame will be entirely bespoke, primarily constructed using 3D-printed components. Steppers will be replaced with brushless DC motors; higher speeds will permit use of transmission for increased torque and low/zero backlash.

Construction
- Main links constructed with standard LEGO technix parts and connections
- Motor mounts are bespoke designs and 3D-printed to fit
- Transmission is uing 2GT belts, standard LEGO Technic gears (introducing backlash) and modified bespoke gears (for belts and motors)
- Interchangeable gripper; pilot with 2-finger gripper (SG90 servo for actuation)

Hardware
- Raspberry Pi Model B Rev 2.0 for processing (Python)
- Arduino MEGA for hardware control (C++)
- 28BYJ-48 12V stepper motors for power, one per axis (azis_2 uses 2x motors to deliver appropriate torque); limit switches for homing
- A4988 motor drivers
- 2MP camera for 2D computer vision

Software
- OpenCV for vision processing
