After unzipping the dist folder, place it anywhere you like. 

To run this application, an older version of the Java Runtime Environment is required, namely version 1.6.  This can be downloaded here:

http://support.apple.com/kb/DL1572

You can check if you have the required JRE by looking in the folder /System/Library/Java/JavaVirtualMachines, which is where the installer from the link above places it.

To run the project from the command line, go to the dist folder and
type the following two commands:

export PATH=/System/Library/Java/JavaVirtualMachines/1.6.0.jdk/Contents/Home/bin:$PATH

java -jar "LPSAnimator.jar"

The first command switches the JRE for the duration of the session, after which the default JRE is restored.
