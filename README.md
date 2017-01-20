# Website Optimization Project

An assignment from the Udacity Front-End Web Developer Nanodegree where I optimize a website that was running very poorly with a low FPS and load times, using Google PageSpeed Insights.

1) index.html took a long time to grab the JavaScript files and CSS files, causing it to render block and take a long time to load. I solved this issue by moving the JavaScript files to the end of the page instead of before, and minimized/inlined the CSS instead of downloading the nessessary files.

2) pizza.html was extremely janky and needed work done to the animations of the moving pizzas in the background (within main.js), as well as faster loading speeds when adjusting the pizza sizes. This was fixed by rebuilding the for loop that was used to move and redraw the pizzas every frame, by instead just moving the already existing image. For the pizza sizes, we changed the "querySelector" to "getElementById" which is more efficient.

## Getting Started

To run the website locally, download the project and run the index.html web page.

### Prerequisites

* [Google Chrome or Other Web Browser](https://www.google.com/chrome/)

## Built With

* [Visual Studio Code](https://code.visualstudio.com/)
* [PageSpeed Insights](https://developers.google.com/speed/pagespeed/insights/)
