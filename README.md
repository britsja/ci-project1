
# The Monkees Website - User Centric Frontend Development Milestone Project  

The Monkees website is the first project from Code Institute as part of the Full Stack Web Development Diploma.

In the project, the client being the band (The Monkees), wants a website for their current and future fans to stay up to date with the activities and media of the band.

The deployed project can be accessed on github pages at the following link: <a href="https://britsja.github.io/ci-project1/">The Monkees</a>

#

### **Table of Contents**

[User Experience](#user-experience)

[Features](#features)

[Features Left to Implement](#features-left-to-implement)

[Technologies Used](#technologies-used)

[Testing](#testing)

[Deployment](#deployment)

#
 
### User Experience

The client would like users to have the following experience and capabilities on the website:
- Current and potential fans should information on band activities as soon as they open the website
- Each section of the website should be accessable from the menu and have some clear separation
- Potential and current fans should get a general overview of who the band is and their members
- Upcoming gigs should provide information and links to Band gigs/tours in the near future
- Media content (Video and Audio) should be playable from the website
- Publicise the availability of the band to perform at events 
- Provide people a means to contact the band to perform at events
- Have social media icons on the website to promote the bands social media presence

#

### Features

The website is a single page site with different sections that are accessible from the menu or by scrolling down. The sections are:

- Menu bar - Band logo on the left and menu options on the right side
- Home - Slogan display, News from the band and social media icons.
- Meet the Monkees - A general overview of who the band is and introduction to the band members
- Upcoming Gigs - Dates, locations and links to tickets for upcoming tours and gigs
- Monkees Media - Audio and Video from the bands music that can be played from the website. Embedded Youtube videos
- Contact Us - Contact form where fans can request the band to perform at their next event.
- Footer - Social media icons and copyright information for the site.
#

### Features Left to Implement

- Contact Form - Connect contact form to a mailing system to generate emails to the band from the contact form
- Social Media - Social Media icons should direct users to the correct social media URL for the band
- Tour Tickets - Under the upcoming Gigs, the ticket links need to point to the correct ticket booking page.

#

### Technologies Used

- [HTML](https://www.w3.org/html/)
    - DOCTYPE of **HTML** is used for the markup of this project
- [CSS](https://www.w3.org/Style/CSS/Overview.en.html)
    - **CSS** used to style the project
- [JQuery](https://jquery.com)
    - The project uses **JQuery Version 3.2.1** to simplify DOM manipulation.
- [Bootstrap](https://getbootstrap.com/)
    - **Bootstrap 4.2.1** front-end component library used to style this project.
- [FontAwesome](https://fontawesome.com/)
    - **Fontawesome 5.6.3** used for social media icons

#

### Testing

Manual website testing was conducted to ensure the functionality of the site and the features are working as required. 

Testing conducted were as follows:

1. Menu items tested - going to each section as specified
2. Monkees News - Clicking on a news entry takes you to the corresponding section
3. The social media icons take you to the social media site but not to the band page on the social media site yet.

3. Browsers:
    - Tested site on both Chrome and Firefox web browsers

4. Responsiveness
    - Used chrome developer tools to test site responsiveness in various display sizes

#

### Deployment

Github pages was used to host the deployed project.
The project can be found at: https://britsja.github.io/ci-project1

To deploy the project the following steps were taken:
- Added the latest files to the Github repository:
    - ```git add .```
    - ```git commit -m "Changes made for GitHub Pages deployment"```
    - ```git push```
- On Github, on the project page, opened the Settings tab
- On the project settings page, went down to the "GitHub Pages" Section and selected "Master Branch" under the Source Dropdown.
- The GitHub Pages section will then display the URL to the hosted website

To clone this project, you can use the following command:
- ```git clone https://github.com/britsja/Interactive-Frontend-Development-Milestone-Project.git```

### Credits

**Content**
- Background information of the band was found on the wiki page and inspired the band information on this website: https://en.wikipedia.org/wiki/The_Monkees

**Media** 
- Some images were sourced by searching google for images with reuse rights
- Majority of the media (including the audio) was taken from the Code Institute repository: https://github.com/Code-Institute-Org/project-assets
- Video content is directly embedded from Youtube 

**Inspiration**
- Code Institute for providing the knowledge and challenge in creating this project.