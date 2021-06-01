# Activity Calculator README
This task was designed to build up my coding skills whilst also seeing how it can be utilised in nuclear physics which allowed me to get a feel for the real life applications of coding despite the task being relatively basic.

The Activity Calculator.ipynb is the file I worked on, the other .ipynb file is my managers (@py1sl) example that he sent me once I had completed the task.

I was asked to write some code that for a given radioactive isotope, initial activity and decay time calculated the activity at said decay time. The csv file i was given (half_lives.txt) included the name of the nuclide, its half life and the corresponding unit which was either years, days, minutes or seconds.

The challenge was to read the file in and then for the given nuclide convert the unit to seconds, calculate the decay constant then finally calculate the activity.

First off I assigned the variables for the given nuclide, initial activity and decay time. 

After that I read in the file using with open making sure to ignore the header line in the csv file. I then split the data into a list of lists so that I could access each dataset separately and created dictionaris for the half lives and the units.

Using these dictionaries I was able to write a loop that converted the half life into seconds given the units. 

Once this was done it was just a matter of writing up the equations for the decay constant and the activity. The results for the Nuclide Co60 are shown in the file.
