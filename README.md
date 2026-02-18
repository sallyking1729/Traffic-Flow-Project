# Traffic-Flow-Project
University scientific computing project to create a cellular model of traffic down a single lane road and to then use take measurements and conduct a scientific investigation. 
Script 1 
Code to produce a space-time plot.
The variables at the top can be altered to change different parameters within the model. ‘vmax’ = maximum speed the cars can reach
‘cars’ = number of cars on the road
‘l’ = length of the road
‘iterations’ = number of timesteps the model runs for 
‘positions’ = starting positions of the cars, this is automatically set to evenly space them along the road, but the array can also be set by hand for a specific starting arrangement.
‘velocities’ = starting velocities of the cars, this is automatically set to 0 for each car but the array can also be set by hand for specific starting velocities.
‘probability’ = this value is the probability for cars to randomly break if they are travelling at a speed greater than zero, this can be set to any value between 0 and 1.

The variables ‘n’ and ‘diagram’ must not be changed.

Script 2 
Code to produce a plot of traffic flow against density and identify the peak traffic flow.
The same variables are used for this script as above. 
‘cars_max’ = The maximum number of cars on the road

Script 3 
Code to produce plot of peak traffic flow against velocity.
The same variable as above
‘number_of_vmax’ = The number of x axis points used

Script 4 
Code to produce a space time plot for cars travelling along a road with the addition of a ‘construction zone’ where the maximum velocity is lowered.
The same variables as above.
‘vmax_reduced’ = the reduced maximum velocity in the construction zone
‘rw_start’ = start point of the section of roadworks
‘rw_end’ = end point of the section of roadworks

Script 5 
Code to produce a plot of the number of slow cars against the percentage of a road occupied by roadworks.
The same variables as above.
‘number_of_rw_lengths’ = the number of different lengths used to plot the graph


To produce figure 7 of the report scripts 2 and 4 were combined to make a flow/density plot with the addition of the construction zone rule.
