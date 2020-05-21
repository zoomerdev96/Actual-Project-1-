# Actual-Project-1-
First workspace folder was trash, so this is official project folder

Logan MacManus

This project is a re-design of the website for Magic Wings Butterfly Conservatory and Gardens. Magic Wings is a public conservatory where people visit to see hundreds of butterflies in their natural habitat. The gardens also have some fish, reptiles, and insects on display. Their current website uses only barebones html and css, and looks very dated. 

I took my girlfriend there on a date for Valentine's Day and had a lot of fun, so I created this project in the hopes that a sleeker website might attract more business to the gardens. I hope to update this project throughout the course, and ultimately offer my site to the gardens for free as a portfolio project. 

Currrently, the site functionality is fairly simple. There are links in the navbar to navigate between pages, and there are sublinks within every page except the about page that will take the user to another page within the site or direct them to a form depending on which button they click. 

I used HTML, CSS, and Bootstrap 4 on this project. 

Ideas for future improvement: 

1. Footer does not appear on bottom of page on vertical monitors (view windows with height of 1300px or greater). 
Can't seem to fix no matter what I do. 

2. Background-color will break on certain containers being used (container vs container-fluid). Had a very hard time keeping 
a consistent background color when my containers would adopt a lighter pink as a block level element, which made the elements 
on my page have 2 different background colors. Limited my styling because I had to work exclusively with container-fluid, rather than containers. 

3. Forms could be styled a lot better, they are very barebones. I could use a container rather than a fluid container to give the form its own background and possibly set a high res still image behind that. (think my landing page image with a form with a dark gray theme/background on top of the image) They are so barebones right now because of improvement #2, the background color problem. Any div placed below the form, no matter what container I put it in, would adopt a light pink background color that did not match the one I currently use. I could not override this color no matter what I did. I tried to use classes, IDs, content divs, etc. Nothing worked, so I simply decided not to add any content below the form. 

4. Could add a vector graphic with the company name to the Navbar, currently it seems empty and needs something bright to take up that space. 

5. Stacking on tablet-size screens could be improved, the elements seem a little mis-aligned. Since this project is so late already, I focused on perfecting my full-screen and mobile breakpoints. 

6. I could add a carousel to the store, about, or visit pages. I had a lot of trouble implementing the carousel feature because I couldn't get the heigh to work properly. I don't like how you can't control both the height and width of the carousel feature, and I don't quite understand why it is dependent upon the size of the image. I found it much simpler to use still images that you can scroll past, rather than try to implement a carousel. 

7. I could add working links to the buttons on my content pages, currently the only working links are to intra-site pages. This would come over time as I gain more knowledge of JS as well as build out the site. 

8. Could use something better to provide padding/margin to my fluid containers than a wrapped div with a class of ".padding". 
This does not look great on small and extra small screen sizes (mobile) because there is padding surrounding the content, thus making it smaller. It would be better if I could put one value for padding on md and above and another for sm and xs. Maybe via a media query? 

9. On my rows with 4 columns, when they break down to a width of 990px, the second row gets squished until it reaches the small breakpoint, where the bottom row of content gets enough space to display correctly. Tried using 2 different media queries, but don't know how to specify that the 990px query does not take effect at smaller break points. 

10. Create a cart/checkout system for the online ticket form and add some sort of calculator for ticket prices/order totals. 
