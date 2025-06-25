# MuJoCo Model for Horizontal Vibration of Ultra-High-Speed Elevator
## Model Introduction
-**Physical System**: A five-body coupling system consisting of guide rails, guide shoes, car frame, shock absorbers, and elevator car.
## Quick Start
1. **Install MuJoCo**.
2. **Visualization**:
   Drag and drop scenes/elevator_scene.xml into MuJoCo Simulate.exe
3. **Load the Model**(Python):
    ```python
   import mujoco
   model = mujoco.MjModel.from_xml_path("elevator.xml")
   data = mujoco.MjData(model)  


    
