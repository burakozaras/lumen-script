The code is a light-lumen calculator that allows the user to calculate the number of lumens of light needed to illuminate a specific area. The user inputs the dimensions of the area (long edge, short edge, and height), as well as some additional values (cu, cm, and the desired luxofarea value). The code then prompts the user to select the units of measurement for the dimensions of the area (meters, feet, or inches) and converts the values to meters if necessary.
-
Next, the code calculates the number of lumens of light needed using the following equation: (luxofarea * area) / (cu * cm), where "area" is the total area of the room. The code then prompts the user to input the lumen value of the lamps and calculates the number of lamps needed using the equation: total lumens needed / lumen value of the lamps. Finally, the code calculates the exact lux value of the area using the equation: (number of lamps * lumen value of the lamps * cu * cm) / area.

To use visualization script:
First, you will need to install 'matplotlib'
Then, you can use the code to create a visual representation of the area.
