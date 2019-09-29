# Milestone Project 1
## Introduction
The main purpose of creating this website is to share and promote support for local talent- particularly Jonathan Lim, an artist who depicts seemingly mundane local scenes into something emotional and beautiful. The website is a static one.

In this website, Jonathan is introduced along with his artworks. Even though these are scenes that many of us (Singaporeans) see in our daily lives, the artist is able to bring out another side of these scenes and give new perspectives that we seem to take for granted.

## Demo
A live website can be found here https://rachaelloh.github.io/Milestone-Project-1/

## UX/UI
### Project Strategy
| User Stories        | Description   |  
| :------------- |:-------------| 
| 1    | As a local artiste (singer/songwriter), I am looking for a potential collaboration with an artist for my album cover.|

-As a local artiste (singer/songwriter), I am looking for a potential collaboration with an artist for my album cover.  

-As a person who does not know about this artist’s works, I want to know who he is and the inspirations behind his pieces.

-As a Singaporean, I am interested to find out more about local productions.

-As a supporter, I wish to be kept updated of his works and upcoming exhibitions where I can go for. 

### Project Scope
The website will be designed based on the identified goals and hence placed in the following sections:

Home page- Landing page with carousel (image slides) and quotes by artist through interviews.

Bio page- Short “About” section to introduce the artist, contact form at the bottom of page

Features page- Some of the featured artist’s work will be shown in this page + video of an interview

Gallery page- More of artist’s artworks 

(i) Wireframes
Find below links for each wireframe I designed for each web page:
[Wireframe Document](https://www.google.com)
Upload onto your google drive, get a sharable link

[Index & Bio Page]()


## Project Skeleton - Features
**Existing Features**

Homepage
Features
-
-
-

Contact Page
-
-
-


-Basic styling of the website was taken from bootstrap which was further customized to suit the accessibility and aesthetics of the website. Stylings out of bootstrap was done through the use of CSS.

-Favicon placed in header of every page as an iconic image that represents the website, in this case it is about an artist, Jonathan Lim. The icon appears at the address bar of the web browser.

-Background attachment of artist’s work, another background attachment of artist with a short “About” section to introduce the artist, form at the bottom of page

-Animations used in the home page to display quotes by the artist, to evoke user’s interest in wanting to find out more about the artist and his work.

-Font used in quotes was selected to project the artistic feel of the website and easily captures the attention of users.

-The navbar has a fixed top so that it is more user friendly as users can easily access to the different pages without having to scroll back to the top.

-A navbar brand is also included where the logo of the artist is being placed on the left side of the navbar which links to the home page upon clicking.

-Carousel is used in the “Home” page to as a way of introduction to the artist.

-Icons are added in front of each navlink buttons to give more aesthetics to the website.

-Background attachments- alternation between fixed and scroll properties give an interesting effect to attract users.

-Form header includes an icon where it the text and icon will enlarge upon mouseover and back to normal on mouseout. Submit button changes color when hovered over. 

-A video of his interview will be embedded into the “Features” page

-Footer with icons links to social medias of the artist so that users can find out and follow the artist through other platforms. Icons will rotate and change color upon mouseover

**Feature(s) for Future Implementation**

-To make images in gallery page more fun by making the images to be of different sizes.

## Testing (Manual)
(i) Mobile Responsiveness
The website has been tested on **Windows destop/Macbook Air/iPad Mini/iPhone XS/iPhone 6** which covers various screen-size. The browsers used for testings are Google Chrome & Apple Safari.

During the testing process, I found out that:

-My images were not responsive when I tested on my iPhone XS as it was bigger than the view width. Hence, I changed the image width to be 100% and the height to be auto. The images are now responsive on the devices that I tested out on. On the features page, the footer, particularly the social media links moved to the next line due to the container. Hence, I excluded the container for the footer so that it has more screen space.

-My copyright portion on the footer seemed to shift to the right when I tested it on my iPad mini while it looked fine on the other devices. Hence, I tried to troubleshoot from my iPad. There were several layers of paddings/margins so I removed it and adjusted accoringly.

Feedback:
Insert screenshot of your website in mobile mode and in laptop mode.


(ii) Test Cases

| Test Case(s)      | Test Description   | Outcome | 
| :------------- |:-------------| :-------------| 
| 1    | User should be able to see x number of links on the navigation bar on the homepage. | Pass|
| 2    | When user clicked on Facebook button on the footer, the page will redirect to (link) | Pass|

All the links on the navbar will link users to the pages that they want to go. At the page that users are at, the navlink will be darker than the rest. When hovered over, the navlinks will have a translucent background to show that user's mouse is at the particular link.

All the social media buttons has been linked directly to artist's instagram page. The facebook icon links to artist's personal faebook page. The twitter logo links to the twitter sign in page (as 2 icons seem to be too little)

Since this is a static website, when users click on the submit button to submit their messages, they will not see their form being sent or being validated.

## Technologies Used
* [HTML5](https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/HTML5) - This was used to structure the layout of the website and build the pages.
* [CSS](https://developer.mozilla.org/en-US/docs/Web/CSS) - This was used to beautify the website and to apply styles on the html.
* [Javascript/JQuery](https://jquery.com) - This is used in conjunction with bootstrap to allow you to place things on your page that would normally require javascript knowledge.
* [Bootstrap](https://getbootstrap.com) - Bootstrap is used to ease the structuring and styles of some parts of the website.
* [Google Fonts](https://fonts.google.com/) - GoogleFonts are used to style the texts.
* [Font Awesome](https://fontawesome.com/) - Icons are taken from font awesome for my navbar, etc.

## Known Bug/Issues
## Deployment
My code was written using [AWS Cloud9](https://aws.amazon.com/cloud9/). AWS Cloud9 serves as the local repository which was then deployed to GitHub. Whenever a new commit is done to the master branch, the deployed site will be updated accordingly. To access the project on Github I would visit the GitHub web page and select rachaelloh/milestone-project. I will then click on settings and click master branch. When the master branch is selected, the deployed website will then be available as a clickable link.

This repository can also be deployed locally by cloning the repository. This can be done by going to the main page of the repository to clone/download directly into the editor of choice by pasting git clone into terminal.
## Credits
References were made mainly from [w3schools](www.w3schools.com), [Code Institute LMS](https://codeinstitute.net/), and [stack overflow](https://stackoverflow.com/) throughout the process of developing the website.

### Content
Bootstrap - I used some some codes from bootstrap such as the navbar and carousel; and allowed me to create my website with more efficiency.

[Material Design Bootstrap](https://mdbootstrap.com/) - I got my code from this website to customise the hamburger at the navbar.

[YP SG](https://www.yp.sg/whereartjon/) - Content of his interviews/quotes were taken from this website.

### Media

The images and background images/attachments used were taken from artist's [instagram](https://www.instagram.com/whereartjon/?hl=en) page.

### Design
Homepage inspirations from https://liamd88.github.io/milestone-project-1-eminem/

Social Media Links - [Bootstrap Social Icons](https://embed.plnkr.co/LpJLnT/)


**This is for educational use only.**
