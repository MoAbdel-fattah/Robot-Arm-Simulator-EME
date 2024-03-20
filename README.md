# Robot-Arm-Simulator-EME
The code utilizes a graphical user interface (GUI) for easy interaction and includes 3D visualization. It assumes the presence of fkine4DOF (forward kinematics) and ikine4DOF_v2 (inverse kinematics) functions, potentially from the Robotics Toolbox.
# Description:
This MATLAB code simulates a 4-DOF (Degree-of-Freedom) robot arm with forward and inverse kinematics capabilities. It allows you to:
- Specify joint angles (Theta 1-4) in degrees.
- Visualize the robot arm's movement in 3D space.
- Calculate the end-effector position (X, Y, Z) based on joint angles (forward kinematics).
- Determine the required joint angles to reach a desired end-effector position (inverse kinematics).
## Features:
- Graphical user interface (GUI) for user interaction.
- 3D visualization of the robot arm using plot3 and SerialLink.plot.
- Forward kinematics calculation using fkine4DOF (assumed function).
- Inverse kinematics calculation using ikine4DOF_v2 (assumed function).
- Joint angle limitations (modify angle_range_motor if needed).
## Requirements:
- MATLAB (tested with specific version, if applicable)
- Robotics Toolbox (if fkine4DOF and ikine4DOF_v2 are from there)
## Installation:
- Download the code files (replace with specific instructions).
- Ensure MATLAB and the Robotics Toolbox (if necessary) are installed.
## Usage:
- Open the main MATLAB script (e.g., Robot.m).
- Enter desired joint angles (Theta 1-4) in the GUI text boxes.
- Click the "Forward" button to calculate and visualize the end-effector position.
- Alternatively, enter the desired end-effector position (X, Y, Z) in the GUI text boxes.
- Click the "Inverse" button to calculate the required joint angles.
## Notes:
- Double-check the functionality of fkine4DOF and ikine4DOF_v2 (modify placeholders if they have different names).
- Adjust angle_range_motor to match your robot arm's actual joint angle limitations.
- Consider adding error handling or validation for user inputs.
- You might need to modify the code depending on your specific robot arm parameters and desired functionalities.
## Further Development:
- Implement error handling for invalid user inputs.
- Enhance the GUI for a more user-friendly experience.
- Add animation capabilities to visualize robot arm movement.
- Integrate with other simulation tools or hardware controllers.
## Disclaimer:
- This code is provided for educational and research purposes only. It may require modifications for specific applications. Use at your own risk.
