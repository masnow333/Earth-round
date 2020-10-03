This project are an animation of the earth rotating (optical illusion).
If you want modify de size of the circle, and that the animation remains, you only need compare the size with the next equation:

    (initial-width-of-your-picture * height-of-your-wrapper) / initial-height-of-your-picture

Example:
You have an image with:

    height: 400px
    width: 780px

And you want that the wrapper have a height of 250px. You need do this equation:

    (780 * 250) / 400 = 487.5

You change the value of variable "--size-of-background" for "487.5px"