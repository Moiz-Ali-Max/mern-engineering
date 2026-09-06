### CSS Gradients
CSS gradient let you display smooth transition between two or more specified colors, three types of gradient;
1. Linear Gradients  (goes down/up/left/right/diagonally)
2. Radial Gradients (defined by their center)
3. Conic Gradients (rotated around a center point)

#### Linear Gradient
To create a linear gradient we must define atleast two color stops. Color Stops are the colors you want to render smooth transitions among. You can also set a starting point and a direction (or an angle) along with the gradient effect.

```
Syntax
background-imgae: linear-gradient(direction, color-stop1, color-stop2, ...);
```

***Direction***
- Default Direction. (Top to Down)
- Specific Direction
    ```
    /* Specific Directions */
        background-image: linear-gradient(to right, Red, Blue);
        background-image: linear-gradient(to left, Red, Blue);
        background-image: linear-gradient(to bottom, Red, Blue);
        background-image: linear-gradient(to top, Red, Blue);
        
        /* for diagonally, use to bottom right, or to bottom left */
        background-image: linear-gradient(to bottom right, Red, Blue, Green); 
    ```

- Using Angles
    ```
    background-image: linear-gradient(210deg, Red, Blue, Green); 
    ```

- Using Transparency 
    ```
    background-image: linear-gradient(to bottom, rgba(255, 0, 0, 0), rgba(0, 0, 255, 1));
    ```

#### Radial Gradient
A Radial Gradient is defined by it's center. To create a radial gradient we must also define atleast two color stops.
```
Syntax:
background-image: radial-gradient(shape size at position, start-color, ..., last-color);
```
***We can change spacing of colors/set pre-defined shapes/repeating gradient.

#### Conic Gradient
A Conic Gradient is a gradient wuth color transitions rotated around a center point. To create a conic gradient we must define at least two colors.
```
Syntax:
background-image: conic-gradient([from anlge] [at position] color [degree], color [degree], ...);
```
