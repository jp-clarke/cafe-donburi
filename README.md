# Cafe Donburi

This is a site for Cafe Donburi, a fictional Japanese Cafe and Takeaway located in East Kilbride, Glasgow.

The site is targeted to locals and visitors to the area to encourage them to try traditional Japanese dishes either dining in or takeaway, as well as allowing both new and returning customers to view the some of the food available, the menu and make table reservations. It will also help customers locate and contact Cafe Donburi.

![Alt text](docs/screenshots/amiresponsive.PNG)

## Features

This is primarily a single page scrolling website with a sticky header to allow for user friendly navigation between sections. There is a single separate page with a form for bookings.

### Navigation Bar

- The Navigation Bar includes links to the Logo/Home, as well as the About, Gallery, Menu and Find Us sections of the page. The Book links to a form in a popup window, which allows the user to make a table reservation.

- The Navigation Bar is fully responsive and switches to a hamburger style menu at smaller screen sizes.

- The Navigation Bar is 'sticky', and remains visible to the user at all times to make navigation easier for the user.

- In large screen format the links are highlighted in a red circle to catch the user's eye, as well as keeping with the Japanese theme.

![Navigation bar for desktop and mobile](docs/screenshots/navbar-desktop-mobile.png)

### Landing

- The landing consists of a hero image of Cafe Donburi's speciality dish with text overlay.

- The text overlay is set in a red circle and establishes the Japanese theme, dining options and location to the user.

![Landing](docs/screenshots/landing.PNG)

### About section

- The About section gives the user an introduction to Cafe Donburi.

- In this section the user is given important pieces of information, including food speciality, location, link for booking a table and phone number for takeaway and home delivery.

![About section](docs/screenshots/about-section.PNG)

### Gallery section

- The Gallery section showcases some of the highlights of the food on offer at Cafe Donburi.

- The user can see the type of food on offer and the appearance of specific dishes and drinks.

![Gallery section](docs/screenshots/gallery-section.PNG)

### Menu section

- The Menu section gives a comprehensive list of the food and drink on offer at Cafe Donburi.

- The user can see everything that's available to order for takeaway and home delivery.

- If dining in, the user can view what's available in advance.

![Menu section](docs/screenshots/menu-section.PNG)

### Find Us section

- As this is a single page scrolling site, the Find Us section forms the footer of the page.

- This section contains a map showing the location of Cafe Donburi, address, phone number, opening hours and social media links.

- The user is given all necessary information to visit or contact Cafe Donburi in this section.

![Find Us section](docs/screenshots/find-us.PNG)

### Booking section

- The Booking section is on a separate page with all other information removed.

- The user can fill out the form to make a table reservation and return to the main page using the 'Go Back' button.

![Booking section](docs/screenshots/booking-section.PNG)

### Features to be implemented

 Better booking section (table availability, more refined date and time selections, etc.)

## Testing

- This site has been tested on the following browsers:
    - Chrome
    - Safari
    - Edge
    - Firefox
    - Opera

- Testing consisted of the following:
    - Loading the home page.
    - Visual inspection of the header, navigation and all sections of the page to ensure that the layout is as expected.
    - Test all links in the navigation bar for functionality and to ensure smooth scrolling between sections.
    - Navigate to booking page to repeat visual inspection of layout.
    - Test booking form works as expected, including back and submit buttons, using https://formdump.codeinstitute.net/

- Responsive design was tested primarily using Chrome DevTools across standard screen sizes from desktop (1920x1080) down to small mobile (320x480). Transitions between media query breakpoints were observed. Testing was also conducted on several available hardware devices within the above range of screen sizes.

### Validator Testing

#### HTML

- No errors returned when checking code with the official W3C validator.

#### CSS

- No errors returned when checking code with the official W3C CSS validator.

#### Accessibility



### Unfixed Bugs



## Deployment

The site was deployed using Github Pages as follows:
- In the GitHub repository, go to settings.
- Navigate to the Pages section.
- Select Deploy from a branch from the Source drop-down menu.
- Select main from the Branch drop-down menu.
- Select /(root) from the Folder drop-down menu, and save.

The live link for the site is:
https://jp-clarke.github.io/cafe-donburi/index.html

## Credits

### Content

- The following page was used for the hamburger menu on smaller screens, and modified to suit:
https://www.w3schools.com/howto/howto_js_dropdown.asp

- Hamburger menu and social media link icons from font awesome.

- The Love Running walkthrough project by Code Institute was used as a starting point for various sections, in particular the Landing and Gallery, as well as the section for social media links and Booking form.

- Google map in Find Us section was added using the following link as a guide:
https://blog.duda.co/responsive-google-maps-for-your-website

- Smooth scrolling code:
https://www.w3schools.com/howto/tryit.asp?filename=tryhow_css_js_dropdown

- Sticky header code:
https://www.w3schools.com/howto/howto_css_sticky_element.asp

- Scroll margin code:
https://www.w3schools.com/cssref/css_pr_scroll-margin-top.php

- The following link was used to solve the issue of the hamburger icon blocking the button below from being clicked:
https://stackoverflow.com/questions/36927140/cant-click-the-button-because-of-the-overlay

### Images

- The hero image (hero-shot.png) was taken from https://www.canva.com/

- The following images were taken from https://www.pexels.com/
    - sushi2.jpg
    - tempura-don.jpg

- The following images were taken from https://pixabay.com/
    - coffee-matcha-latte.jpg
    - donburi.jpg
    - gyudon.jpg

- The following images were taken from https://unsplash.com/
    - gyoza-noodles.jpg
    - ramen1.jpg
    - ramen2.jpg
    - sushi1.jpg
    - teriyaki-chicken.jpg

- The following images are the developer's own
    - katsu-curry.jpg
    - maki-sushi.jpg