2D Football Penalty Shootout

A simple 2D penalty game made in Unity. Aim with the mouse, charge your power, and try to score past the goalkeeper before time runs out.

Made for the course Game Programming using Unity (Project 14).

How to play
Move the mouse to aim (the yellow dot is your target).
Hold the left mouse button to charge the power bar.
Release the button to shoot.
Score 3 goals in 5 shots within 60 seconds to win.
Features
Aim with the mouse and adjust shot power with a power gauge
Ball physics (impulse force, damping, bouncing off the posts and keeper)
Moving goalkeeper
Goal detection and save detection
Score and shots counter
Match timer
Win and lose screens with a Play Again button
Sound effects
Unity concepts used

Input System, Rigidbody2D, Colliders (including a trigger for the goal), Physics, and UI (Canvas, Slider, TextMeshPro, Button).

Main scripts
Script	What it does
BallShooter.cs	Aiming, power charging, shooting, goal / save / miss result, ball reset
Goalkeeper.cs	Moves the goalkeeper to random positions
GoalZone.cs	Trigger behind the keeper that detects a goal
GameManager.cs	Score, shots, timer, messages, win and lose screens
SoundManager.cs	Plays the sound effects
How to open the project
Install Unity Hub and Unity 6 (6000.6.0f1).
Download or clone this repository.
In Unity Hub click Add > Add project from disk and choose the project folder.
Open the scene Assets/Scenes/Game and press Play.
