# Corca Dhuibhne Community Woodlands

![landing page of website](https://github.com/OrlaBr/community-woodlands-project/blob/master/corcadhuibhne-sm.jpg 'Landing page')

The aim of this website is to create a modern visual presence online for a new community based project :herb:‘Corca Dhuibhne Community Woodlands’. The goal is to create awareness of the overall project itself and to get people involved, in some way.
YOu can view the deployed website here: https://orlabr.github.io/community-woodlands-project/


## Table of Contents
- [Description](#description)
- [UX](#ux)
- [Features](#features)
- [Technologies](#technologies)
- [Testing](#testing)
- [Deployment](#deployment)
- [How to Use](#how-to-use)
- [Credits](#credits)
- [Licence](#licence)
- [Acknowledgements](#Acknowledgements)

:black_nib:
## Description
The website has a dual purpose. It was created for a new local community group to use, but it also deploys all my course learning to date with the Code Institute. The elements I used in creating this website, are all practical techniques I have been learning,  working through the User Centric Front End Development modules of the Full Stack Developer Bootcamp.

## UX
The main function of the website was to create a visual presence online for a local community group, :herb: Corca Dhuibhne Community Woodlands, so they can showcase their work to date, engage with the general public to become involved, and also promote activities and events they are running.
- - -
 - *Strategy Plane*  :deciduous_tree:  Create a feel-good visually appealing custom website with calls to action to engage the public to become involved in the project as either active or passive participants. Create the impression of lush greenery and vitality
    - User 1: the general public, who may have heard of the project word of mouth or have heard about the project already through local media or social media sites.
    - User 2 : partnering organisations and funders. Developing a modern professional looking website, will in turn help with future funding applications.  
    - Research: community websites tend to be very plain and content heavy. So focus was on minimal content, visually stunning pictures, to evoke more feeling and reaction. Updates can be added regularly to the all important newsletter, the blog and social media sites.
     - Notes: The responsibility to maintain the website and social media channels is usually met with reluctance among community groups  yet it is of vital importance particularily for groups looking for funding. Funding bodies, like to be visually represented, to be able to add logos, etc.
- - -
 - *Scope Plane* :computer: Creation of a MVW, minimum viable website with mixed content that has the potential to grow.
     - Needs: public information about the role and function of the community group. I decided on a simple scroll down website to reflect modern trends and designed the website using bootstrap mobile 'first’ theory
     - Important features:
          - contact form,
          - access to a newsletter-sign up,
          - active blog to showcase projects and activities.
- - -
 - *Structure* :pencil2: A minimal website, with simple content yet visually stunning. The website needed to reflect the community groups focus, that is to develop and grow the group with predominant calls to action to contact the group, and sign up to the newsletter. The presence of the blog helps to engage the user at a personal level and to promote activities and events.
- - -
 - *Skeleton Plane* :computer:  Top priority is awareness about the aims of the project, using visual imagery, evoking the charms of native woodlands.
     - Large rich images with no overlaying text to appeal to the senses, and woo the user.
     - Support and connect with the project, through information and a contact form
     - Knowledge about the project through the blog
     - Deliberate color scheme, using the same greens and purples that could be found in a few of the images. Eg moss and mushrooms, trees and bluebells.
     - Mockups created using [Canva](https://www.canva.com/), with Bootstrap 'mobile first' in mind
          - [mobile mockup](https://github.com/OrlaBr/community-woodlands-project/blob/master/cdcw-mobile-mockup.pdf)
          - [desktop mockup](https://github.com/OrlaBr/community-woodlands-project/blob/master/cdcw-desktop-mockup.pdf)
 - - -
 - *Surface Plane* :seedling:  Using Canva as a mock up tool, I was able to create a very accurate depiction of what the final website would look like, the colour schemes, placement, colours and fonts. I also decided to use font awesome icons, as these are now universally known. I also revised the text, to be included in the final web design. Although the mock-up isn't exactly the same as the final version of the website, I made small changes along the way, in order to create a more fluid website. Such as making the navigation stick, as I found in the desktop version, it took too long to scroll down and back up again.
 
:ledger:
## Features

#### Existing Features

- *Sign Up Form* - getting users to sign up to a newsletter was one of the top priorities, so I decided to put it on the first page as a pop-up modal. It meant the user could immediately identify with where it is.
- *Contact Us Form*- The website goal is to try to drum up public support for the community group, and inviting people to support in a number of ways was very important. By using a generic contact form it was inviting the user to identify ways they could themselves help, rather than a simple call for money or action. This reflects the long term goals of the project, rather than a simply ‘gofund me’ attitude
- *Blog* - Blogs are very undervalued elements in a website, and especially for a community group, can increase participation hugely. The blog was developed on a card system, with the visual element the biggest, to evoke more feeling and anticipation in the user.\\

##### Features Left to Implement

 - Add pop up message when people have clicked on submit in contact form
 - Add a pop up modal to encourage people to sign up to newsletter
 - Development of the blog to include archives and a search function
 - Development of the footer to include future sponsors and partners section
 
## Technologies Used

- HTML - HTML5
- CSS - CSS3
- Bootstrap - layout and functionality of the website
- Javascript - bootstrap javascript for functionality
- Gitpod - to write and develop the website
- Github -  to host the project in an online repository

*Other web applications used:*
- Repl.it - to practice elements and sections of coding before adding to Gitpod
- Canva - to create a detailed wireframe
- Google Fonts - sytlesheet linked to customize fonts
- Font Awesome - stylesheet linked to custimize icons
 
:wrench:
## Testing  

- Proofreading - all text added to a Google doc for spelling and grammar check. Verified by another person..
- Checking Links - tested all links including: relative, absolute, text, bookmark, e-mail, external  
- Validate form - Contact Us Form
    ```Submitted details in the empty form to verify that an error message about the required fields appears
    Submitted the form with an invalid email address to verify that a relevant error message appears
    Submitted the form with all inputs valid and verify that a success message appears.`
- SEO - Meta Tags inside the head tags
- Accessibility
- Different Browsers : Testing using Chrome Dev Tools, Firebox Firebug, [Browserling](https://www.browserling.com), [Browsershots](http://browsershots.org/)

    `Chrome | Firefox | Safari | Opera |`

- Validate HTML
`HTML validated using https://validator.w3.org/`
- Validate CSS
`CSS validated using http://jigsaw.w3.org/css-validator/`

![mock up samples of website on different browsers and phones](https://github.com/OrlaBr/community-woodlands-project/blob/master/browser-testing.jpg 'Mock-up')

## Deployment
My website was developed using `Gitpod` and hosted using `Github`, generated from a template created by the Code Instutute, and then deployed directly from the master branch. Regular changes were made and all updates were then committed to the master branch. The first or home page is called `index.html`, as servers expect index.html to be the name of the main file of a website folder. An assets folder was then created, to include the CSS stylesheet and all the images used on the site. I proceeded to work on sections, commiting as I went.
Changes made:
Originally the heading wasnt fixed but I had issues with access to navigating when scrolling down the page, so I fixed the navbar to the top. This caused issues with the first section, so I had to adjust the margin and paddings to fit. The 'about' and 'contact' sections were divided into 2 columns on both the mobile and desktop mockups, but after building, I thought the mobile version looked too cramped as 2 columns, so I decided to switch to no columns on mobile view.
Throughout the design and implementation of the website I kept notes in Google Docs, which were to come in useful when writing the ReadMe page. I then cross referenced the Read Me page and the website, working through the sections, eg UX, UI, testing, validation, correcting errors when I came across them.
I added the pdfs of the mockups after writing the readme, uploading them to the directory from github rather than git pod. I feel they should have been loaded through gitpod, and put in their own UX folder.


 
##### Installing a cloned repository

1. Make sure you have these installed
   - [node.js](http://nodejs.org/)
   - [git](http://git-scm.com/)
2. Clone this repository into your local machine using the terminal (mac) or Gitbash (PC) `$ git clone CLONEURL`
3. CD to the folder `cd FOLDERNAME`
4. Run `$ npm install` to install the project dependencies
5. Run `$ npm start` to start live preview server


## Credits
All text by author: Orla Breslin.
All photos copyright free from <https://pixabay.com/>.
All icons copyright free from <https://fontawesome.com/>.
 
## Licence & Copyright
[![License: CC BY-SA 4.0](https://licensebuttons.net/l/by-sa/4.0/80x15.png)](https://creativecommons.org/licenses/by-sa/4.0/)
Orla Breslin 2020
 
 :mega:
## Acknowledgements
Research from community websites include:
- [Community Woodlands](www.communitywoodlands.org), [Woodland League](http://www.woodlandleague.org), [Glengarry](https://www.glengarry.org.uk/)


Coding Tutorilas:
- [Code Institute](https://codeinstitute.net), [YouTube Tutorials](https://www.youtube.com) eg mmtuts, Traversy Media, Academind

Github, Gitpod and Markup Tutorials:
- [Code Institute](https://codeinstitute.net),Various via [Google](https://www.youtube.com) eg [Github Help](https://help.github.com/en), [Git SCM](https://git-scm.com/doc)

- - -

:top: [Back to top](#corca-dhuibhne-community-woodlands)


