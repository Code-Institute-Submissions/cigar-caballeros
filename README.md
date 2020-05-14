# CIGAR CABALLEROS

[logo]: https://github.com/jtwy23/cigar-caballeros/blob/master/README/readme-images/logo.jpg

![alt text][logo]

My project is a 6 page website. Consisting of a home, cigars, the process, cigar time, contact us and a whatsapp 
page. The aim of my website is to draw new and old cigar lovers to meet up and share cigars. As well as a few 
pages with information on cigars for new cigar enthusiasts. The main draw for the website is to have users join 
the group for free and connect with the club through other sources of social media.

## UX

The client wanted a user experience that was simple and easy to navigate. As well as, a site for users to come and
meet fellow cigar lovers and to have good information for new cigar enthusiasts to look into and get started.

Below is the user stories:

* As a user, I want to be able to find local meet ups, so that I can enjoy my cigars with.

* As a user, I want to have a space to communicate with cigar specialists to understand how to care for my own 
cigars.

* As a user, I want to see more instructional videos to learn how to deal with my own cigars.

* As a user, I want more ways to interact with other cigar smokers so that I don’t always need to make it to a 
cigar event.

* As a user, I want to see cigar caballeros social media links so I can find more information on cigars and events.

### Wireframes

[Desktop](https://github.com/jtwy23/cigar-caballeros/commit/1f36c01b581405ee91a20013823cfc7a6c22f80a#diff-a0cb412dde79d293d908854b646abeb4)

[Tablet](https://github.com/jtwy23/cigar-caballeros/commit/1f36c01b581405ee91a20013823cfc7a6c22f80a#diff-b6f2189cc575b22f3fc0809459eb56e6)

[Mobile](https://github.com/jtwy23/cigar-caballeros/commit/1f36c01b581405ee91a20013823cfc7a6c22f80a#diff-80e604f7d251d04a299b65ccfb8b09e7)

## FEATURES

### Existing Features

The features of this website are listed below.

* Header holds the logo image. (Client doesn't have a better logo file at the moment.)

* Navigation bar with toggler when screen size is reduced.

* Images throughout the site. All images are owned by the client.

* A google map of the location of a previous cigar event.

* Forms in cigartime.html and contactus.html.

* Footer contains all the clients social media links. As social media continues to grow in popularity I have 
implemented the clubs social links into the site. For users who are actively looking for Facebook, Instagram or 
the likes we have that to hand for them too.

* Jumbotron (index.html) - The jumbrotron used here is to attract users immediately who land on the page and are 
looking for immdiate sign up. Just click on the 'Join Free' button and it will take you straigh to the sign up form.

* Jumbotron (whatsapp.html) - A seperate page was added to the 'What's App' icon on the footer. When the icon is 
clicked the iuser is taken to the whatsapp page. This is yet another way for new users to connect with the club. A 
mobile number is already available for a new user to take and use. Once connected the user will be automatically 
added to he group. 

* YouTube videos are embedded because currently the club has no unique content for videos. I have implemented some 
other cigar afficionados with cigar instructional videos onto the site. They are slightly longer than a brief clip 
but very informative and educational to amateur or intermediate cogar smokers.

### Features Left To Implement
In the future the club would be looking to take online cigar meets to the next level with more virtual herfing.
Possibly an application that allows users to pay and join in to a cigar event. However this is out of my scope 
at the moment.

The club is looking to do merchandise and will in time implement and online store. This cannot be implemented until
the client has merchandise to sell.

## TECHNOLOGIES USED

[HTML5](https://en.wikipedia.org/wiki/HTML5)

[CSS3](https://en.wikipedia.org/wiki/Cascading_Style_Sheets#CSS_3)

[Boostrap version 4.4.1](https://getbootstrap.com/)

[Cigar Favicon](https://www.freefavicon.com/freefavicons/objects/iconinfo/cuban-cigar-152-204530.html)

[jQuery](https://jquery.com/)

[Javascript](https://www.javascript.com/)

[Fontawesome](https://fontawesome.com/)

[Google Fonts](https://fonts.google.com/)

[Balsamiq Wireframes](https://balsamiq.com/)

## TESTING

I started testing the sites HTML by going to [W3C Markup Validator](https://validator.w3.org/). My HTML code showed 
no errors.

[html]: https://github.com/jtwy23/cigar-caballeros/blob/master/README/readme-images/html-validator.JPG

![alt text][HTML]

After checking HTML I used [W3C CSS Validator](https://jigsaw.w3.org/css-validator/). Only one warning came up
regarding [Google Fonts](https://fonts.google.com/specimen/Quicksand) CSS. So I copied the Google fonts link to 
their CSS and validated that too.

[CSS 01]: https://github.com/jtwy23/cigar-caballeros/blob/master/README/readme-images/css-validator01.JPG

![alt text][CSS 01]

[CSS 02]: https://github.com/jtwy23/cigar-caballeros/blob/master/README/readme-images/css-validator02.JPG

![alt text][CSS 02]

[CSS 03]: https://github.com/jtwy23/cigar-caballeros/blob/master/README/readme-images/css-validator03.JPG

![alt text][CSS 03]

To test the responsiveness of mt site I used [Am I Responsive](http://ami.responsivedesign.is/?url=https%3A%2F%2Fjtwy23.github.io%2Fcigar-caballeros%2F)

- Header: This was tested by navigating away from the page and clicking the logo to see that it points back to the
index.html.

- Footer: There are four social media links on the footer. [Facebook](https://www.facebook.com/), 
[Instagram](https://www.instagram.com/) and [Twitter](https://twitter.com/) were tested to see if when these icons
are clicked it navigates away to the respective page and opens on a new page so the user can get back to our site.
The 'What's App' icon actually helps users navigate to a different part of my site. Therefore no new browser window
needs to be opened. All this came out the way it was expected.

- index.html: There are two images on this page. I made sure that the images load up properly by refreshing the page. I 
also clicked on each image and checked that it opens up into a new window so the user doesn't ever navigate away from
the site. I also added a jumbotron onto this page to allows users to see the 'JOIN FREE!!!' button. When clicked it
navigates to cigartime.html page to allow users to input details ad join the club.

- cigars.html: Again there are two images on this page. I made sure that the images load up properly by refreshing the page. I 
also clicked on each image and checked that it opens up into a new window so the user doesn't ever navigate away from
the site.

- theprocess.html: As the client had no unique video content for this section. I embedded 'Youtube' videos from other
cigar bloggers. The videos were embedded so that users stayed onto the page while the videos played. I tested each
embedded video by playing them for one minute each.

- cigartime.html: There is a form on this page. I tested the form but inputting all relevant details and pressing 
submit. Then I tried leaving one field empty and the others filled and pressing submit. The email field was tested 
by enerting randon names without the @ sign as well. All tests came back as expected. There is also a Google map on
the page and I tested this by loading up the page and refreshing to see if the map loaded up each time.

- contactus.html: The image loads up properly by refreshing the page. I also clicked on each image and checked that 
it opens up into a new window so the user doesn't ever navigate away from the site. There is another form on this 
page. I tested the form but inputting all relevant details and pressing submit. Then I tried leaving one field 
empty and the others filled and pressing submit. The email field was tested by enerting randon names without the 
@ sign as well. All tests came back as expected. 

- whatsapp.html: Only a jumbotron on this page. It was tested byr loading the page up and reloading the page. No 
problems whle doing this.

- Browser Test:

* Google Chrome: GOOD

* Firefox: GOOD

* Opera: GOOD

* Safari: GOOD

* Edge: GOOD

* IE: GOOD

- Mobile/Tablet Test:

* Galaxy S5: GOOD

* Pixel 2: GOOD

* iPhone 5/SE: GOOD

* iPhone 6/7/8: GOOD

* iPhone 6/7/8 Plus: GOOD

* iPhone X: GOOD

* iPad: GOOD

* iPad Pro: GOOD

## DEPLOYMENT

Github was used for deployment

To publish the website, the following steps needs to be taken:

1. Open GitHub and go to your site's **'Repositories'**
2. Go to **'Settings'**
3. Scroll down until you see **'GitHub Pages'**
4. Under GitHub pages, click on the dropdown under **'Source'** and select the **'Master Branch'** option
5. A green box should appear with the following message 
**'Your site is published at https://jtwy23.github.io/cigar-caballeros/'**

[Deployment]: https://github.com/jtwy23/cigar-caballeros/blob/master/README/readme-images/deployment.JPG

![alt text][Deployment]

Clone Website
To clone the website to work locally, follow the steps below:
1. Go to the main page of the GitHub repository and click on the dropdown menu **'Clone or download'**
2. Copy the URL and go to your local IDE (Integrated Development Environment)
3. In the terminal of your IDE type in **'git clone'** and the paste the URL copied from step 2 
4. Press **Enter** and the clone will be created

## CREDITS

### Content

* All content was researched and written by myself.

### Media

* YouTube was used for the instructional videos.

* All images are my own.

### Acknowledgements

* Precious Ijege, my mentor, for all the help and guidance towards my full project.

* All Code Institute tutirs who have helped me through mispelled words and coding problems.

* [HackerThemes](https://hackerthemes.com/bootstrap-cheatsheet/) for helping me find all the classes I needed to 
implement bootstrap.

* Mike Choi at Boutique Smokes for some inspirational words on new world cigars.

* Matthew Yong for his README.md that allowed me to structure my own better.