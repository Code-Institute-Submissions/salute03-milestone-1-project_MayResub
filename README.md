# Grow Kinesis

### [Live Site](https://sean-mc-mahon.github.io/ms1virtualireland/index.html)

### [GitHub](https://github.com/Sean-Mc-Mahon/ms1virtualireland)

![Various Devices](https://github.com/Sean-Mc-Mahon/ms1virtualireland/blob/master/wireframes/vi-responsive.JPG)

Grow KInesis is a Milestone 1 project, it is part of the Fullstack Software Development Course of [Code Institute](https://codeinstitute.net/).

## Table of Contents

1. [**Project overview**](#project-overview)
2. [**UX**](#ux)

- [**UX Planes**](#ux-planes)
  - [**Scope Plane**](#scope-plane)
  - [**Structure Plane**](#structure-plane)
  - [**Skeleton Plane**](#skeleton-plane)
  - [**Surface Plane**](#surface-plane)
- [**User Stories**](#user-stories)
- [**Design**](#design)
  - [**Libraries**](#libraries)
  - [**Color Scheme**](#color-scheme)
  - [**Typography**](#typography)
- [**Wireframes**](#wireframes)

3. [**Features**](#features)

   - [**Existing Features**](#existing-features)
   - [**Features Left to Implement**](#features-left-to-implement)

4. [**Technologies Used**](#technologies-used)

5. [**Testing**](#testing)

- [**Validators**](#validators)
- [**Manual Testing**](#manual-testing)

6. [**Deployment**](#deployment)

7. [**Credits**](#credits)

- [**Content**](#content)
- [**Media**](#media)
- [**Acknowledgements**](#acknowledgements)

---

## Project Overview

VI is a virtual tour of Ireland aimed at people planning on visiting Ireland, people who cannot visit or people who want to look back on trips to some of Ireland’s most beautiful sites.

## UX

VI is aimed at B2C users. Users expect to be able to experience a place and learn more about it without physically being there. The content is a mix of historical, mythological, anecdotal, cultural and geological information on Ireland’s most famous sites aided by imagery (my own photographs). The content is divided into pages based on regions; West, North and South with a direct link to each from the homepage and links to sections of pages for specific locations.

### UX Planes

#### Scope Plane

Home page with own designed animated logo and video links to each 'tour'. Each tour to comprise three locations navigated by an image gallery and each location to incorporate a carousel and text describing history and mythology. About page and contact page to encourage user engagement. Fully responsive and consistent design.

Future sprints to use 360 degree views and tours of the South of Ireland as well as seperate city tours.

#### Structure Plane

Each tour to be accessible from home page in non linear fashion from nav bar or from image gallery as it is impossible to know which tour user may be most interested in. Within each tour the in formation and images is presented in linear fashion for narrative clarity with sub nav giving option of jumping to individual sections for ease of use of user.

#### Skeleton Plane

Shape to remain consistent. Images are to be dominant with text following the following order; history & geology ('sans-serif' dark grey font), culture & mythology('marcellus' green font). Features kept to a minimum and simple navigation, no need for searching filters orpagination. Logo and heading to navigate to home page. Social links and copyright in footer.

#### Surface Plane

Fonts of header, body and footer to contrast in size and style as appropriate. Overlays used on images to ensure contrast while text appears on hover. Text hidden on images for small devices on carousels.

### User Stories

- User Story A: Joe visited Ireland last year and wants to relive the experience and share with others what he saw.
- User Story B: Amanda is planning a trip to Europe and is trying to decide if she wants to include Ireland in her trip and wants to know more about things she might see here.
- User Story C: Liz has been to some of the locations and wants some deeper background information.

### Design

A standard layout is fully responsive on mobile devices and larger screens.

#### Libraries

- [Bootstrap 4](https://getbootstrap.com/) - is a framework for building responsive, mobile-first websites. I primarily used bootstrap to format layouts and for certain components such as buttons and carousel.

#### Color Scheme

Colours are kept to a bare minimum, using only the colors for bootstrap bg-light, bg-dark and one green. My palette is located on [Coolors](https://coolors.co/u/sean_mcmahon)

#### Typography

4 [Google Fonts](https://fonts.google.com/) were used across the site:

- [Poppins](https://fonts.google.com/specimen/Poppins?query=poppins) : body text
- [Marcellus](https://fonts.google.com/specimen/Marcellus?query=marcellus) : blockquote
- [Quicksand](https://fonts.google.com/specimen/Quicksand?query=quicksand) : Logo (animated)
- [Pacifico](https://fonts.google.com/specimen/Pacifico?query=pacifico) : Logo (solid) and icon

### Wireframes

I used Balsamiq and figma to create the wireframes.

- [Balsamiq Wireframe](https://github.com/Sean-Mc-Mahon/ms1virtualireland/blob/master/wireframes/vi-wireframes.pdf)

- [Figma Wireframe](https://github.com/Sean-Mc-Mahon/ms1virtualireland/blob/master/wireframes/vi-figma-wireframe.png)

##### back to [top](#table-of-contents)

---

## Features

### Existing Features

- Index - The index uses three videos as links to the regions North, West and East. I used Google Earth studio to simulate drone footage of the locations, Google Earth Studio is free source once attributed with a watermark.

- North/West/East - These pages use CSS Grid in order to preview the location pages.

- Various - The individual location pages use floated bootstrap carousels, blockquotes and paragraphs to showcase the sites, history and mythology of various locations around Ireland.

- About - This section displays an image and short bio.

- Contact - This section has a form where users can sign up for updates.

### Features Left to Implement

- Google Streetview - this may be used to p rovide 360 degree views of the locations.

##### back to [top](#table-of-contents)

## Technologies Used

1. **HTML (Hyper Text Markup Language):** Used throughout the site;  
   https://developer.mozilla.org/en-US/docs/Web/HTML
2. **CSS (Cascading Style Sheets):** Used throughout the site;
   https://www.w3.org/Style/CSS/Overview.en.html
3. **Bootstrap:** Used to aid responsive design and for componants such as navbars,buttons and carousels. https://getbootstrap.com/
4. **Visual Studio Code:** Code Editor used to create the site.
   https://code.visualstudio.com/
5. **GitHub:** Used to host repos for the site https://github.
6. **Chrome/Firefox/Bing DevTools:** Regularly used to test the the site https://developers.google.com/web/tools/chrome-devtools
7. **W3C Markup Validation Service** Used to test code for errors; https://validator.w3.org/https://jigsaw.w3.org/css-validator/validator
8. **Affinity Designer** Illustration software used to create logo and site icon; https://affinity.serif.com/en-gb/
9. **Figma** Collaborative interface design tool used for some wireframing as well as creating logo; https://figma.com
10. **Balsamiq** Used to create wireframes; https://balsamiq.com/?gclid=EAIaIQobChMIuoqlhfWi6wIV6YBQBh2f9w7DEAAYASAAEgLUTfD_BwE
11. **Tinypng** Used to compress images; https://tinypng.com/
12. **Croppola** Used to crop images; https://croppola.com/
13. **mp4compress** Used to compress video files; https://www.mp4compress.com/
14. **Windows Movie Maker** Used to create videos from Google Earth Studio Images; https://www.mp4compress.com/

## Testing

### Validators

1. **HTML** [W3C HTML Validator](https://validator.w3.org/) Used to identify HTML errors

2. **CSS** [W3C CSS Validator](https://jigsaw.w3.org/css-validator/) Used to identify CSS errors

### Manual Testing

1. **amiresponsive** [Am I Responsive](http://ami.responsivedesign.is/) Used to test responsiveness across a range of devices.

2. **Developer Tools** Chrome, Firefox and Microsoft Edge web dev tools using iPhone 5 and Ipad as toggle devices to test responsiveness.

3. **Mobile Devices** I used my Google Pixel 3a phone and Amazon Fire tablet to test the site, using this method I found that not all of the fonts were loaded properly originally.

4. **Friends and family** I asked for feedback from friends and family in order to get a users perspective.

5. **Contact Form** On the contact page the form may not be submitted without using correct syntax for the e-mail input or if either input is blank. Once inputs are filled properly the sign up button will lead to a form dump page.

## Deployment

1. I Created a Github account at https://github.com
   My account url; https://github.com/Sean-Mc-Mahon

2. I installed Git and set up a username and password.

3. I created a repository on Github (https://github.com/Sean-Mc-Mahon/ms1virtualireland)

4. On VS Code I opened the command pallette and selected Git Clone, I pasted in the URL for the repo on GitHub and selected a folder on my computer to sync to.

5. I uploaded all files to my Github repository.

6. To publish the project to see it on the web, I then went into the Settings on my respository, scrolled down to the heading, GitHub Pages. Under the Source setting, I used the drop-down menu to select master branch as a publishing source and saved it. Refreshed the github page, and you are then given a url where your page is published;
   Your site is published at https://sean-mc-mahon.github.io/ms1virtualireland/index.html

7. To run this code on a local machine, you would go to my respository at
   https://github.com/Sean-Mc-Mahon/ms1virtualireland and on the home page on the right hand side just above all the files, you will see a green button that says,
   "Clone or download", this button will give you options to clone with HTTPS, open in desktop or download as a zip file.
   To continue with cloning, you would;

- Open Git Bash
- Change the current working directory to the location where you want the cloned directory to be made.
- Type git clone, and then paste this URL; https://github.com/BobHerold/RobertHeroldportfolio.git Press Enter. Your local clone will be created.

For more information about the above process; https://help.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository

---

## Credits

### Content

1.  Google Fonts for font styles; https://fonts.google.com/

2.  Youtube; javascript code taken from youtube tutorial by [Bibek Bulan](https://www.youtube.com/watch?v=cBDk5B74kVQ) used for playing index.html videos on hover.

3.  Youtube; Image Gallery inspired by youtube tutorial by [Follow Andrew](https://youtu.be/gvPyJ0rc944)

4.  Youtube; Carousel inspired by youtube tutorial by [CLever Techie](https://youtu.be/AvMl3StAju4) and overlays inspired by [LoharTalk](https://youtu.be/Cfv_9l8F0Lo)

5.  Youtube; Contact form inspired by youtube tutorial by [Dev Ed](https://www.youtube.com/watch?v=IxRJ8vplzAo)

6.  Youtube; SVG Animation inspired by youtube tutorial by [Dev Ed](https://youtu.be/IxRJ8vplzAo)

### Media

1.  [Google Earth Studio](https://www.google.com/earth/studio/) for images used to create videos on homepage.

### Acknowledgements

1.  My mentor Adegbenga Adeye for his support and input.

2.  My peers on slack for their generosity in sharing their knowledge and experience.

##### back to [top](#table-of-contents)
