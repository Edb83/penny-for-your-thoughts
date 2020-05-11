# Penny for your Thoughts

![alt text](responsive.jpg "Responsive sample")

**[Live site](https://edb83.github.io/penny-for-your-thoughts/)**

---

## Index

- <a href="#project">Context</a>
- <a href="#ux">UX</a>
    - <a href="#ux-stories">User stories</a>
    - <a href="#ux-wireframes">Wireframes</a>
    - <a href="#ux-theme">Theme</a>
- <a href="#features">Features</a>
    - <a href="#features-all">Site wide</a>
    - <a href="#features-pages">Pages</a>
    - <a href="#features-future">Still to implement</a>
- <a href="#technologies">Technologies Used</a>
- <a href="#testing">Testing</a>
    - <a href="#testing-auto">Automated</a>
    - <a href="#testing-manual">Manual</a>
    - <a href="#testing-responsive">Responsive</a>
    - <a href="#testing-resolved">Resolved issues</a>
    - <a href="#testing-unresolved">Unresolved issues</a>
    - <a href="#testing-bugs">Known bugs</a>
- <a href="#deployment">Deployment</a>
- <a href="#credits">Credits</a>

---

<span id="context"></span>

## Context

This site is a showcase for an aspiring photographer's work, which is available to purchase either on card or enlarged print.

Since moving to the countryside, Penny has found herself increasingly inspired by her beautiful surroundings and is keen to share them with a wider audience. More than ever in these uncertain, digital times, there's comfort to be found in a personal message written on a physical card, adorned with beautiful, candid pictures of nature.

<span id="ux"></span>

## UX

### Overview

The site is aimed at people looking for greeting cards, specifically those who value supporting local endeavours rather than large, established corporations. The site’s intended audience are people who value the personal touch and ability to communicate directly with the seller.

The enterprise is humble but, as evidenced by the quality of the pictures, has a wealth of emotive images from the English countryside to share. These are the scenes we may all have witnessed but which are seldom captured.

<span id="ux-stories"></span>

### User stories

For ease of reference, the means by which a user's expectations have been met are summarised below each user story:

As the **client** I want

- Visitors to be immediately aware of what the product is

  **Response:** The sub-heading over the hero image, call to action (Purchase button) and the three introductory statements make it immediately clear what the product is

- A clean, consistent interface which will not confuse visitors

  **Response:** The navbar, footer and headings of each page are clear, simple and consistent, as are the spacing, typography, image styling and colours

- My work to be showcased from the outset

  **Response:** The landing page is dedicated to the 100% viewport hero image and samples of the various themes of image below that. This ensures the photographer's work is centre stage

- An immediate link to the gallery

  **Response:** The gallery is accessible in the nav bar, call to action and intro gallery images

- A gallery which allows visitors to quickly browse through high quality images in their original aspect ratio and to add them to a shopping basket

  **Response:** The gallery has a clean and effective modal which displays Full HD images in their original aspect ratio and allows the entire gallery to be browsed with just the mouse wheel / swiping. There is an "Add (to basket)" button on each image for a shopping experience which is expected on sites nowadays

  _NB the table below is a repeat of info above_

| <div style="width: 50%">Client's expectations</div>                                                                                                | How is this met?                                                                                                                                                                                                                                                                                             |
| :------------------------------------------------------------------------------------------------------------------------------------------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Visitors to be immediately aware of what the product is                                                                                            | The sub-heading over the hero image, call to action (Purchase button) and the three introductory statements make it immediately clear what the product is                                                                                                                                                    |
| Clean, consistent interface which will not confuse visitors                                                                                        | The navbar, footer and headings of each page are clear, simple and consistent, as are the spacing, typography, image styling and colours                                                                                                                                                                     |
| My work to be showcased from the outset                                                                                                            | The landing page is dedicated to the 100% viewport hero image and samples of the various themes of image below that. This ensures the photographer's work is centre stage                                                                                                                               |
| An immediate link to the gallery                                                                                                                   | The gallery is accessible in the nav bar, call to action and intro gallery images                                                                                                                                                                                                                            |
| A gallery which allows visitors to quickly browse through high quality images in their original aspect ratio and to add them to a shopping basket | The gallery has a clean and effective modal which displays Full HD images in their original aspect ratio and allows the entire gallery to be browsed with just the mouse wheel / swiping. There is an "Add (to basket)" button on each image for a shopping experience which is expected on sites nowadays |

As a **visitor** I want:

- For it to be immediately clear what the purpose of the site is and what it has to offer

  **Response:** Aligns with client's expectations

- A clean interface and layout which allows me to focus on browsing the images and purchasing them

  **Response:** Aligns with client's expectations

- To be able to quickly navigate the site using navbar and clear links

  **Response:** Aligns with client's expectations

- To see a striking image which is indicative of the product’s nature and quality

  **Response:** Aligns with client's expectations

- To learn something about the photographer

  **Response:** The About page is separate from the rest of the content but is easily accessible for those wishing to learn more about the photographer, and the information itself is not overly dense or excessive

- To be able to contact the photographer directly

  **Response:** The About page includes a contact email

- To be able to quickly find out more about the product, specifically its price and available options

  **Response:** The Pricing page is currently separate and provides an acceptible means of sharing this information, which is laid out in a pair of easily digestible tables containly only pertinent information. As the project develops and the shopping basket is implemented, this information may be conveyed more effectively elsewhere

- To be able to access the gallery quickly and browse its entire contents at once

  **Response:** Aligns with client's expectations

- To be able to choose themes from the image gallery, and access them quickly

  **Response:** Currently this expectation is met (and promoted) using the navbar Gallery dropdown list and intro gallery below the hero image. This method will be re-examined as new images are added and when future functionality enables advanced search options

- To be able to click an image to see its true aspect ratio, if it isn’t immediately obvious

  **Response:** Aligns with client's expectations

- To be able to quickly add desired images to my shopping basket

  **Response:** Aligns with client's expectations

- To be able to quickly find the photographer’s social media presence

  **Response:** The minimalist footer provides available social media links, as is expected by all web users today

- To be able to sign up for more information and updates on the photographer’s work

  **Response:** The Sign Up page has the singular purpose of establishing a connection with potential clients in the hope of securing repeat business

- For the site to be responsive on all devices

  **Response:** Addressed in the Responsiveness section below

- For there to be clear but aesthetically pleasing visual feedback when hovering over clickable links

  **Response:** All clickable links have consistent visual feedback, including the subtle hover effect on the intro gallery images

- For the image gallery to be fast to load and easy to navigate

  **Response:** Efforts have been made to reduce the size of files to what is acceptible on the web today, but there is scope to utilise thumbnails of an even smaller size to improve the speed at which the Gallery loads

- For the signup form to show me if I have inputted incorrectly

  **Response:** Addressed in the Manual testing section below

- For links to external sites to open in a separate tab to prevent loss of focus

  **Response:** This currently only applies to the social media links in the footer, but they all open in a separate browser tab

  _NB the table below is a repeat of info above_

| <div style="width: 50%">Visitor's expectation</div>                                              | How is this met?                                                                                                                                                                                                                                                                                                               |
| :----------------------------------------------------------------------------------------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Immediately clear what the purpose of the site is and what it has to offer                       | Aligns with client's expectations                                                                                                                                                                                                                                                                                              |
| A clean interface and layout which allows me to focus on browsing the images and purchasing them | Aligns with client's expectations                                                                                                                                                                                                                                                                                              |
| Quickly navigate the site using navbar and clear links                                           | Aligns with client's expectations                                                                                                                                                                                                                                                                                              |
| Striking image which is indicative of the product’s nature and quality                           | Aligns with client's expectations                                                                                                                                                                                                                                                                                              |
| Learn something about the photographer                                                           | The About page is separate from the rest of the content but is easily accessible for those wishing to learn more about the photographer, and the information itself is not overly dense or excessive                                                                                                                           |
| Contact the photographer directly                                                                | The About page includes a contact email                                                                                                                                                                                                                                                                                        |
| Quickly find out more about the product, specifically its price and available options            | The Pricing page is currently separate and provides an acceptible means of sharing this information, which is laid out in a pair of easily digestible tables containly only pertinent information. As the project develops and the shopping basket is implemented, this information may be conveyed more effectively elsewhere |
| Access the gallery quickly and browse its entire contents at once                                | Aligns with client's expectations                                                                                                                                                                                                                                                                                              |
| Choose themes from the image gallery, and access them quickly                                    | Currently this expectation is met (and promoted) using the navbar Gallery dropdown list and intro gallery below the hero image. This method will be re-examined as new images are added and when future functionality enables advanced search options                                                                          |
| Click an image to see its true aspect ratio, if it isn’t immediately obvious                     | Aligns with client's expectations                                                                                                                                                                                                                                                                                              |
| Quickly add desired images to my shopping basket                                                 | Aligns with client's expectations                                                                                                                                                                                                                                                                                              |
| Quickly find the photographer’s social media presence                                            | The minimalist footer provides available social media links, as is expected by all web users today                                                                                                                                                                                                                             |
| Sign up for more information and updates on the photographer’s work                              | The Sign Up page has the singular purpose of establishing a connection with potential clients in the hope of securing repeat business                                                                                                                                                                                          |
| Responsive on all devices                                                                        | Addressed in the Responsiveness section below                                                                                                                                                                                                                                                                                  |
| Clear but aesthetically pleasing visual feedback when hovering over clickable links              | All clickable links have consistent visual feedback, including the subtle hover effect on the intro gallery images                                                                                                                                                                                                             |
| Image gallery to be fast to load and easy to navigate                                            | Efforts have been made to reduce the size of files to what is acceptible on the web today, but there is scope to utilise thumbnails of an even smaller size to improve the speed at which the Gallery loads                                                                                                                    |
| Signup form to show me if I have inputted incorrectly                                            | Addressed in the Manual testing section below                                                                                                                                                                                                                                                                                  |
| Links to external sites to open in a separate tab to prevent loss of focus                       | This currently only applies to the social media links in the footer, but they all open in a separate browser tab                                                                                                                                                                                                               |

<span id="ux-wireframes"></span>

### Wireframes

- [Sitemap](assets/wireframes/sitemap.png)

#### Desktop

- [Home](assets/wireframes/home-desktop.png)
- [About](assets/wireframes/about-desktop.png)
- [Pricing](assets/wireframes/pricing-desktop.png)
- [Gallery](assets/wireframes/gallery-desktop.png)
- [Signup](assets/wireframes/signup-desktop.png)

#### Tablet

- [Home](assets/wireframes/home-tablet.png)
- [About](assets/wireframes/about-tablet.png)
- [Pricing](assets/wireframes/pricing-tablet.png)
- [Gallery](assets/wireframes/gallery-tablet.png)
- [Signup](assets/wireframes/signup-desktop.png)

#### Mobile

- [Home](assets/wireframes/home-mobile.png)
- [About](assets/wireframes/about-mobile.png)
- [Pricing](assets/wireframes/pricing-mobile.png)
- [Gallery](assets/wireframes/gallery-mobile.png)
- [Signup](assets/wireframes/signup-mobile.png)

### Site theme

Based on the client's brief and visitors' expectations for the site, a clean, simple aesthetic has been adopted. In previous iterations the theme was more minimalistic in an attempt to focus purely on the content, but this was counterintuitive as the lack of contrast reduced the visibility of important elements and overall the site lacked identity.

At this point, user feedback suggested changing the hero image and after doing so, [Color Scheme Designer](https://colorschemedesigner.com/csd-3.5/) was used to pull out several complimentary and web-friendly colours (#036, #39C, #960) which tied in with the new hero image. The result is a much more vibrant aesthetic based on blues and gold, which gives the site a bolder appearance and more character. Furthermore, visual feedback for user actions became much clearer and the identity of separate elements (e.g images with shadows, golden horizontal rules to indicate consitent headings etc) became more apparent.

<span id="features"></span>

## Features

<span id="features-all"></span>

### Site-wide

**1. Navbar**

- Collapses into a hamburger icon to support the mobile browsing experience
- Brand maintains visibility on all device sizes
- Brand acts as the Home button to avoid duplication and clutter
- Drop down options are scrollable on mobile devices in landscape orientation to prevent frustrating case of hidden options
- High contrast hoverable links provide responsive visual feedback
- Active links clearly indicate current location on site
- Shopping basket for quick access to purchasing selected items (for future implementation and currently disabled)

**2. Footer**

- Social media links with a blank target to prevent disruption to the browsing experience
- Copyright
- Footer is always positioned at the bottom of the page for consistency and visual appeal (primarily for larger displays where content would otherwise not fill the viewport)

<span id="features-pages"></span>

### Pages

**3. Landing page**

- Full viewport hero image to showcase the photographer's imagery (primary goal) and promote the site's colour scheme
- Transparent jumbotron to emphasise the name of the site
- Call to action button linking to the gallery and inviting to purchase (primary goal)
- Succinct and clear introduction outlining the purpose of the site
- Mini gallery showcasing the different themes of images, including links for quick access to the respective sections of the full gallery as well as responsive visual feedback

**4. About**

- Provides the voice of the photographer, plus their background, credentials and reason for setting up the site
- Link to email photographer directly with email subject placeholder to encourage completion

**5. Pricing**

- Brief description of product
- Two clear tables with prices for both cards and prints, including price per unit for multiple orders and statement that postage not included

**6. Gallery**

- Brief introduction explaining how to add items to basket and how to view in full aspect ratio
- Six themed sections (Canals, Coast, Flora and Fauna, Flowers, Landscapes, Trees)
- On mobile, images are clearly displayed in their original aspect ratio, while on larger devices they are displayed uniformly cropped and in a responsive grid for easy browsing
- Clear 'Add (to basket)' button in consistent position on all images. Enables users to add an item to shopping cart (with just two clicks from the landing page) and includes visual feedback on hover
- Ability to enlarge images by clicking on them, and to scroll through a pop-up gallery of images in full aspect ratio. Clicking outside viewing area (or swiping up/down on mobile) returns visitor to the normal gallery
- Within pop-up gallery, user can view thumbnails of all images and use the mouse wheel or swipe to scroll through
- Names of each image are included at bottom of pop-up gallery, providing some context for each scene and enabling visitors to ask specific questions of the photographer
- Image sizes are all below 300kb for faster loading, while preserving FHD resolution to showcase their quality

**7. Signup**

- Simple form allows the user to sign up for more information and news of fresh images being added to gallery
- Validation of user inputs (blank fields, typical email format), indicating any errors clearly

<span id="features-future"></span>

### Features left to implement

- Shopping basket and purchasing functions

  _This crucial missing feature will include payment options (multiple item purchase, choice of size), purchase history and the option to save delivery address and card details for repeat purchases_

- Ability to search for specific images / metadata

  _e.g results for ‘deer’, ‘butterfly’, ‘water’, ‘water’, ‘sunset’, ‘rocks’, ‘tractor’_

- Additional browsing criteria

  _e.g seasons, landscape / portrait_

- Mockup of image for chosen options

  _e.g 'Show me what Twisted Tree looks like on a card / in large print'_

- Option to order cards with a choice of messages / bespoke messages

- Sign-up form submission functionality

<span id="technologies"></span>

## Technologies Used

### Languages

- HTML
- CSS
- Javascript - notably for collapsable navbar and modal gallery

### Project management

- [Balsamiq](https://balsamiq.com/wireframes/) - Wireframe creation tool
- [GitHub](https://github.com/) - Version control and deployment
- [GitPod](https://gitpod.io/) - IDE used to code the site

### Style and theme

- [Autoprefixer](https://autoprefixer.github.io/) - Post CSS plugin which parses CSS and adds vendor prefixes
- [Bootstrap](https://getbootstrap.com/) - Responsive grid and boilerplate styling framework
- [Color Scheme Designer](https://colorschemedesigner.com/csd-3.5/) - Complimentary color scheme for the site
- [CSS Tricks](https://css-tricks.com/examples/hrs/) - Specifically for linear-gradiant horizontal rule
- [Font Awesome](https://fontawesome.com/) - Icon used for shopping cart in navbar
- [Free Formatter](https://www.freeformatter.com/html-formatter.html) - Formatting HTML code
- [Google Fonts](https://fonts.google.com/) - Open Sans and Monserrat fonts
- [Zyro Logo Maker](https://zyro.com/logo-maker) - Creating the favicon

### Visual effects

- [Fancybox](https://fancyapps.com/fancybox/3/) - Simple to use Javascript package for modal gallery
- [Hover.css](https://ianlunn.github.io/Hover/) - Effect applied to intro gallery circular previews

### Image manipulation

- [IrfanView](https://www.irfanview.com/) - Program for cropping image batches to the same aspect ratio
- [Tiny JPG](https://tinyjpg.com/) - Reducing the size of all images without noticeable loss of quality

### Online resources

- [How to Geek](https://www.howtogeek.com/354015/how-to-resize-images-and-photos-in-windows/) - specifically advice on how to efficiently handle a large number of images
- [Stack Overflow](https://stackoverflow.com/)
- [W3 Schools](https://www.w3schools.com/)

<span id="testing"></span>

## Testing

<span id="testing-auto"></span>

### Automated testing

- [Chrome DevTools](https://developers.google.com/web/tools/chrome-devtools) - ran an audit on all pages for both desktop and mobile. Summary:
  - Performance = **Average**
    - The worst metric due to issues around image size and not using next-gen filetypes, particularly on gallery.html where the score was 81% on desktop - it is beyond the scope of this project to address this
    - Unused CSS - removed hover.min.css from all but index.html where it is used on the intro gallery images
  - Accessibility = **Good**
    - Various links missing discernable names (mainly nav bar and footer) - fixed by adding aria labels to all links across the site
    - Insufficient contrast ratio on hero image and nav bar Brand
    - Lowest score 96% on desktop following amendments
  - Best Practices = **Good**
    - Front-end Javascript libraries with known security vulnerabilities (Bootstrap and jQuery) - it is beyond the scope of this project to address this
  - SEO = **Good**
    - `head` was missing `<meta name="description" content="..." />` - fixed
    - Scores 95% on Gallery due to 'Add' button being smaller than 48px x 48px. Tested with larger button sizes but they took up too much real estate - it is beyond the scope of this project to address this
    - Scores 100% across all other pages following amendments
- [W3C - HTML](https://validator.w3.org/) - `alt` tags were missing and call to action `button` with `type="button"` was identified as an issue. On update no HTML errors or warnings detected - **PASS**
- [W3C - CSS](https://jigsaw.w3.org/css-validator/) - no CSS errors detected - **PASS**
    - Update: passing CSS code through [Autoprefixer](https://autoprefixer.github.io/) produced 47 warnings related to unknown vendor extensions
- [Unicorn revealer - overflow](https://chrome.google.com/webstore/detail/unicorn-revealer/lmlkphhdlngaicolpmaakfmhplagoaln/related) - tested all pages and no evidence of overflow - **PASS**

<span id="testing-manual"></span>

### Manual testing

**Summary**:

Alongside the manual tests described below, eight individuals contributed to testing the site and provided feedback on its layout, responsiveness and styling at various points in development.

Of the manual tests conducted, the only ones to fail were those related to predetermined form validation settings. These test were initially carried out on a boilerplate Bootstrap form and subsequently using the `novalidate` JS method described in Bootstrap, but the results were the same.

The following scenarios were tested to ensure that the site is functioning as expected:

**1. Nav bar**

- From each page
  - check that nav bar links take you to the correct page - **PASS**
  - check that each Gallery dropdown link takes you to the correct section of the Gallery page - **PASS**
  - check that nav bar links (including Brand) have the correct styling (blue) when hovered over on desktop devices - **PASS**
  - check that the active / current nav bar link (excluding Brand) is correctly styled and distinguished from the others - **PASS**

**2. Footer**

- From each page
  - check that all social media links take you to the relevant external site, and open in a separate browser tab - **PASS**
  - check that all social media icons have the correct styling (dark yellow) when hovered over on desktop devices - **PASS**

**3. Landing page**

- Click the Purchase button to check it goes to the top of the Gallery page - **PASS**
- On desktop, hover over the Purchase button to check visual feedback is provided (white background, black text) - **PASS**

_Note: the unwanted styling applied by Safari (noted as Unresolved issue below)_

- Click each intro gallery circular image to check it takes you to the relevant anchor within the Gallery page - **PASS**
- On desktop, hover over each intro gallery circular image to check visual feedback is provided (hvr-grow effect) - **PASS**

**4. About page**

- Click the "Contact me" email link to check it creates a new email to the photographer - **PASS**
- Check the Subject of the new email message is correctly filled - **PASS**

_Note: initially a missing ">" was preventing the Subject field being filled but this was corrected_

**5. Pricing page**

- No functionality to test - **N/A**

**6. Gallery page**

- Click each of the 48 images to check it brings up a modal with the correct image enlarged - **PASS**

_Note: initially some file names were incorrect but were all amended_

- Check that the correct caption is displayed for each of the 48 images in the modal gallery - **PASS**
- Check that all 48 "Add" buttons (currently no functionality as shopping basket is beyond scope of project, see Features left to implement) have the correct styling (dark blue) when hovered over on desktop devices - **PASS**

**7. Signup**

- On desktop, hover over the Sign Up button to check visual feedback is provided (dark blue) - **PASS**
- On sign-up form

  - leave all fields blank and click Sign Up button to check validation displays an input issue - **PASS**
  - enter all fields correctly and click Sign Up button to check validation confirms correct inputs - **PASS**
  - enter all fields correctly apart from one (in turn) and check validation correctly identifies issues - **PASS**
  - enter an email address in an incorrect format to check validation displays an input issue. Results:

  |  Entry  | Test result | Comments                                                                |
  | :-----: | :---------: | :---------------------------------------------------------------------- |
  |   `@`   |  **PASS**   |
  |  `_@_`  |  **PASS**   |
  |  `a@b`  |  **FAIL**   | this would need to be corrected but is beyond the scope of this project |
  | `a_@_b` |  **PASS**   |
  | `a@_b`  |  **PASS**   |
  | `a_@b`  |  **PASS**   |

  - enter something different for Password and Confirm Password to check validation displays an input issue - **FAIL**
  - enter a space (" ") as either password to check validation displays an input issue - **FAIL**

<span id="testing-responsive"></span>

### Responsiveness

The site has been designed with a mobile-first philosophy and, supported by [Bootstrap](https://getbootstrap.com/), has been thoroughly tested at all stages of development using [Chrome DevTools](https://developers.google.com/web/tools/chrome-devtools).

The following issues arose and have each been addressed:

| Responsiveness issue                                                                                                                  | Solution                                                                                                                |
| :------------------------------------------------------------------------------------------------------------------------------------ | :---------------------------------------------------------------------------------------------------------------------- |
| Navbar Brand causes hamburger icon to spill                                                                                           | Reduced starting `font-size`, removed `margin-right`and added media query to increase above `min-width: 370px`          |
| Navbar dropdown not visible on landscape mobile devices                                                                               | Added media query to set `overflow-y: scroll`. See Issues and resolutions section below                                 |
| Footer social media icons appear cramped on larger displays                                                                           | Added media query to increase `margin: 0 1rem;`                                                                         |
| Landing page main heading ran to several lines on smaller displays                                                                    | Reduced starting `font-size` of callout header and paragraph and added media query to increase above `min-width: 768px` |
| Pricing tables appear too elongated on larger displays when filling two columns                                                       | Added two media queries to increase `padding` above above `min-width: 768px` and `min-width: 992px`                     |
| Image of photographer in About suffered from unwanted top margin (which was needed in single-column views) when sharing row with text | Added media query to remove `margin-top` of the container and change `max-height` and `max-width` of the image          |
| Gallery images on small displays appear too wide                                                                                      | See Issues and resolutions below                                                                                        |

#### Browsers

Tested on:

- Chrome
- Edge
- Firefox
- Safari (iOS)
  - Noted issue with styles being overwritten on call to action (Purchase button on landing page). See Unresolved issues section below

#### Screen sizes

Tested with Chrome DevTools using profiles for:

- Moto G4
- Galaxy S5
- Pixel 2
- Pixel 2 XL
- iPhone 5 SE
- iPhone 6/7/8
- iPhone 6/7/8 Plus
- iPhone X
- iPad
- iPad Pro

... and also using the responsive profiles of:

- Mobile S (320px)
- Mobile M (375px)
- Mobile L (425px)
- Tablet (768px)
- Laptop (1024px)
- Laptop L (1440px)

Real world testing on:

- iPhone 6
- iPhone 11 Pro
- Asus ZenBook


### Issues and resolutions

<span id="testing-resolved"></span>

#### Resolved

- **Hero image does not display on iOS mobile devices**

  - Resolved by adding a media query for smaller displays which sets `background-attachment: scroll`

- **Navbar does not collapse when clicking links within the same page**

  _When the Gallery or hamburger dropdowns are expanded in the navbar, anchor links within the same page will not collapse the navbar (most noticeable on the Gallery page)_

  - Resolved by customising a Javascript snippet from [Stack Overflow](https://stackoverflow.com/questions/42401606/how-to-hide-collapsible-bootstrap-4-navbar-on-click) to point to the relevant classes in the navbar

- **Navbar dropdown not visible on landscape mobile devices**

  _When expanding the Gallery nav-item in the navbar while in landscape mode on a mobile device, not all list items are visible and cannot be clicked_

  - Resolved by using a suggestion found on [Github](https://github.com/twbs/bootstrap/issues/23374) and adding a media query for smaller displays which sets `overflow-y: scroll` and `height: 115px` to ensure the list items are visible on all displays

- **Intro gallery circular images on right margin cause overflow when hvr-grow effect is appled**

  - Resolved by incrementally reducing the width of intro-gallery and finally settling on `width: 91%`

  - **Links on social media icons in footer apply to the entire containing div**

  - Resolved by switching to an `inline-flex` list and adding class `sm-list` to `a` elements. Subsequently recognised that playing with margins bypasses this issue when compared with padding, however overall the approach is now more flexible. Further issues arose relating to spacing of the icons so it was necessary to include media queries to increase the starting value of `margin: 0 1rem`

- **Links / hover effects on intro gallery circular images apply to the entire containing div**

  - Resolved using suggestion from [Stack Overflow](https://stackoverflow.com/questions/29978500/only-make-a-centered-image-a-link-instead-of-the-whole-parent-div) moving size styling from the image to the `<a>` element within a newly created container class `.intro-gallery-image` and then adding `display: flex`

- **There is white space beneath footer on pages with little content (Pricing and About)**

  - Resolved by using a suggestion from [Philip Walton](https://philipwalton.github.io/solved-by-flexbox/demos/sticky-footer/) to set body element `flex-direction: column` and `min-height: 100vh`. This was a more elegant solution than changing the structure of the site e.g. by adding the Pricing and About pages further down the Landing Page and relying on achor links, or by simply increasing the content on each of the affected pages

- **Gallery image buttons do not stay inside their respective images where images have different aspect ratios**

  _Due to having_ `position: abolute` _buttons were left floating outside of their images_

  - Initially resolved by fixing the height of images to `vh20` but this had the unintended side-effect of making them appear too wide on mobile devices

- **Gallery images on small displays appear too wide**

  - Resolved by giving the image `height: 200px` and adding a media query which changes this to `height: 100%` on smaller devices. This has the added benefit of displaying images in their original aspect ratio on mobile

- **Signup form validation messages display poorly on iOS**

  _Despite displaying correctly in Chrome devtools, the display on iOS leaves validation error messages appearing clipped and ugly_

  - Resolved by using Bootstrap's recommended `needs-validation` class and `novalidate`. A block styled with `invalid-feedback` was avoided to prevent error messages appearing and shifting the lines of input fields

<span id="testing-unresolved"></span>

#### Unresolved

- **iOS browser adds unwanted styling to Pricing button in hero image**

  - Attempts were made to override Apple's styling using `-webkit-` but were unsuccesful

- **Signup form password and confirmation password can be different**

  - This is a key issue which needs to be resolved but is outside the scope of this project

<span id="testing-bugs"></span>

### Known bugs

- None at present

<span id="deployment"></span>

## Deployment

There is just one branch of this project (master) and deployed version of this site is the most current version in the repository.

### How to deploy

To deploy this page to GitHub Pages from its [GitHub repository](https://github.com/Edb83/milestone1), the following steps were taken:

1. From the menu items near the top of the page, select **Settings**
2. Scroll down to the **GitHub Pages** section
3. Under **Source** click the drop-down menu labelled **None** and select **Master Branch**
4. On selecting Master Branch the page will be automatically refreshed and the website is now deployed
5. Scroll back down to the **GitHub Pages** section in **Settings** to retrieve the link to the deployed website. It may take a short time to go live, but typically less than 60 seconds

### How to run locally

To clone this project from GitHub:

1. Under the repository name, click "Clone or download"
2. In the Clone with HTTPs section, copy the clone URL for the repository
3. In your local IDE open Git Bash
4. Change the current working directory to the location where you want the cloned directory to be made
5. Type `git clone`, and then paste the URL you copied in Step 2

```console
git clone https://github.com/Edb83/penny-for-your-thoughts.git
```

6. Press Enter. Your local clone will be created

Further reading and troubleshooting on cloning a repository from GitHub can be found [here](https://help.github.com/en/articles/cloning-a-repository).

<span id="credits"></span>

## Credits

Carlos (Code Institute Slack Community Lead)

Jonathan Munz (Code Institute Mentor)

Richard Wells (Code Institute Lead)

Extremely useful feedback on appearance and user experience was provided by Lola, Tash, Mims, Beckx and Peter!

### Content

The text in the About page and photos used throughout this site were obtained from the client, Penny Holland. All other text was written by me and agreed with the client.

### Acknowledgements

I received inspiration for this project from Penny Holland

### Disclaimer

This site was developed for educational purposes but will likely be put to real world use once the remaining features have been implemented according to client's wishes.
