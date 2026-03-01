# Atom Robot (Swift Student Challenge 26)
Atom Robot is an interactive app playground designed to teach the science behind how robotic arms move. It guides users through the fundamentals of robot joints, degrees of freedom, Denavit Hartenberg conventions, forward kinematics, and inverse kinematics. Instead of relying only on equations, users explore a fully interactive 3D robot arm and see in real time how joint rotations affect the end effector. To apply these concepts, the app includes an Augmented Reality minigame called BalloonPop, where users control the robot in real space and test their understanding of workspace and motion.

# Technologies Used
The interface is built using SwiftUI, providing a clean and intuitive layout :
- The robotic arm was designed in Autodesk Fusion 360 and exported as a USDZ model, refined in Reality Composer Pro for Apple platforms.
- RealityKit handles 3D rendering, transformations, and animations.
- SceneKit is used where camera control is required for interactive exploration.
- The AR experience is powered by ARKit, enabling realistic surface detection, lighting, shadows, and occlusion.
- For high performance matrix calculations and kinematic transformations, I used Apple’s Accelerate framework to ensure smooth, real time robot motion.

# Accessibility
Accessibility was considered throughout the design process. The interface uses high-contrast colors, clear typography, and large touch targets for better readability and interaction. Interactive elements are clearly labeled to support VoiceOver. Animations are smooth and paced to avoid cognitive overload, ensuring the app remains approachable for beginners and users with diverse learning needs.


