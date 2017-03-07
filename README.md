## Project 4 : Website Performance Optimization

###Part 1: Optimize PageSpeed Insights score for index.html

You can view the [Live Demo](www.added.com)

####Results:
1.Mobile : 93/100
1.Desktop : 93/100

####Changes made in index.html
1. Fonts loading using javaScript
1. Sorting out the order of code i.e: Scripts at the bottom
1. External script loading to async
1. Minify Js and Css
1. Redundant and unused styles removed
1. Css inlined for better performance 

###Part 2: Optimize Frames per Second in pizza.html

You can view the [Live Demo](www.added.com)

####Results
1. Time to resize pizza under 5ms.
2. 60 fps

####Changes made in pizza.html
1. updatePositions() updated with memory efficient code.
1. changePizzaSizes() calculating newWidth once in % .
1. for() loops modified for better performance.

### Sources

1. [Compress and minify Pictures](https://tinypng.com/)
1.<http://www.willpeavy.com/minifier/>
1.<>