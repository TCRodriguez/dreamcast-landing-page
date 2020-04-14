====================================
|| Dreamcast Landing Page
====================================

-------
Design
-------












-------
Log
-------

It took some time, but I finally got the 'circle' image to be positioned how I wanted it to and for it to scroll along with the rest of the content and also have the nav bar be sticky.

I found that the property 'position' was jamming me up...I had it sprinkled in several selectors and that was sabotaging my efforts to lay everything out like I had it in Adobe XD.

Next time I need to work on is overlaying an image over the 'circle graphic' image...this image will be the slightly transparent Sega Dreamcast system and controller, and this will be behind the 'sign up' form for the newsletter...

-04/06/2020


I figured out how to position the dreamcast controler and VMU image and <form> element where I want it on the page. It needs some
fine tuning, but I got over the hump of figuring out how to overlay something on top of something else, and that
happens through a combination of 'position: absolute' on the base image and 'position: relative', along with 'margin', for everything else....

-04/07/2020


I learned more about the 'parent-child' relationship in regards to setting up a grid in CSS
At first, 'grid-areas' wasn't positining the items like I wanted them, and I found out that
the styles weren't being applied because I was applying them to 'descendants' and not 'child'
elements. So, I reworked the containers and selectors and got it to layout properly.
This Stack Overflow post gave the answer: https://stackoverflow.com/questions/46800525/grid-properties-not-working-on-elements-inside-grid-container

-04/08/2020

Found that flex-wrap was the answer to get the menu to be below the Dreamcast logo.

I had to play around with margins alot due to the 'justify' series of style declarations weren't applying
how I wanted them to...

-04/12/2020