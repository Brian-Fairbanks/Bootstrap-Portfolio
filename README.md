# Responsive Portfolio

This goal of this project was to familiarize myself with the Bootstrap Framework, and learn best practices for Responsive design, while generating something practical.

Responsive design ensures that web applications render well on a variety of devices and window or screen sizes. My page was developed as desktop-first, and then adapted to allow for a fluid mobile design as well


## Goals/Origins

* Create the following files files: `index.html`, `portfolio.html` and `contact.html`.

### For All
* Using Bootstrap, develop with the following items:
   * A navbar - I developed an elegent, consistant, 1 row sticky header, which will expand to 2 rows when dropping below 768px screens/windows
   * A responsive layout - On an `xs` screen, content takes up the entire screen. On `sm` and larger screens,there are progressively larger margins on the left and right sides of the screen.
   * Responsive images - My images wound up being a bit less openly responsive than inteneded.  The one clear example is on my about me page, only on small mobile screens.
    this image instead floats left at a fixed size when extending past 756px.

   * Make a sticky footer - Confusingly, not the same as a position:sticky footer.  I implemented this using a flex-box method
   * and use sub-rows and sub-columns on your portfolio site

   * The Bootstrap portfolio should minimize the use of media queries outside bootstrap - I used none.
   * Each page must have valid and correct HTML. - HTML validation service reports 0 errors
   * Implement accurate HTML Symantic elements - I learned how to better manage these, and have gotten away from pure divs

### Portfolio
   * I made use Bootstrap's grid system (containers, rows, and columns) to appropriately create a shinking grid to display my project cards.

### Contact
   * I discovered and made use of FontAwesome to implement a variety of icons, representing links to my social accounts.
