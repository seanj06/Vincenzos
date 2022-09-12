# Vincenzo's Fine Dining
Vincenzo's fine dining is a static 3 page website for a fictional Italian Restaurant, complete with a homepage, a menu page and a book online page.

Website developed by Sean Johnston for Code Institute Project Portfolio 1.

[Live Website Link](https://seanj06.github.io/Vincenzos-P1/)

![AmiResponsive](assets/README-images/amiresponsive.jpg)

## Table Of Contents

1. [Project Goals](#project-goals)

2. [User Experience (UX)](#user-experience)
   - [User Stories](#1-user-stories)
   - [Design Choices](#2design-choices)

3. [Features](#features) 
   - [Home Page](#home-page)
   - [Menu Page](#menu-page)
   - [Book Online Page](#9-book-online-page)

4. [Testing](#testing) 
   - [Validator Testing](#validator-testing)
   - [Accessibility](#accessibility) 
   - [Bugs](#bugs)
   - [Testing user stories](#testing-user-stories)

5. [Deployment](#deployment) 

6. [Credits](#credits)

7. [Acknowledgements](#acknowledgements)

## Project Goals

 - This project was created for Code Institute Project Portfolio 1 using both HTML and CSS.

 * Main goals of the site include:

   - Creating a site with consistent styling and easy accessibility for users throughout

   - Creating a site with all relevant and easy to find information for new and returning users.

   - Creating a site with full responsiveness for all screen and device sizes. 

   [Top of page](#vincenzos-fine-dining)

## User Experience (UX)

 ### 1. User Stories

   - #### First time users
     - As a first time user I want to be able to easily navigate the site.
     - As a first time user I want to be able to view the site on mobile and tablet devices as well as desktop.
     - As a first time user I want the site to be simple and easy to read.
     - As a first time user I want to be quickly able to understand the purpose of the site.
     - As a first time user I want to be able to look at the menu online.
     - As a first time user I want to be able to reserve a table online.
     - As a first time user I want to see if there is information on the restaurant location.

  - #### Returning users
    - As a returning user i want to see if the Menu is updated regularly.
    - As a returning user i want to see if there is any update to the opening and closing times of the restaurant.
    - As a returning user i want to see if there is any updates to the book onine page.

  ### 2.Design Choices

  - #### Colors
    
    ![color-scheme](assets/README-images/color-scheme.jpg)
    - The 2 main background colors of the site are #B0A8B9(Heliotrope gray) and #222020(Eerie black).
    - The 2 main text colors are #222020(Eerie black) and #FFFFFF(White)
    - The hero text of the page is #F8F8FF(Ghost White)
    - I chose these colors because i felt they go well together in contrast and are easy to read.

 - #### Fonts

   - The 2 main fonts used in the site are 'Dancing script' and 'Cinzel' both taken from google fonts, with a fallback font of sans-serif.
   - The font used for headings is Dancing script.
   - The font used for all other text is Cinzel.   
 
[Top of page](#vincenzos-fine-dining)

## Features

### Home Page

- ####  Header

  - The Header contains both the Vincenzos fine dining logo to the left of the page and the navigation bar to the right of the page.
  - The logo can be clicked to bring the user back to the home page.
  - The colors were chosen in contrast with each other for easy readability for users
  - The navigation bar links to the 3 pages Home, Menu and Book Online.There is a hover feature implemented which changes the color of the hovered over menu to Gray.There is also a current page feature which shows the user what page they are currently on with white lines around the link heading.

![Headerimage](assets/README-images/header.jpg)

- The navigation bar transforms into a hamburger menu for tablet and mobile devices under 768 pixels wide.

![ClosedHamburgerMenu](assets/README-images/hamburger-menu-closed.jpg)

* When clicked the menu opens into 3 rows with the page links.

![OpenHamburgerMenu](assets/README-images/hamburger-menu-open.jpg)

- ####  Hero Photo Section
  - This section has a background image of a nice restaurant which gives the users an idea of what to expect when coming to the retaurant.

  - The section has a heading with the slogan "The Authentic Dining Experience".

  - This section includes 2 award transparent boxes which slide down from the top of the page when the page is loaded or refreshed.

![photosection](assets/README-images/photo-section.jpg)

- ####  About Us Section

  - This section gives an overview of where the restaurant is located. It also gives a brief history of when the website opened its doors and tells the user that all ingredients are locally sourced and all meals are made fresh.

![about-us-section](assets/README-images/aboutus.jpg)

- ####  Opening Hours Section

  - This section gives the opening hours of the restaurant.

  - It is located on the home page so it is one of the first things the user sees when navigating the site.

![opening-hours](assets/README-images/opening-hours.jpg)

- ####  Where To Find Us Section

  - This section gives an overview of exactly where the restaurant is located and gives users information on nearby parking.

  - The section also has an interactive map with a pin location for the restaurant.

  - This section is located just under the opening hours section for easy user accessibility.

![where-to-find-us](assets/README-images/where-to-find-us.jpg)

- ####  Footer

  - The footer contains 3 clickable links to Facebook, Twitter and Instagram, which all open in a new tab.

  - The section also contains the restaurant contact phone number and contact email address.

  - The bottom of the footer contains a disclaimer explaining that this website is fictional and made for project purposes only.

  - The footer contains all relevant information for the user to contact the restaurant and keep up to date with updates by following social media accounts.

![footer](assets/README-images/footer.jpg)

- ### Menu Page

  - This page contains an online menu for users to look at the meals available to order at the restaurant.

  - The page contains 4 food sections. Starters, Mains, Pizza and Desserts with prices shown for each item and a small image at the head of each section.

![menu1](assets/README-images/menu1.jpg)

* The menu page changes layout to 1 section per line for devices 768 pixels and under.

![menu2](assets/README-images/menu2.jpg)

- ###  Book Online Page

  - This page has a form for users to enter their details to reserve a table online.

  - The form collects the users First name, Last name, Number of people, preferred time slot and any additional requests.

![book-online1](assets/README-images/book-online1.jpg)
![book-online2](assets/README-images/book-online2.jpg)

* When the user submits their details into the form they are taken to a thank you page which confirms their booking and contains a link back to the home page.

![thank-you-page](assets/README-images/thank.you.jpg)

[Top of page](#vincenzos-fine-dining)

## Testing

* I have tested this website works on all browser types.

* I have tested the site on various screen sizes and devices using devtools and confirmed it is responsive to all sizes.

* I have tested all of the clickable links work and open in new tabs and have tested that all form elements in the form section work correctly and are required to submit.

### Validator Testing

* No errors were shown when putting the code through both the w3c html validator and the jigsaw css validator.

![w3c](assets/README-images/w3c.jpg)
![jigsaw](assets/README-images/jigsaw.jpg)

- ### Accessibility

  - I confirm that all 3 pages return a high accessibility rating when running them through the lighthouse tool on devtools.

  </details>
  <details><summary>Home page lighthouse desktop</summary>
  
   ![lighthouse-home](assets/README-images/home-page-lh-desk.jpg)

  </details>
  <details><summary>Home page lighthouse Mobile</summary>

  ![lighthouse-mobile-home](assets/README-images/home-page-lh-mobile.jpg)

  </details>
  <details><summary>Menu page lighthouse Desktop</summary>

  ![lighthouse-menu](assets/README-images/menu-page-lh-desk.jpg)

  </details>
  <details><summary>Menu page lighthouse Mobile</summary>

  ![lighthouse-menu-mobile](assets/README-images/menu-page-lh-mobile.jpg)

  </details>
  <details><summary>Book online lighthouse Desktop</summary>

  ![lighthouse-book-online](assets/README-images/book-online-lighthouse-desk.jpg)

  </details>
  <details><summary>Book online lighthouse Mobile</summary>

  ![Lighthouse-book-online-mobile](assets/README-images/book-online-lh-mobile.jpg)

  </details>
  <details><summary>Thank you lighthouse Desktop</summary>

  ![Lighthouse-thank-you-desktop](assets/README-images/thank-you-lh-desktop.jpg)

  </details>
  <details><summary>Thank you lighthouse Mobile</summary>

  ![Lighthouse-thank-you-mobile](assets/README-images/thank-you-lh-mobile.jpg)

### Bugs

 #### Solved Bugs

- When testing my site for responsiveness I realised that the text in all paragraph areas of the site was overflowing out of the page on smaller screen sizes. To fix this I changed font-size propertys from px to em for responsiveness. I also added 10 pixels of padding to each side of paragraph text.

   <details><summary>Paragraph text css</summary>

  ![p-text-code](assets/README-images/paragraph-text-code.jpg)
  </details>

- When adding my hamburger menu I noticed that when expanded the menu was wider than the page width which caused there to be a horizontal scroll bar. 

   <details><summary>Hamburger menu overflowing</summary>

  ![hamburger-bug](assets/README-images/hamburger-bug.jpg)
  </details>

  - To fix this i removed any default margin and padding from the menu.

  <details><summary>Hamburger menu after removing padding and margin</summary>

  ![hamburger-fixed](assets/README-images/hamburger-fixed.jpg)
  </details>

  <details><summary>Hamburger menu css code</summary>

  ![hamburger-code](assets/README-images/hamburger-code.jpg)
  </details>

- When testing the menu page on smaller screen devices I noticed that the menu section containers were overflowing to the side of the screen. To fix this I added a media query to re size the containers appropriately.

- When testing the responsiveness of my site on different devices I realised that the footer on the Book Online page was not sticking to the bottom of the page on devices with heights of 1250 px or more. I concluded this was because the content on this page was not enough to fill the height of that size. I was unable to fix this bug by resizing the content as this made it look stretched.

  <details><summary>Footer not sticking to bottom</summary>

  ![footer-not-at-bottom](assets/README-images/footer-bug.jpg)
  </details>

  - I fixed the bug by adding a media query for devices with a min height of 1250 pixels to footer position: fixed and bottom: 0.

   
  <details><summary>Media query code</summary>

  ![code](assets/README-images/media-query.jpg)
  </details>

  <details><summary>Fixed footer</summary>

  ![fixed-footer](assets/README-images/fixed-footer.jpg)
  </details>

- When testing my site for responsiveness I noticed that in landscape mode on smaller screens the award boxes were overflowing onto the top of the section below.

  <details><summary>Award boxes overflowing</summary>

  ![award-oveflow](assets/README-images/award-section-overflow.jpg)
  </details> 

  - To fix this i added an orientation:landscape media query and set the margin bottom to zero instead of the deafult keyframes -50 pixels.

  <details><summary>Landscape media query code</summary>

  ![landscape-code](assets/README-images/keyframe-code.jpg) 
  </details> 
  

- #### Unsolved Bugs

  - There are no known unsolved bugs.

  [Top of page](#vincenzos-fine-dining)

 ### Testing user stories

 - As a first time user i want to be able to easly navigate the site.

   - The navbar at the top of the site makes the site easily navigatable for all users, including the clickable logo which takes users back to the home page from any page on the site.

   <details><summary>Top of page navbar</summary>
   
   ![navbar2](assets/README-images/navbar2.jpg)
   </details>

 -  As a first time user I want to be able to view the site on mobile and tablet devices as well as desktop.

   - The site is fully responsive to all screen sizes and devices. The navbar transforms into a hamburger menu for users on small screens. The menu page also transforms into 1 column of menu containers on smaller screens for easy user readability.

   <details><summary>Hamburger menu</summary>

   ![hamburger-menu](assets/README-images/hamburger-menu-open.jpg)
   </details>

   <details><summary>Menu page on mobile</summary>

   ![mobile-menu-page](assets/README-images/menu2.jpg)
   </details>

- As a first time user I want the site to be simple and easy to read. 

  - The design of the site is split into 3 compact pages for easy user accessibility. 

  - The home page includes all relevant information for users including, The navbar with links to the 3 pages, The opening times of the restaurant, The location of the restaurant with an interactive map and the footer with the restaurant phone number, email address and link to social media sites.

  <details><summary>Home Page Information</summary>

  ![home-page-info](assets/README-images/home-page.jpg)
  </details>

  - The menu page has a simple layout for users that inludes information on all of the menu items with prices broken into 4 sections, Starters, Mains, Pizza and Desserts.

  <details><summary>Menu Page</summary>

  ![menu-layout](assets/README-images/menu1.jpg)
  </details>

  - The Book Online page has a simple layout which fits all of the forms on the users screen without need for scrolling.

  <details><summary>Book Online Page</summary>

  ![book-online-layout](assets/README-images/book-online-layout.jpg)
  </details>

- As a first time user i want to be quickly able to understand the purpose of the site.

  - The Award section shows that the purpose of the website is to draw first time and returning users in to the restaurant  by showing them the awards received.

  <details><summary>Award section</summary>

  ![award-section](assets/README-images/photo-section.jpg)
  </details>

 
[Top of page](#vincenzos-fine-dining)


 ## Deployment

- This website was deployed on github pages using the following steps.
 
  - In the Github repository navigate to the settings tab.
  -  From the settings menu scroll down to pages and click it.
  - In the source section of the pages menu navigate to the branch section and select main.
  - Click save and the page will automatically refresh.

  - Navigate back to the pages section and the live link of the published  site will now be there.
  - [Link to site](https://seanj06.github.io/Vincenzos-P1/)

  [Top of page](#vincenzos-fine-dining)


## Credits

- ### Content

  - Template for readme taken from Code Institute sample readme.

  - Code institute gitpod template was used and taken from https://github.com/Code-Institute-Org/gitpod-database-config

  - Hamburger menu design taken from https://alvarotrigo.com/blog/hamburger-menu-css/ 

  - The 2 fonts used on this site "Dancing script" and "Cinzel" taken from https://fonts.google.com

- ### Media 

  - All site images were taken from https://www.pexels.com/

  - Social media logos on footer taken from https://fontawesome.com/

- ### Research

  - https://stackoverflow.com/ was used for any bugs which I could not solve. 

  - https://www.w3schools.com/ was used for research on various code syntax.

  [Top of page](#vincenzos-fine-dining)

  ## Acknowledgements

 - Thank you to my mentor Jubril who helped me along the way by guiding me in the right direction to complete the website.

 - Thank you to the Code Institute slack community and my classmates who helped with any issues i was having while making the website. 

  [Top of page](#vincenzos-fine-dining)








