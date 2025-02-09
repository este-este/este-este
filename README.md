- 👋 Hi, I’m @este-este!
- 👀 I’m interested in robotics in general and the Petoi Bittle quadraped robot in particular.
- 🌱 For the Bittle robot, I am working on both a Windows laptop based controller program and a customized fork of the OpenCatEsp32 source code.  The idea is to provide autonomous behavior for the robot where the BiBoard is the central nervous system and the laptop is the "Bittle brain".
    - The communication is wireless, using Bluetooth, but wireless via wifi is also a possibility.  So far, only a version of the customized OpenCatEsp32 source code is available (https://github.com/este-este/OpenCatEsp32_este/tree/este_release_001-00-00).  The laptop controller is still a WIP and is not yet available.
    - The current OpenCatEsp32 customizations modify the token / command system, especially as it applies to the use of the IMU module for robot inertial guidance.  In particular, it provides bluetooth serial command access to some IMU functions (on, off, toggle, calibrate) and sends IMU telemetry data packets back to the laptop controller program that it can use to then send movement commands to the robot to e.g. maintain a navigation heading.  The ability to directly set the gait speed is also provided.
- 💞️ I’m looking to collaborate with others interested in such topics

<!---
- 👋 Hi, I’m @este-este
- 👀 I’m interested in robotics in general and the Petoi Bittle robot in particular
- 🌱 I’m currently learning everything I can about the OpenCatEsp32 source code for the Petoi Bittle robot
- 💞️ I’m looking to collaborate with others interested in such topics
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

este-este/este-este is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
