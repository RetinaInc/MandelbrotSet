# MandelbrotSet
MandelbrotSet using OpenMP forked from original work of John Burkardt

The Mandelbrot set is a set of points C in the complex plane with the property that the iteration

        z(n+1) = z(n)^2 + c
      
remains bounded.
All the points in the Mandelbrot set are known to lie within the circle of radius 2 and center at the origin.

To make a plot of the Mandelbrot set, one starts with a given point C and carries out the iteration for a fixed number of steps. If the iterates never exceed 2 in magnitude, the point C is taken to be a member of the Mandelbrot set.

Creating an image of the Mandelbrot set requires determining the behavior of many points C under the Mandelbrot mapping. But each point can be studied independently of the others, which makes this calculation suitable for a parallel implementation.

Rabin Awal

Generate an image of the Mandelbrot set, using OpenMP. 
