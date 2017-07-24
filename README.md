# levey-jennings-plotter
A perl script to plot Levey Jennings quality control curve from a datafile containing sequential values of test results.
Need to install 'gnuplot' and 'ttf-liberation' first
i.e. sudo apt-get install gnuplot ttf-liberation

First, create a file of values and put the obtained values line by line, name it for the test i.e 'glucose'

3.1
4.2
3.4
3.76
...

Then run

$ lj

in the same folder; when asked for which test, enter the name of the file just created
