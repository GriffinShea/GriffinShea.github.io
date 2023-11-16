# DEVELOPMENT PORTFOLIO
### [ASTROSURFER DEMO](#Astrosurfer) / [BUGMAN ASSAULT](#BUGMAN) / [SVG CURLING](#SVG)

<a id="Astrosurfer"></a>
## ASTROSURFER DEMO
<div class="row">
	<div class="column">
		<h5>Project Information</h5>
		<p>This short video demonstrates some of the graphics and physics capabilities of my custom game engine. It supports rigid-body dynamics, collision response, as well as pin and angle constraints which are used to simulate a free moving ragdoll. The engine additionally includes a 3D graphics renderer build in OpenGL and a system for game-object and collision event scripting. All work is my own but I use three game development libraries: PyGame (to create the window and collect input), PyOpenGL (for rendering), and PyGLM (for vector/matrix math).</p>
		<h5>Technical accomplishments:</h5>
		<ul>
			<li>Designed with a property-centric (analogous to data-oriented) architecture to optimize memory utilization and enable easy parallelization of game data updates using graphics hardware</li>
			<li>3D graphics renderer built with OpenGL supporting deferred shading with three-term interpolated lighting, shadow mapping, screen-space effects, and supporting particle effects, custom tessellation, geometry, and texture shaders</li>
			<li>Custom 3D physics-based animation system using Verlet integration, rigid-body dynamics, and physics constraints to simulate forces and torques, collisions between objects, doors, furniture, animated ragdolls, and more</li>
			<li>Three-stage collision detection algorithm using a k-d tree, axis-aligned bounding boxes, <a href="https://caseymuratori.com/blog_0003">GJKSM</a> intersection tests to confirm collisions, and expanding polytope algorithm to find and return contact information</li>
			<li>A tool for generating GLSL programs from a template using an input string to select from a variety of lighting and shading options, easing and unifying the task of writing new graphics shaders</li>
		</ul>
	</div>
	<div class="column">
		<iframe src="https://www.youtube.com/embed/4wh63CocHC8" allowfullscreen></iframe>
	</div>
</div>

<a id="BUGMAN"></a>
## BUGMAN ASSAULT [download](https://github.com/GriffinShea/BUGMAN-ASSAULT)
<div class="row">
	<div class="column">
		<h5>Project Information</h5>
		<p>Built in Unity as a course project for COMP-4501 (Advanced Computer Game Design and Development) at Carleton University (February - April 2022).</p>
		<h5>Technical accomplishments:</h5>
		<ul>
			<li>Designed game objects and interactions using class-responsibility-collaboration cards and a game design document to itemize and prioritize development tasks in order to meet deliverable deadlines</li>
			<li>Developed a real-time strategy game in Unity utilizing game engine functions to fulfill design guidelines and provide a player experience emphasizing strategic resource management and decision making</li>
			<li>Programmed high-level game logic in C# using a component-based architecture to organize and reuse code for update steps and interactions common between object types</li>
			<li>Implemented artificial intelligence and animation using finite-state machines to reduce the complexity of controlling the autonomous behaviors of player-controlled units and enemies</li>
		</ul>
		<p>The repository includes a Windows executable build and the Unity source project folder.</p>
	</div>
	<div class="column">
		<img src="images/BUGMAN_ASSAULT.png?raw=true"/>
	</div>
</div>

<a id="SVG"></a>
## SVG CURLING [download](https://github.com/GriffinShea/SVG_Curling)
<div class="row">
	<div class="column">
		<h5>Project Information</h5>
		<p>SVG curling is a two-player digital version of everyone's favourite rock throwing ice sport. Two web browsers connect to a central server that coordinates the shared game state in real-time through a web socket connection. Backend communication logic is carefully defined to avoid deadlocks and disallow abuse from a browser. Developed in Javascript with the .NET framework, graphics are generated using the SVG (Scalable Vector Graphics) library.</p>
		<p>Created as an assignment for COMP-2406 (Fundamentals of Web Applications) at Carleton University (November 2018).</p>
		<p>The repository contains all the files needed to run the game and a readme file which should instruct you how to run it.</p>
	</div>
	<div class="column">
		<img src="images/curling.png?raw=true"/>
	</div>
</div>

