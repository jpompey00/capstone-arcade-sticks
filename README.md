# Controller Crafters Website

Done for Year Up April 2024

Styled with bootstrap and CSS and contains 5 different pages

## Index

A simple 2 column structure with one column holding the logo and the second column holding the text about the business.
The size of the columns changes when the viewport is medium or small due to bootstrap.


![](images/readme_images/index_image.png)


## Products

Uses bootstrap cards to display the services that are offered. The cards are ordered and centered using bootstrap flex attributes. The Amount of cards displayed changes based on the size of the viewport. Known issue is when going between small and medium viewport, there is a range where the cards will appear stretched. I don't think this is a size range any devices will be at however.

![]()

## Login
Simple page using input fields and a checkbox styled by bootstrap. The input fields all require an input before you press submit, but I didn't implement any minimum or maximum character lengths. Alot of this was centered using column sizes rather than with flex, which may not be optimal. Will react well with changing sizes


![]()
## Registration
Registration works in a similar way to Login . Some elements were styled using flex and some using just col sizes. All of the fields on this page require input.


![]()
## Checkout
Checkout uses a two column design which transitions into a one column design when the viewport shrinks. On the left side all fields require input, and for the numerical ones they will only take numbers(Zipcode CardNumber Security Code). I added a rudimentary validation method for these using built in HTTP attributes. Card Number has a min value of 1 * 10^15^. AKA a 16 digit number. It can't check if its a real number without any JS but it can enforce minimum number limits. As for the Zipcode and Security code, I added minimum values of 0 and max values of 99999 and 999 respectively. It at minimum, stop the user from entering a negative number. The rest of the page was done using bootstrap.

![]()
## CSS
The CSS was only used to color the background of some elements, for the font, and for removing the spinner/counter buttons from HTML number inputs




## Final Notes
Between some viewports things get an odd layout so i'm not sure if i'm supposed to handle all those cases.
