# Grow Kinesis

## [Live Site](https://salute03.github.io/milestone-1-project/)
![Screenshot (42)](https://user-images.githubusercontent.com/65897717/99201236-a7807980-276f-11eb-9c09-eaa6f2212826.png)

Grow KInesis is a Milestone 1 project, it is part of the Fullstack WEb Development Course of [Code Institute](https://codeinstitute.net/).

## Project Overview

This is a front-end web page for an outdoor fitness trainer based in Lagos Nigeria, Pelumi.  Pelumi is setting up his own business providing a range of personal training, group workouts and using sport as a mode of training.
He wanted a website that showcases what he offers to his clients and potential clients, how he can help his clients benefit from having a personal trainer, importance of yoga and how it greatly improves more than just flexibility & having fun.  
He want the gallery to showcase pictural representation of the of how his clients achieve their body goals following his training style and how he is uniting different people with the same goals, there by creating friendship outside training.
This webpage was created as the first milestone project as part of the Code Institute ‘Full Stack Development’ course.  
The deployed version can be viewed at: https://salute03.github.io/milestone-1-project/
This is for educational purposes only.

## 1. UX

Pelumi deals with the hustle of showcasing his work via social media alone, as his workout sessions are becoming large, he decided he needs a website to keep his clients community/base exclussively together, showcase the growth of his clients to potential clients in orther to attract more client.

As a user, i expect to:
* Easily navigate through the website
* Access well defined pictures to see what is done and how its been done.
* Read other clients experiences
* See a well colored layout

## 2. Features

This is a three page website which includes:

### Home page 
This is divided into three parts:
* The fist sight which takes the view height(vh) of the window and displays a bold backround image, sign up button that opens sign up form and a font awesome bumbell image that links to the gallery.
* Listing of benefits of yoga and personer training.
* Testimonies of some clients.

### Gallery 
This displays images of different workout sessions, using masonry styling layout.

### About
This page basically introduces Pelumi, the workout instructor and gives a little information about his career, accademics and achievements.

* Navbar and footer are the same acroos the three pages.


## 3. Testing

1. **amiresponsive** [Am I Responsive](http://ami.responsivedesign.is/) Used to test responsiveness across a range of devices.
2. **Developer Tools** Chrome, Firefox and Microsoft Edge, web dev tools using iPhone 6,7,8,x plus, smasung s and Ipad as toggle devices to test responsiveness.
3. **Mobile Devices** I used my Google Pixel 3a phone and Amazon Fire tablet to test the site, using this method I found that not all of the fonts were loaded properly originally.
4. **Friends and family** I asked for feedback from friends and family in order to get a users perspective and i got very good feedback.
5.**Lighthouse** A number of issues were resolved using lighthouse. I used lighthouse to determine the rate of performance, accessibility, best practice and SEO.


6.**[W3C HTML Validator]**(https://validator.w3.org/) Used to identify HTML errors. few errors were identified, which has to do with the modal form.
7.**[W3C CSS Validator]**(https://jigsaw.w3.org/css-validator/) Used to identify CSS errors.

### testing image
[light house](assets/images/test.jpg)
[validator](asstes/images/test2.jpg)

### Manual Testing

1.Expectation 
* The navbar brand is should link back to the home page from any part of the webpages.
* The navlinks should open the pages linked to.
* The sign up button should display a sign up form.
* The images in the gallery should open in another page.
* The dumbell should open the gallery.
* The armburger button should display the menu in the mobile platform.

2.Testing
Each of features was clicked

3.Result
Each of the features responded normarlly to clicks and displayes what was expected.

## 4. Wireframes
I used pen and paper for the wireframes.

## 5. Technologies Used

1. **HTML (Hyper Text Markup Language):** Used throughout the site;  
   HTML: https://www.w3.org/TR/html/ 
2. **CSS (Cascading Style Sheets):** Used throughout the site;
   https://www.w3.org/Style/CSS/Overview.en.html
3. **Bootstrap:** Used to aid responsive design and for componants such as navbars, buttons. This project uses Bootstrap as a framework to assist in page grid layout & navigation.  Bootstrap v4.5 was used.
   https://www.bootstrapcdn.com/
4. **JQuery:** This project uses JQuery to assist in execution of bootstrap.
   https://jquery.com/
5. **GitHub:** THis site was published using GitHub pages.
   http://github.com
6. **Chrome/Firefox/Bing DevTools:** Regularly used to test the the site 
   https://developers.google.com/web/tools/chrome-devtools
7. **Font Awesome:** The social icons,  Facebook, Twitter, Pinterest, Linked-in, instagram and You-tube  in the footer, dumbell icon in the home page, @ icon, cellphone icon and email icon in the contact  were imported from Font Awesome. 
   https://fontawesome.com/icons
8. **Google Font:** Roboto Font family was used throughout the project.
   https://fonts.google.com/

## 6. Development Cycle

* HTML development

The first stage of development was writing the HTML code for the develpopment of the home page, starting with the navbars then use bootstrap jumbotron for the first sight of the home page(seen in 'index.html').
I then created more HTML pages for other pages (i.e. gallery, about).

* CSS Code

Once I feel comfortable with the HTML structures, I then started applying styles by writing CSS code, which can be seen on file 'styles.css'.


## 7. Bug fixing

* The text in the heading of the form and the label texts were not showing, which i fixed by simply changing the colors to black and i got this idea from slack.
* Then i made a mistake in the input, i used type="name" instead of type="text".and also fix some bugs I had not previously encountered during development.
* The armburger menu button didn't display when i first loaded it, The i used font awesome "<i class="fas fa-bars"></i>" which fixed the problem.
* The JQuery code just below the footer in the index.html was provided by @JimLynx_lead in the user-centric-frontend channel on [slack](https/slack.com) because the code i initially copied from bootstaps  was causing a disturtion on the mobile screen and this helps to fix the problem.
* An image link was broken in the index.html, i fixed it by chaging the image because the source of the initial image has problem.


## 8. Deployment

1. I Created a Github account at https://github.com
   My account url; https://github.com/salute03
2. I installed Git and set up a username and password.
3. I created a repository on Github (https://github.com/salute03/milestone-1-project)
4. I uploaded all files to my Github repository.
6. To publish the project to see it on the web, I then went into the Settings on my respository, scrolled down to the heading, GitHub Pages. Under the Source setting, I used the drop-down menu to select master branch as a publishing source and saved it. Refreshed the github page, and you are then given a url where your page is published;
Your site is published at https://salute03.github.io/milestone-1-project/

## 9. Credits

1. **Code Institute**
This project was written using code institute's template https://github.com/Code-Institute-Org/gitpod-full-template. The Home page and gallery was inspired by code institute tutorial vedios of whiskey page landing and love runnimg project respectively.

2.**Slack**

3.**All** text was written by me and with some ideas from the project of https://github.com/eileenpeacock/milestone-1-ucd


### Media
All pictures in this project were gotten from https://egbinolamide87.pixieset.com/workit/

## 8. Acknowledgements

1.  My mentor Moosa Hassan for his support and input.
2.  My peers on **slack** for their generosity in sharing their knowledge and experience. But most importanly @JimLynx_lead, @Feawos, @Toby, Anthony just to mention few.

##### back to [top](#table-of-contents)
                  