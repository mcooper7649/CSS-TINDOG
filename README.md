TinDog Starting Files
# CSS-TINDOG


Useful links:

https://www.codeply.com/p/a6Y0L28iUI | Responsive Site 
https://font.google.com
https://fontawesome.com | Free Icons!!

1. Take NAV bar we've been working on and add to TinDog Skeleton.
2. Use Bootstrap to style TinDog skeleton project.
3. Add Javascript script(s) to your site to make nav dropdown functional.
*Had trouble with bootrap links, found appropriate script src hrefs*

Responsive Site AKA GRID SYSTEM

1. Responsiveness has nothing to do with speed but how the site adjusts depending on the device or viewport.
2. Bootrap uses Columns to structure the layout. Each Row created, has a maximum of 12 "units"
3. Divide by 12 to figure out your layout: for example if I wanted 2 columns in a row I col-6 is needed because 12/6 = 2.
4. 1 div per row and nest each column with a div.
5. Size attribute lets you specify the columns it will be viewed in that size or larger. Smaller will take up the full width.
6. In order to change as the viewport changes you can stack classes | Example <div class="col-lg-3 col-md-4 col-sm-6" </div>


Responsive Site Challenge

1. Create another Row | Different Color in Codeply
2. on Desktop we want 6 col per row
3. on Tablet we want 4 col per row
4. on Mobile we want 1 col per row.
5. Add bg color to "Title" section
6. Make navbar color lighter
7. Use bootstrap grid system to have the title and buttons take up 50% width left on desktop. 
8. Image of the phone take up 50% width on the right on desktop.
9. On tablet and mobile we want to take up 100% the width. 
10. Embed Google Fonts: Ubuntu and Monsterrat

Containers and Bootstrap Buttons

1. Getbootstrap.com>Componenets>buttons
2. Add a Dark and light button to Tindog site
3. Left Button should be Dark Right button should be Opaque Outline aka light.
4. Add fontawesome CDN then add APPLE and Android Icons to Buttons.
5. <i> tag is used for icons but you may also see <span> for the same purpose

Mini Tindog Challenge
1. Change the whole websites font to Montserrat.
2. Change Title section so font color are white. 
3. Add Ubuntu font-family to navbar-brand
4. Rotate image using Transform.

2nd Section of Tindog Challenge | Freehand Styling

1. Add font awesome icons and format the text and icons. The icons to choose from font-awesome are: check-circle, bullseye and heart.

2. Make sure the layout is responsive, the icons should take up full width on medium sized screens and below e.g. iPad, phone. But on desktop or large screen devices it should take up a 1/3 of the screen width.

3. Make the icons change colour when you mouse over the icons.


Tindog Carousel Lesson

1. Carousel ID and Buttons need to be the same.
2. Read Carousel on getboostrap.com to see class functionality.
3. 1 class HAS to be marked active.
4. Aria-Hidden is for disabling visually impaired screen readers from reading that portion of code.


Tindog Bootstrap Cards
1. Use the Bootstrap Pricing Example and add 3 cards to your dogs in the pricing section.
2. Use Bootstrap grid system to show ALL on desktop, 2 on 1 row on tablet and 100% on last row on tablet. Then on mobile size make them take up 100%.

3. Add Bootstrap pricing buttons using the same styles as our examples.

4. Add Custom Class to to each column. Add padding between the columns and text-align center the text.

Tindog Z-Index

1. Z Index is a layering technique.
2. Default index on all elements is 0.
3.  1 is a layer on top of 0 and -1 is layer below.
4. Z-Index only works with a position specified. IE position:absolute or relative.
5. if no z-index is specified but position is, the element farther down in the html will sit on top.

Tindog Z-Index Challenge
1. Get the Phone image to sit behind the "features" section. 
