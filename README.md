# Vincenzo's Fine Dining
Vincenzo's fine dining is a static 3 page website for a fictional Italian Restaurant, complete with a homepage, a menu page and a book online page.

![AmiResponsive](assets/README-images/amiresponsive.jpg)

## Features

### 1. Header
* The Header contains both the Vincenzos fine dining logo to the left of the page and the navigation bar to the right of the page.
* The colors were chosen in contrast with each other for easy readability
* The navigation bar links to the 3 pages Home, Menu and Book Online.There is a hover feature implemented which changes the color of the hovered over menu to Gray.There is also a current page feature which shows the user what page they are currently on with white lines around the link heading.

![Headerimage](assets/README-images/header.jpg)

* The navigation bar transforms into a hamburger menu for tablet and mobile devices under 768 pixels wide.

![ClosedHamburgerMenu](assets/README-images/hamburger-menu-closed.jpg)

* When clicked the menu opens into 3 columns with the page links.

![OpenHamburgerMenu](assets/README-images/hamburger-menu-open.jpg)

### 2. Hero Photo section
* This section has a background image of a nice restaurant which gives the users an idea of what to expect when coming to the retaurant.

* The section has a heading with the slogan "The Authentic Dining Experience".

* This section includes 2 award transparent boxes which slide down from the top of the page when the page is loaded or refreshed.

![photosection](assets/README-images/photo-section.jpg)

### 3. About us section
* This section gives an overview of where the restaurant is located. It also gives a brief history of when the website opened its doors and tells the user that all ingredients are locally sourced and all meals are made fresh.

![about-us-section](assets/README-images/aboutus.jpg)

### 4. Opening hours section
* This section gives the opening hours of the restaurant.

![opening-hours](assets/README-images/opening-hours.jpg)

### 5. Where to find us section
* This section gives an overview of exactly where the restaurant is loacated and gives information on nearby parking.

* The section also has an interactive map with a pin location for the restaurant.

![where-to-find-us](assets/README-images/where-to-find-us.jpg)

### 6. Footer
* The footer contains 3 clickable links to Facebook, Twitter and Instagram, which all open in a new tab.

* The section also contains the restaurant contact phone number and contact email address.

* The bottom of the footer contains a disclaimer explaining that this website is fictional and made for project purposes only.

![footer](assets/README-images/footer.jpg)

### 8. Menu Page

* This page contains an online menu for users to look at the meals available to order at the restaurant.

* The page contains 4 food sections. Starters, Mains, Pizza and Desserts with prices shown for each item and a small image at the head of each section.

![menu1](assets/README-images/menu1.jpg)

### 9. Book online page
* This page has a form for users to enter their details to reserve a table online.

* The form collects the users First name, Last name, Number of people, preferred time slot and any additional requests.

![book-online1](assets/README-images/book-online1.jpg)
![book-online2](assets/README-images/book-online2.jpg)

## Testing

* I have tested this website works on all browser types.

* I have tested the site on various screen sizes and devices using devtools and confirmed it is responsive to all sizes.

* I have tested all of the clickable links work and open in new tabs and have tested that all form elements in the form section work correctly and are required to submit.

### Validator Testing

* No errors were shown when putting the code through both the w3c html validator and the jigsaw css validator.

![w3c](assets/README-images/w3c.jpg)
![jigsaw](assets/README-images/jigsaw.jpg)

* ### Accessibility

* I confirm that all 3 pages return a high accessibility rating when running them through the lighthouse tool on devtools.

* Home page lighthouse

![lighthouse-home](assets/README-images/home-page-lighthouse.jpg)

* Menu page lighthouse

![lighthouse-menu](assets/README-images/menu-page-lighthouse.jpg)

* Book online lighthouse

![lighthouse-book-online](assets/README-images/book-online-lighthouse.jpg)

### Bugs

#### Solved bugs

* When testing my site for responsiveness i realised that the text in all paragraph areas of the site was overflowing out of the page on smaller screen sizes. To fix this i changed font-size propertys from px to em.

* When adding my hamburger menu i noticed that when expanded the menu was wider than the page width which caused there to be a horizontal scroll bar. To fix this i removed any default margin and padding from the menu.

* When testing the menu page on smaller screen devices I noticed that the menu section containers were overflowing to the side of the screen. To fix this i added a media query to re size the containers appropriately.

#### Unsolved bugs

* There are no unsolved bugs.

## Deployment

* This website was deployed on github pages.

## Credits

### Content

* Template for readme taken from Code Institute sample readme.

* Hamburger menu taken from https://alvarotrigo.com/blog/hamburger-menu-css/ 

* The 2 fonts used on this site "Dancing script" and "Cinzel" taken from https://fonts.google.com

### Media 

* All site images were taken from https://www.pexels.com/

* Social media logos on footer taken from https://fontawesome.com/








