# 2-Breed-Website

## [Live Website Link!](https://rajakhan017.github.io/2-Breed-Website/)

## Structure of the web page

![image](https://github.com/rajakhan017/2-Breed-Website/assets/135150598/3f5f8f75-7a5b-4013-8501-62cb18839680)


---

## Table of Contents

- [Assignment](#assignment)
  - [Live Website Link!](#live-website-link)
  - [Structure of the web page](#structure-of-the-web-page)
  - [Table of Contents](#table-of-contents)
    - [In `style.css`](#in-stylecss)
      - [`@import`](#import)
      - [CSS Selector: `*`](#css-selector-)
    - [In `logo-fruits.css`](#in-logo-fruitscss)
      - [CSS Selector: `.main`](#css-selector-main)
      - [CSS Selector: `.container`](#css-selector-container)
      - [CSS Selector: `.logo`](#css-selector-logo)
      - [CSS Selector: `.container span`](#css-selector-container-span)
      - [CSS Selector: `.container-tomato` and `.container-kiwi`](#css-selector-container-tomato-and-container-kiwi)
      - [CSS Selector: `.top`](#css-selector-top)
      - [CSS Selector: `.top a`](#css-selector-top-a)
      - [Hover States for `.top .main-page` and `.top .about-us`](#hover-states-for-top-main-page-and-top-about-us)
      - [CSS Selector: `.container .container-text`](#css-selector-container-container-text)
      - [CSS Selector: `.container h2`](#css-selector-container-h2)
      - [CSS Selector: `.container-text .sub-heading`](#css-selector-container-text-sub-heading)
      - [CSS Selector: `.container-text-paragraph`](#css-selector-container-text-paragraph)
      - [CSS Selector: `.container-text-paragraph a`](#css-selector-container-text-paragraph-a)
      - [Hover State for `.container-tomato .container-text .read-more-button` and `.container-kiwi .container-text .read-more-button`](#hover-state-for-container-tomato-container-text-read-more-button-and-container-kiwi-container-text-read-more-button)
      - [CSS Selector: `.sub-heading-date`](#css-selector-sub-heading-date)
      - [CSS Selector: `.sub-heading-date .second-date`](#css-selector-sub-heading-date-second-date)
    - [In `right-column.css`](#in-right-columncss)
      - [CSS Selector: `.right-column`](#css-selector-right-column)
      - [CSS Selector: `.links`](#css-selector-links)
      - [CSS Selector: `.links ul li`](#css-selector-links-ul-li)
      - [CSS Selector: `.links ul li a`](#css-selector-links-ul-li-a)
      - [Hover State for `.links ul li a`](#hover-state-for-links-ul-li-a)
      - [CSS Selector: `.banner`](#css-selector-banner)
      - [CSS Selector: `.right-column h2`](#css-selector-right-column-h2)
      - [CSS Selector: `.more-links ul`](#css-selector-more-links-ul)
      - [CSS Selector: `.more-links ul li a`](#css-selector-more-links-ul-li-a)
      - [Hover State for `.more-links ul li a`](#hover-state-for-more-links-ul-li-a)
      - [CSS Selector: `.button-group`](#css-selector-button-group)
      - [CSS Selector: `.image-button`](#css-selector-image-button)
      - [CSS Selector: `.image-button.ideas`, `.image-button.sign-up`, and `.image-button.blog`](#css-selector-image-buttonideas-image-buttonsign-up-and-image-buttonblog)
      - [CSS Selector: `.newsletter`](#css-selector-newsletter)
      - [CSS Selector: `.form`](#css-selector-form)
      - [CSS Selector: `.form input`](#css-selector-form-input)
      - [CSS Selector: `.submit`](#css-selector-submit)
    - [In `features.css`](#in-featurescss)
      - [CSS Selector: `.features`](#css-selector-features)
      - [CSS Selector: `.features-box`](#css-selector-features-box)
      - [CSS Selector: `.features-desc`](#css-selector-features-desc)
      - [CSS Selector: `.features-desc h2`](#css-selector-features-desc-h2)
      - [CSS Selector: `.features-desc p`](#css-selector-features-desc-p)
      - [CSS Selector: `.features-desc span`](#css-selector-features-desc-span)
      - [CSS Selector: `.read-more-button.red`](#css-selector-read-more-buttonred)
      - [CSS Selector: `.login-form`](#css-selector-login-form)
      - [CSS Selector: `.login-form h2`](#css-selector-login-form-h2)
      - [CSS Selector: `.login-form-box`](#css-selector-login-form-box)
      - [CSS Selector: `.login-form-box h3`](#css-selector-login-form-box-h3)
      - [CSS Selector: `.login-form-box input`](#css-selector-login-form-box-input)
      - [CSS Selector: `.forgot-password`](#css-selector-forgot-password)
      - [CSS Selector: `.forgot-password a`](#css-selector-forgot-password-a)
      - [CSS Selector: `.forgot-password button`](#css-selector-forgot-password-button)
      - [CSS Selector: `.contact`](#css-selector-contact)
      - [CSS Selector: `.contact p`](#css-selector-contact-p)
    - [In `footer.css`](#in-footercss)
      - [CSS Selector: `.footer`](#css-selector-footer)
      - [CSS Selector: `.footer-box`](#css-selector-footer-box)
      - [CSS Selector: `.foot-nav ul`](#css-selector-foot-nav-ul)
      - [CSS Selector: `.foot-nav ul li`](#css-selector-foot-nav-ul-li)
      - [CSS Selector: `.foot-nav ul li a`](#css-selector-foot-nav-ul-li-a)
      - [CSS Selector: `.copyright`](#css-selector-copyright)
      - [CSS Selector: `.credits`](#css-selector-credits)
      - [CSS Selector: `.credits a`](#css-selector-credits-a)
      - [CSS Selector: `.validation-buttons`](#css-selector-validation-buttons)
      - [CSS Selector: `.validation-buttons button`](#css-selector-validation-buttons-button)

Click on the link to navigate between them.

### In `style.css`


---

#### CSS Selector: `*`

| Property    | Value                        | Explanation                                                                             |
| ----------- | ---------------------------- | --------------------------------------------------------------------------------------- |
| padding     | 0                            | Sets the padding of all elements to 0.                                                  |
| margin      | 0                            | Sets the margin of all elements to 0.                                                   |
| box-sizing  | border-box                   | Specifies that padding and border are included in the element's total width and height. |
| font-family | Arial, Helvetica, sans-serif | Defines the font family for all elements.                                               |

Explanation: The `*` selector targets all elements on the page, applying these CSS properties to all elements.
![image](https://github.com/rajakhan017/2-Breed-Website/assets/135150598/7b979ab1-79ca-4e5b-ad61-87d19f883a61)

### In `logo-fruits.css`

#### CSS Selector: `.main`

| Property   | Value                | Explanation                                               |
| ---------- | -------------------- | --------------------------------------------------------- |
| background | rgb(249, 247, 219)   | Sets the background color to a light beige color.         |
|            | linear-gradient(...) | Applies a linear gradient background to `.main` elements. |

Explanation: The `.main` class styles the main content area with a background gradient.

---
![image](https://github.com/rajakhan017/2-Breed-Website/assets/135150598/e6f35662-d3ca-443d-ae04-d82b61fd4c2a)

#### CSS Selector: `.container`

| Property | Value  | Explanation                                             |
| -------- | ------ | ------------------------------------------------------- |
| height   | 740px  | Sets the height of `.container` elements to 740 pixels. |
| width    | 928px  | Sets the width of `.container` elements to 928 pixels.  |
| margin   | 0 auto | Centers `.container` horizontally using auto margins.   |
| display  | flex   | Uses flexbox layout for `.container` elements.          |

Explanation: The `.container` class styles a container with specific dimensions and flexbox layout.
![image](https://github.com/rajakhan017/2-Breed-Website/assets/135150598/a1ff9025-111a-4c3a-93fb-8332bac12a95)

---

#### CSS Selector: `.logo`

| Property   | Value                                | Explanation                                      |
| ---------- | ------------------------------------ | ------------------------------------------------ |
| background | url(/images/globalpic.jpg) no-repeat | Sets a background image for `.logo` elements.    |
| width      | 75px                                 | Sets the width of `.logo` elements to 75 pixels. |
| height     | inherit                              | Inherits the height from the parent element.     |

Explanation: The `.logo` class styles elements with a background image.

---
![image](https://github.com/rajakhan017/2-Breed-Website/assets/135150598/aeb8873b-4fbb-491e-8c3e-f3595d0cb29c)

#### CSS Selector: `.container span`

| Property    | Value | Explanation                                           |
| ----------- | ----- | ----------------------------------------------------- |
| font-size   | 3rem  | Sets the font size of `span` elements to 3 rem units. |
| margin-left | 1rem  | Sets a left margin of 1 rem for `span` elements.      |

Explanation: The `.container span` selector styles text within `.container` elements.

---

#### CSS Selector: `.container-tomato` and `.container-kiwi`

| Property   | Value                                             | Explanation                                                                                            |
| ---------- | ------------------------------------------------- | ------------------------------------------------------------------------------------------------------ |
| background | #cd4007                                           | Sets a background color for `.container-tomato` elements.                                              |
|            | url(/images/globalpic.jpg) no-repeat -77px -494px | Sets a background image for `.container-tomato` elements with positioning.                             |
| width      | 216px                                             | Sets the width of `.container-tomato` and `.container-kiwi` elements to 216 pixels.                    |
| height     | 96%                                               | Sets the height of `.container-tomato` and `.container-kiwi` elements to 96% of their parent's height. |

Explanation: These selectors style specific containers with backgrounds and dimensions.

---
![image](https://github.com/rajakhan017/2-Breed-Website/assets/135150598/e1257f1a-ce78-46dc-bddc-d7febf00b5bf)

#### CSS Selector: `.top`

| Property   | Value    | Explanation                                                        |
| ---------- | -------- | ------------------------------------------------------------------ |
| height     | 110px    | Sets the height of `.top` elements to 110 pixels.                  |
| width      | 100%     | Sets the width of `.top` elements to 100% of their parent's width. |
| position   | relative | Sets a relative positioning context for `.top` elements.           |
| text-align | center   | Centers text within `.top` elements.                               |

Explanation: The `.top` class styles the top section of the page.

---

#### CSS Selector: `.top a`

| Property        | Value   | Explanation                                     |
| --------------- | ------- | ----------------------------------------------- |
| text-decoration | none    | Removes text decoration (underline) from links. |
| color           | #646464 | Sets the text color for links to a light gray.  |
| font-size       | 12px    | Sets the font size of links to 12 pixels.       |
| font-weight     | 700     | Sets the font weight of links to 700 (bold).    |
| padding-top     | 56px    | Adds padding to the top of links for spacing.   |

Explanation: The `.top a` selector styles links within the top section.

---
![image](https://github.com/rajakhan017/2-Breed-Website/assets/135150598/776bbf79-9128-4bb1-8ae5-37e32f14c06a)

#### Hover States for `.top .main-page` and `.top .about-us`

| Property                | Value             | Explanation                                                  |
| ----------------------- | ----------------- | ------------------------------------------------------------ |
| `.top .main-page:hover` | padding-top: 74px | Increases padding and changes the background image on hover. |
| `.top .about-us:hover`  | padding-top: 74px | Increases padding and changes the background image on hover. |

Explanation: These hover states define transitions and effects when hovering over specific elements.

---

#### CSS Selector: `.container .container-text`

| Property | Value        | Explanation                                                                  |
| -------- | ------------ | ---------------------------------------------------------------------------- |
| width    | 80%          | Sets the width of `.container-text` elements to 80% of their parent's width. |
| margin   | 200px auto 0 | Sets margins for `.container-text` elements.                                 |
| position | relative     | Sets a relative positioning context for `.container-text` elements.          |

Explanation: The `.container .container-text` selector styles a container with text content.

---

#### CSS Selector: `.container h2`

| Property    | Value    | Explanation                                             |
| ----------- | -------- | ------------------------------------------------------- |
| color       | #fff     | Sets the text color for `h2` elements to white.         |
| font-weight | 400      | Sets the font weight of `h2` elements to 400.           |
| font-size   | 1.625rem | Sets the font size of `h2` elements to 1.625 rem units. |

Explanation: The `.container h2` selector styles subheadings within the container.

---

#### CSS Selector: `.container-text .sub-heading`

| Property    | Value     | Explanation                                                        |
| ----------- | --------- | ------------------------------------------------------------------ |
| color       | #ffe996   | Sets the text color for `.sub-heading` elements to a light yellow. |
| font-size   | 0.75rem   | Sets the font size of `.sub-heading` elements to 0.75 rem units.   |
| font-weight | 700       | Sets the font weight of `.sub-heading` elements to 700 (bold).     |
| margin-top  | 0.5rem    | Sets a top margin of 0.5 rem for `.sub-heading` elements.          |
| line-height | 1.1875rem | Sets the line height of `.sub-heading` elements to 1.1875 rem.     |

Explanation: The `.container-text .sub-heading` selector styles subheadings within the text container.

---

#### CSS Selector: `.container-text-paragraph`

| Property    | Value     | Explanation                                                                     |
| ----------- | --------- | ------------------------------------------------------------------------------- |
| margin-top  | 20px      | Sets a top margin of 20 pixels for `.container-text-paragraph` elements.        |
| font-size   | 0.75rem   | Sets the font size of `.container-text-paragraph` elements to 0.75 rem units.   |
| color       | #f8d85e   | Sets the text color for `.container-text-paragraph` elements to a light yellow. |
| line-height | 1.1875rem | Sets the line height of `.container-text-paragraph` elements to 1.1875 rem.     |

Explanation: The `.container-text-paragraph` selector styles paragraphs within the text container.

---

#### CSS Selector: `.container-text-paragraph a`

| Property         | Value   | Explanation                                      |
| ---------------- | ------- | ------------------------------------------------ |
| text-decoration  | none    | Removes text decoration (underline) from links.  |
| background-color | #9f3105 | Sets the background color for links.             |
| color            | #f8d85e | Sets the text color for links to a light yellow. |

Explanation: The `.container-text-paragraph a` selector styles links within paragraphs.

---

#### Hover State for `.container-tomato .container-text .read-more-button` and `.container-kiwi .container-text .read-more-button`

| Property                                                    | Value          | Explanation                                                 |
| ----------------------------------------------------------- | -------------- | ----------------------------------------------------------- |
| `.container-tomato .container-text .read-more-button:hover` | color: #cd4007 | Changes the text color on hover for the "Read More" button. |
| `.container-kiwi .container-text .read-more-button:hover`   | color: #9fb31a | Changes the text color on hover for the "Read More" button. |

Explanation: These hover states define transitions and effects when hovering over the "Read More" button in specific containers.

---

#### CSS Selector: `.sub-heading-date`

| Property | Value                     | Explanation                                            |
| -------- | ------------------------- | ------------------------------------------------------ |
| h3       | color: #fff               | Sets the text color for `h3` elements to white.        |
|          | font-size: 0.75rem        | Sets the font size of `h3` elements to 0.75 rem units. |
|          | margin: 0.9rem 0 0.5rem   | Sets margins for `h3` elements.                        |
| p        | font-size: 0.75rem        | Sets the font size of `p` elements to 0.75 rem units.  |
|          | color: #f2ff9a            | Sets the text color for `p` elements to a light green. |
| a        | color: #f2ff9a            | Sets the text color for links to a light green.        |
|          | text-decoration: none     | Removes text decoration (underline) from links.        |
|          | background-color: #75850e | Sets the background color for links.                   |

Explanation: The `.sub-heading-date` selector styles headings, paragraphs, and links within date-related content.

---

#### CSS Selector: `.sub-heading-date .second-date`

| Property   | Value | Explanation                                             |
| ---------- | ----- | ------------------------------------------------------- |
| margin-top | 3rem  | Sets a top margin of 3 rem for `.second-date` elements. |

Explanation: The `.sub-heading-date .second-date` selector styles a specific date-related element.

### In `right-column.css`

#### CSS Selector: `.right-column`

| Property       | Value  | Explanation                                                   |
| -------------- | ------ | ------------------------------------------------------------- |
| width          | 420px  | Sets the width of `.right-column` elements to 420 pixels.     |
| display        | flex   | Uses flexbox layout for `.right-column` elements.             |
| flex-direction | column | Arranges flex items in a column layout.                       |
| margin-left    | 34px   | Sets a left margin of 34 pixels for `.right-column` elements. |

Explanation: The `.right-column` class styles a right column container with specific dimensions and a column layout.

---

#### CSS Selector: `.links`

| Property        | Value         | Explanation                                                      |
| --------------- | ------------- | ---------------------------------------------------------------- |
| margin-top      | 22px          | Sets a top margin of 22 pixels for `.links` elements.            |
| display         | flex          | Uses flexbox layout for `.links` elements.                       |
| justify-content | space-between | Distributes space evenly between flex items along the main axis. |

Explanation: The `.links` class styles a container for links with a margin and space between links.

---

#### CSS Selector: `.links ul li`

| Property   | Value | Explanation                                              |
| ---------- | ----- | -------------------------------------------------------- |
| list-style | none  | Removes the default list-style (bullets) for list items. |

Explanation: The `.links ul li` selector removes list-style from list items within `.links`.

---

#### CSS Selector: `.links ul li a`

| Property        | Value                                      | Explanation                                                    |
| --------------- | ------------------------------------------ | -------------------------------------------------------------- |
| display         | inline-block                               | Makes links behave as inline-block elements.                   |
| padding-left    | 15px                                       | Adds left padding to links for spacing.                        |
| font-size       | 0.75rem                                    | Sets the font size of links to 0.75 rem units.                 |
| color           | #636038                                    | Sets the text color for links to a muted green.                |
| line-height     | 22px                                       | Sets the line height of links to 22 pixels.                    |
| height          | 24px                                       | Sets the height of links to 24 pixels.                         |
| width           | 176px                                      | Sets the width of links to 176 pixels.                         |
| font-weight     | 700                                        | Sets the font weight of links to 700 (bold).                   |
| text-decoration | none                                       | Removes text decoration (underline) from links.                |
| border-bottom   | #b1ae7e dotted 1px                         | Adds a dotted border bottom to links with a muted green color. |
| background      | url(/images/liststyle.jpg) no-repeat 0 7px | Sets a background image for links with positioning.            |

Explanation: The `.links ul li a` selector styles links within list items.

---

#### Hover State for `.links ul li a`

| Property               | Value          | Explanation                                       |
| ---------------------- | -------------- | ------------------------------------------------- |
| `.links ul li a:hover` | color: #75850e | Changes the text color on hover to a light green. |

Explanation: This hover state defines a transition effect for links within list items.

---

#### CSS Selector: `.banner`

| Property   | Value                                              | Explanation                                                      |
| ---------- | -------------------------------------------------- | ---------------------------------------------------------------- |
| width      | 171px                                              | Sets the width of `.banner` elements to 171 pixels.              |
| height     | 195px                                              | Sets the height of `.banner` elements to 195 pixels.             |
| background | url(/images/globalpic.jpg) no-repeat -337px -110px | Sets a background image for `.banner` elements with positioning. |

Explanation: The `.banner` class styles a banner element with a specific background image and dimensions.

---

#### CSS Selector: `.right-column h2`

| Property     | Value                                              | Explanation                                                              |
| ------------ | -------------------------------------------------- | ------------------------------------------------------------------------ |
| margin-top   | 29px                                               | Sets a top margin of 29 pixels for `h2` elements within `.right-column`. |
| padding-left | 57px                                               | Adds left padding to `h2` elements for spacing.                          |
| font-size    | 34px                                               | Sets the font size of `h2` elements to 34 pixels.                        |
| color        | #cb3e07                                            | Sets the text color for `h2` elements to a specific shade of orange.     |
| line-height  | 40px                                               | Sets the line height of `h2` elements to 40 pixels.                      |
| font-weight  | 400                                                | Sets the font weight of `h2` elements to 400.                            |
| background   | url(/images/globalpic.jpg) no-repeat -467px -308px | Sets a background image for `h2` elements with positioning.              |

Explanation: The `.right-column h2` selector styles headings within the right column.

---

#### CSS Selector: `.more-links ul`

| Property   | Value | Explanation                                                            |
| ---------- | ----- | ---------------------------------------------------------------------- |
| margin-top | 12px  | Sets a top margin of 12 pixels for `ul` elements within `.more-links`. |
| list-style | none  | Removes the default list-style (bullets) for list items.               |

Explanation: The `.more-links ul` selector removes list-style from lists within `.more-links`.

---

#### CSS Selector: `.more-links ul li a`

| Property        | Value                                            | Explanation                                         |
| --------------- | ------------------------------------------------ | --------------------------------------------------- |
| width           | 400px                                            | Sets the width of links to 400 pixels.              |
| height          | 27px                                             | Sets the height of links to 27 pixels.              |
| margin-top      | 3px                                              | Sets a top margin of 3 pixels for links.            |
| padding-left    | 27px                                             | Adds left padding to links for spacing.             |
| font-size       | 0.75rem                                          | Sets the font size of links to 0.75 rem units.      |
| float           | left                                             | Floats links to the left within list items.         |
| color           | #3b3a2b                                          | Sets the text color for links to a muted brown.     |
| line-height     | 25px                                             | Sets the line height of links to 25 pixels.         |
| text-decoration | none                                             | Removes text decoration (underline) from links.     |
| background      | url(/images/globalpic.jpg) no-repeat -75px -83px | Sets a background image for links with positioning. |

Explanation: The `.more-links ul li a` selector styles links within list items.

---

#### Hover State for `.more-links ul li a`

| Property                    | Value          | Explanation                                       |
| --------------------------- | -------------- | ------------------------------------------------- |
| `.more-links ul li a:hover` | color: #9fb31a | Changes the text color on hover to a light green. |

Explanation: This hover state defines a transition effect for links within list items.

---

#### CSS Selector: `.button-group`

| Property        | Value         | Explanation                                                      |
| --------------- | ------------- | ---------------------------------------------------------------- |
| display         | flex          | Uses flexbox layout for `.button-group` elements.                |
| justify-content | space-between | Distributes space evenly between flex items along the main axis. |
| margin-top      | 25px          | Sets a top margin of 25 pixels for `.button-group` elements.     |
| width           | 400px         | Sets the width of `.button-group` elements to 400 pixels.        |

Explanation: The `.button-group` class styles a container for buttons with flexbox layout and spacing.

---

#### CSS Selector: `.image-button`

| Property    | Value         | Explanation                                                       |
| ----------- | ------------- | ----------------------------------------------------------------- |
| width       | 127px         | Sets the width of `.image-button` elements to 127 pixels.         |
| height      | 101px         | Sets the height of `.image-button` elements to 101 pixels.        |
| margin      | 0px           | Removes margin for `.image-button` elements.                      |
| padding     | 15px 0 0 25px | Adds padding to `.image-button` elements.                         |
| font-size   | 10px          | Sets the font size of `.image-button` elements to 10 pixels.      |
| color       | #a8a8a8       | Sets the text color for `.image-button` elements to a light gray. |
| line-height | 14px          | Sets the line height of `.image-button` elements to 14 pixels.    |
| border      | none          | Removes the border from `.image-button` elements.                 |
| cursor      | pointer       | Sets a pointer cursor for `.image-button` elements.               |

Explanation: The `.image-button` class styles buttons with specific dimensions and design.

---

#### CSS Selector: `.image-button.ideas`, `.image-button.sign-up`, and `.image-button.blog`

| Property                | Value                                                           | Explanation                                                           |
| ----------------------- | --------------------------------------------------------------- | --------------------------------------------------------------------- |
| `.image-button.ideas`   | background: url(/images/globalpic.jpg) no-repeat -77px -392px;  | Sets a background image for `.image-button.ideas` with positioning.   |
| `.image-button.sign-up` | background: url(/images/globalpic.jpg) no-repeat -204px -392px; | Sets a background image for `.image-button.sign-up` with positioning. |
| `.image-button.blog`    | background: url(/images/globalpic.jpg) no-repeat -331px -392px; | Sets a background image for `.image-button.blog` with positioning.    |

Explanation: These selectors style specific buttons with different background images based on their class.

---

#### CSS Selector: `.newsletter`

| Property   | Value                                        | Explanation                                                          |
| ---------- | -------------------------------------------- | -------------------------------------------------------------------- |
| width      | 398px                                        | Sets the width of `.newsletter` elements to 398 pixels.              |
| height     | 81px                                         | Sets the height of `.newsletter` elements to 81 pixels.              |
| margin     | 25px 0 0 0                                   | Sets margins for `.newsletter` elements.                             |
| padding    | 10px 0 0 114px                               | Adds padding to `.newsletter` elements.                              |
| float      | left                                         | Floats `.newsletter` elements to the left.                           |
| background | url(/images/globalpic.jpg) no-repeat -75px 0 | Sets a background image for `.newsletter` elements with positioning. |

Explanation: The `.newsletter` class styles a newsletter container with specific dimensions and a background image.

---

#### CSS Selector: `.form`

| Property   | Value | Explanation                                                |
| ---------- | ----- | ---------------------------------------------------------- |
| margin-top | 5px   | Sets a top margin of 5 pixels for elements within `.form`. |

Explanation: The `.form` class styles a form element within the newsletter container.

---

#### CSS Selector: `.form input`

| Property    | Value | Explanation                                          |
| ----------- | ----- | ---------------------------------------------------- |
| font-size   | 12px  | Sets the font size of input elements to 12 pixels.   |
| line-height | 14px  | Sets the line height of input elements to 14 pixels. |
| padding     | 3px   | Adds padding to input elements.                      |
| width       | 206px | Sets the width of input elements to 206 pixels.      |

Explanation: The `.form input` selector styles input elements within the form.

---

#### CSS Selector: `.submit`

| Property         | Value   | Explanation                                              |
| ---------------- | ------- | -------------------------------------------------------- |
| width            | 41px    | Sets the width of `.submit` elements to 41 pixels.       |
| height           | 23px    | Sets the height of `.submit` elements to 23 pixels.      |
| background-color | #cd4008 | Sets the background color of `.submit` elements.         |
| color            | #fff    | Sets the text color of `.submit` elements to white.      |
| border           | none    | Removes the border from `.submit` elements.              |
| border-radius    | 4px     | Adds a border-radius of 4 pixels to `.submit` elements.  |
| font-size        | 11px    | Sets the font size of `.submit` elements to 11 pixels.   |
| line-height      | 20px    | Sets the line height of `.submit` elements to 20 pixels. |
| cursor           | pointer | Sets a pointer cursor for `.submit` elements.            |

Explanation: The `.submit` class styles a submit button.

### In `features.css`

#### CSS Selector: `.features`

| Property   | Value                                                                                                     | Explanation                                                 |
| ---------- | --------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------- |
| height     | 240px                                                                                                     | Sets the height of `.features` elements to 240 pixels.      |
| background | rgb(233, 230, 195)                                                                                        | Sets the background color for `.features` elements.         |
|            | linear-gradient(0deg, rgba(233, 230, 195, 1) 0%, rgba(232, 227, 193, 1) 95%, rgba(232, 227, 193, 1) 100%) | Sets a linear gradient background for `.features` elements. |

Explanation: The `.features` class styles a section with specific height and background gradient.

---

#### CSS Selector: `.features-box`

| Property | Value  | Explanation                                                   |
| -------- | ------ | ------------------------------------------------------------- |
| margin   | 0 auto | Centers `.features-box` horizontally in its parent container. |
| width    | 928px  | Sets the width of `.features-box` elements to 928 pixels.     |
| display  | flex   | Uses flexbox layout for `.features-box` elements.             |

Explanation: The `.features-box` class styles a container with a specific width and uses flexbox layout.

---

#### CSS Selector: `.features-desc`

| Property     | Value         | Explanation                                                     |
| ------------ | ------------- | --------------------------------------------------------------- |
| width        | 473px         | Sets the width of `.features-desc` elements to 473 pixels.      |
| padding      | 24px 31px 0 0 | Sets padding for `.features-desc` elements.                     |
| position     | relative      | Sets the positioning context for child elements.                |
| margin-right | 31px          | Sets a right margin of 31 pixels for `.features-desc` elements. |

Explanation: The `.features-desc` class styles a description box within the features section.

---

#### CSS Selector: `.features-desc h2`

| Property     | Value                                              | Explanation                                                             |
| ------------ | -------------------------------------------------- | ----------------------------------------------------------------------- |
| padding-left | 50px                                               | Adds left padding to `h2` elements within `.features-desc` for spacing. |
| font-size    | 34px                                               | Sets the font size of `h2` elements to 34 pixels.                       |
| color        | #1d1d1d                                            | Sets the text color for `h2` elements to a dark gray.                   |
| line-height  | 38px                                               | Sets the line height of `h2` elements to 38 pixels.                     |
| font-weight  | 400                                                | Sets the font weight of `h2` elements to 400.                           |
| background   | url(/images/globalpic.jpg) no-repeat -474px -357px | Sets a background image for `h2` elements with positioning.             |

Explanation: The `.features-desc h2` selector styles headings within the features description.

---

#### CSS Selector: `.features-desc p`

| Property    | Value   | Explanation                                                             |
| ----------- | ------- | ----------------------------------------------------------------------- |
| margin-top  | 9px     | Sets a top margin of 9 pixels for `p` elements within `.features-desc`. |
| font-size   | 12px    | Sets the font size of `p` elements to 12 pixels.                        |
| color       | #575433 | Sets the text color for `p` elements to a muted greenish color.         |
| line-height | 19px    | Sets the line height of `p` elements to 19 pixels.                      |

Explanation: The `.features-desc p` selector styles paragraphs within the features description.

---

#### CSS Selector: `.features-desc span`

| Property    | Value   | Explanation                                               |
| ----------- | ------- | --------------------------------------------------------- |
| color       | #8da00d | Sets the text color for `span` elements to a light green. |
| font-weight | 700     | Sets the font weight of `span` elements to 700 (bold).    |

Explanation: The `.features-desc span` selector styles specific spans within the features description.

---

#### CSS Selector: `.read-more-button.red`

| Property         | Value   | Explanation                                                     |
| ---------------- | ------- | --------------------------------------------------------------- |
| background-color | #cd4008 | Sets the background color for `.read-more-button.red` elements. |

Explanation: The `.read-more-button.red` class styles a "Read More" button with a red background.

---

#### CSS Selector: `.login-form`

| Property   | Value             | Explanation                                                           |
| ---------- | ----------------- | --------------------------------------------------------------------- |
| height     | 184px             | Sets the height of `.login-form` elements to 184 pixels.              |
| width      | 202px             | Sets the width of `.login-form` elements to 202 pixels.               |
| margin     | 19px 22px 0 0     | Sets margins for `.login-form` elements.                              |
| border     | #d7d3aa solid 1px | Sets a solid border for `.login-form` elements with a specific color. |
| background | #f1eed0           | Sets the background color for `.login-form` elements.                 |

Explanation: The `.login-form` class styles a login form with specific dimensions and styling.

---

#### CSS Selector: `.login-form h2`

| Property     | Value                                                      | Explanation                                                   |
| ------------ | ---------------------------------------------------------- | ------------------------------------------------------------- |
| width        | 100%                                                       | Sets the width of `h2` elements within `.login-form` to 100%. |
| height       | 34px                                                       | Sets the height of `h2` elements to 34 pixels.                |
| padding-left | 33px                                                       | Adds left padding to `h2` elements for spacing.               |
| font-size    | 18px                                                       | Sets the font size of `h2` elements to 18 pixels.             |
| color        | #212121                                                    | Sets the text color for `h2` elements to a dark gray.         |
| line-height  | 30px                                                       | Sets the line height of `h2` elements to 30 pixels.           |
| font-weight  | 400                                                        | Sets the font weight of `h2` elements to 400.                 |
| background   | #ffffff url(/images/globalpic.jpg) no-repeat -483px -399px | Sets a background image for `h2` elements with positioning.   |

Explanation: The `.login-form h2` selector styles headings within the login form.

---

#### CSS Selector: `.login-form-box`

| Property       | Value  | Explanation                                                     |
| -------------- | ------ | --------------------------------------------------------------- |
| display        | flex   | Uses flexbox layout for `.login-form-box` elements.             |
| flex-direction | column | Sets the flex direction to column for child elements.           |
| width          | 168px  | Sets the width of `.login-form-box` elements to 168 pixels.     |
| margin         | 0 auto | Centers `.login-form-box` horizontally in its parent container. |

Explanation: The `.login-form-box` class styles a container for the login form with specific dimensions and flex layout.

---

#### CSS Selector: `.login-form-box h3`

| Property    | Value   | Explanation                                                               |
| ----------- | ------- | ------------------------------------------------------------------------- |
| margin-top  | 8px     | Sets a top margin of 8 pixels for `h3` elements within `.login-form-box`. |
| font-size   | 10px    | Sets the font size of `h3` elements to 10 pixels.                         |
| color       | #1d1d1d | Sets the text color for `h3` elements to a dark gray.                     |
| line-height | 14px    | Sets the line height of `h3` elements to 14 pixels.                       |
| font-weight | 400     | Sets the font weight of `h3` elements to 400.                             |

Explanation: The `.login-form-box h3` selector styles subheadings within the login form box.

---

#### CSS Selector: `.login-form-box input`

| Property     | Value   | Explanation                                                                  |
| ------------ | ------- | ---------------------------------------------------------------------------- |
| height       | 24px    | Sets the height of `input` elements to 24 pixels.                            |
| margin-top   | 3px     | Sets a top margin of 3 pixels for `input` elements within `.login-form-box`. |
| padding-left | 3px     | Adds left padding to `input` elements for spacing.                           |
| font-size    | 10px    | Sets the font size of `input` elements to 10 pixels.                         |
| color        | #212121 | Sets the text color for `input` elements to a dark gray.                     |
| line-height  | 14px    | Sets the line height of `input` elements to 14 pixels.                       |

Explanation: The `.login-form-box input` selector styles input elements within the login form box.

---

#### CSS Selector: `.forgot-password`

| Property        | Value         | Explanation                                                      |
| --------------- | ------------- | ---------------------------------------------------------------- |
| margin-top      | 9px           | Sets a top margin of 9 pixels for `.forgot-password` elements.   |
| display         | flex          | Uses flexbox layout for `.forgot-password` elements.             |
| justify-content | space-between | Distributes space evenly between flex items along the main axis. |

Explanation: The `.forgot-password` class styles a section with flex layout and spacing.

---

#### CSS Selector: `.forgot-password a`

| Property        | Value   | Explanation                                                                |
| --------------- | ------- | -------------------------------------------------------------------------- |
| font-size       | 12px    | Sets the font size of `a` elements within `.forgot-password` to 12 pixels. |
| color           | #9fb31a | Sets the text color for `a` elements to a greenish color.                  |
| font-weight     | 700     | Sets the font weight of `a` elements to 700 (bold).                        |
| line-height     | 16px    | Sets the line height of `a` elements to 16 pixels.                         |
| text-decoration | none    | Removes underlines from `a` elements.                                      |
| cursor          | pointer | Sets a pointer cursor for `a` elements.                                    |

Explanation: The `.forgot-password a` selector styles links within the "Forgot Password" section.

---

#### CSS Selector: `.forgot-password button`

| Property         | Value   | Explanation                                                             |
| ---------------- | ------- | ----------------------------------------------------------------------- |
| border           | none    | Removes the border from `.forgot-password button` elements.             |
| border-radius    | 4px     | Adds a border-radius of 4 pixels to `.forgot-password button` elements. |
| background-color | #cd4008 | Sets the background color for `.forgot-password button` elements.       |
| color            | #fff    | Sets the text color for `.forgot-password button` elements to white.    |
| cursor           | pointer | Sets a pointer cursor for `.forgot-password button` elements.           |
| padding          | 4px     | Adds padding to `.forgot-password button` elements.                     |
| font-size        | 12px    | Sets the font size of `.forgot-password button` elements to 12 pixels.  |

Explanation: The `.forgot-password button` class styles a button within the "Forgot Password" section.

---

#### CSS Selector: `.contact`

| Property   | Value                                             | Explanation                                                       |
| ---------- | ------------------------------------------------- | ----------------------------------------------------------------- |
| width      | 175px                                             | Sets the width of `.contact` elements to 175 pixels.              |
| height     | 107px                                             | Sets the height of `.contact` elements to 107 pixels.             |
| margin-top | 21px                                              | Sets a top margin of 21 pixels for `.contact` elements.           |
| background | url(/images/globalpic.jpg) no-repeat -75px -111px | Sets a background image for `.contact` elements with positioning. |

Explanation: The `.contact` class styles a contact section with specific dimensions and a background image.

---

#### CSS Selector: `.contact p`

| Property     | Value          | Explanation                                              |
| ------------ | -------------- | -------------------------------------------------------- |
| font-family  | 'Arial Narrow' | Sets the font family for `p` elements within `.contact`. |
| font-size    | 26px           | Sets the font size of `p` elements to 26 pixels.         |
| color        | #252525        | Sets the text color for `p` elements to a dark gray.     |
| line-height  | 30px           | Sets the line height of `p` elements to 30 pixels.       |
| padding-left | 28px           | Adds left padding to `p` elements for spacing.           |

Explanation: The `.contact p` selector styles paragraphs within the contact section.

### In `footer.css`

#### CSS Selector: `.footer`

| Property   | Value                                                                   | Explanation                                               |
| ---------- | ----------------------------------------------------------------------- | --------------------------------------------------------- |
| background | rgb(65, 65, 65)                                                         | Sets the background color for `.footer` elements.         |
|            | linear-gradient(0deg, rgba(65, 65, 65, 1) 0%, rgba(36, 36, 36, 1) 100%) | Sets a linear gradient background for `.footer` elements. |
| height     | 140px                                                                   | Sets the height of `.footer` elements to 140 pixels.      |

Explanation: The `.footer` class styles a footer section with a gradient background and specific height.

---

#### CSS Selector: `.footer-box`

| Property       | Value  | Explanation                                                 |
| -------------- | ------ | ----------------------------------------------------------- |
| width          | 928px  | Sets the width of `.footer-box` elements to 928 pixels.     |
| margin         | 0 auto | Centers `.footer-box` horizontally in its parent container. |
| display        | flex   | Uses flexbox layout for `.footer-box` elements.             |
| flex-direction | column | Sets the flex direction to column for child elements.       |
| align-items    | center | Aligns child elements vertically at the center.             |

Explanation: The `.footer-box` class styles a container for the footer content with specific dimensions and flex layout.

---

#### CSS Selector: `.foot-nav ul`

| Property    | Value | Explanation                                                        |
| ----------- | ----- | ------------------------------------------------------------------ |
| padding-top | 25px  | Adds top padding of 25 pixels to `ul` elements within `.foot-nav`. |
| display     | flex  | Uses flexbox layout for `ul` elements within `.foot-nav`.          |
| list-style  | none  | Removes the default list bullet points for `ul` elements.          |

Explanation: The `.foot-nav ul` selector styles an unordered list within the footer.

---

#### CSS Selector: `.foot-nav ul li`

| Property | Value   | Explanation                                                  |
| -------- | ------- | ------------------------------------------------------------ |
| color    | #d5d5d5 | Sets the text color for `li` elements within `.foot-nav ul`. |

Explanation: The `.foot-nav ul li` selector styles list items within the footer navigation.

---

#### CSS Selector: `.foot-nav ul li a`

| Property        | Value   | Explanation                                                               |
| --------------- | ------- | ------------------------------------------------------------------------- |
| font-size       | 11px    | Sets the font size of `a` elements within `.foot-nav ul li` to 11 pixels. |
| color           | #d5d5d5 | Sets the text color for `a` elements to a light gray.                     |
| line-height     | 15px    | Sets the line height of `a` elements to 15 pixels.                        |
| text-decoration | none    | Removes underlines from `a` elements.                                     |
| cursor          | pointer | Sets a pointer cursor for `a` elements.                                   |

Explanation: The `.foot-nav ul li a` selector styles links within the footer navigation.

---

#### CSS Selector: `.copyright`

| Property    | Value   | Explanation                                                        |
| ----------- | ------- | ------------------------------------------------------------------ |
| margin-top  | 3px     | Sets a top margin of 3 pixels for `.copyright` elements.           |
| font-size   | 10px    | Sets the font size of `.copyright` elements to 10 pixels.          |
| color       | #9fb31a | Sets the text color for `.copyright` elements to a greenish color. |
| line-height | 14px    | Sets the line height of `.copyright` elements to 14 pixels.        |

Explanation: The `.copyright` class styles a copyright notice in the footer.

---

#### CSS Selector: `.credits`

| Property    | Value   | Explanation                                                   |
| ----------- | ------- | ------------------------------------------------------------- |
| margin-top  | 7px     | Sets a top margin of 7 pixels for `.credits` elements.        |
| font-size   | 12px    | Sets the font size of `.credits` elements to 12 pixels.       |
| color       | #e9e6c3 | Sets the text color for `.credits` elements to a light beige. |
| line-height | 16px    | Sets the line height of `.credits` elements to 16 pixels.     |
| font-weight | 700     | Sets the font weight of `.credits` elements to 700 (bold).    |

Explanation: The `.credits` class styles a section for giving credits in the footer.

---

#### CSS Selector: `.credits a`

| Property        | Value   | Explanation                                                      |
| --------------- | ------- | ---------------------------------------------------------------- |
| color           | #fff    | Sets the text color for `a` elements within `.credits` to white. |
| background      | #252525 | Sets the background color for `a` elements within `.credits`.    |
| text-decoration | none    | Removes underlines from `a` elements.                            |

Explanation: The `.credits a` selector styles links within the credits section.

---

#### CSS Selector: `.validation-buttons`

| Property   | Value | Explanation                                                        |
| ---------- | ----- | ------------------------------------------------------------------ |
| margin-top | 11px  | Sets a top margin of 11 pixels for `.validation-buttons` elements. |

Explanation: The `.validation-buttons` class styles a section for validation buttons in the footer.

---

#### CSS Selector: `.validation-buttons button`

| Property         | Value   | Explanation                                                                        |
| ---------------- | ------- | ---------------------------------------------------------------------------------- |
| font-size        | 10px    | Sets the font size of `button` elements within `.validation-buttons` to 10 pixels. |
| color            | #ffffff | Sets the text color for `button` elements to white.                                |
| padding          | 8px 6px | Sets padding for `button` elements.                                                |
| text-align       | center  | Centers text horizontally within `button` elements.                                |
| background-color | #cd4008 | Sets the background color for `button` elements to red.                            |
| border           | none    | Removes the border from `button` elements.                                         |
| border-radius    | 4px     | Adds a border-radius of 4 pixels to `button` elements.                             |
| margin-right     | 4px     | Sets a right margin of 4 pixels for `button` elements.                             |
| cursor           | pointer | Sets a pointer cursor for `button` elements.                                       |

Explanation: The `.validation-buttons button` selector styles buttons within the validation buttons section in the footer.
