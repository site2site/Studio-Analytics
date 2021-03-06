## September 28, 2013

You will provide a grid of microphone sensors as simple analog sensors to collect the amplitude of sound at all grid points in Studio-X. From this simple amplitude information, you will be able to pull out spatial information - ie. where is it most loud? - temporal information - ie. what is the rhythm of loud and quiet? - and thereby be able to infer much more.

This requires:

1.	The design of a grid specific to Studio-X

2.	The design of a mounting apparatus

3.	Setting up the actual array and getting it to stream information to the cloud

4.	Designing a user interface - a visualization of the information to be seen on the web


Your group took the initiative to think through the limitations of the technology, so we are asking you to take the lead on figuring out a grid based approach to distributing analog sensors throughout the space. You can assume that you will have 6 Raspberry Pi + Arduino sets, as your grid will be combined with the grid needed by the Studio-X Press group. You will use the same Raspberry Pis and Arduinos, but will provide different sensors.



## September 20, 2013

Your first task is to determine a high level metric that you want to measure and expose for every square inch of the space. For instance, if you are focused on collaboration, there should be a collaboration quotient that is been presented for any spot in the space at any time. It's up to you to figure out, then, how to capture collaboration. What is the formula for the collaboration quotient? Is it multiple chairs in close proximity around a table with humans seated in them? Is it chairs with temperatures above a certain level that are facing each other? In short, what determines "collaborativeness", or whichever metric you decide to take on.

You also need to think about cost. If you are the "array" analytics group, your solution can't rely on 50 Raspberry Pi + Arduino set-ups, as this would cost $5000. So, perhaps its more about looking at the Studio-X current setup, and putting proximity sensors in key places, or cameras around the room doing facial recognition in order to determine if people are facing each other, or a string of sensors on the walls that can be connected with just a few arduinos and Raspberry Pis. In short, even though you are the "array" group, it may not be feasible to connect to the most atomized objects, chairs, as they are mobile and so would each require their own autonomous module of hardware to get a reading. Try to think of a metric that can be measured by embedding sensors in or along larger objects (wall, floor, group of tables) where the cheap sensors may be replicated, but the control hardware (Arduinos and Pis) can be limited.
