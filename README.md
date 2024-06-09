# Waterford Chess Club

[Link to a live site](https://petrokuida.github.io/waterford-chess-club/)

![Responsive view of Waterford Chess Club website](https://github.com/PatrycjaBlaszkowska/project-WizardsTower/blob/main/docs/images/introduction-image.PNG)

## Introduction

Waterford Chess Club is a local community website designed to unite chess enthusiasts in the Waterford area. The primary purpose of this platform is to organize events, recruit new members, and provide information on club activities. Waterford Chess Club aims to promote the game of chess, foster a sense of community, and offer members opportunities to enhance their skills through regular meetups, tournaments, and online resources. Whether you are a seasoned player or a beginner, Waterford Chess Club offers a welcoming environment for all skill levels.

### Features present across the project 

### Navigation bar :

- Navabar is present on every page, fully responsive across all resolutions.
- Navbar toggles to a hamburger menu on mobile devices. 
- The user can navigate across the site freely.

**Desktop** : 

![Desktop navbar]()

**Mobile** :

![Mobile navbar]()

### Footer :

- Footer is present on every page, for the user who wishes to navigate to the pages from the bottom, rather than having to scroll up.
- Footer contains social media links that are opening in a new tab.

![Footer]()

### Hero images :

- Included to draw the user's attention and show the purpose of the website stright away.

**Desktop** :

![Hero image desktop]()

**Mobile** :

![Hero image mobile]()

### Introduction section :

- The introduction section shows the purpose of the business right away, so the user can determine if this website is useful for him within the first few minutes.

![Home page - introduction]()

### Contact form :

- Allows users to contact businesses with any inquiries.
- The user is also able to book activities or a table via a contact form.
- The user is able to provide feedback to the business. 

![Contact form](https://github.com/PatrycjaBlaszkowska/project-WizardsTower/blob/main/docs/testing/contact-form.PNG)

## Testing

### User stories :

[User stories testing](https://github.com/PatrycjaBlaszkowska/project-WizardsTower/blob/main/docs/testing/testing.md)

### Manual testing

- Navigation bar :
    - Navigation bar is fully responsive on large/medium/small resolutions.
    - Navigation bar toggles to a hamburger menu on mobile devices and stays fully responsive.
    - All links to pages are working properly.
    - Hover CSS is correctly working. (Available on desktop only)

- Footer :
    - Footer is fully responsive on large/medium/small resolutions.
    - Social media links are working and opening in a new tab.
    - Links to pages are working properly.
    - Hover CSS is correctly working. (Available on desktop only).

- Hero image :
    - Image is succesfully changing for a different on on devices smaller than 922px.

- Contact form links :
    - Links located in the introduction section on a main page and in the new cocktails section are both working properly.

- Background images :
    - Menu and contact form background photos are linked correctly.
    - Images are successfully scaling on mobile devices. 

- Contact form :
    - The form is working as intended.
    - The form is successfully redirecting the user to the "thank you" page.
    - Submit button is working correctly. 
    - The form is looking good on smaller devices.

#### Devices used during testing:

- Desktop Computer
- Iphone 13
- Lenovo Tab M10 Plus

### Chrome Dev Tools

Chrome dev tools was used throughout the development of the project to test responsiveness. 
Responsiveness was tested using Dev Tools to emulate the following devices :

- Iphone SE
- Iphone XR
- Iphone 12 Pro
- Iphone 14 Pro Max
- Pixel 7
- Samsung Galaxy S8+
- Samsung Galaxy S20 Ultra
- iPad Mini
- iPad Air
- iPad Pro
- Surface Pro 7
- Surface Duo
- Galaxy Fold
- Samsung Galaxy A51/71
- Nest Hub
- Nest Hub Max

### Browser Testing

During development, webpage was mainly tested on Google Chrome. 
However, during testing process below browsers have been used :

- Google Chrome
- Microsoft Edge
- Mozilla Firefox
- Opera
- Safari

### Validation

[HTML validator](https://validator.w3.org/)

- 0 errors
- 0 warnings
- 18 info messages which are cased by CodeAnywhere's built-in code beautifier. CodeAnywhere is adding closing tag to the self-closing tags and causing this info messages.

![HTML validator results]()

[CSS validator](https://jigsaw.w3.org/css-validator/)

- 0 errors
- 0 warnings
- 0 info messages

![CSS validator results]()

### Bugs and Fixes

- Navbar wasn't "pushing" content down despite margin and padding :
    - Resolved by adding Bootstrap's "fixed-top" class to the navbar's tag. 

- Activities section was not working properly on smaller devices when created with div's and positioned with a float attribute. 
  Float caused this section to overlapp content under it on a mobile device :
    - Decided to use Bootstrap's grid system instead. 

### Un-resolved Bugs

- There is no un-resolved bugs

## Deployment 

The master branch of this repository is the most current version and has been used for the deployed version of the site.
The Code Institiue student template was used to create this project.

[Code Institute Template for CodeAnywhere](https://github.com/Code-Institute-Org/ci-full-template)

1. Click **Use This Template** button.
2. Give your repository a name, and description.
3. Open [CodeAnywhere EDI](https://app.codeanywhere.com/) and log into your account.
4. Click **New Workspace** button.
5. Create a workspace from your project repository by creating a clone.

### Creating a clone

1. From the repository, click **Code**.
2. In the **Clone >> HTTPS** section, copy the clone URL for the repository.
3. Paste a link into the designated area on the CodeAnywhere. 

### Forking

1. From the repository, click **Fork**.
2. Give your repository a name.
3. Click **Create fork**.

## Credits

### Images :

- Unsplash

[Hero image - desktop](https://unsplash.com/photos/person-holding-wand-on-top-of-bowl-3n7DdlkMfEg)

### Code :

- [Code Institute, Love running project](https://github.com/Code-Institute-Solutions/Love-Running-Solutions) :
    - Inspiration for a contact page/form.

- [Font Awesome](https://fontawesome.com/) :
    - Used for all icons across the website.