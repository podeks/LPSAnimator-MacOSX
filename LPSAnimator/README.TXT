After unzipping the dist folder, place it anywhere you like. 

To run this application, an older version of the Java Runtime Environment is required, namely version 1.6.  This can be downloaded here:

http://support.apple.com/kb/DL1572

You can check if you already have the required JRE by looking in the folder /System/Library/Java/JavaVirtualMachines, which is where the installer from the link above places it.

To run the project from the command line, go to the dist folder and
type the following two commands:

export PATH=/System/Library/Java/JavaVirtualMachines/1.6.0.jdk/Contents/Home/bin:$PATH

java -jar "LPSAnimator.jar"

The first command switches the JRE for the duration of the session, after which the default JRE is restored (which is located in Library/Java/JavaVirtualMachines).

This application allows one to view an animated drawing of the LPS graphs LPS(p, q), where p and q are distinct odd primes, which displays the octahedral fixed point symmetry that these graphs possess.  In this application, p and q are restricted to being less than or equal to 31.  Use the horizontal arrow keys to change the parameter p (which sets the degree of the graph to be p+1), and use the vertical arrow keys to change the parameter q (which sets the number of vertices to be either q^3-q or half that).

Further keyboard controls are as follows (note that the arrow keys only function to change the graph when both the orbit walker and the camera sequencer are on):

V show/hide the vertex set
C show/hide a cube
O show hide an octahedron

P pause/play the camera sequencer
W pause/play the orbit walker

- decelerate the orbit walker
= accelerate the orbit walker 

-SPACEBAR pause both the camera sequencer and the orbit walker if both are on / play both if either or both are off.

If either the camera sequencer or the orbit walker are paused, the arrow keys can be used to step through the animation.  Use the horizontal arrow keys to advance both the camera and the walker.  Use the vertical arrow keys to advance just the camera.

Tip: Pause the animation and then step the camera through so that the line of view is along the intersection of two of the planes of reflection for the symmetry group, which happens when you see a circle of green points aligning with your view (you can also show the cube or the octahedron to assist with aligning the line of view).  Then play the orbit walker with the “W” key to see the symmetry associated with the cyclic subgroups.  Use the “-/=” keys to adjust the speed of the walker.



