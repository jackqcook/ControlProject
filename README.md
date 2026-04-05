# ControlProject: Gain-Scheduled LQG Quadrotor Tracking

This project develops and tests a nonlinear quadrotor control pipeline for tracking a target drone.

We built:
- A 12-state nonlinear quadrotor model
- A hover trim and Jacobian-based linearization
- A gain-scheduled LQG controller for tracking a moving target
- Simulations 

## Animations

### 1) 3D Tracker vs Target Motion
This animation shows the tracker drone following the target trajectory in 3D space under the gain-scheduled LQG controller.

![3D tracker and target animation](tracker_target_3d.gif)

### 2) Camera/Measurement View
This animation shows the camera-style relative measurement view used by the tracker while it follows the target.

![Camera view animation](camera_view.gif)
