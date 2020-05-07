# Nick Dry Stone Walling 

Nick is the owner of a small drystone walling company. I have created this website to help give a professional perception to his company and increase sales and exposure.
 
## UX

As a user, I would expect to be ablt to find out a bit about the company, easily get in contact and see examples of the companies work.

- User must be able to easily contact the buisness.
- User must be able to fine out what dry stone walling is (difference from normal mortar walls?).
- User must be able be presented with the benefits of drystone walling.
- User must be able to see examples of pervious walling jobs completed by the company.

## Features

### Existing Features
- About us feature is a page where the user can learn a little bit about the company.
- User can call the buisness with the click of a button when on mobile - allows users easily contact the buisness
- User can contact the business straight from the website by filling our a form - This was achieved using https://formsubmit.io/examples/. I used 
the example with unique tokens then edited it and adding css styling. When a user fills out this form, an email is sent directly to the buisness.
- Gallery feature which a is a page where the user can see examples of completed jobs.
- This site uses the modal feature in BootStrap to be ableto present complete images to the user in a pop out light-box.


### Features Left to Implement
- Improve the form feature, so it send the user a confimiation email upon submitting the form.

## Technologies Used
HTML
CSS
Bootstrap (4.41)
FontAwesome

## Testing

### Testing approach
All testing was carried out on a range of devices and on multiple browesers (Chrome, Edge, Firefox & Safarr). The devices used for testing were a combination of 
pysical devices and using the emulator feature on chrome. Testing was carries out regularly throughtout the developments of the website, right from the beginning of the project.

To test this website I first began with functional testing of the user stories.

- User must be able to easily contact the buisness.
    - To test this I checked the the user can navigate the site easily and all link work. Note - The instagram icon doesnt take the user to an instagram page, this is because 
    I am waiting for the buisness to create their page.
    - I Tested the call call now feature on the burger menu work (Mobile only)
    - I Tested the contact form, by trying invalid input for the email address, this caused an error message. I also tested trying to spam the form by attempting to repeatedly 
    send fake inquiries and the user was unable to. I also checked with the owner of the business that he is receiving the email when users submit a form.
- User must be able to fine out what dry stone walling is (difference from normal mortar walls?).
    - This is achieved by information on the Home page and About us.
- User must be able be presented with the benefits of drystone walling.
    - This is achieved by information on the Home page and About us.
- User must be able to see examples of pervious walling jobs completed by the company.
        - This is achieved by the gallery page.

I then completes some User Accepance testing, mainly concentrating on the visual aesthetics of the site. As iphone5 is the smallest screen size 
of commonly used mobliles, I made sure the site look good on all pages for this site pages. I then choose a vareity of ither screen sizes,  
iPhoneX, Galaxy s10, iPad and Desktop view. All images are presented well across all
screen sized that it has been tested against. 

When Testing on iPhone, I found the gallery was displaying incorrctly. A fix for thi can be seen in the commits to my repositry.

## Deployment
This site is hosted by GitHub pages and deployed directly from the master branch. Site is published at 
https://jackthorntonfswd.github.io/Nick-Dry-Stone-Walling-Website/ and the GitHub Repositry is
https://github.com/JackThorntonFSWD/Nick-Dry-Stone-Walling-Website. The deployed site is updated automatically upon 
new commits to the master branch as the master branch was chosen to bee deployed in the repositry settings, then the GitHub Pages section. 
There must be a index.html file, this will be the home page.


## Credits

### Content
- All text content was written by myself
### Media
- 4 images were purchased from VectorStock.com the 3 images above each section on the home page, and the mouse image on the homepage.
- free image from pexels.com for the uderline of titles (all pages).
- Other images were given to me by the owner of the business.
