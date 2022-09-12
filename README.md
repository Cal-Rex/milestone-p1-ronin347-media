![amiresponsive render](../milestone-p1-ronin347-media/assets/images/readme/amiresponsive.png)
# RONIN 347
## Media Production and consultancy
<hr>
<br>

# CONTENTS
1. [INTRODUCTION](#introduction)
<br>

2. [UX](#ux)
   - stakeholder Interview
   - Competitor Review
   - Target Demographics
   - User Goals
   - Business Interview
   - Development planes
     - Strategy
     - Scope
     - Structure
     - Skeleton
     <br><br>

3. [Design](#design)
   - Colors
   - Typography
   - Imagery
   <br><br>

4. [FEATURES](#features)
   - Design Features
   - index Page
   - about Page
   - Portfolio page
   - FAQ Page
   - Conatct Page
   - 404 Page
   - 500 Page
   - Features to implement in future
  <br><br>

 5. [BUGS](#bugs)
 <br>

 6. [TECHNOLOGIES](#technologies)
    - Languages used
    - Frameworks
    - Libraries
    - Programs
<br><br>

6. [TESTING](https://github.com/Cal-Rex/milestone-p1-ronin347-media/blob/main/testing.md#-index-)
  - is contained as a seperate document [here](https://github.com/Cal-Rex/milestone-p1-ronin347-media/blob/main/testing.md#-index-)
   <br><br>

7. [DEPLOYMENT](#deployment)
    - step by step guide on how to deploy
 <br><br>

8. [CREDITS](#credits)
<br>

9. [ACKNOWLEDGEMENTS](#acknowledgements)
<br>

<hr>

# INTRODUCTION

This website was developed for the media production company _Ronin347 Media_.
Ronin347 Media focuses on delivering bespoke and affordable media, mainly aimed at the fitness industry, through the use of empirical knowledge garnered from working in both the fitness industry and acting/performance world.
This website targets potential customers for Ronin347 as its main demographic. This would include; but not limited to:
 - Personal trainers
 - Fitness product owners
 - Small independent businesses
 <br>

The concept for this build focuses on the existing media of Ronin347, creating an interactive portfolio and opportunity to contact. The focus is to showcase the quality of work created by Ronin347 in an accessible format that can be brought up on a phone during conversation, most likely out on a location or in a gym environment.
<br>
However; being a website, the site also contains features where visitors can contact the company.
<br>

As this Project has been primarily created for assessment purposes. The site utilizes a database storage link created by Code Institute, to allow for external working elements with regard to the contact form.
<br>

This project is the first of the five projects to be created for the Diploma in Full Stack Software Development (Common Curriculum).
<br>

In accordance with assessment guidance outlined by the Code Institute this project aims to achieve the following learning outcomes: 
<br>

**(_From the Code Institute Assessment Handbook for Portfolio Project 1_)**
<br>
 - "Design an interactive Front-End web application using HTML and CSS based on the principles of user experience design, accessibility and responsivity"
 - "Test a Front-End web application through the development, implementation and deployment stages"
 - "Deploy a Front-End web application to a Cloud platform"
 - "Maximize future maintainability through documentation, code structure and organization"
 - "Demonstrate and document the development process through a version control system such as GitHub"
 <br>
<br>

<hr>

# UX

## **| Stakeholder Interview |**
<br>

### **what are the main services of this company:**
<p><em>"Affordable cinematic promotional content for independent and small businesses, either narrative-based, documentary or tutorial content."</em></p><br>

###	**how does it differ from competitors:**
<p><em>“My background as an actor and my experience from being on film sets and some of the biggest theatre stages in the world allows me to bring the scale of that production rigour to smaller scale projects – industry leading standards for small scale businesses”</em></p><br>

### **What makes it special:**
<p></em>“my unique experience being on the other side of the camera and being in the clients position makes it easy for me to make them feel comfortable and relaxed. As an actor - I focus on the story they are trying to tell, so that the end product becomes a very personable and relatable narrative driven piece of media that demonstrates the real value of the client”</em></p><br>

###	**what would give him value by having this product out in the wild:**
<p><em>“have an online platform and online catalogue of resources that a client can easily access and see the quality and standard of work that I do, in addition to bridging the gap between ideas that I am verbally pitching to the client – as these could initially be quite grand, in terms of narrative, relatability and accessibility – having a visual representation would help consolidate ideas and pitches to clients. In addition to giving proof of that such ideas can be made real”</em></p><br>

### **What would add value to such a service:**
<p><em>“contact details, an faq would be really handy, anything to streamline initial dialogue and answer any questions prior to reaching out to me, other features like a gallery or a playlist of embedded videos would be ideal”</em></p><br><br>

## **| Competitor Review |**
<br>

### **https://www.christopherbailey.co.uk** 
does fitness photography and studio hire. Site has modern feel but a bit slow to load due to high amount of media, made as a desktop-first approach, some sizing could be done better.

#### **pros and cons of what they are doing**
**pros:**
* modern style focusing immediately on quality of work using content in design
* information is clear
* method of contact is clear

**cons:**
* enormous network payload
* limited alt text and labels
* some images not suitable at certain resolutions

#### **what are they missing**
* alt text and accessibility solutions

#### **what are they doing that could be done better**
* all of the cons listed are fairly simple fixes, down to webdesign.
<br><br>

<hr>

### **https://www.matt-thomas-photography.co.uk/**
focus on bodybuilding photography. has a more simple/intuitive layout compared to the above

#### **pros and cons of what they are doing**
**pros**
* clean and modern feel
* draws immediate focus to quality of product
* big focus on call to action/booking

**cons**
* very high demand on browser due to high data payload of highres images 
* limited alt text
* a lot of information on the first page to digest

#### **what are they missing**
* alt text and accessibility solutions

#### **what are they doing that could be done better**
* images could be optimized for site to reduce site load
<br><br>

<hr>

###	**https://1fitlife.com/**
focus on videography for fitness

#### **pros and cons of what they are doing**
**pros**
* index is concise with powerful imagery and good colourscheme
* links to partners and projects
* immediate method of contact

**cons:**
*	some imagery not optimized for web
*	some tooltips in all caps while others are not

####	**what are they missing**
*	congruence in some smaller elements

####	**what are they doing that could be done better**
*	some elements kind of sound the same, clearer titling or perhaps mergaing sections would be more ideal.
*	Fix imagery
<br><br>

<hr>

# Development Planes

## **| Strategy Plane |**
<br>

### **Target Demographics**
Talking with the client the, the target Demographic/s for this business are:
* Small independent Businesses
* Personal Trainers
* Sports oriented therapists
* semi-professional Athletes

<hr>

##  **User Stories**
<br>

### **Small Independent Businesses**
* _As a small business owner, I need to create some short instructional videos for our new staff in regard to some of our internal work systems_
*	_As a small business owner, I have a new product that I want to market and want to create some new media to promote this_
*	_As a small business owner, I want to know upfront how it will cost to create media for my potential projects_
* _As a small business owner, I want to document the development or trial run of a new product I am developing_

### **Personal Trainers**
*	_As a Personal trainer, I am looking to create a promotional video that I can advertise myself with online_
*	_As a personal trainer, I want to create a series of instructional workouts that I can sell in a package_

### **Sports Oriented Therapists**
* _As a Sports Oriented Therapist, i am looking to create some video media for my own website that demonstrates my specific services_

### **Semi-Professional Athletes**
* _As a Semi-professional Athelete, I want to document a trial or challenge that I am training for, which I can then publish or blog about._

## **Based on the User Goals, this website needs to achieve the following:**
* Demonstrate what this company does
* Showcase skills and portfolio of the company
* Show Pricing of different types of projects and packages
* answer any initial queries about creating such projects with the company
* Get in touch with the company to start a dialogue

## **Based on the stakeholder goals, this website needs to achieve the following:**
* inspire site visitors to contact the company
* answer any frequently asked questions prior to contacting
* Showcase previous work with partners and affiliates
* Link to existing partners to show ongiong healthy business relationships
<br><br>

## **| Scope Plane |**
<br>

Using goals discerned in the strategy plane, site features have been categorised into _Content_ and _Functional_ requirements:
<br>

**Content Requirements**
* Portfolio of existing content
* FAQ
* Pricelist
* Contact Form
* Links to affiliates
<br>

**Functional Requirements**
* Straightforward navigation
* linear narrative that leads to starting a dialogue
* concise information
* Immediate demonstration of value
<br><br>

<hr>

## **| Structure Plane |**

Given the Above information. Site structure was created with the focus of immediate demonstration of product value, which then leads to a point of contact, with an FAQ and Project Library supplementing the main page:
Site structure created in [Balsamiq](https://balsamiq.com/)
<br>

![Sitemap](assets/images/readme/site-map.png "Sitemap")
<br>

As the project developed, and after numerous meetings with the client business, the structure expanded and augmented to suit the client needs. As such, additional pages were added and names amended to suit the the purpose of the pages:
 - pages amended
   - Projects: renamed to portfolio
 - pages added
   - contact:
     - almost identical design to the contact section of the index, but now on it's own page due to evolution of the project (originally removed as per request of client, later re-instated for assessment purposes)
   - about:
    - The main page - as it was being built, begun to look too wordy. A decision was made to split the content into it's own page using the existing style created for all pages
    <br><br>

<hr>

## **| Skeleton Plane |**
<br>

Wireframes for the site were created in [Balsamiq](https://balsamiq.com/). Given that the company has high face-to-face interaction with potential clients on a daly basis, a mobile-first approach was adopted:

_smartphone wireframes_
![Smartphone Wireframes](assets/images/readme/wireframe-smaller-smartphones-iphone-se.png "Smartphone Wireframes")

_Tablet Wireframes_
![Tablet Wireframes](assets/images/readme/wireframe-tablet-ipad-mini-scale.png "Tablet Wireframes")

_Desktop/Laptop Wireframes_
![Desktop and Latptop Wireframes](assets/images/readme/wireframe-desktop-laptop-16x9.png "Desktop and Latptop Wireframes")
<br>

 - Contact information in the footer was removed in the final product at the wishes of the client.
 - Given that the site was taking a mobile first approach, the menu was revised during development so that accessability to all site areas was maximised without comprimising on display content. As such, a `fixed` `nav` expanding burger button was created for the top left corner, banner `nav` was removed.
 - FAQ was changed from a ropdown menu to visible blocks, as there wasn't enough content on the page to necessitate compartmentalising of information
 - due to time constraints, a contact confirmed page was never created, instead, the code institute form-dump link was used [https://formdump.codeinstitute.net/](https://formdump.codeinstitute.net/).
 - the link to the latest project button was updated to be an extra portfolio link, as the hero image became a video
 - the portfolio link was then moved to the left of the page so as to not clash with the `fixed` nav bar which is aligned right
 - the title on the index page was animated to disappear upon the video hero loading, as the video contains branding (index only)
 <br><br>

<hr>

# Design


## **| Colors |**
![Original Ronin Logo](assets/images/readme/old-ronin-logo.png "Original Ronin Logo")

The client's Original Logo was taken as inspiration to create a color palette for the site. the image was ran through [Colorimind.io](http://colormind.io/) to create a color palette

![Colormind Palette](assets/images/readme/colormind-palette.png "Colormind Palette")
<br>

The Palette was used as a guide to create colours, while the red and pink and off-white were adopted into the style, a solid black (#000000) was decided upon for easy implementation of external artwork and design features created outside of Git.
<br><br>


### **| typography |**

Taking the old Logo as a reference, Fonts were sampled from [Google fonts](https://fonts.google.com/) and new logo samples were created from the selected fonts. As the Original Logo fonts had specific rights reserved by the author, they could not be embedded within a website.

![Font samples](assets/images/readme/ronin-logo-swatch.png "Font Samples")

The final choices from the shortlist of fonts were:

| 'Teko' for `H1` | 'Michroma' for `H2` | 'Montserrat' for `body` |
| --------------- | ------------------- | ----------------------- |
| ![teko sample](assets/images/readme/teko-example.png "Teko Example") | ![Michroma Sample](assets/images/readme/michroma-example.png "Michroma Example") | ![montserrat example](assets/images/readme/montserrat-example.png "Montserrat Example") |

Given the client's interest in Japanese culture, and, to match the brand name, it was decided that the navigation menu should resemble somewhat of a sashimono banner.

To attempt to adopt this kind of style while giving the page a more modern look (which more aligns with the content), many serif fonts were experimented with. after a lot of painstaking deliberation, 'Times New Roman' fit the style the most.

|Example of Sashimono Banner from [The MET Museum](https://www.metmuseum.org/art/collection/search/23882)| Depiction of Sashimono banner sourced from [alamy.com](https://www.alamy.com/stock-photo/sashimono.html) | Rendition on site |
| ----- | ----- | ----- |
|![Sashimono banner](assets/images/readme/sashimono-real.jpg "Sashimono Banner") | ![Sashimono depiction](assets/images/readme/sashimono-diagram.jpg "Sashimono banner depiction") | ![Inspired navigation](assets/images/readme/sashimono-nav.png "Sashimono banner inspired navigation") |
<br>

### **| Imagery |**
<br>

Fortunately, all imagery was supplied by the client. so full consent for all imagery has been given.
Anything that wasn't supplied by the client was created in ProCreate, MS Powerpoint and MS Paint.

[ink line used to partition elements, as an example.](../milestone-p1-ronin347-media/assets/images/site-wide/ink-partition-4.png)
<br><br>

<hr>

# FEATURES

### **Consistent Design Features**
The following Design features are prevalent across all pages, with the exception of the 404 and 500 pages (and the index page with regard to the page header)
- **Background:** background on all pages has a slow 30 second animation where the background image scales down from `scale(1.1)` to `scale(1)` to give the site a cinematic feel.
   - backgrounds will also adjust to make sure desire focal point of image is always visible (where possible). 
   <br><br>

- **header:** contains the company logo and an H1 title separated with a grid feature. This allows for a responsive design. The texts adjusts to fit all tested screen sizes and logo always adjusts to fit within the viewing screen.
<br><br>

- **Navigation:** The Navigation element resides within a button that remains in a fixed position, regardless of the page being scrolled. meaning users can always access the navigation menu with a click or tap. The button also adjusts in size below resolutions under 1000px and becomes more compact to accomodate the drop and change in orientation of viewport real estate.
   - when clicked, the navigation menu expands into a vertical banner, each link is resonsive with slow expanding text to let the user know that the element is clickable/interactive.
   <br><br>

- **Body** text: With the exception of the index page (at mid-to-high resolutions), there is a blurred opaque background on all text boxes to ensure legibility and easy reading of all text.
<br><br>

- **Footer:** The footer is at the bottom of all conventional pages. it contains respoinsive social media buttons that highlight in the relevant social media brand colours when hovered over. 
   - a placeholder link is being used for twitter. as the client has not yet created a business twiter account. for assessment purposes it has reained on the page.
   - The Youtube links directly link to the client's youtube channel. but at this moment they have yet to upload any public material.
   - all social media links open in seperate tabs
   - there is also a link to the author's Github in the bottom left, and copyright information on the right. 
   <br><br>

<hr>

### **Index Page**
When this page loads, it first loads the background and body text, then after 1 second, the hero video scrolls down from the top, followed by swiping animation entry of the navigation button and portfolio button. This give the user a peak of the body text of the page, prompting the understanding that the page can be scrolled. This is especially useful, as on landscape devices, most of the time the hero banner will take up near all of the viewport. 
another minor prompt is added with the use of the ink partition aong the bottom of the video, further implying there is more below the hero video.
<br><br>

 - **Hero Video**
   - kept under 50mb to ensure web optimisation
   <br><br>

 - **Watch our portfolio**
   - this alternative link to the portfolio appears on the bottom left of the hero video. This is responsive to lower screen resolutions. On mobile, it changes to a red ink splash instead of black and aligns to the bottom right of the video. Changing it to a link that can be tapped and avoid a hover animation that would be obsolete on a touchpad device. 
   <br><br>

 - **Tell your Story**
   - This introductory page text gives a brief overview of the purpose of this site, it also gives prompts to different sections in the site with their intended use. links to the pages are also embedded in the body text in addition to the navigation bar for further call to action.
   - This section's margins adjust to always show the focal point of the background image. when this no longer becomes possible, a blurred background appears in the `div` housing the text to improve legibility. 
   <br><br>

<hr>

### **About Page**
This page uses a responsive grid layout that has a landscape design for larger screens and a portrait design for narrower screens. Images shift to accomodate the layout adjustment. all other features have already been listed in the **Consistent Design Features** section
<br><br>

<hr>

### **Portfolio page**
This page consists of multiple grids stacked as block elements to give a strong pattern and continuity with other pages. Like the About page, this page has landscape focused grids for each block. which adjust to portrait orientation as necessary when resolution shifts. Each Section contains branding or a background representing the company/person or topic it is about.
  - all videos on this page are sourced from the client's youtube.
  - videos are embedded from youtube in `iframe`s
  - videos embedded into iframes allows for responsive aspect ratio on videos as resolution adjusts
  <br><br>

<hr>

### **FAQ Page**
The most straightforward of all pages. Following the site wide design, each Question is stached in a margined block element, complete with all **Consistent Design Features** listed.
<br><br>

<hr>

### **Contact Page**
This page contains a singular block element housing the contact form. To have some congruence with site design. when a `text` input or `textarea` field is in `focus`, the style of the field changes to match the navigation style when it is in `focus`. The Button to submit the form also adopts the same styling, but on `hover` instead of `focus`.
  - **Contact form**
   - both the name and email field require information to be entered
   - the email field will only accept a valid email
   - form data is posted to [https://formdump.codeinstitute.net/](https://formdump.codeinstitute.net/) for assessment purposes.
   <br><br>

<hr>

### **404 Page**
following a different, but simplistic style to the rest of the site. this page calls to a meme that the client finds amusing. the page is simplistic, it displays the 404 error, then after 1 second, the [Pot of Greed](../milestone-p1-ronin347-media/assets/images/readme/pot-of-greed-pop.png) card is "played" on the page. it glows with a yellow border and scales slightly in size on `hover`. the prompt on the page tells the user to click it to return to the homepage. The card image is anchored to the Index.
 - This image was bought royalty free on [sketchfab.com](https://sketchfab.com/3d-models/pot-of-greed-yugioh-049d734aa46845ec9f74a5d2a8a16b05) ([proof of purchase](../milestone-p1-ronin347-media/assets/images/readme/pot-of-greed-pop.png)) and then edited into a card style using MS Powerpoint and MS Paint.
 <br><br>

### **500 Page**
Shares all same design features as 404, only one line of text is changed.
<br><br>

<hr>

## **| Features to implement in future |**
After testing and discussion with test users, the following features may be implemented int he future:
- add more transitions into the loading of background images and and general site imagery to make the loading experience appear smoother.
- Find a method to implement some adaptable styling to individuals who may acces the page using a "dark-reader" extension on their browser, so that the darker background images are not blacked out.
- more appropriate images could be used in the future or the pages. more pictures of the client doing some filming, however media like this was not available at time of development
- add a testimonials page separate from the portfolio page
- add a more in-depth contact form, may contain field such as "project details", "budget" and "length of project"
- add icons that consolidate what is being explained int he introductory text on the index. adding visual aid to the text and more clearly highlighting the services of the business.
- in the future maybe implement some more javascript to improve the smootheness of some of the animated elements.
<br><br>

<hr>

# BUGS

**index video does not autoplay on safari/iOS devices**
- tried resolving this with various suggestions across the internet. The common solution was to add `playsinline` to the `video` tag, however, while this makes the video playable, it does not enable an autoplay function.

**alignment and styling for screenwidth's below 300px**
- upon the last revision of the site body style, the background of the divs misaligns with the text when going below a width of 300px. While this could be fixed in the future easily with media queries, there was not enough time to fix this issue before the project submission date.

**some animations clip if hovered right on the edge of the element for too long**
- because a lot of the transitions and animations rely on changing of padding or changing absolute/relative position, animations can clip and repeat until unhovered, if hovered over the correct/incorrect point for too long
- elements effected:
  - navigation button
  - index hero portfolio button when on desktop resolution
  - pot of greed card on 404 and 500 pages

**index logo appearing/disappearing when manually resizing window**
- due to the transition animation assigned to the logo element, when manually sizing the page window, the logo can randomly appear and then fade, but due to the alignment (why it disspears in the first place), it overlaps other elements briefly before dissapearing. there was not enough time before the project submission date to further investigate this issue.
<br><br>

<hr>

# TECHNOLOGIES

### **Main Languages used**

- [CSS3](https://en.wikipedia.org/wiki/CSS)
- [HTML5](https://en.wikipedia.org/wiki/HTML5)
- [Markdown](https://en.wikipedia.org/wiki/Markdown)
<br><br>

### **Frameworks | Libraries | Programs**
<br>

**[Github](https://github.com/)**
- Used to store, deploy and publish site.
<br><br>

**[Gitpod](https://gitpod.io/)**
- Used to write and preview code, commit and push to Github.
<br><br>

**[Google Chrome](https://www.google.co.uk/chrome)**
- Used developer tools to check site responsiveness, preview site outside of gitpod, preview and make minor tweaks in real time to code without messing up original code during development.
<br><br>

**[W3C Markup Validation Service](https://validator.w3.org/)**
- Used to validate and format code.

**[Apple Procreate](https://apps.apple.com/gb/app/procreate/id425073498)**
- Used ot create the ink line used for partitions and the background for buttons
<br><br>

**[GIMP - GNU Image Manipulation Program](https://www.gimp.org/)**
- Used to convert images to .WEBP format.

**[MS Word](https://www.microsoft.com/en-us/microsoft-365/word)**
- Used to spellcheck and format text.
<br><br>

**[MS Paint](https://apps.microsoft.com/store/detail/paint/9PCFS5B6T72H?hl=en-us&gl=us)**
- Used to make 404/500 image.
<br><br>

**[MS Powerpoint](https://www.microsoft.com/en-us/microsoft-365/powerpoint)**
- Used to make 404/500 image.
<br><br>

**[ScreenRec](https://screenrec.com/)**
- Used to capture screen recordings of live site testing for testing.md.
<br><br>

**[Cloud Converter](https://cloudconvert.com/mp4-to-gif)**
- Used to convert screen captures into gifs to reduce file size in repo and testing.md.
<br><br>

**[Opera](https://www.opera.com/)**
- Used to test UX.
<br><br>

**[Firefox](https://www.mozilla.org/en-GB/firefox/new/)**
- Used to test UX.
<br><br>

**[Balsamiq](https://balsamiq.com/)**
- Used to create site wireframes.
<br><br>

**[Google Fonts](https://fonts.google.com/about)**
- Used to implement custom/bespoke fonts to site text and headings.
<br><br>

**[Fontawesome](https://fontawesome.com/)**
- Used to implement Custom Icons for social media links and also navigation button.
<br><br>

**[amiresponsive](https://ui.dev/amiresponsive)**
- used to create Example image at top of the readme

<hr>

## [TESTING](https://github.com/Cal-Rex/milestone-p1-ronin347-media/blob/main/testing.md#-index- "click here to jump to the testing.md") - Click to jump to the testing.md.


<hr>

# DEPLOYMENT
This Site was created, developed, manages and stored on Github and Gitpod.

The site is deployed on Github Pages, the following steps can be replicated to achieve the same result:
1. Sign up/create an account with Github (or, log in with existing details).
2. locate this repository (repo) by using the _search_ function.
3. once clicked into the the repo, click the settings cogwheel at the top right of the project.
4. navigate to the pages section.
5. Navigate to source, select `main` from the dropdown menu to designate what branch to deploy.
6. Once this has been selected, the page will refresh and the site will begin to deply. This could take some time.
7. once the page has been deployed you will be able to see it on the right hand side of the main repo page.
8. you can click into the deployment page and then click "view deployment" to ge the deployed link.

This project was developed using GitPod, which was then committed and pushed to GitHub using the GitPod terminal.

Deploying on GitHub Pages
To deploy this page to GitHub Pages from its GitHub repository, the following steps were taken:

Log into GitHub or create an account.
Locate the GitHub Repository.
At the top of the repository, select Settings from the menu items.
Scroll down the Settings page to the "Pages" section.
Under "Source" click the drop-down menu labelled "None" and select "Main".
Upon selection, the page will automatically refresh meaning that the website is now deployed.
Scroll back down to the "Pages" section to retrieve the deployed link.

<hr>

# CREDITS

Content and Media:
All Main media not created by myself was contributed by [Ronin347 Media © 2022](https://cal-rex.github.io/milestone-p1-ronin347-media/index.html)

Video iframe on main page:
[Ben Marshall](https://www.benmarshall.me/responsive-iframes/)

creating and uploading favicon:
[lcn](https://www.lcn.com/blog/beginners-guide-favicons/) - instructions on how to implement favicon
[faviconer.com](http://faviconer.com/) - for creating favicon

Javasciript to make interactive navigation button:
[w3schools: how to make an accordion](https://www.w3schools.com/howto/howto_js_accordion.asp)

Code:
The following sites were used as general rsources and reference for correct writing of code:
[Stack Overflow](https://stackoverflow.com/)
[W3Schools](https://www.w3schools.com/)
[css-tricks](https://css-tricks.com/)
[Adam-p on Github](https://github.com/adam-p/markdown-here)
[google.com](google.com)

<hr>

# ACKNOWLEDGEMENTS

- Many thanks to every individual on slack who helped tackle the bugs on my site as they cropped up
- Thank you to Chris Williams for helping me with placing my script
- Thank you to Lucy Woodman who helped me understand linking headings in markdown
- Thank you to Christina Myrvold for her meticulous critique of features on the site
- Thank you to Sarah Breen and Gemma Hammil, who tested the site rigorously on iOS devices
- Thank you to Code institute student care team for accomodating an extension on my time due to Covid-19
- Thank you to my partner for her patience with my obsessiveness over this project
- Many thanks to My mentor, Seun, for her guidance, even though due to my own poor time management i was unable to get a final mentoring session in before the deadline.
