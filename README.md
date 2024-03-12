<h1>2D Gravity Simulator</h1>
<h6>OOP ESP - 2nd Semester</h6>

<h4>Breif Intro</h4>
<p>By using Newton's Equations and Projectile motion, a set of planets can be created that mimic the solar system with planets revolving around a central planet or a star. The simulation is shown on the screen in where new planets can be added. As the simulation runs, the details of the simulation are added to a database at the backend.</p>

<h3>Technologies:</h3>
<ol>
  <li>Java</li>
  <li>JavaFX</li>
  <li>MySQL</li>
</ol>

<h3>Architecture:</h3>
<ol>
  <li>Presentation Layer</li>
  <li>Logic Layer</li>
  <li>Data Layer</li>
</ol>

<h3>Presentation Layer</h3>
<p>The presentation layer has 3 main windows: Title Screen, Simulation window and Form window for adding new planets, designed in JavaFX</p>
<p>Some screenshots of the system</p>
<h6>Title Screen</h6>
<img width=550 src="https://github.com/OmerFarooq246/Gravity-Simulator/assets/110720771/81b9ffb0-4323-4880-b507-c9f35ef7fbe1">
<br>
<h6>Simulation Window</h6>
<img width=550 src="https://github.com/OmerFarooq246/Gravity-Simulator/assets/110720771/58af77ee-f6d9-4f44-b027-87723b0d980f">
<br>
<h6>Form</h6>
<img width=250 src="https://github.com/OmerFarooq246/Gravity-Simulator/assets/110720771/7bb06695-f4d1-4520-8090-ebcb05d088e8">
<br>

<h3>Logic Layer</h3>
<p>The basic logic behind this simulation revolves around the use of physics equations, vectors and a basic understanding of how bodies in space attract one another. Simulation in 2-dimensions require two variables: X and Y to represent the positions, accelerations, and velocities of all planets, and also the forces acting on the planets. For gravitation pull, we used the equation Force = G.M.m/r2. For newton’s laws of motion, we used the conventional Force = mass*acceleration equation, which allowed us to find the acceleration acting on each planet due to gravitational pulls from all other planets. Finally, projectile motion equations define how acceleration changes the velocity of the object and how the velocity changes the position of the object. Lastly, we coded a default planet arrangement that would run whenever a new simulation began, but we also allowed the user to add their own custom planets, with their own names, radii, masses, colors, velocities and at their specified location so that they could test different scenarios on the simulation for recreational or educational purposes.</p>

<h3>Data Layer</h3>
<p>The project utilizes the MySQL Database for storing the details of the simulations. Two types log tables are maintained, first type for storing specific details of each similation, where each similation will have its own, and the other is used as general log, containing the general details of all the simulations run on the system.</p>

<h3>Demonstration Video</h3>


https://github.com/OmerFarooq246/Gravity-Simulator/assets/110720771/07923199-e728-429f-b9ab-97b469142171


