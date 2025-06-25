# MuJoCo Model for Horizontal Vibration of Ultra-High-Speed Elevator (DFCCA Control)
## Model Introduction
-**Physical System**: A five-body coupling system consisting of guide rails, guide shoes, car frame, shock absorbers, and elevator car.
## Quick Start
1. **Install MuJoCo**.
2. **Load the Model**:
    ```python
   import mujoco
   model = mujoco.MjModel.from_xml_path("elevator.xml")
   data = mujoco.MjData(model)
3. **Visualization**:
   Drag and drop scenes/elevator_scene.xml into MuJoCo Simulate.exe
    


    
