# dotstimhw11

a psychopy experiment for a random dot motion task. during this task participants view a collection of moving dot stimuli and indicate whether it is moving left or right 

overview and experimental design 
task type: 2 alternative forced choice motion discrimination task 
coherance levels: [0.05, 0.1, 0.2, 0.4, 0.8]
motion directions: left (180 degrees) and right (0 degrees)
trial structure: configured at startup:[10,50,100,or 150 trials]. trials evenly favor all cohernace and direction combinations possible
stimulus parameters: 150 total dots in field size 2; dot size 5 pixels, speed 0.1 units/frame, opacity 0.5
there are both signal dots which move in a distinct direction and noice dots that move randomly to obscure the pattern and dots move with no time restriction 
fixation period: + shown for duration between 0.5 and 1.5 seconds
stimulus & response: dots presented on screen until participant records "left" or "right" on keyboard 
inter-trial interval (iti): no stimulus shown for 0.5 seconds after each response

prerequisites & setup 
dependencies: built in python and pyschopy, using pandas and matplotlib for functions
configuration: window size 1200, 800 

save data to excel file with participant name and type of task 
