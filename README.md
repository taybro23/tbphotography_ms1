# Code Institute Milestone Project 1. 

## Taylor Brookes Photography. 
[Live Website Here!](https://taybro23.github.io/tbphotography_ms1/)

## **About.** 
I have created a website whereby I am promoting myself as a professional photographer. 
My aim with this website is to showcase my abilities as a photographer to my potential clients. 
There is a page where people can learn a little about me, and a gallery where people can view 
my most recent photographs. I have also included a Contact Me page where potential clients can get in 
touch using a contact form. 

# UX (User Experience).
## **Target audience.** 
The target audience for my website is people who are looking for photos for personal and/or 
commercial use, such as small businesses for promotional purposes and reporters for newspaper articles. 

## **User Stories.**
### **Personal Customer Stories**
* A personal customer wants a good looking website with lots of information and examples of work. 
* They are more interested to learn more about the person, what kind of photo shoots they do and experiences that previous customers have had. 
* They would like to have the information needed to be able to contact the person if they wish to discuss a possible photo shoot.
* Social media may be more important to a personal customer, and they will be able to find these links on the footer of each page. 

### **Commercial Customer Stories**
* For a business owner, they would like to see a simple design that is easy to navigate.
* All the information they needed would be easily accessible. Main information to be provided to the potential client upon arrival of the website, this is on the footer of each page, and in the clearly marked “Contact Me” page. 
* A business customer is less likely to have ample amounts of time to look through sites so all information is put on separate pages so they can go directly to what they are looking for.
* Examples of previous work is important. The gallery page showcases the best/most recent photographs and shows the photographers versatility.


## **Wireframes.**
The Link to my wireframes is below. I have changed the website layout since doing the wireframes,
however I believe these changes have made the live website look better overall.

* [Wireframes](assets/wireframes/photography.pdf)


# Features.

## **Existing Features.**

### **Across All Pages.**

* Navbar
  * The navbar is has been set to "fixed top" so that it will alway be accessible and pages can easily be
navigated between. This improves overall user experience.
  * Underline used in CSS to show which page the user is currently on.
* Responsive design
  * My website was built mobile first and is fully responsive. This was done using Bootstrap.
* Hover effects
  * I used hover effects throughout the website to make the site more visually appealing and to 
  help users navigate more easily.
* Colour scheme
  * I used background colours throughout my site to differentiate between sections. This makes it more pleasing to the eye
  and helps to break the view up from a pure white background features on many sites.

### **Home.**
* Large homepage image 
  * The large homepage image welcomes people to the site and lets them get a taste of what to expect throughout 
  the rest of the site. The bright colours and welcoming layout make sure that the user has a great intial 
  response to the design.

### **About Me.**
* Central photo
  * The central photo of myself allows people to see who I am, and it also adds a personal touch to the website.
* Carousel review section
  * For the review section on my website I wanted it to look good and flow well with the rest of the site. 
  I achieved this by implimenting a carousel. Users are able to easily flick between reviews without being 
  bombarded with paragraphs and paragraphs of text at one time. 

### **Gallery.**
* Area breakdown
  * Gallery is broken down into areas where photos were taken. This allows the user to see my versatility as a photographer
and get an idea of what they can expect from me.

### **Contact Me.**
* Large background cover image 
  * A large background image behind the form works well as it avoids any blank space behind or around the form.
  The contact form itself is slightly transparent to help it blend in.


# Design.
## **Typography.**
* Open Sans Condensed – This is the main font I used for the site due to its simple and clean look.
* Bad Script – I wanted something a bit more artistic for the secondary font, and Bad Script fit that for me.
* Sans Serif – This is the reserve font should anything go wrong with the previous two. 

## **Colours.**
The main colours for my website are shades of blues and greens that complement the images used throughout 
the site. Black and white colours are kept for the text and alternative backgrounds, and I used a shade of 
pink for the review section to make it stand out. I used different opacities of these colours in order to 
improve the overall look of the site.

List of colours used;
* #000 - Black used for the text
* rgb(86, 172, 245) - A shade of blue used mainly for the navbar, as well as the hover colour for the Submit 
button on the Contact Me page.
* rgb(55, 135, 56) - A shade of green used for the footer.
* #fff - White used for social links on the footer and the contact form background colour. 
* #c6ebffa3 - A shade of blue used on the homepage section one.
* #dffbe6ab - A shade of green used on the homepage section two.
* #ade5ff66 - Another shade of blue, used on the About Me page for the background
of the images.
* #ff40d180 - Pink, used for the review section on my About Me page.

## **Imagery.** 
All photos used on my website are photos taken by myself. 


# Technologies Used.
## **Languages.**
In this project, I used the following languages;
* HTML
* CSS

## **Frameworks, Libraries and Programs Used.**
* Boostrap – Bootstrap was used to help me with the basic layouts for the pages, as well as providing 
me with JavaScript to create a collapsible menu on mobile devices.
* Google Fonts – I used google fonts to find the best two fonts to suit the needs of my website. 
* Github – Github was used to store the code for the project.
* Chrome Developer Tools – This helped me by allowing me to make amendments live to the site, as well as to check media queries.
* Balsamiq – This was used to create the original wireframes.


# Testing.
* [W3C HTML Validator](https://validator.w3.org/#validate_by_input) was used for HTML validation. The test came back with no found issues.
* [W3C CSS Validator](https://jigsaw.w3.org/css-validator/#validate_by_input) was used for CSS validation. The test came back with no found issues.

## **Features and Functionality Tests.**
Across All Pages;
* Navbar.
  * I checked that all links work correctly and go to the correct pages. 
  * Fixed top. This was not a feature that I initially had on the site but wanted to add it to make navigating the website more easily. I made sure the code worked on the index page then copied the code across to all pages.
  * I initially had issues with the collapsible menu on mobile devices and tablets, but I realised this was because I did not have the correct script code. This was corrected and now works without issue.
  * The logo font size was too large on some mobile devices and was pushing the hamburger menu down to the next line. I made the text slightly smaller on smaller screens and this has fixed the issue. 
* Footer.
  * I checked all social links are working correctly.
  * The icons for the social links were not working correctly as I had forgotten to include the link to fontawesome. This has been rectified.
  * The footer is to remain at the bottom of all content. I tested this by removing and adding placeholder content to make sure the code worked. 
* Images.
  * I found that when loading the website, it was quite slow, especially on the gallery page. This was due to the file sizes of the images as the photographs were taken using a professional camera. I resized and compressed them all, and it now loads a lot quicker, and takes up significantly less MB when browsing the website. 
* Hover.
  * I checked the hover functionality on the navbar menu items first, and once I had that fully working I used the same base code and implemented it on the logo.
  * I used hover effects on the footer to show which social link is being hovered over, this helps the site user visually. 
* Media Queries.
  * I amended the media queries a few times to make sure they were set to the correct breakpoints and checked across multiple web browsers. They all worked as intended.

Page Specific;
* Home page images.
  * The images for the homepage would squash down and distort when the screen size was made smaller. I fixed this by amending the “col” sizes so that the breakpoints were more frequent to stop the images from distorting.
* Carousel.
  * After implementing the carousel I checked that the arrow keys worked as intended on mobile and desktop devices. 
  * The carousel size was an issue as it was tricky to get it right across all screen sizes so I used media queries to get the correct size for each screen size. 
* Contact form.
  * The contact form was thoroughly tested to make sure all fields are correctly set to “required”. 
  * The inputs were all checked as well to make sure that the correct types had to be entered eg, email address field had to have the email format. 
  * Telephone number issues with letters being able to be submitted, this has since been fixed and although letters can still be entered in the field, they cannot be submitted and an error message is shown.

## **User story testing.**
Personal Customer Stories;
* *A personal customer wants a good looking website with lots of information and examples of work.*
  * I personally believe my website looks good and is easy on the eye, and I used bright colours to improve this. The home page has snippets of information about me and what I do, as well as showcasing a couple of photos. The about me page has an image of myself with some information about me, as well as reviews at the bottom of the page so users can see how previous clients have found working with me to be. The gallery shows my most recent photos, split into areas where they were taken to show versatility in my abilities. On the contact me page, further contact information can be found as well as a form where potential clients can submit a query. 
* *They are more interested to learn more about the person, what kind of photo shoots they do and experiences that previous customers have had.*
  * My about me and gallery pages fulfil these wants of a potential client. Lots of reviews and photos are provided on the site. 
* *They would like to have the information needed to be able to contact the person if they wish to discuss a possible photo shoot.*
  * The footer is the same on every page and contains links to my social media as well as an email address. My contact me page contains my mobile number and a form where they can submit any questions, queries or requests. 
* *Social media may be more important to a personal customer, and they will be able to find these links on the footer of each page.*
  * Social media links can be found on the footer of every page. 

Commercial Customer Stories;
* *For a business owner, they would like to see a simple design that is easy to navigate.*
  * I have kept the website simple with a fixed navbar so that pages can easily be navigated between regardless of position on the site. 
* *All the information they needed would be easily accessible. Main information to be provided to the potential client upon arrival of the website, this is on the footer of each page, and in the clearly marked “Contact Me” page.*
  *  As stated here, all the information they would need is on the about me and contact me pages, as well as social media links and an email address being provided on the footer of each page. 
* *A business customer is less likely to have ample amounts of time to look through sites so all information is put on separate pages so they can go directly to what they are looking for.*
  * I have kept each section separate to their respective pages for ease of use for all clients, for example, if they are looking for more information about the photographer to see if they are the right person for the job, the about me page will be the most useful page for them. This is clearly indicated on the navbar, and again is available throughout each page and is fixed to the top so it can be easily navigated to. 
* *Examples of previous work is important. The gallery page showcases the best/most recent photographs and shows the photographers versatility.*
  * The gallery page is perfect for showing the abilities of the photographer in a clear and concise way. 


# Credits.
## **Content.** 
* JPEG-Optimiser – I used a JPEG-optimiser to make my images smaller and more condensed in size to help with the website loading speed.
* Navbar – I used Bootstrap for the navbar and edited the code to change the style and colour. 
* Social Links – For the social links I followed the code from a tutorial at Code Institute, 
specifically the CV website build. I made small amendments. I also used icons from Font Awesome.
* About me – For the circular pictures on the “About Me” page I followed the code from the 
Love Running tutorial at Code Institute.
* Review – The carousel I used for the review section was code from Bootstrap. I made some amendments.
* Bootstrap indicator edit – I used stack overflow to help me with editing the indicators and the 
general look over the carousel. 
* Form – The code I used for the form was a tutorial from Code Institute, used specifically 
on the CV website build. 

## **Acknowledgements.**
I want to thank my mentor Maranatha for helping me to improve my site, and my fellow Code Institute students 
for their assistance in code queries and improvements!
