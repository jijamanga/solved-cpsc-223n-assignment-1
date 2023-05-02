Download Link: https://assignmentchef.com/product/solved-cpsc-223n-assignment-1
<br>
<strong>Flashing Red Stop Light</strong>

A flashing red light means an approaching vehicle must stop before proceeding.  When a standard traffic signal fails the back up software initiates a flashing red light.

<strong>Your assignment</strong>

Create a C# program.  It outputs a virtual flashing red light in a frame that we call the user interface (UI).

The entire UI is one large graphical area.  However, a “title panel” is drawn horizontally at the top of the UI and a “control panel” is drawn horizontally at the bottom of the UI.  The fact is that the UI is one single graphical area, but the viewer sees it as a window with three panels:

title panel, graph area, and control panel.

<strong>Requirements and choices</strong>




<ol>

 <li>You as programmer may select another color scheme for your UI. The only rigid requirement is that the light must be red.</li>

</ol>




<ol start="2">

 <li>You should create your own title for the program. Don’t depend on Linda Tran to choose the title for you.  Obviously, you should remove Linda’s name completely.  Your own name should be displayed as author of the program.</li>

</ol>




<ol start="3">

 <li>Pick a nice even rate of flashing. Obviously, 20 times per second is too fast because the light appears to be one hazy blur.  On the other hand if the interval of time between flashes is 30 seconds then the viewer will become bored waiting for the light to change.  You run some experiments and choose a flash rate that the will appreciate.</li>

</ol>




<ol start="4">

 <li>We do not allow tiny UI’s in this course. Suppose S is the size of your UI.  Then S must be in this range:  1280×720  ≤  S  ≤  1920×1080.</li>

</ol>




1280×720 is generally called Standard Definition TV, or SD-TV.

1920×1080 is generally called High Definition TV, or HD-TV.




You pick a nice size between those two ranges.




<ol start="5">

 <li>The “Pause Button” has two labels. When the program starts the label is “Pause”.  When the user clicks on the Pause button the label changes to “Resume”.</li>

</ol>




<ol start="6">

 <li>The “Exit Button” performs two actions, namely: stop the clock and close all the window. In this program there is only one window, and therefore, the Exit button must close the one UI.</li>

</ol>




<ol start="7">

 <li>There are two C# source files and one Bash script file in this assignment. The first source file outputs a welcome message and then it launches the UI.  When the program is ready to terminate the first C# source file output a nice good-bye message.</li>

</ol>




The second source file defines the UI and the components of the UI.  This is where most of the programming is done.




The third file is called a script file.  It is written in bash language.  Its job is to compile the two C# files and then run the program.











