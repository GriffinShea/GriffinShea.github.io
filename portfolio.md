# DEVELOPMENT PORTFOLIO
### [ASTROSURFER DEMO](#Astrosurfer) / [BUGMAN ASSAULT](#BUGMAN) / [SVG CURLING](#SVG)

<a id="Astrosurfer"></a>
## ASTROSURFER DEMO
<div class="row">
	<div class="column">
		<p>I am excited to finally release the first public demo of Astrosurfer, a game created in my 3D property-centric game engine. The video to the left showcases some of the physics capabilities of the engine. It includes fully fledged rigid-body dynamics, collision response, as well as pin and angle constraints which are used to simulate free moving ragdolls. This little game was created with just over 500 lines of user defined code (i.e. excluding core engine features).</p>
		<p>The engine additionally includes a 3D graphics renderer build in OpenGL and a system for game-object and collision event scripting. I initially chose to develop in Python to facilitate accessibility and modding for less-experienced programmers and hobbiests curious about game engines. More information about the engine follows in the feature list below:</p>
		<ul>
			<li>Designed with a property-centric (analogous to data-oriented) architecture to optimize memory utilization and enable easy parallelization of game data updates using graphics hardware</li>
			<li>3D graphics renderer build with OpenGL and GLSL shaders, supporting deferred shading with three-term interpolated lighting, shadow mapping, screen-space effects, and supporting particle effects, custom tessellation, geometry, and texture shaders to facilitate complex and visually interesting graphics</li>
			<li>Real-time 3D physics system with Verlet integration, rigid-body dynamics, and constraints to simulate application of forces and torques to bodies, collisions, animated ragdolls, and more</li>
			<li>Optimized collision detection performance using a k-d tree to partition space and AABB intersection tests to comb through potential collisions, minimizing the number of costlier GJKSM intersection tests</li>
			<li>A tool for generating GLSL programs from a template using an input string to select from a variety of lighting and shading options, easing and unifying the task of writing new graphics shaders</li>
		</ul>
		<p>Note that this is a work in progress. Suggestions and questions are welcome! Stay tuned for a full release of Astrosurfer coming soon...</p>
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
		<p>SVG curling is a two-player digital version of everyone's favourite rock throwing ice sport. Two web browsers connect to a central server that coordinates the shared game state in real-time through a web socket connection. Backend communication logic is carefully defined to avoid deadlocks and disallow abuse from a browser. Developed in Javascript with the .NET framework, graphics are generated using the SVG (Scalable Vector Graphics) library.</p>
		<p>Created as an assignment for COMP-2406 (Fundamentals of Web Applications) at Carleton University (November 2018).</p>
		<p>The repository contains all the files needed to run the game and a readme file which should instruct you how to run it.</p>
	</div>
	<div class="column">
		<img src="images/curling.png?raw=true"/>
	</div>
</div>

