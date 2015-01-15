---
layout: post
title: Logic Circuits
language: Logic circuit
time: Senior year, 2012
image: /images/logic/logic2.jpg
thumb: /images/logic/logic2-thumb.jpg
---

My Organization of Computer Systems class involved a lot of circuit building. 

<h3>Elevator</h3>
This simple, three floor elevator logic circuit was designed and simulated for my Organization of Computer Systems class. In the simulation, you’ll notice three “lights” in the upper left hand corner. Those are the buttons inside the elevator to select the floor you would like to go to. On the right bottom side, you’ll notice eight more lights. The represent, in left to right order:

1) Elevator motor going up (green = on)

2) Elevator motor going down

3) Lobby door open (green)/closed (red)

4) 1st floor door open

5) 2nd floor door open

6) Elevator located at lobby level (green = yes)

7) Elevator located at 1st floor

8) Elevator located at 2nd floor

If you watch the video closely, you can see the elevator moving up and down and tell its different locations by the indicator lights.

The logic for this circuit involves a truth table in a look up table handing the next state, and another look up table handling the motor, doors, and indicator lights.

This simulation was completed in Dr. Michael Black’s Computer Simulator, available [here](http://rodent.cs.american.edu/mblack/simulator)

<h3>Links</h3>

<a href="http://www.youtube.com/watch?v=UwGpW9k9yF8" target="_blank">Watch a video</a>

<h3>Traffic Light</h3>

This logic circuit controls the traffic lights for a simple T intersection. It is provided in simulated form and in a physical circuit, which consists of two EPROMs, a D-Flip Flop and 6 LEDs.

<h3>Links</h3>

<a href="http://www.youtube.com/watch?v=YeH2NMJ2Rlc" target="_blank">Watch a video</a>

<h3>Images</h3>
<a href="/images/logic/logic1.jpg" target="_blank"><img src="/images/logic/logic1-thumb.jpg" alt="Adder"></a>
<a href="/images/logic/logic2.jpg" target="_blank"><img src="/images/logic/logic2-thumb.jpg" alt="Adder"></a>

-----