Julius Ceasar
Julius Ceasar is a website that allows users to go into depth of the life Julius Ceasar. It will give a detailed timeline of Ceasar political career until his death. it also gives a showcase of legendary battles that influenced his life. View the live site <a href="">here</a>

Mockup

Features
Site wide
Navigation Menu
Contains links to the Home, Political Career and Legendary battles pages and will be responsive on all devices.xxxxx
This will allow users to easily navigate between the pages within the site on any size device.
Nav Menu picture

Footer
This will contain icons as links to social media websites that will open in new tabs. Icons will be accessible to the visually impaired who may be using a screen reader, by the use of aria labels. The second part of the footer will contain bibliography of the website where all the text and info comes from. 
This will allow the user to go to various social media where they can share the website. 
The Bibliography will allow user to go the sources of the website and go even more into depth into the life of ceasar.
Footer picture

Landing Page
Landing page image
This will be a collection of the hero images from the politcal career and legendary battle page. 
This will help to immediately show the user what the website is about.
Landing Page Image

Website information on 'Home'
Information about 'Julius Ceasar' and the websites purpose including an image of "julius Ceasor" of one of his honorary statues.
This information lets the user know what the site is about.

picture

Political Career 


Contact Form Received

will provide the user with a timeline of Ceasar political career. together with Basic information of what the different politcal positions are.



Adventures
Adventure Summary
Sections containing 2 photos of the trip, a paragraph about the trip and a link to the gallery page to see more photos.
The sections will give the user an overview of the adventures that Taco has been on and the links will take the user to the gallery page where the user can view all the pictures that have been uplaoded for that trip.
Adventure Summary

More details dropdown
Hidden sections at the end of each Adventure Summary that will show a more detailed description of the trip which may include more details about longer trips and information about places visited along the way.
These section will be hidden by default so that user can only see the summaries on the page when loaded but the user will have ability with this feature to click and view more details at the end of the summary. This will allow user to easily scroll through the page and only view details of trips that they want to read more about.
Details Dropdown

Existing Features
Responsive design
Hidden interactive sections on Legendary Battle page
Responsive gallery with filtering
3 legendary battles and information
Timeline of Political career

Features Left to Implement
xxx

xxx

Design
Wireframes



Technologies
HTML
The structure of the Website was developed using HTML as the main language.
CSS
The Website was styled using custom CSS in an external file.
Visual Studio Code
The website was developed using Visual Studio Code IDE
GitHub
Source code is hosted on GitHub and delpoyed using Git Pages.
Git
Used to commit and push code during the development opf the Website
Font Awesome
Icons obtained from https://fontawesome.com/ were used as the Social media links in the footer section.
wireframes were created using balsamiq from https://balsamiq.com/wireframes/desktop/#
Testing
Responsiveness
All pages were tested to ensure responsiveness on screen sizes from 320px and upwards as defined in WCAG 2.1 Reflow criteria for responsive design on Chrome, Edge, Firefox and Opera browsers.

Steps to test:

Open browser and navigate to Julius Ceasar
Open the developer tools (right click and inspect)
Set to responsive and decrease width to 320px
Set the zoom to 50%
Click and drag the responsive window to maximum width
Expected:

Website is responsive on all screen sizes and no images are pixelated or stretched. No horizontal scroll is present. No elements overlap.

Actual:

Website behaved as expected with the exception of switching to landscape view in Mozilla Firefox. Details can be found in Unfixed Bugs

Website was also opened on the following devices and no responsive issues were seen:

Oukitel C21 Pro
TCL 30 Pro
iPhone SE
Samsung Galaxy Tablet
Accessibility


Testing was focused to ensure the following criteria were met:

Color contrasts meet a minimum ratio as specified in WCAG 2.1 Contrast Guidelines
Heading levels are not missed or skipped to ensure the importance of content is relayed correctly to the end user
All content is contained within landmarks to ensure ease of use for assistive technology, allowing the user to navigate by page regions
All not textual content had alternative text or titles so descriptions are read out to screen readers
HTML page lang attribute has been set
Aria properties have been implemented correctly
WCAG 2.1 Coding best practices being followed
Manual tests were also performed to ensure the website was accessible as possible and an accessibility issue was identified.

Issue #1: Use of hidden check boxes and labels for the gallery filter and accordion on the gallery page were not accessible via the keyboard due to the property display: none;

Fix: I could not find a way to fix this issue with html and css alone so a tabindex of 0 was added to allow the label to be tabbed to and an onkeypress event to target and click the correct checkbox was implemented. Javascript code was taken from this Mozilla Doc

Issue #2: After keyboard controls were implemented, while testing the site with windows 'Narrator' screenreader, it was not clearly known what the purpose of the labels/checkboxes were. An aria-label label was added to the labels for screen readers to alert them that the labels were clickable and what their purpose was.

Lighthouse Testing
Home

Gallery

Adventures

Functional Testing
Navigation Links

Testing was performed to ensure all navigation links on the respective pages, navigated to the correct pages as per design. This was done by clicking on the navigation links on each page.

Navigation Link	Page to Load
Home	index.html
Aventures	adventures.html
Gallery	gallery.html
Links on all pages navigated to the correct pages as exptected.

Footer Social Media Icons / Links

Testing was performed on the Font Awesome Social Media icons in the footer to ensure that each one opened in a new tab and that each one had a hover affect of the orange branding color.

Each item opened a new tab when clicked as expected and correct hover color was present.

Footer Contact Information

Testing was performed on the phone number in the contact information section of the footer to ensure behaviour was as expected.


Validator Testing
HTML
No errors were returned when passing through the official W3C validator
Contact HTML Validator Results

Avdentures HTML Validator Results

Home HTML Validator Results

Gallery HTML Validator Results

404 HTML Validator Results

CSS
No errors were found when passing through the official (Jigsaw) validator
CSS Validator Results

Unfixed Bugs
Responsiveness of the website worked on all devices, screen sizes and orientation with the exception of landscape orientation on mozilla firefox. I was unable to resolve this bug on time but will address in a future release.

Deployment
Version Control
The site was created using the Visual Studio code editor and pushed to github to the remote repository ‘tacos-travels’.

The following git commands were used throughout development to push code to the remote repo:

git add <file> - This command was used to add the file(s) to the staging area before they are committed.

git commit -m “commit message” - This command was used to commit changes to the local repository queue ready for the final step.

git push - This command was used to push all committed code to the remote repository on github.

Deployment to Github Pages
The site was deployed to GitHub pages. The steps to deploy are as follows:
In the GitHub repository, navigate to the Settings tab
From the menu on left select 'Pages'
From the source section drop-down menu, select the Branch: main
Click 'Save'
A live link will be displayed in a green banner when published successfully.
The live link can be found here - xxxx

Clone the Repository Code Locally
Navigate to the GitHub Repository you want to clone to use locally:

Click on the code drop down button
Click on HTTPS
Copy the repository link to the clipboard
Open your IDE of choice (git must be installed for the next steps)
Type git clone copied-git-url into the IDE terminal
The project will now of been cloned on your local machine for use.

Credits
Timeline W3C schools
Code was used from this site to create the accordian effect on the politcal career page timeline section. Styles were changed to suit styling on my Website.

Code insitute
the code insitute curriculum was used to develop the entire website.

Media
all media were taken form free image sources and wikepidia. the sources can be found the in the Bibliography
