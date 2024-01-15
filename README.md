![Website logo](documentation/logo.png)

---

# Adamiani

### This site is designed as a vow renewal website to be used by those invited to the festivities.

Adamiani is an informative wedding-vow renewal website with the aim of providing the invited guests with a convenient, yet stylish, repository of information regarding the upcoming event. It provides value through its RSVP form, travel and accommodation details, contact details, and the celebration schedule. The development followed a mobile-first approach utilising Bootstrap 5, as many users would need to access the information on the go; when either travelling for the event of on the day itself.

![A mock-up image of the wedding website](/documents/websitename-mockup.png)

[Click here to access the site](https://amfairley.github.io/website_name/)

---

## Project Goals

### User Goals
- A website that displays well on different devices and is easy to navigate.
- Immediately know vital information about who is renewing their vows and where and when the event is being held.
- Easy to find contact information of the couple.
- Able to locate information regarding travel and accommodation options for the event.
- Positive and immediate feedback from the site such as hover effects to ensure a good user experience.
- Sufficient information about the event that attempts to answer all guest questions.

### Site Owner Goals
- Provide key event information to all the guests.
- Allow for digital RSVPs to reduced issues common to physical post (lost letters, postal delays etc.)
- Provide answers to frequently asked questions to reduce repetition if they were to respond to individual guests.
- Provide contact information to the guests for further queries.
- Promote the event in a way that encourages invitees to attend and RSVP.
- The website works well on desktops for guests that are exploring the site and works well on mobiles for guests that need to access key information whilst on the go.

### Developer Goals
- A well-designed website that stands out and catches the attention of the users.
- A website that is responsive where the function and design are not hampered by changing screen or device size.
- An easy to navigate website that stores information on separate pages that can be intuitively navigated to by the user.
- A website designed with accessibility in mind.
- A finished project that the developer would be proud to include in their portfolio.

## User Stories (UX)
### First Time Visitor Goals
1. As a First Time Visitor, I want to immediately know the purpose of the site, who is involved, and the time and location of the event so that I can make sure that I am on the correct site and add it to my diary.
2. As a First Time Visitor, I want the site navigation to be intuitive so that I can easily access the desired information.
3. As a First Time Visitor, I want to be able to RSVP to the event so as to inform the couple of my attendance.

### Returning Visitor Goals
4. As a Returning Visitor, I want to know the deadline by which I need to RSVP by so that I do not miss out on attending the event.
5. As a Returning Visitor, I want to see accommodation options near the event so I can plan my trip.
6. As a Returning Visitor, I want to see travel options to get to the event so I can plan my trip.
7. As a Returning Visitor, I want to be able to contact the married couple so as to pass on my congratulations or ask questions.
8. As a Returning Visitor, I want to see if my children are welcome at the event so I can arrange child care if needed.
9. As a Returning Visitor, I want to be able to check the dress code for the event so that I will not look out of place.
10. As a Returning Visitor, I want to be able to check what sort of gift I should bring so I can set myself a budget.

### Frequent Visitor Goals
11. As a Frequent Visitor, I want to be able to tell which page of the site I am currently on so I can know what the page is about at a glance.
12. As a Frequent Visitor, I want to see the itinerary for the day of the event so I am prepared for the event.
13. As a Frequent Visitor, I want to see social links so I can follow them for any updates or image sharing.
14. As a Frequent Visitor, I want to be able to check if there are any rules surrounding using social media at/for the event so I do not go against the wishes of the couple.
15. As a Frequent Visitor, I want to see background information on the couple so as to keep myself better informed.
16. As a Frequent Visitor, I want to be able to contact the married couple if I have any personal queries that are not answered in the FAQs.
17. As a Frequent Visitor, I want to be to check some Frequently Asked Questions to answer my question or inform me of things I have not yet considered.

## Five Planes of UX
### Strategy
- **What value does the project provide?** This wedding-renewal website allows guests to the event to see key information included, but not limited to:
	- Who the event is celebrating
	- When and where the event is
	- Travel and accommadation options for the event
- **What are the business needs?** The business in this case would be the couple arranging the event. Their needs would be:
	- Easy way to get RSVP responses
	- An FAQ page that answers basic questions, in order to reduce repeating answers to different invitees
- **Who is the target audience?** The target audience is the invited guests to the vow-renewal service.
- **What are the user requirements and expectations?**
	- An intuitive and simple navigation system.
	- Able to quickly and easily locate relevant information.
	- All functions and links work as expected.
	- External links open in a new browser tab.
	- Any embedded video or audio does not autoplay and has options to play, pause, adjust volume, fullscreen, and share.
	- The functionality and design of the website works regardless of screen size.
	- Contact information readily available.
	- Accessibility.
- **What information is required?** Through previous use of wedding websites, brainstorming, and discussions with friends and colleagues; the following are requirements for an all-encompassing wedding or wedding vow renewal website:
	- **Who?**: A clear indication of who is having the ceremony
	- **When?**: The time and date of the ceremony
	- **Where?**: The location of the ceremony, travel details, and accommodation recommendations
	- **Guests**: What is the dress code and is the event child-friendly?
	- **RSVP**: What are the meal options, when do I need to submit the RSVP by, and can I access this data after sending?
	- **Contact**: The contact details of the couple including social media
	- **Background information**: Background information on the couple and location
- Through research on other wedding websites and blogs; the following criteria were found to be suggested by [The Knot](https://www.theknot.com/content/what-to-put-on-your-wedding-website) and [Wedsites](https://blog.wedsites.com/include-wedding-website/):
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
Clickable links will have obvious changes when hovered over to offer clear feedback to the user. Any video content will have controls available to the user and will not autoplay or automatically replay. Any external links such as social media will open in a new tab. Any new content flowing down the page will utilise content hinting where appropriate.

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

#### Wireframes

### Home page
- [Desktop](docs/wireframes/homepage_desktop.png)
- [Tablet](docs/wireframes/homepage_tablet.png)
- [Mobile](docs/wireframes/homepage_mobile.png)

### About us
- [Desktop](docs/wireframes/aboutus_desktop.png)
- [Tablet](docs/wireframes/aboutus_tablet.png)
- [Mobile](docs/wireframes/aboutus_mobile.png)

### Travel
- [Desktop](docs/wireframes/travel_desktop.png)
- [Tablet](docs/wireframes/travel_tablet.png)
- [Mobile](docs/wireframes/travel_mobile.png)

### RSVP
- [Desktop](docs/wireframes/rsvp_desktop.png)
- [Tablet](docs/wireframes/rsvp_tablet.png)
- [Mobile](docs/wireframes/rsvp_mobile.png)

### FAQ
- [Desktop](docs/wireframes/faq_desktop.png)
- [Tablet](docs/wireframes/faq_tablet.png)
- [Mobile](docs/wireframes/faq_mobile.png)

### Surface 

#### Changes from Skeleton
- Collapsing the navigation bar into a burger menu on smaller screens did not look as good as I hoped; instead I kept the navigation icons with some hover effects. This works well, as there are only a handful of navigation icons.
- 

#### Colour Scheme
I used the colour #E7BCDE as a starting point due to it’s romantic nature and utilised [adobe’s colour wheel](https://color.adobe.com/create/color-wheel) to create the following colour palettes:

**Shades**

![shades](docs/images/colour_scheme_shades.png)

**Analogous**

![analogous](docs/images/colour_scheme_analogous.png)

**Complementary**

![complementary](docs/images/colour_scheme_complementary.png)

Chosen colours:
-	#E7BCDE for the background colour to the webpage, including header and footer content and a border around the main content. It is also used for font colour where the font needs to pop against a darker background; for example the hero-text on index.html.
-	#4A3C47 from shades due to it’s dark off-black nature allowing text to stand out clearly on a lighter background
-	#D0BCE8 from analogous for a lighter colour that will stand out against a darker background
-	#A87D9F from complementary for the background colour of hover-able items such as RSVP buttons and the items in the navigation bar
-	#E8C1BC was chosen for a light off-orange colour to be the background of the page sections. This colour was found through experimentation with the starting pink

Extra colours used:
-	#000 (black) was used in parts where the contrast with a lighter background needed to be increased 
-	#fff (white) was used sparingly in the website design
-	#fafafa this off-white was used to colour most of the font awesome icons used in page titles
-	#ff0000 (red) was used to colour the font awesome heart icons on the about us page

Social media links:
-	The hover effects given to the social media links takes them from in the style of the page to the style of the social media platform, representing the transition of one webpage to another when clicked.
-	The facebook icons were coloured with the facebook blue #1877F2 and a white background
-	The X/twitter icon was coloured with white text on a black background
-	The Instagram icon was coloured with black text on a white background to match the site’s favicon; as the actual logo is multicoloured and was not able to be replicated here

#### Typography

I researched elegant fonts typically used for romantic themes and constructed the following “font palette” for my site:

**[Sail](https://fonts.google.com/specimen/Sail)**:

![sail](docs/images/typography_sail.png)

The elegant lower case letters of Sail, combined with the flourishes on the capital letters lends itself perfectly to my legible site logo and was used for the logos both in the header and footer throughout the website. The back up typefaces provided were Times New Roman, Times, and Serif.

**[Courgette](https://fonts.google.com/specimen/Courgette)**:

![courgette](docs/images/typography_courgette.png)

Navigation bar items were styled with Courgette. This capital letters of this font is easy to read at a glance whilst still maintaining elegance. The back up typefaces provided were Times New Roman, Times, and Serif.

**[Meie Script](https://fonts.google.com/specimen/Meie+Script)**:

![meie script](docs/images/typography_meie_script.png)

The elegant flowing letters of Meie Script was used for the bride and groom names to convcey elegance and class. The back up typefaces provided were Times New Roman, Times, and Serif.

**[Parisienne](https://fonts.google.com/specimen/Parisienne)**:

![parisienne](docs/images/typography_parisienne.png)

Meie Script did not prove legible at smaller font sizes; so parisienne was used for section titles to achieve the same effect. The back up typefaces provided were Arial, Helvetic, and Sans-Serif.

**[Roboto](https://fonts.google.com/specimen/Roboto)**:

![roboto](docs/images/typography_roboto.png)

The text in the contact and hashtags for social media will used the Roboto typeface. This is the most popular font on google fonts, easy to read, and recognisable. The back up typefaces provided were Arial, Helvetic, and Sans-Serif.

#### Images
All images used were optimised using [adobe photoshop](https://www.adobe.com/uk/) and converted to .webp format for faster loading times using [cloud convert](https://cloudconvert.com/png-to-webp).

## Technologies Used 

### Languages

- [HTML](https://en.wikipedia.org/wiki/HTML)
- [CSS](https://en.wikipedia.org/wiki/CSS)

### Frameworks and Tools 

1. [Visual Studio Code](https://code.visualstudio.com/)
	* My IDE of choice for writing the HTML and CSS code for this project
2. [Git](https://git-scm.com/)
	* Used for version control
3. [Github](https://github.com/)
	* Used to store the code
4. [Bootstrap v5.3](https://getbootstrap.com/)
	* Used for its grid system and easier styling and responsiveness
5. [Font Awesome](https://fontawesome.com/search)
	* Used for the decorative icons throughout
6. [Hover.css](https://ianlunn.github.io/Hover/)
	* Used for the navigation bar hover effect
7. [Google Fonts](https://fonts.google.com/about)
	* Used to import typefaces
8. [Favicon](https://favicon.io/)
	* Used for the browser icon
9. [Chrome Dev Tools](https://developer.chrome.com/docs/devtools/)
	* Used for testing
10. [Balsamiq](https://balsamiq.com/wireframes/)
	* Used for producing wireframes
11. [Adobe Color Wheel](https://color.adobe.com/create/color-wheel)
	* Used for creating the colour scheme
12. [Pexels](https://www.pexels.com/)
	* Used for stock images
13. [Adobe Photoshop](https://www.adobe.com/uk/)
	* Used for image editing
14. [Cloud Convert](https://cloudconvert.com/png-to-webp)
	* Used to convert images from .png to .webp
15. [Hexadecimal to RGB converter](https://www.rapidtables.com/convert/color/hex-to-rgb.html)
	* Used for converting some colour schemes to rgb


## Features 

## Testing 

### HTML Validation 

### CSS Validation 

### Accessibility

### Device Testing

### Browser Compatability 

### Testing User Stories 

1. Number 1 user story example

| **Feature** | **Action** | **Expected Result** | **Actual Result** |
| ----------- | ---------- | ------------------- | ----------------- |
| Example Feature | Action Taken | What should happen | What did happen | 

## Bugs 

### Mistakes

- Commit nomenclature was altered starting with commit 26 to be more in-line with professional standards. Commits prior to this utilised past-tense language.
- Despite aiming for a mobile-first approach; a desktop first approach was actually taken in the development of this website. Due to my inexperience with HTML and CSS, I found it easier to imagine the layout of the website on desktop first and work towards mobile whilst I practiced and mastered CSS.

## Deployment 

### Deployment to GitHub pages

This site was deployed using GitHub pages following these steps:
- Once in the [GitHub repository](https://github.com/amfairley/adamiani), go to the Settings tab
- Under the **Code and automation** section on the left hand side; select **Pages**
- Ensure your build and deployment source is **Deploy from a branch**
- In the **Branch** section, click on the dropdown menu currently set to none and select the main branch
- Click save

You can fork the repository by going the [GitHub repository](https://github.com/amfairley/adamiani) and selecting **Fork** in the top right corner.

### Deploying Locally

To deploy locally; you can clone this project by typing `git clone https://github.com/amfairley/adamiani.git` into the terminal of your IDE of choice.

## Credits 

### Documentation 
- The code-institute [template](https://github.com/Code-Institute-Org/ci-full-template) was used in order to have necessary tools preinstalled

### Media

Most media images used were owned or created by the developer. Those that were not owned or created by the developer were taken from [Pexels](https://www.pexels.com) with credit to:

- [Craig Adderly](https://www.pexels.com/@thatguycraig000/)
    <details><summary>Index Reception Image</summary>
    <img src="assets/images/index_reception.webp">
    </details>
- [Carlos Pernalete Tua](https://www.pexels.com/@carlos-pernalete-tua-210498/)
    <details><summary>Travel Airplane Image</summary>
    <img src="assets/images/travel_airplane.webp">
    </details>
- [Artem Yellow](https://www.pexels.com/@artem-yellow-422929671/)
    <details><summary>Travel Svetiskhoveli Image</summary>
    <img src="assets/images/travel_cathedral.webp">
    </details>
- [Rene Asmussen](https://www.pexels.com/@reneasmussen/)
    <details><summary>Travel Reception Image</summary>
    <img src="assets/images/travel_reception.webp">
    </details>
- [Vishwanth PindiBoina](https://www.pexels.com/@vishwanth07/)
    <details><summary>Hotel Fancy Image</summary>
    <img src="assets/images/hotel_fancy.webp">
    </details>
- [Dids .](https://www.pexels.com/@didsss/)
    <details><summary>Mid-range Hotel Image</summary>
    <img src="assets/images/hotel_mid.webp">
    </details>
- [John Smith](https://www.pexels.com/@manualman32/)
    <details><summary>Budget Hotel Image</summary>
    <img src="assets/images/hotel_cheap.webp">
    </details>

### Code

The CSS for the sticky footer used in lines 79-86 of [assets/css/style.css](assets/css/style.css) was taken from [materialize css](https://materializecss.com/footer.html).

## Acknowledgements 