# Vincenzo's Fine Dining
Vincenzo's fine dining is a static 3 page website for a fictional Italian Restaurant, complete with a homepage, a menu page and a book online page.

![AmiResponsive](assets/README-images/amiresponsive.jpg)

## User experience

 ### 1. User stories

   - #### First time users
     - As a first time user i want to be able to easily navigate the site.
     - I want to be able to view the site on mobile and tablet devices as well as desktop.
     - As a first time user i want the site to be simple and easy to read.
     - As a first time user i want to be quickly able to understand the purpose of the site.
     - As a first time user i want to be able to look at the menu online.
     - As a first time user i want to be able to reserve a table online.
     - As a first time user i want to see if there is information on the restaurant location.

  - #### Returning users
    - As a returning user i want to see if the Menu is updated regularly.
    - As a returning user i want to see if there is any update to the opening and closing times of the restaurant.
    - As a returning user i want to see if there is any updates to the book onine page.

  ### 2.Design choices

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
 

## Features

### Home Page

####  Header
* The Header contains both the Vincenzos fine dining logo to the left of the page and the navigation bar to the right of the page.
* The logo can be clicked to bring the user back to the home page.
* The colors were chosen in contrast with each other for easy readability for users
* The navigation bar links to the 3 pages Home, Menu and Book Online.There is a hover feature implemented which changes the color of the hovered over menu to Gray.There is also a current page feature which shows the user what page they are currently on with white lines around the link heading.

![Headerimage](assets/README-images/header.jpg)

* The navigation bar transforms into a hamburger menu for tablet and mobile devices under 768 pixels wide.

![ClosedHamburgerMenu](assets/README-images/hamburger-menu-closed.jpg)

* When clicked the menu opens into 3 columns with the page links.

![OpenHamburgerMenu](assets/README-images/hamburger-menu-open.jpg)

####  Hero Photo section
* This section has a background image of a nice restaurant which gives the users an idea of what to expect when coming to the retaurant.

* The section has a heading with the slogan "The Authentic Dining Experience".

* This section includes 2 award transparent boxes which slide down from the top of the page when the page is loaded or refreshed.

![photosection](assets/README-images/photo-section.jpg)

####  About us section
* This section gives an overview of where the restaurant is located. It also gives a brief history of when the website opened its doors and tells the user that all ingredients are locally sourced and all meals are made fresh.

![about-us-section](assets/README-images/aboutus.jpg)

####  Opening hours section
* This section gives the opening hours of the restaurant.

* It is located on the home page so it is one of the first things the user sees when navigating the site.

![opening-hours](assets/README-images/opening-hours.jpg)

####  Where to find us section
* This section gives an overview of exactly where the restaurant is loacated and gives information on nearby parking.

* The section also has an interactive map with a pin location for the restaurant.

* This section is located just under the opening hours section for easy user accessibility.

![where-to-find-us](assets/README-images/where-to-find-us.jpg)

####  Footer
* The footer contains 3 clickable links to Facebook, Twitter and Instagram, which all open in a new tab.

* The section also contains the restaurant contact phone number and contact email address.

* The bottom of the footer contains a disclaimer explaining that this website is fictional and made for project purposes only.

* The footer contains all relevant information for the user to contact the restaurant and keep up to date with updates by following social media accounts.

![footer](assets/README-images/footer.jpg)

### Menu Page

* This page contains an online menu for users to look at the meals available to order at the restaurant.

* The page contains 4 food sections. Starters, Mains, Pizza and Desserts with prices shown for each item and a small image at the head of each section.

![menu1](assets/README-images/menu1.jpg)

* The menu page changes layout to 1 section per line for devices 768 pixels and under.

![menu2](assets/README-images/menu2.jpg)

### 9. Book online page
* This page has a form for users to enter their details to reserve a table online.

* The form collects the users First name, Last name, Number of people, preferred time slot and any additional requests.

![book-online1](assets/README-images/book-online1.jpg)
![book-online2](assets/README-images/book-online2.jpg)

* When the user submits their details into the form they are taken to a thank you page which confirms their booking and contains a link back to the home page.

![thank-you-page](assets/README-images/thank.you.jpg)

## Testing
---
* I have tested this website works on all browser types.

* I have tested the site on various screen sizes and devices using devtools and confirmed it is responsive to all sizes.

* I have tested all of the clickable links work and open in new tabs and have tested that all form elements in the form section work correctly and are required to submit.

### Validator Testing

* No errors were shown when putting the code through both the w3c html validator and the jigsaw css validator.

![w3c](assets/README-images/w3c.jpg)
![jigsaw](assets/README-images/jigsaw.jpg)

* ### Accessibility

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

#### Solved bugs

* When testing my site for responsiveness i realised that the text in all paragraph areas of the site was overflowing out of the page on smaller screen sizes. To fix this i changed font-size propertys from px to em.

* When adding my hamburger menu i noticed that when expanded the menu was wider than the page width which caused there to be a horizontal scroll bar. To fix this i removed any default margin and padding from the menu.

* When testing the menu page on smaller screen devices I noticed that the menu section containers were overflowing to the side of the screen. To fix this I added a media query to re size the containers appropriately.

#### Unsolved bugs

* There are no unsolved bugs.

 ## Deployment

- This website was deployed on github pages using the following steps.
 
  - In the Github repository navigate to the settings tab.
  -  From the settings menu scroll down to pages and click it.
  - In the source section of the pages menu navigate to the branch section and select main.
  - Click save and the page will automatically refresh.

  - Navigate back to the pages section and the live link of the published will now be there.
  - [Link to site](https://seanj06.github.io/Vincenzos/)


## Credits
---
### Content

* Template for readme taken from Code Institute sample readme.

* Hamburger menu taken from https://alvarotrigo.com/blog/hamburger-menu-css/ 

* The 2 fonts used on this site "Dancing script" and "Cinzel" taken from https://fonts.google.com

### Media 

* All site images were taken from https://www.pexels.com/

* Social media logos on footer taken from https://fontawesome.com/








