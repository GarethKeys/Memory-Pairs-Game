# Memory-Pairs-Game

This is a game I have created to showcase the Frontend developer and Javascript skills I have learned to date through the online Learning People Full Stack Developer course. My game is used to test the players memory by matching pairs whilst also educating them on the various freshwater fish species currently inhabiting the waterways of Ireland. I have added matching colours to the pairs to simplify the game for the younger generation of player.

## UX
***

My game is for all ages and genders to enjoy. I have allowed coloured pairs to be matched as well as the fish species pairs to simplify the game. These include pictures of the fish and the naming of the various species. The aim is to educate the gamer about the various fish species while also having some fun testing their memory. I have added a total score display as well as two different levels of difficulty to enhance the gaming experience for each user. 

I have included multiple methods of contact for myself into the footer of each page with the aim of attracting some communication due to an interest in the game and my coding skills showcase.

The style and layout of the game is kept simple with 3 different main layout colours. This is to prevent distraction from the cards and the imagery on the cards due to over-complicated colours or design.

## Features of the Website
***

### All Pages

- **Page Styling**: I have styled each page in black, grey, and light blue. I chose these colours as I feel they work well together to make the cards standout while also not oversaturating the gamers vision with too many colours.
- **Horizontal Navigation Bar**: I chose the horizontal navigation option to always allow the gamer simplified control of the page. The Navigation bar is kept centered on the page for easy accessibility while navigating the game. I have styled the Navbar to be a slightly darker grey than the page, so it blends in enough but also stands out when needed. The navigation links within allow the user to move between pages on the website. The navigation items also highlight when hovered over for added effect and ease.
- **Collapsible Navbar**: On smaller devices below width 992px the navigation bar will collapse to a toggle button on the top center of the screen. This responsiveness allows the user to still have full access to the navbar on smaller devices.
- **Social media links**: Incorporated into the footer are clickable icon links (from Font awesome) to contact me (phone/email) or view my various social media sites (LinkedIn, Github and Facebook). I also added a link to my Resume/C.V. for potential employers to have a browse.

### index.html
- This is very much a welcome screen for the user. The aim here is to welcome the visitor and provide a very brief description of myself and what code was used to build the game. I detail the background of why the theme of fish was chosen and also the aim of the game. A final wish of good luck is to leave the visitor feeling positive before beginning the game.

### easy.html
- This page is the starter level of the game and very much the reduced difficulty level. I have reduced the number of cards to 4 in total to simplify the process of finding matches. This will suit the younger player and provide a "warmup" level for all gamers. I have included the "Score" output at the bottom of the page to tally up how many clicks were made on cards before all matching pairs are found. This score is in red colour to make it stand out from the rest of the page. I have also included a "restart" button in blue at the bottom of the page. The function of this button is to reload the page and hide all the cards again to begin the game once more. This button also resets the score to 0. 
The page has a title in black colour and underlined to remind the visitor of what the pictures of fish represent. 
I have included the following functionality to the page:
- cards increase in size when hovered over before being selected.
- if incorrect pairs are chosen then keyframes animation is introduced to vibrate the cards and alert of the mismatch.
- if a pair is mismatched the lower area of the card will also turn red in colour before they are rehidden behind the blue.
- if a pair is matched correctly the lower card area exhibits a green colour and the cards remain in the "turned up" position until the game is over.

### main.html
- This page has the same game functionality, but with the number of cards increased to 16 to add a higher level of difficulty. The page has the same title, score output and restart button functionality. It also has the same functionality introduced when selecting cards as the easy.html page.

## Features to be implemented in future

If I had more time to spend on the project and more experience with the various developer languages and tools, I would like to add the following functionality:

- I would like to add some sound to the page in the form of a background track, but also sounds when cards are clicked, or pages are selected. These would include different sounds for when a correct pair or incorrect pair is matched. This will improve the UX further and leave a lasting memory for the visitor.
- I would like to add the various cards to a json file and write some Javascript code to shuffle the cards after each time the restart button is pressed. This would add a further level of difficulty for the gamer to increase the longevity of the game.
- I would style the backsides of the cards more to look more like real playing cards and improve the visual aspect of the game.
- I would also introduce animation to flip the cards over instead of using the transparency functionality.
- I would also add a further level of difficulty with even more cards.
- I could also add a "high scores" page with cookie functionality to store the best scores and names of the gamers to date. This would be done using the form input method.
- I would also add a timer to start after the first click and stop after the last pair was matched.

## Technologies used
---

- **HTML 5**: 
    - The website uses HTML5 for the majority of the content.
- **CSS3**:
    - The website uses CSS3 to style the various elements and contents to improve the visual aspect and UX.
- **Bootstrap V5.3**:
    - My project uses Bootstrap's easy to understand flexible grid system and CSS to add the responsiveness needed to automatically adjust the layout to different device sizes. 
    - This was used for my horizontal navigation bar, but also in the layout of each page to ensure it responded accordingly when switching between the various screen sizes and dimensions.
- **Javascript**:
    - The website uses the Javascript which is in built to the Bootstrap components to add some functionality.
    - The website also uses Javascript for the functionality of card pairing and how clicks on the various cards are handled.
- **Font Awesome**:
    - Font Awesome was used for the active icons added within the footer.
- **Canva.com**:
    - Was used to create and design the various card images.
- **Git**:
    - I used Git as the version control system for adding and committing changes made to my project in Visual Studio Code.
- **GitHub**:
    - I used GitHub as the remote repository to which I pushed and saved the committed changes on my website from Git. I also deployed my website using GitHub pages allowing it to be viewed in a live environment.


## Testing
---

- I tested the responsiveness of my website using Google Chrome's developer tools within the Inspect toolbar. This allowed me to display my website on the various device types and screen sizes to ensure the responsive functionality was as it should be, and layout was not corrupted. 
- I also tested the game manually on an Iphone 8 and Iphone 12 phones as I was aware of some Safari display corruption issues from my previous project.

I used the https://validator.w3.org/#validate_by_input program to check my 3 HTML files with the following corrections:
- Moved the footer closing </div> to within the footer line 137.
- Removed the spaces withing the "fish-image" names.
- Corrected the extra speech mark " from line 100.
- Line 101 "Element button must note be descendant of <a> element", so removed the <button></button> tags and verified functionality to be OK with bootstrap button definitions.
- index.html line 51 closing p tag was <p/>, so corrected to </p>.
- Added lang=en attribute to each html tag at beginning of each html file.

I used the http://jigsaw.w3.org/css-validator/ to validate my 3 css files with the following corrections:
- .navbar and .heading had extra commas after the san-serif in font-family declaration which needed to be removed.
- withing the easy.css file p was double defined, so one was removed and functionality checked to be OK.
- All 3 .css files now return no errors.


### Issues encountered


- **Responsiveness**: I spent a lot of time playing around with the various Bootstrap5.3 setups to make the pages responsive while maintaining the layout. This was a learning curve and I have gained a lot of experience through doing this.
- **Stretching of footer**: When viewing footer on a laptop screen the footer was very stretched. I removed the CSS - min-height:100vh to resolve this issue.
- **Time available**: This was my biggest issue encountered. I have a full-time job and three children under the age of seven, so finding time in the evenings to dedicate to the project was difficult. In the end it makes it all the more rewarding to have met and overcome the challenges to complete the project.

## Deployment
---

I hosted my website on GitHub pages. To deploy my website, I used the following steps:

1. Using Visual Studio Code Source Control tooling I "Initialized the Git Repository".
2. Using Source Control Tooling within VS code I regularly staged and committed my coding changes to the main branch of Git repository on GitHub.

## Repository Link

https://github.com/GarethKeys/Memory-Pairs-Game

## GitHub Pages live site link

https://garethkeys.github.io/Memory-Pairs-Game/

## Credits
---
- Navbar layout guidance was taken from http://www.Getbootstrap.com webpage.
- http://mdbootstrap.com website was also used for guidance on Bootstrap and the footer design. Footer design was copied from my previous project and only the CSS modified slightly to suit the new colours.
- Card Javascript code guidance was taken from youtube page https://www.youtube.com/watch?v=B6aJpbX_IZU - Code Grind - "Creating a Memory Game using CSS and JavaScript!".
- Score output functionality and Restart button ideas were taken from youtube page https://www.youtube.com/watch?v=xWdkt6KSirw - Javascript Academy - "Build Your Own Memory Card Game with HTML, CSS, and JavaScript".
- Keyframe card shake animation guidance was taken from https://css-tricks.com/.







