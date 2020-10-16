# Wepre Hall Website

## UX

As a local resident and having some interest in the local history after some research of the hall online, I discovered although there are various bits of information about the hall there is no one website dedicated to the hall itself. As the hall has been demolished my aim is to create a website to prevent the history of the hall being lost to time.

### User Stories

user 1: "I would like to know about the history of Wepre hall, why was it demolished?

user 2: "What did Wepre hall look like?"

user 3: "Where was the location of the hall and what is there now?"

user 4: "What are the visitor centre opening times?"  

### Strategy

As the site owner my goal is to consolidate all the past and present information about the hall into one place and provide users with this information in as simple a format as possible.  To achieve this, I aim to:
-	Give information of the history of the hall
-	Provide details of the present-day situation
-	Show pictures of what the hall used to look like
-	Give the halls location and visitor centre opening times

The target audience for the website is:
-	Local people wanting to know more about the history of the area
-	Visitors to the area looking for places to visit

### Scope

The website requirements and key functionality will include:

-	Users should be able to see a clear timeline of the history of the hall 
-	Users should be informed concisely what is now at the site of where the hall used to be
-	Image carousel of what the hall used to look like
-	Embedded map of the location of the site
-	Users should be given the opening times of the visitor centre
-	The approach should be within my current capabilities
-	Website should provide users with a clean and easy UX
-	Users shouldn’t be overwhelmed with too much information 
-	A contact me page

### Structure

The main objective of the website is to essentially provide information to a target audience of pretty much any age group or technical ability so it needs to be structured in as linear format as possible whilst still providing adequate information to the user.

### Skeleton

The website will contain 4 pages:
-	Home:  Image carousel, brief description of history and present day
-	History: Image, timeline of Wepre hall history
-	Visit: Image, description of the site now, visitor centre location and opening times. 
-	Contact: Image and contact form for people wishing for more information

Each of the pages will include:
-	Navbar: Will navigate between the pages
-	Footer: Links to wepre park website and leaflet download

#### Sketches

- <a href="assets/wireframes/Sketches.pdf" target="_blank" >Sketches</a>

#### Desktop Wireframes

- <a href="assets/wireframes/desktop-home.png" target="_blank" >Desktop Home</a>
- <a href="assets/wireframes/desktop-history.png" target="_blank" >Desktop History</a>
- <a href="assets/wireframes/desktop-visit.png" target="_blank" >Desktop Visit</a>
- <a href="assets/wireframes/desktop-contact.png" target="_blank" >Desktop Contact</a>

#### Mobile Wireframes

- <a href="assets/wireframes/mobile-home.png" target="_blank" >Mobile Home</a>
- <a href="assets/wireframes/mobile-history.png" target="_blank" >Mobile History</a>
- <a href="assets/wireframes/mobile-visit.png" target="_blank" >Mobile Visit</a>
- <a href="assets/wireframes/mobile-contact.png" target="_blank" >Mobile Contact</a>

#### Tablet view

The tablet view will be the same as the desktop view.

### Surface

Taking inspiration from the nationaltrust.org.uk as they will have a similar target demographic, use of strong pastel colours for header and footer that mix well with the images of the hall. And white space in-between content to aid readability 



## Features

- Navbar: Responsive Nav bar with logo and title on the left and page navigation on the right, which collapses into a burger icon when viewed on a mobile.

- Image Carousel: Large image carousel on home page, allows users to scroll through three hero images of the hall. 

- Timeline: Sets out history of the hall in a timeline down the page using custom attributes.

- Embedded Maps: Iframe to allow users to see the hall location on google maps.

- Contact form: A contact from with required fields and placeholders, with a submit radio button.


### Features to implement later

- I would like to add functionality to the form so that when the data is submitted it get sent somewhere, this is currently beyond my skill set.

## Technologies used

### Languages

- Html: Used for the site structure.

- CSS: Used for adding styles to the website.

- Javascript: Used for CDNs to JQuery for nav bar burger and for font awesome for title icons.

### Libraries

- Bootstrap 4 : Used for creating navbar, image carousel, opening times table and used the grid system layout to make the website responsive.

- JQuery: Used for implementing the navbar burger collapse feature.

### IDE And Version Control

- Gitpod: Used as IDE environment.

- Git: Used for verion control.

- Github: Used for verion control and hosting.

### Tools 

- [LogoMakr.com](http://LogoMakr.com) - Used for the creation of the logo.

- [Fontawesome.com](http://Fontawesome.com) - Used for title icons.

- [Google fonts](http://Fonts.google.com) - Used for the fonts.

- [Coolers.co](http://Coolers.co) - Used for help with deciding on colour scheme.

- [Google Maps](http://Maps.google.com) - Used for embedded map feature.

- [Realfavicongenerator.net](http://Realfavicongenerator.net) - Used for creation, implementation and testing of favicon.

- [Validator.w3.org](http://Validator.w3.org) - Used for validation of HTML code when testing.

-  [Jigsaw.w3.org/css-validator](http://Jigsaw.w3.org/css-validator) - Used for validation of CSS code when testing.

- [Google.com/test/mobile-friendly](http://Search.google.com/test/mobile-friendly) - Used for testing the website mobile responsiveness.

- Google Chrome DevTools - Used for testing website responsiveness 


## Testing

### Manual Testing

#### Home Page
- Tested all links to other pages work in the navbar.
- Tested all links work in the footer.
- Tested the carousel manually and automatically scrolls through 3 images. Left and right.
- Tested the carousel indicator bar, scrolls to image which is clicked
- Tested resposiveness in desktop, mobile and tablet views using Google Chrome Devtools.

#### History Page
- Tested all links to other pages work in the navbar.
- Tested all links work in the footer.
- Tested resposiveness in desktop, mobile and tablet views using Google Chrome Devtools.

#### Visit Page
- Tested all links to other pages work in the navbar.
- Tested all links work in the footer.
- Tested map is working.
- Tested resposiveness in desktop, mobile and tablet views using Google Chrome Devtools.

#### Contact Page

- Tested all links to other pages work in the navbar.
- Tested all links work in the footer.
- Tested name and message field respond with error "Please fill in this field" when left empty and send button pressed.
- Tested email field responds with error when email is written in an incorrect format.
- Tested resposiveness in desktop, mobile and tablet views using Google Chrome Devtools.

#### Friends and family

I requested some feedback from friends and family on the how website displays on there devices, so was tested on iphone 7, iphone 8, iphone 11, ipad and two laptop computers, the website looked good on all of these screen sizes. 

#### W3 Validators

- Passed the HTML validator on second attempt, after fixing a bug (see bugs).

![Image](assets/readme-images/html-validator-test.png)

- CSS validator had two errors (see bugs)

![Image](assets/readme-images/css-validator-test.png)

#### Mobile Friendly Test

- Passed the google mobile friendly test.

![Image](assets/readme-images/mobile-friendly-test.png)

### User Story Testing Outcomes

- user 1: "I would like to know about the history of Wepre hall, why was it demolished?  
These questions are answered on the history page.
- user 2: "What did Wepre hall look like?"  
Images of the hall are displayed on the home, history and contact page.
- user 3: "Where was the location of the hall and what is there now?"  
This is addressed on the visit page.
- user 4: "What are the visitor centre opening times?"  
This information can be found on the visit page.

### Bugs

- Burger icon drop down menu did not appear, to fix I found the answer on stack overflow and copied the code from there - I had to add some javascript to the pages this is mentioned in a comment above the code itself. 
 
- Footer links were underlined, to fix I added a css class and set: `text-decoration: none;`

- Carousel had white space either side, to fix I found the answer on stack overflow and added `img-responsive` bootstrap class to carousel HTML.

- Embedded maps wasnt responsive in all views, to fix I found the answer on OS training website and copied there `map-responsive` css classes.

- When testing in Devtools I found in the galaxy fold view the content text on the home page was encroaching into the footer, I found the problem was because I had added a height to the class for the content and that was stopping the bootstrap grid system from working. So to fix I removed the height property.

- Failed HTML W3 validator because I had the hero image as a section element with no headings, to fix changed it to an aside element.

- CSS validatior had 2 errors both were from the bootstaps CDN so could not be changed.

## Deployment

The website is hosted on GitHub pages on GitHub.com, where i saved all my repositories. The method I used for deployement was as follows:

- Logged into GitHub.com.
- Opened my repositories.
- Opened my Milestone 1 project repository.
- Under setting tab scrolled to GitHub Pages.
- Under source section selected branch > master and folder > root.
- Upon saving this my website was successfully deployed to  [https://rhysseddon.github.io/Milestone-1-Project/](https://rhysseddon.github.io/Milestone-1-Project/)



## Credits

### Features
- Took some inspiration for the footer from CI mini project with Bootstap 4. 

- Timeline feature was copied then altered from CI mini project with Bootstap 4 work history page.

- Contact form was copied then altered from CI mini project with Bootstap 4 contact page.



### Content

- The text on the home, history and visit pages was copied from the Wepre Park Wikipedia page everything else was written myself.
- The opening times were from the Old Hall Cafe Facebook page.

### Images

All images are from open source from either [https://pixabay.com/](Pixabay.com) or [https://www.pexels.com/](Pexels.com)

## Difficulties Encountered
The main problem I encountered was after deciding on building a website for Wepre Hall, I soon realised as the hall was demolished in the 1960s there was a very limited amount of pictures available and next to none of these were good enough quality. 
So I made the decision for decorative purposes I would substitute the old photographs for high quality images of similar settings. The original images of the hall and park are on the Wepre Park Wikipedia page and in the Wepre Park Leaflet and both can be found in the footer on the webpage.  

## Acknowlegements

