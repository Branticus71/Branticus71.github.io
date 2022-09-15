# Reflections on Project 1
[HTML results for the project](projects/Project-1.html)
## What was the purpose of the project?
The purpose of the project was to get practice processing data in R then creating functions that could parse and graph out similar datasets.

## What did you learn?
I learned quite a bit from this project.
-If a function doesn't quite do exactly what you want then you can often find a modified version in another package. I found that substr dealt poorly with variables
that had varying widths so when I wanted to simply take the last two values to form a state variable things got complicated. However, after a quick search I found that
in the `Stringr` packages there was a function named `str_sub` that worked much better for my purposes.
-Creating functions to do repetitive tasks is extremely time efficient. Had I needed to re-write my code to parse and graph every csv given to me the project would have 
taken much longer.
-You can do some very interesting things with patterns in R. I've used SAS before but had never seen something like the `grep` function used before.
-If a function is not performing as expected the best way to troubleshoot is to simply create a new code block and try to perform the action without a function.
I had a few issues with how things were being stored and called within my functions and it would have taken much longer to find the problem had I not used this method.
## What would you do differently
Looking back what I most likely would have done differently is start earlier then after the project is finished spend some time practicing making more interesting 
markdown files and graphs. I am sure there are lots of interesting things you can customize to better present a project and it would have been a good idea for me
to go ahead and get familiar with them now rather than later.
