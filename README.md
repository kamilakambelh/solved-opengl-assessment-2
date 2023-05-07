Download Link: https://assignmentchef.com/product/solved-opengl-assessment-2
<br>
<h2>Task</h2>

Write an OpenGL program that displays a simple 3D scene with lighting.

<ul>

 <li>A simple 3D scene.</li>

</ul>

o Construct a room with four walls, a ceiling and a floor. Create the room by manually specifying vertex positions and surface normals.

The room should contain a table and some stools. You can scale the vertex specifications of a cube to different sizes to represent the table and stools.

Place two different ornaments on the table. Load the meshes for these ornaments using two different model files (other than the cube model) that were previously provided in the tutorials.

Your program should have a movable camera that the user can control using keyboard and mouse input.

(3 marks)

<ul>

 <li>Lighting and shading o The room must be lit using two point light sources on opposite sides of the room. Use a small sphere/cube to represent each point light sources’ position.</li>

</ul>

Assign different material properties for each object, i.e. walls, ceiling, floor, table, each stool and each ornament.

(2 marks) o Create a spotlight near the ceiling in the centre of the room. Use a small sphere/cube to represent the spotlight’s position

(1 mark) o Implement constant, linear and quadratic attenuation factors for each light.

(1 mark) o Create a user interface (using the AntTweakBar library) for the user to be able to adjust the properties of the three light sources. To keep camera rotation separate from interaction with the user interface, only allow camera rotation when the right mouse button is pressed and held.

The user interface should allow the user to:

<ul>

 <li>Toggle between wireframe and solid mode</li>

 <li>Turn individual lights on and off</li>

 <li>Adjust the properties for each of the two point light sources:</li>

</ul>

<ul>

 <li>The ambient, specular and diffuse components for all 3 colour channels (i.e. red, green and blue),</li>

 <li>The constant, linear and quadratic attenuation factors.</li>

</ul>

The colour of the object that you use to represent each light source’s position should change to match the light source’s colour.

(2 marks) o Disco mode

<ul>

 <li>Using the user interface, allow the user to toggle disco mode.</li>

 <li>In this mode, animate the light sources in the scene:

  <ul>

   <li>The two point lights should move around the room.</li>

   <li>The spotlight’s colour and direction should change periodically.</li>

  </ul></li>

 <li>Get the ornaments on the table to “dance” (just make them rotate and bounce up and down).</li>

</ul>

(2 marks)

 Multi-view orthographic o Create the following multiple views layout:

<table width="365">

 <tbody>

  <tr>

   <td width="188">Top View  (orthographic)</td>

   <td width="176">Side View  (orthographic)</td>

  </tr>

  <tr>

   <td width="188">Front View  (orthographic)</td>

   <td width="176">Perspective View(perspective)</td>

  </tr>

 </tbody>

</table>




For the top view, remove the ceiling so that the user can see into the room. For the side and front views, remove the respective side and front walls, so that the user can see into the room. Moving the camera should only affect the perspective view.

(3 marks) o Allow the user to switch between a single perspective view and the above multiple views when the user presses “v”

(1 mark)

<h2>Instructions and Assessment</h2>

Submit an electronic copy of your work to your tutor at the start of the lab in which this assessment task is due. Do not try to fix your code during this lab, otherwise late penalties may apply. Your program must work on the computers in the lab or you must demonstrate it in the lab using your own laptop. The assignment must be your own work. If asked, you must be able to explain what you did and how you did it. Marks will be deducted if you cannot correctly explain your code.

The marking allocations shown above are merely a guide. Marks will be awarded based on the overall quality of your work. Marks may be deducted for other reasons, e.g., if your code is too messy or inefficient, is not well commented, if you cannot correctly explain your code, etc. For code that does not compile, does not work or for programs that crash, the most you can get is half the assessment marks or less.


