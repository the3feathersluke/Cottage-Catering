## Introduction
# Cottage Catering 

Cottage Catering & Events is a local, family-owned catering and event planning business that prides itself on creating unforgettable experiences for every occasion. Whether you're hosting an intimate dinner, a large celebration, or a corporate gathering, Cottage Catering & Events offers personalized service and mouthwatering dishes that are sure to impress your guests.

As a company run by a friend of mine, I’m excited to be helping bring their vision online with this brand-new website. It’s designed to give you a glimpse into the exceptional services they offer, from delicious custom menus to seamless event coordination. Here, you’ll find everything you need to plan your next event with ease.

![](https://file%2B.vscode-resource.vscode-cdn.net/Users/Luke/Documents/vscode-projects/Cottage-Catering/Cottage-Catering/assets/read-me-images/image-1.png?version%3D1739109725662)

View the live site [here](https://the3feathersluke.github.io/Cottage-Catering/)



View Main Page [here](https://ui.dev/amiresponsive?url=https://the3feathersluke.github.io/Cottage-Catering/)


View Gallery Page [here](https://ui.dev/amiresponsive?url=https://the3feathersluke.github.io/Cottage-Catering/gallery.html)

View Contact us Page [here](https://ui.dev/amiresponsive?url=https://the3feathersluke.github.io/Cottage-Catering/contact-us.html)

View Success Page [here](https://ui.dev/amiresponsive?url=https://the3feathersluke.github.io/Cottage-Catering/success-page.html?first_name=luke&last_name=crampton&email_address=the3feathers%40gmail.com&message=message%0D%0A&event-type=dry-hire)

View 404 Page [here](https://ui.dev/amiresponsive?url=https://the3feathersluke.github.io/Cottage-Catering/indesx.html)




## User Experience
### User Stories

User Requirment 1

Homepage


- [ ] Eye-catching hero image showcasing beautifully presented food.
- [ ]•	Tagline: “Welcome to Cottage Catering & Events.”
- [ ]•	Brief introduction highlighting expertise in private event catering for weddings, parties, corporate                                                                
                 events, and more.
- [ ]•	Call-to-action button : “Contact Us.”
- [ ] •	Story about the company’s origins and passion for catering.
- [ ] •	Commitment to sustainability and local partnerships, if applicable.

Business Owner Requirment 1 

Events Page


• Clear sections for each type of event (e.g., weddings, Private Hire and Dry Hire options ).

• Information on past and upcoming events with pictures

• contains Testimonials from past clients to build trust.

User Requirment 2
Gallery
	

- [ ] •	High-quality images of past events showcasing diverse catering styles and food presentation.

Business Owner Requirment 2

Contact Page
	

- [ ] •	Simple contact form asking for name, event type, contact email and any specific requirements.	

Business Owner Requirment 3

Social Media Integration

- [ ] 	•	Social media icons (Facebook, Instagram, TikTok, etc.) in the footer for easy access.

User Requirment 3

Must be visible on all screen size types and responsive

## Design
The site needs to be user friendly and easy to navigate while still providing enough information to end user, the site is responsive on all screen sizes. 

### Colour Scheme
The color scheme was used from the colours of the existing business colours of sage green and cream these were then checked for visability using a contrast grid to ensure readability for the end user.
![Contrast checker](<assets/read-me-images/Contrast Checker.png>)
### Typography
the font was kept minamalsitic inline with the oweners requirements
### Imagery
imagery used was from existing photos owned by the company and used to showcase the services and events on offer


------------------

## Features 

### Site wide
* Navigation Menu
    * Contains links to the Home, Gallery, Events, Testimoniasls and Contact page and will be responsive on all devices.
    * This will allow users to easily navigate between the pages within the site on any size device. 

![Nav Menu](docs/readme_images/navigation_menu.JPG)
* Footer
    * This will contain icons as links to social media websites that will open in new tabs. Icons will be accessible to the visually impaired who may be using a screen reader, by the use of aria labels. The second part of the footer will contain contact information for 'Taco'.
    * This will allow the user to follow 'Taco' on various social media where they can get more up to date information that may not be displayed on the website. The contact information will allow the user to contact 'Taco' directly.

![Footer](docs/readme_images/footer.JPG)
* Favicon
    * A site wide favicon will be implemented with the Hair O' The Dog clubs emblem.
    * This will provide an image in the the tabs header to allow the user to easily identify the website if they have multiple tabs open.

![Favicon](docs/readme_images/favicon.JPG)
* 404 Page
    * A 404 page will be implemented and will display if a user navigates to a broken link.
    * The 404 page will allow the user to easily navigate back to the main website if they direct to a broken link / missing page, without the need  of the browsers back button.

![404](docs/readme_images/404_page.JPG)

### Landing Page
* Landing page image
    * This will be a collection of favourite images from some of 'Taco's Travels. Images will change on a timer. 
    * This will help to immediately show the user what the website is about and help to animate the page. 

![Landing Page Image](docs/readme_images/landing_page_image.JPG)
* Website information on 'Taco'
    * Information about 'Taco' and the websites purpose including an image of 'Taco' on his travels.
    * This information lets the user know what the site is about. 

![Bio](docs/readme_images/about_me.JPG)

* Contact form
    * A contact form will be implemented to allow users to contact 'Taco'. The form will consist of the following fields and attributes: 
        * First Name (required, type=text)
        * Last Name (required, type=text)
        * Email (required, type=email)
        * Message (required, type=textarea)
    * On successful submission of the contact form, the user will be navigated to contact.html displaying a success message.
    * This will allow user to contact 'Taco' if they have any queiries about travel destinations, charity events, club information or maybe to join him on some of his travels. 

![Contact Form](docs/readme_images/contact_form.JPG)

![Contact Form Received](docs/readme_images/contact_form_received.JPG)
### Gallery Page
* Gallery
    * The gallery will provide the user with photos of 'Taco's Motorcycle adventures from various trips and charity events. The gallery will be fully     responsive on all devices and allows the user to filter by categories provided in a sub navigation.
    * This will allow users that are interested in 'Taco's Travels to filter items based on the category they wish to be displayed. As the gallery is responsive it will allow the user to view content from any device. 

![Gallery](docs/readme_images/gallery.JPG)
### Adventures
* Adventure Summary
    * Sections containing 2 photos of the trip, a paragraph about the trip and a link to the gallery page to see more photos. 
    * The sections will give the user an overview of the adventures that Taco has been on and the links will take the user to the gallery page where the user can view all the pictures that have been uplaoded for that trip.

![Adventure Summary](docs/readme_images/adventures_summary.JPG)
* More details dropdown
    * Hidden sections at the end of each Adventure Summary that will show a more detailed description of the trip which may include more details about longer trips and information about places visited along the way. 
    * These section will be hidden by default so that user can only see the summaries on the page when loaded but the user will have ability with this feature to click and view more details at the end of the summary. This will allow user to easily scroll through the page and only view details of trips that they want to read more about. 

![Details Dropdown](docs/readme_images/details_dropdown.JPG)
### Existing Features

* Responsive design
* Contact form and success page
* 404 page


### Wireframes
<br>
Home page
<br><br>

![Home Page large screen](docs/readme_images/home_wireframe.JPG)

![Home Page small screen](docs/readme_images/home_mobile_wireframe.JPG)
<br><br>
Contact form successful submission page.
<br><br>
![Contact form submission success](docs/readme_images/contact_wireframe.JPG)

![Contact form submission success](docs/readme_images/contact_mobile_wireframe.JPG)


Adventures page
<br><br>
![Adventures page large screen](docs/readme_images/adventures_wireframe.JPG)

![Adventures page small screen](docs/readme_images/adventures_mobile_wireframe.JPG)

Gallery page
<br><br>
![Gallery page large screen](docs/readme_images/gallery_wireframe.JPG)

![Gallery page small screen](docs/readme_images/gallery_mobile.JPG)

404 page
<br><br>
![Gallery page large screen](docs/readme_images/404_wireframe.JPG)

![Gallery page small screen](docs/readme_images/404_mobile_wireframe.JPG)
<br><br><br><br>


## Features to be Added
In the future i would look to add a search section that will search for keywords accros the site so that users can easily navigte to a section they were looking for for example if a user was soley looking for information on wedinngs

Another future development could be able to see a calendar of availability to ensure that the catering unit is avialable on a specific date.

Another future development would be for users to add a review onto the site.

------------
## Testing
## Testing 

### Responsiveness

All pages were tested to ensure responsiveness on screen sizes from 320px and upwards as defined in [WCAG 2.1 Reflow criteria for responsive design](https://www.w3.org/WAI/WCAG21/Understanding/reflow.html) on Chrome, Edge, Firefox and Opera browsers.

Steps to test:

1. Open browser and navigate to [Tacos Travels](https://gareth-mcgirr.github.io/tacos-travels/)
2. Open the developer tools (right click and inspect)
3. Set to responsive and decrease width to 320px
4. Set the zoom to 50%
5. Click and drag the responsive window to maximum width

Expected:

Website is responsive on all screen sizes and no images are pixelated or stretched.
No horizontal scroll is present.
No elements overlap.

Actual:

Website behaved as expected with the exception of switching to landscape view in Mozilla Firefox. Details can be found in [Unfixed Bugs](#Unfixed-Bugs)

Website was also opened on the following devices and no responsive issues were seen:

- Oukitel C21 Pro
- TCL 30 Pro
- iPhone SE
- Samsung Galaxy Tablet

### Accessibility

[Wave Accessibility](https://wave.webaim.org/) tool was used throughout development and for final testing of the deployed website to check for any aid accessibility testing.

Testing was focused to ensure the following criteria were met:

- All forms have associated labels or aria-labels so that this is read out on a screen reader to users who tab to form inputs
- Color contrasts meet a minimum ratio as specified in [WCAG 2.1 Contrast Guidelines](https://www.w3.org/WAI/WCAG21/Understanding/contrast-minimum.html)
- Heading levels are not missed or skipped to ensure the importance of content is relayed correctly to the end user
- All content is contained within landmarks to ensure ease of use for assistive technology, allowing the user to navigate by page regions
- All not textual content had alternative text or titles so descriptions are read out to screen readers
- HTML page lang attribute has been set
- Aria properties have been implemented correctly
- WCAG 2.1 Coding best practices being followed

Manual tests were also performed to ensure the website was accessible as possible and an accessibility issue was identified.

Issue #1: Use of hidden check boxes and labels for the gallery filter and accordion on the gallery page were not accessible via the keyboard due to the property display: none;

Fix: I could not find a way to fix this issue with html and css alone so a tabindex of 0 was added to allow the label to be tabbed to and an onkeypress event to target and click the correct checkbox was implemented. Javascript code was taken from this [Mozilla Doc](https://developer.mozilla.org/en-US/docs/Web/API/HTMLElement/click)

Issue #2: After keyboard controls were implemented, while testing the site with windows 'Narrator' screenreader, it was not clearly known what the purpose of the labels/checkboxes were. An aria-label label was added to the labels for screen readers to alert them that the labels were clickable and what their purpose was.

### Lighthouse Testing

![Home](docs/testing/index_lighthouse.JPG)

![Gallery](docs/testing/gallery_lighthouse.JPG)

![Adventures](docs/testing/adventures_lighthouse.JPG)

### Functional Testing

**Navigation Links**

Testing was performed to ensure all navigation links on the respective pages, navigated to the correct pages as per design. This was done by clicking on the navigation links on each page.

| Navigation Link | Page to Load    |
| --------------- | --------------- |
| Home            | index.html      |
| Aventures       | adventures.html |
| Gallery         | gallery.html    |

Links on all pages navigated to the correct pages as exptected.

**Form Testing**

The form on the home page was tested to ensure it functioned as expected when correct data was input and when incorrect data was input. The following test scenarios were covered:

_Scenario One - Correct Inputs_

Steps to test:

1. Navigate to [Tacos Travels - Home Page](https://gareth-mcgirr.github.io/tacos-travels/index.html)
2. Scroll down to the form and input the following data:
   - First Name: John
   - Last Name: Doe
   - Email: doe.john@test.com
   - Comment: This is a test.
3. Click Submit
4. User should be redirected to contact.html confirmation page

Expected:

Form submits with no warnings or errors and user is redirected to contact.html confirmation page.

Actual:

Website behaved as expected with no errors or warnings and redirected to contact.html.

_Scenario Two - Missing Required Field First Name_

Steps to test:

1. Navigate to [Tacos Travels - Home Page](https://gareth-mcgirr.github.io/tacos-travels/index.html)
2. Scroll down to the form and input the following data:
   - First Name:
   - Last Name: Doe
   - Email: doe.john@test.com
   - Comment: This is a test.
3. Click Submit

Expected:

The form does not submit and an Error is displayed to tell the user that the field is required.

Actual:

Website behaved as expected, error message was displayed and the form did not submit.

_Scenario Three - Missing Required Field Last Name_

Steps to test:

1. Navigate to [Tacos Travels - Home Page](https://gareth-mcgirr.github.io/tacos-travels/index.html)
2. Scroll down to the form and input the following data:
   - First Name:John
   - Last Name:
   - Email: doe.john@test.com
   - Comment: This is a test.
3. Click Submit

Expected:

The form does not submit and an Error is displayed to tell the user that the field is required.

Actual:

Website behaved as expected, error message was displayed and the form did not submit.

_Scenario Four - Missing Required Field Email_

Steps to test:

1. Navigate to [Tacos Travels - Home Page](https://gareth-mcgirr.github.io/tacos-travels/index.html)
2. Scroll down to the form and input the following data:
   - First Name:John
   - Last Name: Doe
   - Email:
   - Comment: This is a test.
3. Click Submit

Expected:

The form does not submit and an Error is displayed to tell the user that the field is required.

Actual:

Website behaved as expected, error message was displayed and the form did not submit.

_Scenario Six - Incorrect email format_

Steps to test:

1. Navigate to [Tacos Travels - Home Page](https://gareth-mcgirr.github.io/tacos-travels/index.html)
2. Scroll down to the form and input the following data:
   - First Name:John
   - Last Name: Doe
   - Email: doe.johntest.com
   - Comment: This is a test.
3. Click Submit

Expected:

The form does not submit and an Error is displayed to tell the user that a valid email is required and the format it should be in.

Actual:

Website behaved as expected, error message was displayed and the form did not submit.

**Footer Social Media Icons / Links**

Testing was performed on the Font Awesome Social Media icons in the footer to ensure that each one opened in a new tab and that each one had a hover affect of the orange branding color.

Each item opened a new tab when clicked as expected and correct hover color was present.

**Footer Contact Information**

Testing was performed on the phone number in the contact information section of the footer to ensure behaviour was as expected.

_Steps to test Telephone Number_

1. Navigate to [Tacos Travels - Home Page](https://gareth-mcgirr.github.io/tacos-travels/index.html)
2. Click the phone number in the footer (01 123 456 789)

Expected:

A window is opened asking which device you would like to call from.

Actual:

Behavior was as expected and the window presented me with the following option to call:

- Oukitel Mobile Phone

_Steps to test Email Link_

1. Navigate to [Tacos Travels - Home Page](https://gareth-mcgirr.github.io/tacos-travels/index.html)
2. Click the email address in the footer (taco@gmail.com)

Expected:

A windows popup is displayed asking what application you would like to send a mail from or your default email application is opened.

Actual:

Behavior was as expected and my outlook application was opened ready to send an email to the target address.

### Validator Testing 

- HTML
  - No errors were returned when passing through the official [W3C validator](https://validator.w3.org)

![Contact HTML Validator Results](docs/testing/contact_validator.JPG)

![Avdentures HTML Validator Results](docs/testing/adventures_validator.JPG)

![Home HTML Validator Results](docs/testing/home_validator.JPG)

![Gallery HTML Validator Results](docs/testing/gallery_validator.JPG)

![404 HTML Validator Results](docs/testing/404_validator.JPG)

- CSS
  - No errors were found when passing through the official [(Jigsaw) validator](https://jigsaw.w3.org)

![CSS Validator Results](docs/testing/css_validator.JPG)

### Unfixed Bugs
Responsiveness of the website worked on all devices, screen sizes and orientation with the exception of landscape orientation on mozilla firefox. I was unable to resolve this bug on time but will address in a future release.


### Validation of Code
Insert screenshots of HTML, CSS and any other code files being tested in the relevant code validator - CSS validator might not validate newer CSS syntax - be careful to read and fully understand why it is giving you an error.

### Lighthouse
You can perform a test of your website for performance, accessibility, best practices and SEO through the google chrome lighthouse test - it is in your Dev tools. Bear in mind that your internet connection speed plays a part in the performance figures obtained. Where it scores low, it will give you suggestions on how to improve the site - read the suggestions and think about how to implement them - it could be a good idea.
Do this for both Desktop and Mobile.

### Wave Webaim - accessibility testing
You can test your site for accessibility through the wave.webaim site - it needs to be deployed in order for it to test it. Fix any errors that it gives

### Manual Testing

You need to perform, and document everything you did to manually test your site.
At a minimum - you need to check every link on every page works as intended.
So that is check every link in the nav bar (do this on every single page because its a link in a different file) and any other links that appear on your site.
Test the responsiveness of the site - you can do this in the dev tools in responsive mode.
You should also load the site once deployed on as many devices you have access to. What is different from one device to the next? why is it different?

Test the user stories that you created earlier in the readme - did you satisfy the goal, how?

To write up the tests you can use a table,
| Feature being tested | Expected Outcome | Testing Performed | Actual Outcome | Result (Pass or fail) |
| -------------------- | ---------------- | ----------------- | -------------- | --------------------- |
| enter details here | enter details here | enter details here | enter details here | enter details here | <- duplicate this line for each line you need

You should have tests for every section of every page.. individually.
-----------------

## Technologies

* HTML
    * The structure of the Website was developed using HTML as the main language.
* CSS
    * The Website was styled using custom CSS in an external file.
* Visual Studio Code
    * The website was developed using Visual Studio Code IDE
* GitHub
    * Source code is hosted on GitHub and delpoyed using Git Pages.
* Git 
    * Used to commit and push code during the development opf the Website
* Font Awesome
    * Icons obtained from https://fontawesome.com/ were used as the Social media links in the footer section. 
* Tinyjpg
    * https://tinyjpg.com/ was used to reduce the size of the images used throughout the website
* Favicon.io
    * favicon files were created at https://favicon.io/favicon-converter/ 
* balsamiq
    * wireframes were created using balsamiq from https://balsamiq.com/wireframes/desktop/#

### Version Control

The site was created using the Visual Studio code editor and pushed to github to the remote repository ‘cottage-catering’.

The following git commands were used throughout development to push code to the remote repo:

```git add <file>``` - This command was used to add the file(s) to the staging area before they are committed.

```git commit -m “commit message”``` - This command was used to commit changes to the local repository queue ready for the final step.

```git push``` - This command was used to push all committed code to the remote repository on github.

### Deployment to Github Pages

- The site was deployed to GitHub pages. The steps to deploy are as follows: 
  - In the GitHub repository, navigate to the Settings tab 
  - From the menu on left select 'Pages'
  - From the source section drop-down menu, select the Branch: main
  - Click 'Save'
  - A live link will be displayed in a green banner when published successfully. 


## Acknowledgements
To my mentor matthew boddin, who was always on callto help with any snags 

### Content 
 Permission was granted from the owner to use the images.

### Media

Website Logo was created by the owener using Canva.
