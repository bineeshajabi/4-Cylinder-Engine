# 4-Cylinder-Engine

This project showcases the dynamic simulation of a **4-cylinder internal combustion engine** using **MATLAB/Simscape Multibody**. The goal is to model the engine’s mechanical components and observe realistic piston-crankshaft dynamics.

## Features

- Realistic simulation of a 4-cylinder inline engine.
- Modeled pistons, crankshaft, and connecting rods.
- Visualized synchronized piston movement and crankshaft rotation.

## Engine Components and Their Functions

This model includes the following key components, each vital to the engine’s operation:

### 1. Crankshaft
- **Purpose:** Converts the reciprocating motion of pistons into continuous rotational motion.
- **Role:** Drives the flywheel and transfers energy to the drivetrain.

### 2. Connecting Rod
- **Purpose:** Links the piston to the crankshaft.
- **Role:** Transmits force from combustion to rotate the crankshaft.

### 3. Connecting Rod Cover
- **Purpose:** Secures the connecting rod to the crankshaft journal.
- **Role:** Forms a bearing surface that holds the crankshaft in place at the connecting point.

### 4. Piston
- **Purpose:** Moves up and down inside the cylinder as combustion occurs.
- **Role:** Translates combustion pressure into mechanical motion through the connecting rod.

### 5. Piston Rings
- **Purpose:** Seal the gap between the piston and cylinder wall.
- **Role:** 
  - Prevent gas leakage (compression rings)
  - Control oil movement (oil rings)
  - Improve combustion efficiency

### 6. Piston Rod (Wrist Pin Interface)
- **Purpose:** Connects the piston to the connecting rod via a pivot (gudgeon pin).
- **Role:** Allows the piston to pivot as it moves up and down.

![image alt](4 _cylinder-engine(drawing sheet).PDF)
