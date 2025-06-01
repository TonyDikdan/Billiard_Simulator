# Billiard_Simulator
 an interactive web-based pool game that simulates billiard physics, shot prediction, and cue control. Here’s a summary of how it works and its main features:

#Simulator Overview
Physics Simulation:
The game simulates realistic billiard ball movement, including friction, spin (side and vertical), collisions (ball-ball and ball-wall), and pocket detection. Each ball is an object with position, velocity, spin, and color.

#Cue Ball Control:
You can aim the cue ball with your mouse. Click or drag to strike or reposition the cue ball (when in "ball in hand" mode).

#Predictive Trajectories:
The simulator can show predicted ball paths for your shot, including advanced multi-ball and decision-tree predictions. You can toggle and cycle through prediction modes using keyboard shortcuts.

#Customizable Controls:
The UI allows you to adjust shot power, spin, cue stick color and length, and toggle a 3D ball rendering effect. All controls can be accessed via sliders, color pickers, and keyboard shortcuts.

#Settings & Key Bindings:
There’s a settings modal where you can view and customize all keyboard shortcuts for actions like power, spin, prediction modes, and more.

#Game Modes:
By default, it sets up a standard 8-ball rack (16 balls), but you can cycle through different ball counts.

#Controls
Mouse:

Aim: Move the mouse to aim the cue.
Strike: Click the canvas to shoot when the cue ball is stationary.
Drag: Drag the cue ball to reposition it when in "ball in hand" mode.
UI Controls:

Shot Power: Adjust with the slider.
Spin: Adjust side and vertical spin with sliders.
3D View: Toggle for realistic ball shading.
Cue Stick Color/Length: Change with color picker and slider.
Reset, Ball In Hand, Release Cue Ball: Use buttons for quick actions.
Keyboard Shortcuts (default):

Arrow Up/Down: Increase/decrease shot power.

Arrow Left/Right: Adjust side spin.

W/S: Adjust vertical spin.

Z: Reset spin angles.

X: Reset shot power.

E: Reset game.

H: Ball in hand mode.

G: Release cue ball.

R/F: Reset or cycle ball count.

D/A/Q: Adjust or cycle cue stick length.

C: Cycle cue stick color.

B: Toggle 3D view.

O/K/I/L/J/M/P: Change prediction modes and toggle sticky prediction.

You can view and customize all key bindings in the Settings modal.
