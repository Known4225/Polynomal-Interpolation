# Polynomal-Interpolation
It's like lagrange interpolation, I think

Install: Download Polynomial_Interpolation.html and run it in your browser of choice.

What does this project do?
A Gregory-Newton polynomial is a special kind of polynomic function that goes through a given set of points. It's constructed in a way that uses those points as inputs and makes a polynomial of degree n where n is the number of points that is given.

These kinds of polynomials are used for interpolation, which is a way of guessing the points between certain known data, you can do a linear interpolation which just makes a straight line between two points or you can use something like this or lagrange interpolation for more advanced things. Lagrange interpolation actually produces the same output as this project but it does so in a slightly different way. The advantage of gregory-newton is that you can do a cool optimisation when you just want to add data points one at a time to the set, a technique that is automatically implemented whenever a point is added.

Another application for this kind of polynomial is for sequences. You can fit a function to any finite sequence and then use the function to predict the 'next' item in the sequence. This is not super useful but it is a lot of fun. Like instead of a curve fit, what if I could do better: A function that goes through every data point.

Obviously it won't work if two points share the same x coordinate, because functions can't do that. I also would've liked to find an easy way to calculate an inverse function, but right now the best you can do is swap the X and Y values and create another curve, but this will not be the inverse unfortunately.


General Controls:
- You can drag around the windows and resize them like you would in Windows™

Graph Window Controls:
- Use mouse to move around the graph and window
- Use the scroll wheel to zoom in and out
- Hold space and click to place a point
- Hold 'a' while holding a point to snap it to the grid
- Hold 'x' and click on a point to delete it (or hold x and click a row in the table to delete it)
- Use the left and right arrows to select window (data)
- Click File -> New for a new table and graph
- Click File -> Settings to do nothing
- Click File -> Adjust resolution slider to change the resolution (how many values are rendered in the graph)

Table Window Controls:
- Click on a segment of the table to edit it
- Click the + symbol to add an item
- Click File -> New for a new table and graph
- Click File -> Settings to do nothing
- Click File -> Coefficients to switch between showing data points and polynomial coefficients
