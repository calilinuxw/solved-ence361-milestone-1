Download Link: https://assignmentchef.com/product/solved-ence361-milestone-1
<br>
Milestone 1 involves generating a TIVA program to read data from the Orbit board’s threeaxis accelerometer and display that data on the OLED display.

The specification for Milestone 1 is as follows:

M1.1. The accelerometer should be sampled at regular intervals.

M1.2. Data from the accelerometer should be stored continually in three circular buffers, one for x-direction acceleration, one for y-direction acceleration, and one for z-direction acceleration. The mean values of the samples in each of the three buffers should be computed at regular intervals.

M1.3. At the initiation of the program the mean sample values should be recorded as the reference orientation. This is required so that the orientation of the fitness monitor can be calculated.

M1.4. From the time of initiation onwards (cf. M1.3) the raw x, y, and z accelerations should be displayed on the Orbit OLED display, except as indicated in M1.6.

M1.5. From the time of initiation onwards, operating the DOWN button, a.k.a. BTN1 on the Orbit board, should repeat the action detailed in M1.3.

M1.6. A single push of the UP button, BTN2 on the Orbit board, should change the display of acceleration from raw units to multiples of the gravity of earth, <em>g</em>, equivalent to 9.81 ms-2. A second push of the UP button should change the display of acceleration to units of ms-2. Pushing the UP button a third time should change the display back to raw acceleration values. Thereafter subsequent pushes should make the display cycle through the same three states: raw acceleration -&gt; acceleration in <em>g</em> -&gt; acceleration in ms<sup>-2</sup>.

M1.7. The source code used to achieve Milestone 1 should be pushed to the group’s repository on the same day that Milestone 1 is assessed.

<strong>NB:</strong> Your group’s program will only be tested on the specification above. Do not “over deliver” by adding more features or exceeding the specification. Information about your design and how you have tried to meet the specification should be part of your lab book write up. Examples of the information you should record is how you decided what sampling rate to use and the size of the buffer to use. Groups will receive feedback on the quality of the Milestone 1 source code they have pushed to their repository.