
# Milestone Project 1
## Reason For Site
This Website was created for the  purposes of completing the first Milestone Project for Code Institute's Full Stack Development course as well as to show off all of my skills and achievements.
It was built using the knowledge learned from the HTML, CSS and the User Centric Design module

*** 
## User Experience

### User stories

#### Goals for First Time Visitors

* As a User For The First Time, I want to easily understand the main purpose of the site
* As a User For The First Time, I want to be able to easily navigate throughout the site to find content.
* As a User For The First Time, I want to view the website and content clearly on my mobile device.
* As a User For The First Time, 

#### Goals for Returning Visitors

* As a Returning user, I want to order tickets online in advance of events so that I am garanteed entry.
* As a Returning user, I want to contact the organisation so I can request more information.

#### Goals for Frequent Visitors

* As a Frequent user, I want to check to see if there are any new upcoming events.
* As a Frequent user, I want to check to see if there are any new photos and media from the clubs activities.
* As a Frequent user, I want to sign up to the Newsletter so that I am emailed any major updates and/or changes to the website or organisation.

### Structure
There is a Navigation menu at the top of the Webpage that directs them to the relevant information
The Nav Menu will be collapsable on a Mobile device to make use of space on smaller devices.
The purpose of this is to fulfill user story:
> As a First Time user, I want to be able to easily navigate throughout the site to find content.

The Home Page will contain a small bio about the club.
The purpose of this is to fulfill user story:
> As a First Time user, I want to easily understand the main purpose of the site and learn more about the organisation.

Custom CSS and/or Bootstrap will be used to make the Website responsive by the use of media queries and/or the Boostrap Grid system.

All pages will be responsive and the layouts will change dependant on screen size. This is to ensure content flow is appealing,
images are displayed properly and that the content is not shrunk side by side, so small that it is unreadable.
The purpose of this is to fulfill user story:
> As a First Time user, I want to view the website and content clearly on my mobile device.

All pages will contain a Footer Element with Contact Information, Event Booking and Social Media Icons. The icons used will be
from font-awesome. These are referenced below in the Frameworks-Libraries-and-Programs-Used section of this document. The event 
Booking section will not be visible on smaller devices. The aim of the Footer elements are to fulfill user stories:
> As a First Time user, I want to find ways to follow the HOTD Club on different social media platforms.<br>
> As a Returning user, I want to order tickets online in advance of events so that I am garanteed entry.<br>
> As a Returning user, I want to contact the club so I can request more information.

The About Page will contain The History of the Club, their current members, titles and personal bios. This page is to help 
implement user story:
> As a First Time user, I want to easily understand the main purpose of the site and learn more about the organisation.

The Events Page will contain information on upcoming and previous events run by the Club. There will be a booking form 
connected to this page. 
The purpose of this is to fulfull user stories:
> As a Returning user, I want to order tickets online in advance of events so that I am garanteed entry.<br>
> As a Frequent user, I want to check to see if there are any new upcoming events.

The Gallery Page will contain several Galleries with 8 photographs in each from various activities the club has engaged in.
The purpose of these galleries are to fulfill user story:
> As a Frequent user, I want to check to see if there are any new photos and media from the clubs activities.

The Contact Page will contain a form that can be used to contact the Club through the website. This will also contain a check 
box that will allow the user to sign up for the Clubs newsletter in order to keep up to date with the club.
The purpose of this Page is to fulfill user stories:
> As a Returning user, I want to contact the organisation so I can request more information.<br>
> As a Frequent user, I want to sign up to the Newsletter so that I am emailed any major updates and/or changes to the website or organisation.

#### Wireframes
Home Page<br>
![Home Page Wireframe](assets/wireframes/home-wireframe.JPG)<br>
About Page<br>
![About Page Wireframe](assets/wireframes/about-wireframe.JPG)<br>
Event Page<br>
![Events Page Wireframe](assets/wireframes/events-wireframe.jpg)<br>
Gallery Page<br>
![Gallery Page Wireframe](assets/wireframes/gallery-wireframe.JPG)<br>
Contact Page<br>
![Contact Page Wireframe](assets/wireframes/contact-wireframe.JPG)<br>

***

## Technologies Used

* HTML
	* This project uses HTML as the main language used to complete the structure of the Website.
* CSS
	* This project uses custom written CSS to style the Website.
* [Bootstrap](https://getbootstrap.com/)
	* The Bootstrap framework is used throughout this website for layouts and styling. The car
	* This has also been used to import JavaScript/Query used for the pop up Event booking modal
* [Font Awesome](https://fontawesome.com/)
	* Font awesome Icons are used for the Social media links contained in the Footer section of the website.
* [Google Fonts](https://fonts.google.com/)
	* Google fonts are used throughout the project to import the *Libre Baskerville* and *Cabin* fonts.
* [GitHub](https://github.com/)
	* GithHub is the hosting site used to store the source code for the Website and [Git Pages](https://pages.github.com/) is used for the deployment of the live site.
* [Git](https://git-scm.com/)
	* Git is used as version control software to commit and push code to the GitHub repository where the source code is stored.
* [FireFox Developer Tools]
	* Firefox's built in developer tools are used to inspect page elements and help debug issues with the site layout and test different CSS styles.
***
## Testing

### Test Strategy 

#### Summary 

Testing is required on MilestoneProject-1 – Hair O’ The Dog MCC Responsive Website.

As this project is static and contains no back-end functionality, the testing performed will be on the visual effects and layout of the Website. Testing to be done on at least three web browsers and all screen sizes.

No elements should overlap another container div. All elements should remain on the screen at all sizes above 300px. All carousel items should be controllable with the mouse as well as sliding on a timer. 

All nav links should direct to the correct html pages as per their names. The Home page is the exception, this one will redirect to index.html. 

All links to external websites must open in a new browser.


### Test Results
![Results](assets/images/readme-images/test-results.JPG)<br>
Testing results can be found [here](assets/test-results/test-results.xlsx)<br>
Please note these results are a .xlsx file and will require excel, google docs or compatiable program to open the file.<br>
All Pages were run through the [W3C HTML Validator](https://validator.w3.org/) and showed no errors.<br>
CSS Stylesheet was run through the [W3C CSS Validator](https://jigsaw.w3.org/css-validator/validator) and showed no errors.<br>
Website was tested by running locally and tested on the deployed version. No differences found.

* As a First Time user, I want to easily understand the main purpose of the site and learn more about the organisation. - Testing was performed to ensure Club information was displayed on the Home Page.
* As a First Time user, I want to be able to easily navigate throughout the site to find content. - Testing was performed on all Navigation links to ensure users can easily navigate the Website.
* As a First Time user, I want to view the website and content clearly on my mobile device. - Testing was performed to ensure the Website was responsive on all devices.
* As a First Time user, I want to find ways to follow the HOTD Club on different social media platforms. - Testing was performed to ensure Social Media links had been added to the Website.

* As a Returning user, I want to order tickets online in advance of events so that I am garanteed entry. - Testing was performed to ensure the Booking Modal(Alert on the top of Pages and Booking Button on Events Page) was functioning throughout the Website.
* As a Returning user, I want to contact the organisation so I can request more information. - Testing was done to ensure there was a contact form on the Website and that the Footer also contained contact information.

* As a Frequent user, I want to check to see if there are any new upcoming events. - Testing was done to ensure upcoming events were displayed on the Events Page.
* As a Frequent user, I want to check to see if there are any new photos and media from the clubs activities. - Testing was performed to ensure a gallery had been added with photos from the clubs activities.
* As a Frequent user, I want to sign up to the Newsletter so that I am emailed any major updates and/or changes to the website or organisation. - Testing was performed to validate a checkbox had been added to the contact form allowing users to sign up for the Club newsletter.

### Issues and Resolutions to issues found during testing
* Clicking the logo doesn't redirect to home page. This was resolved by updating the href on all Pages.
* Photo alignment issue on Home Page, this was fixed by adding bootstrap classes d-flex align-items-center and img-fluid.
* YouTube video on Events page was causing overlapping on small screens due to having a fixed size. This was resolved by removing fixed width and height and setting img-fluid in the div.
* Navigation menu items were being covered on smaller screens due to amount of items and text not shrinking. This was resolved by adding a media query between min width 576px and max width 654px that changes to a smaller font size.
* Spelling mistakes were found when proof reading, these were corrected.
* About page Meet the member section photos and text were overlapping on medium and below screens. This was fixed by correcting column sizes and adding class member-alignment with corresponding css styling.
* On extra wide screens content was being stretched across the entire width of the screen. This was fixed by changing container-fluid to container.
* Modal Booking form was accepting any inputs in fields. This was resolved by adding the required attribute to all fields.
* Carousel on Events page was expanding the full width of the screen, this was causing the images to be distorted and strected. This was resolved by by adding a maximum height and width to the containing div.
* On the Gallery page, the HR was sitting beside the title on large and medium screen sizes. This was resolved by wrapping the titles into a a div and assigning col-12 class.
***
## Deployment

* git add filename - This command was used to add fils to the staging area before commiting.
* git commit -m *commit message explaining the updates* - This command was used to to commit changes to the local repository.
* git push - This command is used to push all commited changes to the GitHub repository. 

***
## Credits
### Code
The code to style the check-box background color was taken from the comments of [Stackoverflow post](https://stackoverflow.com/questions/24322599/why-cannot-change-checkbox-color-whatever-i-do)

### Media
The photos and video used in this video are property of Hair O' The Dog MCC. Permission was granted to use all media files by Ronnie Robinson, club Founder.
The YouTube video on the events page is property of Marijus Ltu. Permission was obtained to use this video.

### Acknowledgements

I'd like to thank my mentor Spencer Baribell for his guidance throughout my project.<br>
Thanks to fellow classmate @Jay Bradley for helping me figure out how to link my TOC to headings with spaces.<br>
I'd like to give a special mention to past students Anthony and Mr_Bim_alumni who guided me and helped me learn to debug with developer tools whenever I faced alignment issues with my Website.<br>

## Comments
Git commits are showing up as two contributors, one as Your Name and one verified as Daisy-McG. This was caused by pushing without setting a signature for commits from VS Code, a signature was added on 25/10/2020 and all new commits are now verified. All commits were pushed by Daisy McGirr.