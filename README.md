# Optimizing Background Rendering to Reduce Load Time

I started out with a site that was originally loading the file number-one-background.svg as a background url in the hero and need to optimize load time of the site.

Doing that means they could not lazy load the image easily since it was part of the main content the user will see right when the site loads.

It also did not help that the svg to start was nearly a megabyte(832K) in size applify the performance hit this caused.

This was the test page I used to work on some way I could go about tackling the problem.

Right now we are down to loading an asset that is 24K make it 97.12% smaller then the original images.
