# MKFTS

## The Milton Keynes Federation of Traditional Shotokan

This is a website designed for MKFTS, a fictional karate club. It is a site with three aims in mind: first, to advertise to visitors that the club exists and where/when it can be accessed; second, to encourage and motivate a visitor to begin taking karate classes, through text and images; and third, to give visitors a little information about Shotokan karate in general. The site is targeted primarily towards those new to the hobby, but would contain information that would be useful for existing practitioners as well. MKFTS's main use would be to advertise club times and locations - the most important information for anyone visiting.

The site is designed to work on three different screen sizes, including Desktop, Tablet and Phone sizes.

## User Stories
As a newcomer to the hobby, I want (in order):
+ Visuals that give me a general idea of the club, and are eye-catching
+ Some questions/answers about why I would want to do this as a hobby
+ Information about the locations of clubs
+ Information about the times of clubs
+ Confirmation that the hobby is safe, that instructors are insured, etc.
+ The ability to get in touch should I not just want to turn up
+ Some extra information so I don't feel like I know nothing

As an existing member of the club, I want:
+ A reminder of information for organisation - where sessions are, when they are
+ The ability to get in touch with teachers between sessions

As a caregiver for a member of the club, I want:
+ Information that might help get my dependent to their club - where and when
+ Information about the adults I am trusting my dependent to
+ Knowledge that those adults are safe, insured, etc

## Features
This site comprises four pages: a home page, an 'about' page, a 'clubs' page and a 'contact' page.

### Common Features
All four pages have the following features in common:

#### Header with Nav Bar
![Header with Nav Bar](readme_docs/prototype/header.png "Desktop Home")
![Phone Header with Nav Bar](readme_docs/prototype/phone_header.png "Phone Home")

The header includes a text logo that is clickable, taking the user to the home page; and a menu with clickable links to all four pages. The curently-selected page is underlined, clearly indicating to the user where they are. This is identical across all four pages, and easily allows the user to navigate the website without becoming lost or using the 'back' button. For the phone, this will aim to include a hamburger-style menu which opens in a menu with the same four options and styling.

#### Hero Image
All four pages have a Hero image of identical size (with one small exception - see Contact for Desktop page). This image is consistent across three different screen sizes, although cropping may differ. This image also contains a box-out in blue that contains text in white, giving the full name of the site and also tying in to the key colour palette used throughout, in #104678 with 60% opacity. These hero images have a gentle animation, easing in, to catch the eye and assure the user that the website is functioning.

![Home page hero image](readme_docs/prototype/hero.png "Hero Image")

#### Footer
All four pages have the same social-media links in grey, in grey #7D7D7D.

![Footer](readme_docs/prototype/footer.png "Footer")

### Features Unique to the Home Page
![Desktop Home Page](readme_docs/prototype/desktop_home_prototype.png "Desktop Home") 
![Tablet Home Page](readme_docs/prototype/tablet_home_prototype.png "Tablet Home") 
![Phone Home Page](readme_docs/prototype/phone_home_prototype.png "Phone Home")

The Home page in all formats has, in addition to the common features, three or four 'why study karate' text areas. Tablet and Desktop have a central image; phone loses this image in favour of space-saving. Below this, four training sessions are called out - landscape on tablet and desktop, portrait on phone. These are click-through, taking the user to the Clubs page.

### Features Unique to the Clubs Page
![Desktop Clubs Page](readme_docs/prototype/desktop_clubs_prototype.png "Desktop Clubs") 
![Tablet Clubs Page](readme_docs/prototype/tablet_clubs_prototype.png "Tablet Clubs") 
![Phone Clubs Page](readme_docs/prototype/phone_clubs_prototype.png "Phone Clubs")

The Clubs page in all formats has, in addition to the common features, detail cards for three clubs. These cards include a portrait picture of the teacher for the club; text information detailing the time, location and cost of classes; and, taking up the same width as both the text and the picture, a Google Map embedded. On the Phone, these are displayed full-width in a vertical stack; on Tablet, there are two to a line, with the third centred; on Desktop, all three are displayed inline.

### Features Unique to the About Page

![Desktop About Page](readme_docs/prototype/desktop_about_prototype.png "Desktop About") 
![Tablet About Page](readme_docs/prototype/tablet_about_prototype.png "Tablet About") 
![Phone About Page](readme_docs/prototype/phone_about_prototype.png "Phone About")

The About page in all formats has, in addition to the common features, two text blocks that detail some interesting information for the user. Terms such as 'karate' and 'shotokan' may not be familiar to a newcomer; this page is primarily for these users. The second block of text also contains important information about DBS checks and first-aid certification. The first block is wrapped tightly around a square picture.

### Features Unique to the Contact Page

![Desktop Contact Page](readme_docs/prototype/desktop_contact_prototype.png "Desktop Contact") 
![Tablet Contact Page](readme_docs/prototype/tablet_contact_prototype.png "Tablet Contact") 
![Phone Contact Page](readme_docs/prototype/phone_contact_prototype.png "Phone Contact")

The Contact page in all formats has, in addition to the common features, a contact form featuring text inputs for Name, Email and Enquiry, as well as a Submit button. On Desktop, the Hero image is unclipped with the 'Contact us' section overlapping it. On both Tablet and Phone, the regular layout is preserved. The button is in #104678 to match the boxouts over the Hero images.

## Upcoming features
Gallery - currently not implemented, but would be a logical fifth page, linked from the Clubs page.

## Wireframe
### Home page
![Desktop Home Page](readme_docs/wireframes/desktop_home_wireframe.png "Desktop Home") 
![Tablet Home Page](readme_docs/wireframes/tablet_home_wireframe.png "Tablet Home") 
![Phone Home Page](readme_docs/wireframes/phone_home_wireframe.png "Phone Home")

### Clubs page
![Desktop Clubs Page](readme_docs/wireframes/desktop_clubs_wireframe.png "Desktop Clubs") 
![Tablet Clubs Page](readme_docs/wireframes/tablet_clubs_wireframe.png "Tablet Clubs") 
![Phone Clubs Page](readme_docs/wireframes/phone_clubs_wireframe.png "Phone Clubs")

### About page
![Desktop About Page](readme_docs/wireframes/desktop_about_wireframe.png "Desktop About") 
![Tablet About Page](readme_docs/wireframes/tablet_about_wireframe.png "Tablet About") 
![Phone About Page](readme_docs/wireframes/phone_about_wireframe.png "Phone About")

### Contact page
![Desktop Contact Page](readme_docs/wireframes/desktop_contact_wireframe.png "Desktop Contact") 
![Tablet Contact Page](readme_docs/wireframes/tablet_contact_wireframe.png "Tablet Contact") 
![Phone Contact Page](readme_docs/wireframes/phone_contact_wireframe.png "Phone Contact")

## Testing
### Test Cases
This section details testing runs that have been done on the project, including on different devices, browsers, against different user stories, and verifying that it meets the design criteria. Lighthouse in Chrome DevTools can be used to check usability and performance. Manual testing should include Expected outcome, Test performed, Result, and any Fixes.

### Bugs discovered
Any interesting or particularly difficult bugs can go in here, along with the steps taken to fix them.

## Code validation
W3C - https://validator.w3.org/

Jigsaw - https://jigsaw.w3.org/css-validator/

## Deployment
This section is for detailing the deployment of the site. For this project, this will be GitHub Pages. It should include all steps needed to run the content. It should also include steps needed to clone, install and run my code so that a future developer can contribute to my project. - also links to Github

## Credits
### Content
Text is written in its entirety by Steve Cook, with some inspiration taken from www.cfts-karate.co.uk

### Media
#### Images
Images for the wireframes of this site have been sourced from Unsplash through Figma, and can be found at the following addresses:


Images used in the site itself have been sourced through Pexels Stock Images and can be found at the following addresses:

https://www.pexels.com/photo/woman-doing-a-karate-pose-6005472/
https://www.pexels.com/photo/woman-in-white-judo-uniform-7045407/
https://www.pexels.com/photo/a-man-doing-a-karate-punch-7045749/
https://www.pexels.com/photo/man-breaking-a-board-8041997/
https://www.pexels.com/photo/man-people-woman-girl-7045607/  