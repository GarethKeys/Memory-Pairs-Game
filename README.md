# Memory-Pairs-Game

This is a game I have created in order to showcase the Frontend developer and Javascript skills I have learned to date through the online Learning People Full Stack Developer course. My game is used to test the players memory by matching pairs whilst also educating them on the various freshwater fish species currently inhabiting the waterways of Ireland. I have added matching colours to the pairs to simplify the game for the younger generation of player.

## UX
***

My game is for all ages and genders to enjoy. I have allowed colour pairs to be matched as well as the fish species pairs. These include pictures of the fish as well as the name of the various species. The aim is to teach the gamer about the various fish species while also having some fun testing their memory. I have included multiple methods of contact into the footer of each page the hope of attracting some communication if there is an interest in the game and my skills showcase.

The style and layout of the game is kept simple with 3 different main layout colours. This is to prevent distraction from the cards and the imagery on the cards.

## Features of the Website
***

### All Pages

- **Background Image**: Stunning scenic background image of beautiful mountains, crisp calm water and reflections of light. I believe this image is an eye-catcher and a thought provoker which I feel my websites will be in the future. I want the visitor to be transported to a happy place while also learning a bit about me and my skillset along the way. Life and nature are very important to me, so I wanted to capture that in my website.
- **Vertical Navigation Bar**: I chose the vertical navigation option as It seemed most portfolio websites I studied used the standard horizontal bar at the top of the screen. I am aiming to get the point across I like to think outside the box and am not afraid to challenge myself to make a design different and standout from the rest. The Navigation bar is to the extreme left of the screen on larger devices, so as not to block or take away from the background image. I have also styled the Navbar to be transparent and allow the user to still see the background image. The navigation links within allow the user to move between pages on the website.
- **Collapsible Navbar**: On smaller devices below width 768px the navigation bar will collapse to a toggle button on the top right of the screen. This responsiveness allows the user to still have full view of the background image and full access to the navbar on smaller devices.
- **G.K. icon image**: I added an image at the top of the navbar with my initials and activated it to be clickable. When clicked from any page within the website it will return the user to the home page.
- **Mask applied behind text**: I have added a mask behind the text on each page to allow the text to stand out from the background image and be easily read. The colour styling of the text was also chosen to pop out from the colouring of the background image, but remain subtle enough to blend in with the overall theme.
- **Social media links**: Incorporated into the footer are clickable icon links (from Font awesome) to make contact with me (phone/email) or view my various social media sites (LinkedIn, Github and Facebook). I also added a link to my Resume/C.V. for potential employers to have a browse.
- **Contact me link**: I added an active link at the bottom of the footer on each page which opens a new window to send me an email and make contact if desired. This is an extra point of contact added to draw the visitor into reaching out to me and making contact.

### index.html
- This is very much a welcome screen for the user. The aim here is to welcome the visitor and provide a very brief description of who I am and where I am currently based. I also encourage the visitor to make contact if they are impressed by the setup of the website.

### about.html
- This page provides a more in-depth guide to the visitor about who I am as a person and a bit about where I have come from in life and in my career. My aim is to get across that I am a very experienced and confident trouble-shooter through my current and previous employments and I thrive in challenging environments. I also want to make it clear how important life and family-life are to me and have added the photograph of me and my youngest daughter (Gráinne) to show a snippet of my family life. I explain how I am currently on my learning journey with Learning People and the Full stack developer course. Also, how I am thoroughly enjoying it and the many challenges that come with it. I have added an active link to the learningpeople.com/uk website to showcase the learning opportunities available there.

### contact.html
- This is a basic contact form made up of 4 fields. These are Name, Phone number, Email address and a box for a personal message. The submit button currently does not have any function linked to it, so this will be added when I progress my knowledge in the Full Stack course.

## Features to be implemented in future

If I had more time to spend on the project and more experience with the various developer languages and tools I would like to add the following functionality:

- Add functionality to the navbar items, so they change colour when hovered over, plus remain a different colour when selected to let the user know without doubt which page they are currently on.
- Add some animation to the background graphic, so it comes to life and draws the user in to the image and the theme.
- Add functionality to the mouse, so it interacts with the background image when hovered over and moved around which will increase the UX for the visitor, enhance the visitor experience and extend the duration of the website visit.
- Add functionality to the "Contact me" link at the bottom of the footer. I would make this subtly change colour or flash to entice the visitor to click the link and make contact.
- I would like to add some sound to the page in the form of a background track, but also sounds when items are clicked, or pages are selected. This will improve the UX further and leave a lasting memory for the visitor.
- In the about.html page I would change the single photo for an active slide show of photos of my life and images of my various projects completed to date. These would be active and selectable by the user to get more detail on particular projects.
- In the contact.html I would add functionality to the "Submit" button. Currently this button is not active, so the data entered is not processed.
    - In the contact.html I would also like a pop-up message when the Submit button is clicked to thank the visitor for their details and for making contact. Also, to ensure the user I would reply soon.

## Technologies used
---

- **HTML 5**: 
    - The website uses HTML5 for the majority of the content.
- **CSS3**:
    - The website uses CSS3 to style the various elements and contents to improve the visual aspect and UX.
- **Bootstrap V5.3**:
    - My project uses Bootstrap's easy to understand flexible grid system and CSS to add the responsiveness needed to automatically adjust the layout to different device sizes. 
    - This was used for my vertical navigation bar, but also in the layout of each page to ensure it responded accordingly when switching between the various screen sizes and dimensions.
- **Javascript**:
    - The website uses the Javascript which is in built to the Bootstrap components to add some functionality.
- **Font Awesome**:
    - Font Awesome was used for the active icons added within the footer.
- **Cool text**: 
    - Cooltext website was used to create the G.K. icon at the top of the navbar.
- **Git**:
    - I used Git as the version control system for adding and committing changes made to my project in Visual Studio Code.
- **GitHub**:
    - I used GitHub as the remote repository to which I pushed and saved the committed changes on my website from Git. I also deployed my website using GitHub pages allowing it to be viewed in a live environment.


## Testing
---

- I tested the responsiveness of my website using Google Chrome's developer tools within the Inspect toolbar. This allowed me to display my website on the various different device types and screen sizes to ensure the responsive functionality was as it should be and layout was not corrupted.
- I discovered even though the responsiveness passed all layout testing using the Inspect developer tool, when I viewed the website using Safari on an iphone the layout was not OK. Further troubleshooting was required to ensure the responsiveness was OK within Safari environment also.

### Issues encountered

- **Vertical Navbar**: Choosing the vertical navbar was challenging as it split my pages vertically into columns which created some interesting responsive issues when switching between different device sizes. I learned a lot about Bootstrap functionality while troubleshooting these issues.
- **Background Image**: Adding the background image added a level of difficulty to the website. Due to the fact it is so detailed and colourful, text on the page was difficult to read when over-layed on it. To get around this I added a mask around the text to make it standout from the background image.
- **Contact From**: I had planned to split the form page into two columns with one column containing the form and the other containing a map with my address and contact phone number. When I implemented this, it looked too cluttered on the page, so I decided to simplify it to one column dedicated to the contact form. Visually I think this was the correct decision. Perhaps if the navbar was horizontally at the top of the page it would not be as cluttered with two columns.
- **Responsiveness**: I spent a lot of time playing around with the various Bootstrap5.3 setups to make the pages responsive while maintaining the layout. This was a learning curve and I have gained a lot of experience through doing this.
- **White space below footer**: When viewing the index.html and contact.html on desktop there was a large block of white space below the footer. This was due to not enough content in the main container to push the footer down. To resolve this I added padding-bottom to the background image.
- **Time available**: This was my biggest issue encountered. I have a full-time job and three children under the age of seven, so finding time in the evenings to dedicate to the project was difficult. In the end it makes it more rewarding the challenge I have met and overcome to complete the project.

## Deployment
---

I hosted my website on GitHub pages. In order to deploy my website, I used the following steps:

1. Using Visual Studio Code Source Control tooling I "Initialized the Git Repository".
2. Using Source Control Tooling within VS code I regularly staged and committed my coding changes to the main branch of Git repository on GitHub.

## Repository Link

https://github.com/GarethKeys/Personal-Portfolio

## GitHub Pages live site link

https://garethkeys.github.io/Personal-Portfolio/

## Credits
---
- Navbar layout guidance was taken from YouTube - "a designer who codes" (https://www.youtube.com/watch?v=3GNBl-v-ZHI)
- G.K. image icon was created using http://www.cooltext.com
- http://stackoverflow.com website was used for guidance on Bootstrap.
- http://mdbootstrap.com website was also used for guidance on Bootstrap and the footer design.
- Contact form design ideas were taken from YouTube videos by Divinector - https://www.youtube.com/@Divinector.
    - Also from https://getbootstrap.com website.
- Background image was taken from http://pexels.com




