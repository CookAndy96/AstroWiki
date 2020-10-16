# AstroWiki

This wiki, or rather code repository and resource list, is designed to help new PhD students get familiar with typical practices in the astronomy community. I, for one, started my PhD with no Python experience, and very little coding experience in general. I had no knowledge of how a FITS file was put together, or how to fit a Gaussian to an emission line, or how to model more complex things. That information is scattered around the internet. Sometimes it is easy to find. Sometimes it is well documented. Sometimes it isn't either of those things. This wiki will present a number of useful practice scripts, examples, and tutorials, as well as provide links to resources and other helpful bits of information. But that is not all this is for. Take a look below the contents list to see what else this wiki is doing for the astro community.

## Contents
---
- [Working With Fits Files](./WorkingWithFitsFiles/WORKINGWITHFITSFILES.md)
- [Opening and Exploring FITS Files Example](./WorkingWithFitsFiles/Opening%20and%20Exploring%20FITS%20Files.ipynb)
---
- [Astronomical Image Plotting Examples](./AstroImagePlotting/ASTROIMAGEPLOTTING.md)
- [Plotting Astronimical Images Without Coordinates](./AstroImagePlotting/Plotting%20Astronomical%20Images%20Without%20Coordiantes.ipynb)
- [Plotting Astronimical Images With Real Coordinates (Using WCSAxes)](./AstroImagePlotting/Plotting%20Astronomical%20Images%20With%20Real%20Coordiantes%20(Using%20WCSAxes).ipynb)
---
## What this wiki is for

In addition to helping new PhD students, this wiki has a couple of other functions:

1. To help new PhD students get used to the astronomy community's way of doing things
2. To act as a reference guide throughout students' studies
3. To serve those same functions for staff, enabling the community to transition to using the same tools (or at least similar ones)
4. To help community members gain experience with collaborative coding projects and GitHub

The first 3 are fairly self explanitory, but the 4th requires a bit of expanding. Most astronomers are fantastic code-heads. We can see a problem, spot a route to its solution, and then solve it with code. We do this day in and day out. After a PhD, even with no prior Python experience, just by exposure, most Astro PhD students are considered "expert level" coders. Even if you think you are not at that stage by the end of your PhD, you probably are. 

Generally, though, astronomers don't follow the best programming practices. And it's not really our fault. Most of what we, as a community, do is self-taught scripting. We write one script to make an image here, and then never use it again. Another to quickly fit something there. Simulationists do a lot better but best coding practices are few and far between in astro. And while we can learn how to properly use classes, and to use style guides, and to not reuse code (there will be a **LOT** of code resue in this wiki!), it is harder for us to get experience with proper collaborative coding projects, and with utilising GitHub properly. 

So, I strongly encourage anyone who wants to contribute to this project to skip to the end of this document and see how to do so. It may differ from what you have done before, but it will be a hugely helpful habit to get into. 

## How to contribute

Ok, lets talk about how I used GitHub until recently. I would create a repository, clone it to my local machine, commit all changes directly to the master branch, and then push directly back to github. This is OK for personal repositories, but is, in general, really, really bad. 

So, if you want to contribute, here is what you should do:

1. Go to the Issues tab at the top of this repository.
..* Either find an issue you wish to help with (this will likely be adding a new example or something) and post your interest in it **or**
..* Create a new issue stating that you want to add/fix something that is not currently listed
2. Once I (or another admin) has reviewed your interest, and given the go ahead, **FORK** a copy to your own GitHub
3. **CLONE** your fork to your local machine.
4. On your local machine, create a **NEW BRANCH**. I cannot stress how important this is. 
5. Make any changes or additions. Then **COMMIT TO THE NEW BRANCH**. Not the master branch.
6. From here, the easiest thing to do is **PUSH** the new branch to your forked GitHub repository, then use the **PULL REQUEST** button. 

Each step should be fairly easy to follow. Once the last step is complete, it will open a Pull Request and we can chat about it and it can be merged with the master branch once it has been tested. And **THAT** is how GitHub is supposed to work (apprently). 

A final word, Jupyter Notebooks is not the best place for coding, but it is great for tutorials, please use it. Also, we should try to use Python 3 rather than Python 2. Most of the old scripts still work in Python 3 with only minor editing, and it will help those across multiple institutes. 
