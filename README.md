# Penny for your Thoughts

<div>
<img src="responsive.jpg" alt="Responsive sample">
</div>

**[Live site](https://edb83.github.io/milestone1/)**

---

## Context

This site is a showcase for an aspiring photographer's work, which is available to purchase either on card or enlarged print.

Since moving to the countryside, Penny has found herself increasingly inspired by her beautiful surroundings and is keen to share them with a wider audience. More than ever in these uncertain, digital times, there's comfort to be found in a personal message written on a physical card, adorned with beautiful, candid pictures of nature.

## UX

### Overview

The site is aimed at people looking for greeting cards, specifically those who value supporting local endeavours rather than large, established corporations. The site’s intended audience are people who value the personal touch and ability to communicate directly with the seller.

The enterprise is humble but, as evidenced by the quality of the pictures, has a wealth of emotive images from the English countryside to share. These are the scenes we may all have witnessed but which are seldom captured.

### User stories

As the **client** I want:
  * Visitors to be immediately aware of what the product is
  * A clean, consistent interface which will not confuse visitors
  * My work to be showcased from the outset
  * An immediate link to the gallery
  * A gallery which allows visitors to quickly browse through high quality images and add them to a shopping basket

As a **visitor** I want:
  * For it to be immediately clear what the purpose of the site is and what it has to offer
  * A clean interface and layout which allows me to focus on browsing the images and purchasing them
  * To be able to quickly navigate the site using navbar and clear links
  * To see a striking image which is indicative of the product’s nature and quality
  * To learn something about the photographer
  * To be able to contact the photographer directly
  * To be able to quickly find out more about the product, specifically its price and available options
  * To be able to access the gallery quickly and browse its entire contents at once
  * To be able to choose themes from the image gallery, and access them quickly
  * To be able to click an image to see its true aspect ratio, if it isn’t immediately obvious
  * To be able to quickly add desired images to my shopping basket
  * To be able to quickly find the photographer’s social media presence
  * To be able to sign up for more information and updates on the photographer’s work
  * For the site to be responsive on all devices
  * For there to be clear but aesthetically pleasing visual feedback when hovering over clickable links
  * For the image gallery to be fast to load and easy to navigate
  * For the signup form to show me if I have inputted incorrectly
  * For links to external sites to open in a separate tab to prevent loss of focus

### Wireframes

--TBC--




### Site theme

--TBC--




## Features

### Site-wide

**1. Navbar**
  * Collapses into a hamburger icon to support the mobile browsing experience
  * Brand maintains visibility on all device sizes
  * Brand acts as the Home button to avoid duplication and clutter
  * Drop down options are scrollable on mobile devices in landscape orientation to prevent frustrating case of hidden options
  * High contrast hoverable links provide responsive visual feedback
  * Active links clearly indicate current location on site
  * Shopping basket for quick access to purchasing selected items (currently disabled for future implementation)

**2. Footer**
  * Social media links with a blank target to prevent disruption to the browsing experience
  * Copyright
  * Footer is always positioned at the bottom of the page for consistency and visual appeal (primarily for larger displays where content would otherwise not fill the viewport)

### Pages

**3. Landing page**
  * Full viewport hero image to showcase the photographer's imagery (primary goal) and promote the site's colour scheme
  * Transparent jumbotron to emphasise the name of the site
  * Call to action button linking to the gallery andand  invitation to purchase (primary goal)
  * Succinct and clear introduction outlining the purpose of the site
  * Mini gallery showcasing the different themes of images, including links for quick access to the respective sections of the full gallery and responsive visual feedback

**4. About**
  * Provides the voice of the photographer, plus their background, credentials and reason for setting up the site
  * Link to email photographer directly with email subject placeholder to encourage completion

**5. Pricing**
  * Brief description of product
  * Two clear tables with prices for both cards and prints, including price per unit for multiple orders and postage not included

**6. Gallery**
  * Brief introduction explaining how to add items to basket and how to view in full aspect ratio
  * Six themed sections (Canals, Coast, Flora and Fauna, Flowers, Landscapes, Trees)
  * Images arranged in responsive grid and set width/height to maintain image integrity and provide a consistent display
  * On mobile, images are clearly displayed in their original aspect ratio, while on larger devices they are displayed uniformly cropped and in a responsive grid for easy browsing 
  * Clear 'Add (to basket)' button in consistent position on all images. Enables users to add an item to shooing cart (with just two clicks from the landing page) and includes visual feedback on hover
  * Ability to enlarge images by clicking on them, and to scroll through a pop-up gallery of images in full aspect ratio. Clicking outside viewing area (or swiping up/down on mobile) returns visitor to the normal gallery
  * Within pop-up gallery, user can view thumbnails of all images and use the mouse wheel or swipe to scroll through
  * Names of each image are included at bottom of pop-up gallery, providing some context for each scene and allowing for specific questions of the photographer
  * Image sizes are all below 300kb for faster loading, while preserving FHD resolution to showcase their quality

**7. Signup**
  * Simple form allows the user to sign up for more information and news of fresh images being added to gallery
  * Validation of user inputs (blank fields, typical email format), indicating any errors clearly
  * *NB at present this form is not linked up to any database and will not record inputs*

### Features left to implement

  * Shopping basket and purchasing functions
  
    *This crucial missing feature will include payment options (multiple item purchase, choice of size), purchase history and the option to save delivery address and card details for repeat purchases*

  * Ability to search for specific images / metadata
  
    *e.g results for ‘deer’, ‘butterfly’, ‘water’, ‘water’, ‘sunset’, ‘rocks’, ‘tractor’*

  * Additional browsing criteria

    *e.g seasons, landscape / portrait*

  * Mockup of image for chosen options

    *e.g 'Show me what Twisted Tree looks like on a card / in large print'*

  * Option to order cards with a choice of messages / bespoke messages


## Technologies Used

### Languages

  * HTML
  * CSS
  * Javascript - notably for collapsable navbar and modal gallery

### Project management

  * [Balsamiq](https://balsamiq.com/wireframes/) - Wireframe creation tool
  * [GitHub](https://github.com/) - Version control and deployment
  * [GitPod](https://gitpod.io/) - IDE used to code the site

### Style and theme

  * [Bootstrap](https://getbootstrap.com/) - Responsive grid system (prioritising a mobile-first design philosophy) and boilerplate styling
  * [Color Scheme Designer](https://colorschemedesigner.com/csd-3.5/) - Complimentary color scheme for the site
  * [CSS Tricks](https://css-tricks.com/examples/hrs/) - Specifically for linear-gradiant horizontal rule
  * [Font Awesome](https://fontawesome.com/) - Icons used for shopping cart in navbar
  * [Google Fonts](https://fonts.google.com/) - Open Sans and Monserrat fonts
  * [Zyro Logo Maker](https://zyro.com/logo-maker) - Creating the favicon
  
### Visual effects

  * [Fancybox](https://fancyapps.com/fancybox/3/) - Simple to use Javascript package for modal gallery
  * [Hover.css](https://ianlunn.github.io/Hover/) - Effect applied to intro gallery circular previews

### Image manipulation

  * [IrfanView](https://www.irfanview.com/) - Program for cropping image batches to the same aspect ratio
  * [Tiny JPG](https://tinyjpg.com/) - Reducing the size of all images without noticeable loss of quality
  
### Online resources

  * [How to Geek](https://www.howtogeek.com/354015/how-to-resize-images-and-photos-in-windows/) - specifically advice on how to efficiently handle a large number of images
  * [Stack Overflow](https://stackoverflow.com/)
  * [W3 Schools](https://www.w3schools.com/)
  

## Testing

### Automated testing

  * [W3C - HTML](https://validator.w3.org/) - once ```alt``` tags had been filled, no HTML issues detected - **PASS**
  * [W3C - CSS](https://jigsaw.w3.org/css-validator/) - no CSS issues detected - **PASS**
  * [Unicorn revealer - overflow](https://chrome.google.com/webstore/detail/unicorn-revealer/lmlkphhdlngaicolpmaakfmhplagoaln/related) - tested all pages and no evidence of overflow - **PASS**

### Manual testing

**Summary**:

The only manual tests which failed are related to the in-built form validation settings. These test were carried out initially with the boilerplate Bootstrap form and then using the ```novalidate``` property but the results were the same.

The following scenarios were tested to ensure that the site is functioning as expected:

**1. Nav bar**
  * From each page, check that nav bar links take you to the correct page - **PASS**
  * From each page, check that each Gallery dropdown link takes you to the correct section of the Gallery page - **PASS**
  * From each page, check that nav bar links (including Brand) have the correct styling (blue) when hovered over on desktop devices - **PASS**
  * From each page, check that the active / current nav bar link (excluding Brand) is correctly styled and distinguished from the others - **PASS**

**2. Footer**
  * From each page, check that all social media links take you to the relevant external site, and open in a separate browser tab - **PASS**
  * From each page, check that all social media icons have the correct styling (dark yellow) when hovered over on desktop devices - **PASS**

**3. Landing page**
  * Click the Purchase button to check it goes to the top of the Gallery page - **PASS**
  * On desktop, hover over the Purchase button to check visual feedback is provided (white background, black text) - **PASS** - however, NB the unwanted styling applied by Safari (noted as Unresolved issue below)
  * Click each intro gallery circular image to check it takes you to the relevant anchor within the Gallery page - **PASS**
  * On desktop, hover over each intro gallery circular image to check visual feedback is provided (hvr-grow effect) - **PASS** - however, NB minor distortion of the text. A decision was made to apply this effect to the entire block to provide a smoother application of the effect when sweeping over the images

**4. About page**
  * Click the "Contact me" email link to check it creates a new email to the photographer - **PASS**
  * Check the Subject of the new email message is correctly filled - **PASS** - initially a missing ">" was preventing the Subject field being filled but this was corrected

**5. Pricing page**
  * No functionality to test - **N/A**

**6. Gallery page**
  * Click each of the 48 images to check it brings up a modal with the correct image enlarged - **PASS** - initially some file names were incorrect but were all amended
  * Check that the correct caption is displayed for each of the 48 images in the modal gallery - **PASS**
  * Check that all 48 "Add" buttons (currently no functionality as shopping basket is beyond scope of project, see Features left to implement) have the correct styling (dark blue) when hovered over on desktop devices - **PASS**

**7. Signup**
  * On desktop, hover over the Sign Up button to check visual feedback is provided (dark blue) - **PASS**
  * On sign-up form, leave all fields blank and click Sign Up button to check validation displays an input issue - **PASS**
  * On sign-up form, enter all fields correctly and click Sign Up button to check validation confirms correct inputs - **PASS**
  * On sign-up form and for each input field individually, enter all fields correctly apart from one and check validation correctly identifies issues - **PASS**
  * On sign-up form, enter an email address in an incorrect format to check validation displays an input issue. Results:
    
    "@" - **PASS**
    " @ " - **PASS**
    "a@b" - **FAIL** - this would need to be corrected but is beyond the scope of this project
    "a @ b" - **PASS**
    "a@ b" - **PASS**
    "a @b" - **PASS**

  * On sign-up form, enter something different for Password and Confirm Password to check validation displays an input issue - **FAIL**
  * On sign-up form, enter a space (" ") as either password to check validation displays an input issue - **FAIL**

Additionally, eight individuals contributed to testing the site and provided feedback on its layout, responsiveness and styling at various points in development.


### Responsivity

--TBC--

#### Browsers

--TBC--

#### Screen sizes

--TBC--


### Issues and resolutions

#### Resolved

  * **Hero image does not display on iOS mobile devices**

    Resolved by adding a media query for smaller displays which sets ```background-attachment: scroll```

  * **Navbar does not collapse when clicking links within the same page**

    *When the Gallery or hamburger dropdowns are expanded in the navbar, anchor links within the same page will not collapse the navbar (most noticeable on the Gallery page)*
    
    Resolved by customising a Javascript snippet from [Stack Overflow](https://stackoverflow.com/questions/42401606/how-to-hide-collapsible-bootstrap-4-navbar-on-click) to point to the relevant classes in the navbar

  * **Navbar dropdown not visible on landscape mobile devices**

    *When expanding the Gallery nav-item in the navbar while in landscape mode on a mobile device, not all list items are visible and cannot be clicked*
    
    Resolved by using a suggestion found on [Github](https://github.com/twbs/bootstrap/issues/23374) and adding a media query for smaller displays which sets ```overflow-y: scroll``` and ```height: 115px``` to ensure the list items are visible on all displays

  * **Intro gallery circular images on right margin cause overflow when hvr-grow effect is appled**

    Resolved by incrementally reducing the width of intro-gallery and finally settling on ```width: 91%```

  * **There is white space beneath footer on pages with little content (Pricing and About)**

    Resolved by using a suggestion from [Philip Walton](https://philipwalton.github.io/solved-by-flexbox/demos/sticky-footer/) to set body element ```flex-direction: column``` and ```min-height: 100vh```. This was a more elegant solution than changing the structure of the site e.g. by adding the Pricing and About pages further down the Landing Page and relying on achor links, or by simply increasing the content on each of the affected pages

  * **Gallery image buttons do not stay inside their respective images where images have different aspect ratios**

    *Due to having ```position: abolute``` buttons were left floating outside of their images*
    
    Initially resolved by fixing the height of images to ```vh20``` but this had the unintended side-effect of making them appear too wide on mobile devices

  * **Gallery images on small displays appear too wide**

    Resolved by giving the image ```height: 200px``` and adding a media query which changes this to ```height: 100%``` on smaller devices. This has the added benefit of displaying images in their original aspect ratio on mobile

  * **Signup form validation messages display poorly on iOS**

    *Despite displaying correctly in Chrome devtools, the display on iOS leaves validation error messages appearing clipped and ugly*
    
    Resolved by using Bootstrap's recommended ```needs-validation``` class and ```novalidate```. A block styled with ```invalid-feedback``` was avoided to prevent error messages appearing and shifting the lines of input fields 


#### Unresolved

  * **iOS browser adds unwanted styling to Pricing button in hero image**

    Attempts were made to override Apple's styling using ```-webkit-``` but were unsuccesful

  * **Signup form password and confirmation password can be different**



### Known bugs

  * None at present

## Deployment

To deploy this page to GitHub Pages from its [GitHub repository](https://github.com/Edb83/milestone1), the following steps were taken: 

1. From the menu items near the top of the page, select **Settings**
2. Scroll down to the **GitHub Pages** section
3. Under **Source** click the drop-down menu labelled **None** and select **Master Branch**
4. On selecting Master Branch the page is automatically refreshed, the website is now deployed
5. Scroll back down to the **GitHub Pages** section in **Settings** to retrieve the link to the deployed website. It may take a short time to go live, but typically less than 60 seconds
 
### How to run this project locally

To clone this project from GitHub:

1. Under the repository name, click "Clone or download"
2. In the Clone with HTTPs section, copy the clone URL for the repository
3. In your local IDE open Git Bash
4. Change the current working directory to the location where you want the cloned directory to be made
5. Type ```git clone```, and then paste the URL you copied in Step 3
```console
git clone https://github.com/Edb83/milestone1.git
```
6. Press Enter. Your local clone will be created

Further reading and troubleshooting on cloning a repository from GitHub can be found [here](https://help.github.com/en/articles/cloning-a-repository).


## Credits

Carlos (Code Institute student)
Jonathan Munz (Code Institute mentor)
Richard Wells (Code Institute lead)

Extremely useful feedback on appearance and user experience was provided by Lola, Tash, Mims, Beckx and Peter!


## Content

The text in the About page and photos used throughout this site were obtained from the client, Penny Holland. All other text was written by me and agreed with the client.


## Acknowledgements

I received inspiration for this project from Penny Holland


## Disclaimer

This site was developed for educational purposes but will be used as envisaged once the remaining features have been implemented