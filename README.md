![Website logo](documentation/logo.png)

---

# Adamiani

### This site is designed as a vow renewal website to be used by those invited to the festivities.

Adamiani is an informative wedding-vow renewal website with the aim of providing the invited guests with a convenient, yet stylish, repository of information regarding the upcoming event. It provides value through its RSVP form, travel and accommodation details, contact details, and the celebration schedule. The development followed a mobile-first approach utilising Bootstrap 5, as many users would need to access the information on the go; when either travelling for the event of on the day itself.

![A mock-up image of the wedding website](/documents/websitename-mockup.png)

-[Click here to access the site] (https://amfairley.github.io/website_name/)

---

## Table of Contents

1. [User Experience (UX)](#user-experience-ux)
2. [Five Planes of UX](#five-planes-of-ux)
3. [Wireframes](#wireframes)
4. [Credits](#credits)

## User Experience (UX) <a name="user-experience-ux"></a>
### User Stories
* #### First Time Visitor Goals
	1. As a First Time Visitor, I want to immediately know the purpose of the site, who is involved, and the time and location of the event.
	2. As a First Time Visitor, I want the site navigation to be intuitive allowing easy access to desired information.
	3. As a First Time Visitor, I want to be able to RSVP to the event.

* #### Returning Visitor Goals
	1. As a Returning Visitor, I want to see accommadation options near the event.
	2. As a Returning Visitor, I want to see travel options to get to the event.
	3. As a Returning Visitor, I want to be able to contact the married couple.
	4. As a Returning Visitor, I want to see if my children are welcome at the event.
	5. As a Returning Visitor, I want to be able to check some Frequently Asked Questions to answer my question or inform me of things I have not yet considered.
* #### Frequent Visitor Goals
	1. As a Frequent Visitor, I want to see the itinerary for the day of the event.
	2. As a Frequent Visitor, I want to see social links for any updates or image sharing.
	3. As a Frequent Visitor, I want to see background information on the couple.
	4. As a Frequent Visitor, I want to be able to contact the married couple if I have any personal queries that are not answered in the FAQs.

## Five Planes of UX <a name="five-planes-of-ux"></a>
### Strategy
- What value does the project provide?
This wedding-renewal website allows guests to the event to see key information included, but not limited to:
	- Who the event is celebrating
	- When and where the event is
	- Travel and accommadation options for the event
- What are the business needs?
The business in this case would be the couple arranging the event. Their needs would be:
	- Easy way to get RSVP responses
	- An FAQ page that answers basic questions, in order to reduce repeating answers to different invitees
- Who is the target audience?
The target audience is the invited guests to the vow-renewal service.
- What are the user needs?
Through previous use of wedding websites, brainstorming, and discussions with friends and colleagues; the following are requirements for an all-encompassing wedding or wedding vow renewal website:
- **Who?**: A clear indication of who is having the ceremony
- **When?**: The time and date of the ceremony
- **Where?**: The location of the ceremony, travel details, and accommodation recommendations
- **Guests**: What is the dress code and is the event child-friendly?
- **RSVP**: What are the meal options, when do I need to submit the RSVP by, and can I access this data after sending?
- **Contact**: The contact details of the couple including social media
- **Background information**: Background information on the couple and location
Through research on other wedding websites and blogs; the following criteria were found to be suggested by [The Knot](https://www.theknot.com/content/what-to-put-on-your-wedding-website) and [Wedsites](https://blog.wedsites.com/include-wedding-website/):
    - Rules about social media
    - Local recommendations
    - Link to a registry

#### Viability and Feasibility
Followed is an analysis of the above value and user and business needs:
|   Task |   Importance | Viability/Feasibility |
| --------- | ------------- | ----------------- |
| Time and place information section | 5 | 5 |
| Travel and accommodation section | 4 | 4 |
| FAQ section | 5 | 5 |
| Contact details | 4 | 5 |
| Background information section| 3 | 2 |
| Social media links | 2 | 4 |
| RSVP form | 5 | 5 |
| Updates | 3 | 1 |
| Link to wedding register | 1 | 1 |
| Responsive on all devices | 5 | 4 |

### Scope

#### Content Requirements
A link to the wedding register is deemed unnecessary; as the celebration will include substantial travel for many guests and that their attendance would be gift enough. Likewise; the ability to receive updates to the event will not be considered here as it is outside the purview of this project.
A mobile-first approach is taken to ensure optimal performance on mobile devices and the Bootstrap 5 size limits will be considered when designing each section to make it suitable for all devices (phones, tablets, desktops). On top of this, a hamburger menu will be utilised to hide the navigation menu on smaller screen sizes.

The following proposed web-pages and sections will cover the remaining content and feature requirements established in the strategy plane:

##### Section: Navigation bar
- This section will be present on every page to create a cohesive structure across the site
##### Section: Footer
- This section will be present on every page to create unity across the site
- This section will house contact details, as to be available on every webpage
- The contact details will cover email address, whatsapp, and postal address
- Social media links will be grouped here
##### Webpage: Homepage
- The heading and hero image will convey the time and location of the event
##### Webpage: About Us
- This will house background information on the couple and their journey together
- Mixed media will be used to accentuate the story including images and video footage
##### Webpage: Travel/Accommodation
- This will house sections detailing travel and accommodation options
- Information will be emphasised using mixed media including images, a map, and links to different options
##### Webpage: RSVP
- This page will hold the RSVP form
##### Webpage: FAQ
- This will house a list of Frequently Asked Questions including dress-code and the child-friendly nature of the event
- There will be no images as to not detract from the information


### Structure
Each page will consist of:
- **Navigation bar**: Meeting the navigation requirement
- **Main section**: Meeting the requirements of the page
- **Footer**: Meeting the contact details and social media requirements

Required pages and their main sections:
- **Home**: Meets the time and place information requirement
    1. Header describing the title of the site and time and location of event
    2. Hero image of the couple
	3. Key information for the user about the ceremony
	4. Key information for the user about the reception
- **About Us**: Meets the the background information requirements
	1. Text of the back-story
	2. Images displaying the journey that the couple has been on together
	3. A video highlighting the original wedding
- **Travel/Accommodation**: Meets the travel and accommodation requirements
	1. Details of how to get there
	2. Map of the location of the event
	3. Details of accommodation recommendations
	4. Images of accommodation recommendations
- **RSVP**: Meets the RSVP requirment
	1. A central form consisting of:
		- Name 
		- Whose plus-one (if applicable)
		- Contact email
		- Dietry restrictions
		- Meal choices
		- A message for the happy couple
		- A song recommendation for the evening disco
		- A submit button
- **FAQ**: Meets the FAQ requirment
	1. Central Q/A paragraphs posing and answering FAQs
	2. Links to other parts of websites if the answers can be found there
	3. Contact information for any other queries

#### Information Architecture

Each page will use the same navigation bar and footer to create a consistent website design that is easy to use and pleasing to look at.
The navigation bar will consist of a site brand/logo linking to the home page and separete links to the other pages. In this way, the user can access the desired part of the website with a single click, well within the 3 click maximum that many websites adhere to.
There will be no sub-category navigation links within each webpage.

#### Interactive Experience
Clickable links will have obvious changes when hovered over to offer clear feedback to the user
Any video content will have controls available to the user and will not autoplay or automatically replay
Any external links such as social media will open in a new tab
Any new content flowing down the page will utilise content hinting where appropriate.

### Skeleton

[Balsamiq Wireframes](https://balsamiq.com/) was used during this section to create wireframes.


To maintain a pleasing layout and consistency throughout the website:
- All pages will follow the same layout to enable easy navigation for the user. They will consist of the same navigation bar arranged at the top of the page, the same footer arranged at the bottom of the page, and a central section providing the page information
- Sections within the pages containing elements will keep to the same size or keep within a ratio of sizes
- The rule of thirds will be kept to where possible 
- The navigation bar and the footer will be the same height
- On smaller (phone) screens the navigation bar will be reduced to a hamburger menu
- On tablet screens "Travel/Accommodation" will be changed to "Travel/Accom"

The **navigation bar** will be organised in the following order:
- Logo: On the top left of the navigation bar, following current accepted convention for its location, it will link to the homepage
- A home button: allowing the user to navigate back to the homepage without having to click the logo
- About us: Third on the navigation bar, allowing the navigation bar to follow the intuitve pattern for wedding websites of home/the couple/travel suggestions/RSVP/FAQ
- Travel: Fourth on the navigation bar, having the most useful information for the user when planning their trip, earning it a place above the RSVP and FAQ
- RSVP: Though important for the business (the couple), RSVP will be placed below the bulk of the information that the user (guest) would need to consult before deciding on their attendence 
- FAQ: Though quite high in importance to the user, this will be placed at the far right of the navigation bar, following current accepted convention, so that the user will intuitively look for it in this location	 

The **footer** will contain a logo, contact details, and social media links that will open in a new tab.
- On smaller (tablet and phone) screens the footer will not show the physical mailing address, as this takes up much needed room and is likely not a requiremnt for the user whilst on the go
- On smaller (tablet and phone) screens the footer will not show the logo, as it takes up too much space that could otherwise be used for more important information such as the contact details and social media links

The **homepage** will be split into four sections on desktop to be clear and conise; a hero image with key information overlayed, a ceremony details and image section (split 2:1), a reception details and image section (split 2:1), and an images section (split 1:1:1) to add some space between the information and footer.
- A link and reminder to RSVP will be included
- On tablet; the ceremony and reception information sections will be split 1:1 with the image, there will only be 2 images in the images section
- On mobile; the overlaid text on the hero image will instead appear below it. The ceremony image will be placed vertically above the ceremony details. Likewise with the reception details and image. The images section preceding the footer will contain only 1 image

The **about us** page will consist of a title with an image underneath and then 4 sections containing an image and text.
- The header section will use take up half of the page width and will be centred
- The text and image sections will also take up half of the page width and will be centred to create a pleasing column effect to the page  
- The images used to accompany the text sections will be small, stylised, and vertically centred
- The order of text/image will be reversed for each section giving the impression of pages in a book
- On tablet; the sections will be set to 100%
- On mobile; the images will be removed from the text sections and instead appear above the footer

The **travel/accommodation** page will consist of a heading, followed by three sections detailing flights, travel to the ceremoney, and travel to the reception. These three sections will be split equalling into a text element with the information, an image, and a map element. Each consecutive section will have the position of the map and image flipped. Before the footer there will be an accommodation section detailing hotel options for three budgets and links to the respective hotel websites.
- At tablet sizes the images will be lost for the flight, ceremony, and travel sections with the containing elements now taking up 50% of the width each
- On tablets the hotel options will be split over two lines, equally sized and centred on the page
- On mobiles the flight, ceremony, and reception details will appear above the map elements and the hotel options will appear on their own lines arranged vertically
- On mobiles the column width for content will take up 70% of the width

The **RSVP** page will consist of a title, a central RSVP form and a border image each side
- On tablet and mobile the border images will be moved to inside the title and below the RSVP form

The **FAQ** page will resemble the RSVP page but with a bootstrap accordion component housing the questions instead of a form


## Wireframes <a name="wireframes"></a>

### Home page
- [Desktop](assets/documentation/homepage_desktop.png)
- [Tablet](assets/documentation/homepage_tablet.png)
- [Mobile](assets/documentation/homepage_mobile.png)

### About us
- [Desktop](assets/documentation/aboutus_desktop.png)
- [Tablet](assets/documentation/aboutus_tablet.png)
- [Mobile](assets/documentation/aboutus_mobile.png)

### Travel
- [Desktop](assets/documentation/travel_desktop.png)
- [Tablet](assets/documentation/travel_tablet.png)
- [Mobile](assets/documentation/travel_mobile.png)

### RSVP
- [Desktop](assets/documentation/rsvp_desktop.png)
- [Tablet](assets/documentation/rsvp_tablet.png)
- [Mobile](assets/documentation/rsvp_mobile.png)

### FAQ
- [Desktop](assets/documentation/faq_desktop.png)
- [Tablet](assets/documentation/faq_tablet.png)
- [Mobile](assets/documentation/faq_mobile.png)

## Credits <a name="credits"></a>

#### Documentation
- The code-institute [template] (https://github.com/Code-Institute-Org/ci-full-template) was used in order to have necessary tools preinstalled
	

