# iDeal Bachata School

This is a website for a fictional dance school that teaches bachata. The website is primarily meant for prospective students, 
providing information about the courses on offer, along with a schedule, as well as copy convincing prospective students why 
they should dance, and why they should choose this school over others. 

This was created as an assignment for the Code Institute Full Stack Web Developer course following their modules on HTML, CSS, 
Bootstrap and User Centric Front-End Development.


## Demo

A live demo can be found here: [petter0619.github.io/milestoneProjectOne](https://petter0619.github.io/milestoneProjectOne)


## UX

### User Stories

As a newbie dancer who is thinking about dancing bachata (or just dancing in general) for the first time I expect to get an overview of 
what bachata is and why I should choose this school over others, as well as the benefits of dancing. I also expect the ability to sign up 
for classes.

As a prospective customer who has danced bachata before I expect to get an overview of the classes on offer, a reason to choose this school 
over others as well as a schedule clearly showing when the classes take place. I also expect the ability to sign up for classes.

### Strategy

My goal with the design was to create a professional yet minimalistic design that was easy for users to navigate that not only includes 
the basic course information but also incorporates certain marketing elements that I believe (based on my experience in marketing) every 
business should have:
* Copy to convince prospective customers why they should learn to dance (something that is often lacking on the websites of dance schools in Stockholm)
* Copy about why they should choose this school over the competition
* An opt-in form that exchanges information the user wants in exchange for a way to follow up later (email). 


### Structure

A one-page layout was chosen so that users will not have to load or navigate around a variety of different pages to find the 
information they are looking for. A one-page layout also presents all the information in its optimum order.

The top navigation will be fixed and provide links that allow the user to quickly jump to the sections they are interested in.

As for the structure of the content I decided to go with was to have a large header with a hero image, incorporating an opt-in 
form that exchanges some form of information that is valuable to someone who dances (or is thinking about) dancing bachata in exchange 
for a way to stay in touch with them (in this case email).

This will be followed by copy that presents the benefits of dancing, then a brief overview of what bachata is, followed by copy telling the potential customer what makes this dance school different.

This will be followed by brief descriptions of the different classes on offer.


### Skeleton

[Desktop wireframe](wireframes/wireframeDesktop.pdf)

[Mobile wireframe](wireframes/wireframeMobile.pdf)

[Tablet wireframe](wireframes/wireframeTablet.pdf)


### Surface

The blue/white/grey color scheme that was used is the same color scheme used by the website of the dance school iDance (idance.se). I chose this color scheme because I thought it looked good. 

Using background images for every other section makes the site look better than simply having one long white page. It also provides a break for the eyes as opposed to having image after image which I find can become slightly overwhelming.

Boxes with white backgrounds were used for text in image sections because text that is overlaid directly on an image is harder to read.

The design for the weekly schedule was chosen because it provides a relatively clear overview of when the classes take place without incorporating a lot of blank space which a design that shows a full 24 hour day would have (since no classes take place during the daytime).


## Technologies

Main:
1. HTML
2. CSS
3. Bootstrap (version 4.4.1)

Some Javascript was also added in order to make the modals appear upon submission of the contact and opt-in forms.


## Features

### Existing features

* Responsive design. 
* Fixed top navigation (built using Bootstrap) that collapses into a so called “burger menu” on smaller devices
* Responsive opt-in and contact forms.
* The schedule is custom coded but was inspired by a design from the website Dansasalsa.se


### Features left to implement

* If the website was to be developed further some features I would like to add would be:
* On mobile devices the longer text sections become very scroll intensive. Adding a “read more” function that collapses part of the text would be useful on smaller devices.
* Have a message window open when clicking the email icon in the footer.
* If this was an actual dance school I would use a custom demo video that would be played in a modal on the website. Linked to the video on Youtube because it is third party content.


## Testing

If you try to submit the opt-in form with an invalid email address, there will be an error noting the invalid email address. Furthermore, the 'required' attribute is added to the 'name' and 'email' fields, so if those fields are not filled in, the form will not submit. If all field are valid a modal will appear thanking the user for testing the website and explain that it is a fictitious website. This was tested by manually filling in and submitting the form.

If you try to submit the contact form with an invalid email address, there will be an error noting the invalid email address. Furthermore, the 'required' attribute is added to the 'name,' 'email,' and 'message' fields, so if those fields are not filled in, the form will not submit. If all field are valid a modal will appear thanking the user for testing the website and explain that it is a fictitious website. This was tested by manually filling in and submitting the form.

All internal links in the top menu that point to sections of the page have been manually tested to ensure that they are pointing to the correct destination.

Most external links will open in a new tab using 'target="_blank"'. The phone and email icons in the footer open modals that thank the user for testing the website and explain that it is a fictitious website. All links have been manually tested to ensure that they are pointing to the correct destination.

This site was tested across multiple browsers (Chrome, Safari, Internet Explorer, FireFox) and on multiple mobile devices (iPhone 5: Chrome and Safari, iPad 1: Safari) to ensure compatibility and responsiveness. Most responsiveness testing was done using the Developer Tools in Google Chrome. During the testing phase, I realized the following: 
* The header did not look right when viewed in landscape view on mobile devices because the width used for the mobile media query was designed for when the device was viewed in portrait mode. Another media query was added to address this issue.
* The background images, as well as some of the layout properties will not render on the iPad 1 Safari browser. This issue is still present.
* Background-attachment: fixed; was not compatible with the Safari browser on iPhone 5; the background photos appeared zoomed-in and blurry. To fix this, the background-attachment: scroll property value was added in the media query for screens belo 540px. No access to current iPad in order to test if this is an issue there (Chrome Developer Tools view for iPad and iPhone 5 both rendered background images as expected with background-position: fixed;).


## Deployment

This site is hosted using GitHub pages, deployed directly from the master branch. The deployed site will update automatically upon new commits to the master branch. Link to deployed site: [petter0619.github.io/milestoneProjectOne](https://petter0619.github.io/milestoneProjectOne)


## Credit

### Content 
* Most of the content used in the “Why Dance” section came from the following article: https://rebeccabrightly.com/top-10-reasons-nerdy-person-learn-dance/, with some alteration by me.
* The remaining content was written by me,

### Media
* The background images used all came from [stock.adobe.com](https://stock.adobe.com). A greyscale filter was applied to each one prior to upload using the [Lunapic.com](https://www.lunapic.com) online photo editing tool for a better effect after applying the blue overlay.
* The opt-in image was the thumbnail image of the Youtube video “[Top 10 Social Dance Etiquette Tips](https://www.youtube.com/watch?v=gj7_f8BAeRw)” by Interfusion Festival 
* The icons used on the site (menu, footer and list bullets) all came from [Fontawesome.com](https://www.fontawesome.com).
* The linked to demo video was created by Dance Space and Cornel Rodrigues and can be found on [Youtube here](https://www.youtube.com/watch?v=hCMAFEkyibc) 

### Acknowledgements: 
* [w3schools.com](https://www-w3schools.com) was often used as property reference throughout the project.
* [Fontawesome](https://www.fontawesome.com) provided the tutorial to replace the default list bullets with their icons.
* The idea of how to offset the top navigation anchor links to adjust for the fixed top menu came from the following [Stack Overflow tutorial](https://stackoverflow.com/questions/10732690/offsetting-an-html-anchor-to-adjust-for-fixed-header)
* The Javascript used to open the Bootstrap modal upon form submission came from the following [Stack Overflow tutorial](https://stackoverflow.com/questions/46054499/open-modal-bootstrap-on-submit-form)
* [iDance.se](https://www.idance.se) - For the color scheme
* [Dansasalsa.se](https://www.dansasalsa.se) - For the design of the schedule section 
* [Brendon.com](https://www.brendon.com) - For the layout of header hero image and opt-in box
* The [Code Institute example Readme.md file](https://github.com/Code-Institute-Solutions/StudentExampleProjectGradeFive/blob/master/README.md) for suggesting that background-attachment: fixed; was the reason background photos appeared blurry on iPhone5 Safari browser. I thought it was a case of older browser not being able to handle photo.

## Thank You

Thank you for checking out my website!

//Petter Carlsson