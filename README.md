# comp-phys-python

A collection of simple, single purpose programs to simulate physical systems and generate visualizations using matplotlib. Each script reproduces plots from [*Computational Physics, 2nd Ed.*](https://www.amazon.com/Computational-Physics-2nd-Nicholas-Giordano/dp/0131469908)  by N. Giordano and H. Nakanishi. These were written as assignments in a collegiate computational physics course and may be freely used to aid in any application. Please do not copy this work in order to complete school assignments.

- Requires: python, matplotlib

#### Usage:
Matplotlib must be installed to generate plots. Install it with 'pip install matplotlib'.
Then simply type 'python3 <filename>.py' or run scripts from your preferred IDE or text editor.

## List of program groups:

1. bicycle
  - bicycle.py: Calculates velocity vs. time with and without simplified air resistance, given a constant amount of work.
<center><img src="1_bicycle/bicycle.png" alt="bicycle.py image"></center>
2. baseball
  - baseball-trajectory-wind.py: calculates the arc of a pop fly under different wind conditions. Simplified wind.
  - baseball-curveball.py: calculates drop and curve of a curveball.
  <center><img src="2_baseball/baseball-trajectory-wind.png" alt="baseball-trajectory-wind image"><img src="2_baseball/baseball-curveball.png" alt="baseball-curveball image"></center>>
3. simple-pendulum
  - simple-pendulum.py: simulates pendulum motion with zero drag and wind resistance.
  - driven-simple-pendulum.py: simulates three pendulums with drag and different driving forces.

4. billiards (bouncing ball off containing walls)
  - billiards-circular.py: simple bouncing off inner-walls of circle
  - billiards-stadium.py: same but with small flat section in the middle, altering the shape and bouncing behavior
  

*more soon*