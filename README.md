<h1 align="center">PiaNotes</h1>

[The PiaNotes website](https://alexah88.github.io/pianotes/) has been developed for anyone interested in music, piano, and playing mini-games online. The user can play a virtual piano, challenge themselves in a Simon Says type mini-game against the computer, play along to a selection of sheet music, and find out how to use the site on a dedicated instructions page.

<h2 align="center"><img src="assets/images/mockup-pianotes.png"></h2>

## __User Experience (UX)__

-   ### ***User stories***

    -   #### First Time Visitor Goals

        1. As a First Time Visitor, I want to easily understand the main purpose of the site and have fun playing a virtual piano and/or a mini game.
        2. As a First Time Visitor, I want to be able to easily be able to navigate throughout the site to find content, including on how to use the virtual piano and play the game. 
        3. As a First Time Visitor, I want to locate the site creator's social media links to see their following on social media to determine how trusted and known they are.

    -   #### Returning Visitor Goals

        1. As a Returning Visitor, I want to use the sheet music to try and play along to well-known songs.
        2. As a Returning Visitor, I want to re-read the challenge instructions to try and beat the computer.
        3. As a Returning Visitor, I want to get in contact with the site creator with any questions I may have about the site.

    -   #### Frequent User Goals

        1. As a Frequent User, I want to attempt to play the sheet music songs using only the computer keyboard, without making any mistakes.
        2. As a Frequent User, I want to try and beat my personal best score on the challenge.
        3. As a Frequent User, I want to see if any new sheet music had been added.

-   ### ***Design***
    
    -   #### Colour Palette

        - The colour palette is made up of four colours: 
          - Yellow #FFDE59
          - Purple #5E17EB
          - Black #000000
          - White #FFFFFF

        - The yellow #FFDE59 and purple #5E17EB were chosen for their playfulness and retro feel, fitting with the theme of the site, all the while taking into account their compatibility with each other and the site as a whole. Black #000000 and white #FFFFFF are used as the third and fourth colours on the site as neutral tones.

    -   #### Typography

        - The [Orelega One](https://fonts.google.com/specimen/Orelega+One?query=orelega) and [Poppins](https://fonts.google.com/specimen/Poppins?query=poppins) fonts are used across the site, with 'Orelega One' used for the headings and 'Poppins' used for the remaining text. 

        - The fonts were chosen for their playful and retro feel, taking into account the theme of the site. 
    
    -   #### Imagery

        - The piano and computer mouse icons on the Instructions Page were added to avoid having a text-heavy page and to create a playful and fun look and feel. The graphics use the same colours and style of the site in order to keep things coherent.  

-   ### ***Wireframes***

    - The Play and Challenge pages at the wireframe stage were later combined to create one page (Play), with the ability to switch between Freestlye and Challenge modes. This was done in order to improve UX and repetitive code on two pages. 

    -   Play page:
        ![Play Wireframe](assets/images/wireframes-play-page.png)

    -   Challenge page:
        ![Challenge Wireframe](assets/images/wireframes-challenge-page.png)

    -   Sheet Music page:
        ![Sheet Music Wireframe](assets/images/wireframes-sheet-music-page.png)
    
    -   Instructions page:
        ![Instructions Wireframe](assets/images/wireframes-instructions-page.png)

## __Features__

### ***Existing Features***

- #### Navigation Bar

  ![Nav Bar](assets/images/nav-bar.png)

  - The navigation bar includes four clickable links, allowing the user to easily access the three pages on the site: 
    - PiaNotes site name (links to the Play home page)
    - Play page
    - Sheet Music page
    - Instructions page

  - In order to make navigation easier for the user, the navigation bar is in a fixed position, meaning that it remains at the top of the page as the user scrolls down.

  - The navigation bar follows the same style as the footer, and appears in the same format on all three pages - this allows for consistency throughout the site.

  - A hover effect of the text turning purple, and the cursor becoming a pointer is included, allowing the user to understand that the link is clickable. Once the link has been clicked, the text remains pruple to indicate to the user which page they find themselves on. 

  - The navigation bar was created with HTML, CSS and JavaScript and is fully responsive across devices.
    ![Responsive Nav Bar](assets/images/nav-bar-responsive.png)

- #### Play Page

  ![Play Page](assets/images/page-play.png)

  - The Play page is the landing page of the website and as the user's first port of call serves as the main purpose of the site, namely to be able to play a virtual piano - on Freestyle mode, or on Challenge mode. 
  
  - The page is split into two sections:
    - The play mode choice, including a clickable button each for Freestyle mode and Challenge mode. And the score board, including counters for the number of rounds played, the number of games won, the number of games lost, and a results message showing either "Won!" or "Lost!". A hover effect of the buttons inversing colours, and the cursor becoming a pointer is included, allowing the user to understand that the button is clickable.
    - The virtual piano, including computer keyboard keys to be used on non-touchscreen devices. A hover effect on the keys of the cursor becoming a pointer is included, allowing the user to understand that the keys is clickable.

- #### Sheet Music Page

  ![Sheet Music Page](assets/images/page-sheet-music.png)

  - The Sheet Music page allows the user to view a selection of sheet music that they can play along to on the piano, by opening the page in a separate tab. 

  - Each piece of sheet music includes the corresponding audio file that users can listen to in order to familiarise themselves with the song. 

  - The page has a choice of seven songs:
    - The Entertainer - Scott Joplin
    - Für Elise - Ludwig van Beethoven
    - Clair de Lune - Claude Debussy
    - Canon in D - Johann Pachelbel
    - Dance of the Sugar Plum Fairy - Pyotr Ilyich Tchaikovsky
    - Greensleeves - Unknown Composer
    - Happy Birthday - Patty & Mildred J. Hill

- #### Instructions Page

  ![Instructions Page](assets/images/page-instructions.png)

  - The Intructions page serves to inform the user on how to play and how to use the virtual piano. 

  - The page is split into two sections:
    - How to Play - explaining to the user the difference between the two play modes and how to access them, and the use of the sheet music. 
    - Using the Virtual Piano - explaining to the user in which ways the piano can be played on various devices. 

  - The user can access a popup window in the How to Play section, detailing the rules of the challenge. A hover effect of the text turning purple, and the cursor becoming a pointer is included, allowing the user to understand that the word 'here' is clickable. A popup was used to avoid overloading the page with text, and thus discouraging the user from reading the information. 

  - A piano and computer mouse graphic were used for each of the sections, to break up the text-heavy page and instantly make clear to the user what the secions are about. The graphics use the same colours and style of the site in order to keep things coherent.  

- #### Footer

  ![Footer](assets/images/footer.png)

  - The footer follows the same style as the navigation bar, and appears in the same format on all three pages - this allows for consistency throughout the site.

  - The footer contains three elements:
    - The copyrighted site name on the left hand side. 
    - Information about the site and how it was created. 
    - Social media links, allowing the user to visit the site creator's LinkedIn and GitHub pages. Hovering over the link icons turns them purple to signal to the user that there is an interaction possible. All links are opened in separate tabs so that the user remains on the site. 

  - The footer was created with HTML and CSS only and is fully responsive across devices.

    ![Responsive Footer](assets/images/footer-responsive.png)

### ***Future Implementations***

- #### General
  
  - Use a [recreation of the in-game font](https://www.fontspace.com/category/horizon-zero-dawn) for headings across the site.

  - Add a Tribe Quiz page with JavaScript, allowing the user to answer questions about their gaming style resulting in being assigned to a tribe from the Horizon universe. 

  - Add a chat room function to the site for users to be able to connect socially. 

  - Improve Lighthouse Performance score on all pages by further compressing image sizes without losing the quality, or by using a next-gen image format such as WebP or AVIF. 

- #### Navigation Bar
  
  - Add sub-menu on navigation bar, linking to the h3 and h4 sections on the site.

  - Make header invisible on smaller viewports and allow for swipe down or hover to make it appear. 

  - Improve the hamburger menu functionality by using a JavaScript version instead. 

- #### Hero Images

  - Add a text box or scroll down arrow on the hero images to make it clearer to users that there is content below the images - as they take up a lot of the screen space in order to be visually striking.  

- #### Machine Catalogue Page

  - Include all the machines from the Horizon games to have the full collection of existing machines. 

  - Make the machine catalogue info text on the images visually more appealing on smaller viewports, for example using a different system instead e.g. modals with Java. 

- #### Sign Up Page

  - Make the newsletter an actual function of the site.

  - Create user profile and login options in order to create a true community where users can connect. 

  - Make the how many hours a day do you play selector into a range slider instead and show the 1-24 hour values with JavaScript. 

- #### The Footer

  - Add a back to top arrow or button to allow the user to get back to the top of the screen easily. 

## __Technologies Used__

### ***Languages Used***

-   [HTML5](https://en.wikipedia.org/wiki/HTML5)

-   [CSS3](https://en.wikipedia.org/wiki/Cascading_Style_Sheets)

-   [JavaScript](https://en.wikipedia.org/wiki/JavaScript)

### ***Frameworks, Libraries & Programs Used***

1. [Google Fonts:](https://fonts.google.com/)
    - Google Fonts was used to import the ''Orelega One' and 'Poppins' fonts into the style.css file which is used on all pages throughout the project. [Orelega One](https://fonts.google.com/specimen/Orelega+One?query=orelega) for the headings and [Poppins](https://fonts.google.com/specimen/Poppins?query=poppins) is used for the remaining text.

1. [Font Awesome:](https://fontawesome.com/)
    - Font Awesome was used on all pages throughout the website to add icons for aesthetic and UX purposes.

1. [Git:](https://git-scm.com/)
    - Git was used for version control by utilizing the Gitpod terminal to commit to Git and Push to GitHub.

1. [GitHub:](https://github.com/)
    - GitHub is used to store the projects code after being pushed from Git.

1. [Canva:](https://www.canva.com/)
    - Canva was used to create the wireframes during the design process.

1. [Chrome DevTools:](https://developer.chrome.com/docs/devtools/)
    - Chrome DevTools was used to consistently check the site in terms of responsivity, performance, accessibility, best practice and SEO.

1. [Font Awesome Favicon Generator:](https://gauger.io/fonticon/)
    - Font Awesome Favicon Generator was used to reproduce a favicon version of the [Font Awesome Music Icon](https://fontawesome.com/icons/music?s=solid) used in the header site name.

1. [Responsinator:](https://www.responsinator.com/)
    - Responsinator was used to check responsivity across all devices.

## __Testing__

### ***HTML and CSS Testing***

-   [W3C Markup Validator](https://jigsaw.w3.org/css-validator/#validate_by_input) was used to validate every page of the project to ensure there were no HTML syntax errors in the project.
    - [Results index.html](assets/testing/testing-html-index.pdf)
    - [Results game-developer-history.html](assets/testing/testing-html-game-developer-history.pdf)
    - [Results machine-catalogue.html](assets/testing/testing-html-machine-catalogue.pdf)
    - [Results sign-up.html](assets/testing/testing-html-sign-up.pdf)

-   [W3C CSS Validator](https://jigsaw.w3.org/css-validator/#validate_by_input) was used to validate every page of the project to ensure there were no CSS syntax errors in the project.
    - [Results style.css](assets/testing/testing-style-css.pdf)

### ***Performance, Accessibility, Best Practices, and SEO Testing***

  [Chrome DevTools Lighthouse](https://developers.google.com/web/tools/lighthouse) was used to test Performance, Accessibility, Best Practices and SEO. All tests performed in the 90-100 green score, except for in the Performance category on some pages that came in the yellow range. Compressing the image size resulted in pixelated images and was therefore dismissed and a lower performance rating accepted. 
  - The About The Games Page scored 77 on mobile.
  - The Game Developer History Page scored 65 on mobile.
  - The Sign Up Page scored 80 on mobile and 84 on desktop.

- #### Desktop Testing with [Chrome DevTools Lighthouse](https://developers.google.com/web/tools/lighthouse)

  - [About The Games Page](assets/testing/testing-lighthouse-index-desktop.pdf)
  - [Game Developer History Page](assets/testing/testing-lighthouse-developer-history-desktop.pdf)
  - [Machine Catalogue Page](assets/testing/testing-lighthouse-machine-catalogue-desktop.pdf)
  - [Sign Up Page](assets/testing/testing-lighthouse-sign-up-desktop.pdf)

- #### Mobile Testing with [Chrome DevTools Lighthouse](https://developers.google.com/web/tools/lighthouse)

  - [About The Games Page](assets/testing/testing-lighthouse-index-mobile.pdf)
  - [Game Developer History Page](assets/testing/testing-lighthouse-developer-history-mobile.pdf)
  - [Machine Catalogue Page](assets/testing/testing-lighthouse-machine-catalogue-mobile.pdf)
  - [Sign Up Page](assets/testing/testing-lighthouse-sign-up-mobile.pdf)

- #### Further Accessibility Testing

  - [EightShapes Contrast Grid](http://eightshapes.com/) was used to test the colour palette of the site for any accessibility issues. Only AAA and AA rating options were used on the site. 
  ![Colour Palette Contrast Grid](assets/images/color-palette-contrast-grid.png)
  
  - Any icons on the site that are for decorative purposes only use the aria-hidden="true" attribute to accommodate for accessibility, as recommended by [Font Awesome's Accessiblity Page](https://fontawesome.com/v5/docs/web/other-topics/accessibility)
  ![Font Awesome Accessiblity Page](assets/images/font-awesome-accessibility.png)

### ***Responsive Testing***

  - [Chrome DevTools](https://developer.chrome.com/docs/devtools/) and [Responsinator](https://www.responsinator.com/) were used to regularly check for any responsive design issues. Rather than only checking for specific device screen widths, I used DevTools to reduce the viewport width gradually and noted any and all issues for each width. My media queries are based on these specific pixel widths rather than typical viewport breakpoints to allow for an enjoyable experience for all users, on any devices they use. 

  - The site is responsive down to 320px viewport widths, and in most cases even down to 280px.  

### ***Testing User Stories from User Experience (UX) Section***

-   #### First Time Visitor Goals

    1. As a First Time Visitor, I want to easily understand the main purpose of the site and learn more about the Horizon games.

        1. Upon entering the site, users are automatically greeted with a clean and easily readable navigation bar to go to the page of their choice. Underneath there is a Hero Image and upon scrolling down the user discovers the main section of the page.
        2. The main points are made immediately clear with the hero image. It serves to introduce the user to the world of Horizon if they don't know the games, or to plunge the user back into this world as if they were playing the games.  
        3. The user has the option to scroll down, which will lead to the main page content, allowing them to learn more about the Horizon games.  

    2. As a First Time Visitor, I want to be able to easily be able to navigate throughout the site to find content.

        1. The site has been designed to be fluid and never to entrap the user. At the top of each page there is a clean navigation bar, each link clearly describes what page they will end up on. There is also a visual aid in the form of colours to help the user understand which page they are on: white for the current page, light blue for the other pages they can click on to visit. 
        2. The navigation bar is in the fixed position and thus stays at the top of the page as the user navigates the site, allowing the user to easily switch between pages and get back to the top of the page again by clicking on the page link they are currently on. 
        3. On smaller viewports the navigation bar remains fixed, but is reduced in size as to not take up too much space, and includes the site name only, which remains clickable. In order to access the other site pages there is a hamburger bar to the left of the site name, which pops out onto the screen and disappears again once the desired page has been selected. 
        4. On the Sign Up Page, after a form response is submitted, the user is notified that the form has been successfully sent.

    3. As a First Time Visitor, I want to locate the site creator's social media links to see their following on social media to determine how trusted and known they are.
        
        1. The user can scroll to the bottom of any page on the site to locate social media links in the footer.

-   #### Returning Visitor Goals

    1. As a Returning Visitor, I want to look up the machine catalogue page, to find out how to beat the enemy machines in the game.

        1. The navigation bar clearly highlights the "Machine Catalogue" Page.
        2. The user will be directed to the page with another hero image and the machine catalogue in the main page area below.
        3. The Beat The Machines section explains to the user that they need to hover over (or tap on touchscreens) the machine images below in order for the info text to appear, which details how they can override and destroy the machines. 

    2. As a Returning Visitor, I want to rewatch the YouTube videos on the About The Games page and the Machine Catalogue page, to immerse myself in the Horizon gaming world.
        
        1. The navigation bar clearly highlights the "About The Games" and "Machine Catalogue" Pages.
        2. The videos do not autoplay and it is up to the user to press the play button, making it a chosen action. 
        3. The videos can either be played on the site directly with a set window size, or they can be made full-screen - depending on what the user prefers. 

    3. As a Returning Visitor, I want to sign up for the newsletter and join the community.
        
        1. The navigation bar clearly highlights the "Sign Up" Page.
        2. The form on the sign up page is clear in its instruction, detailing three sections to complete: user details, survey questions, and newsletter subscription. 
        3. Once complete the user is instructed to click the "Join Us!" button and once clicked is informed that the form has successfully been submitted.

    4. As a Returning Visitor, I want to get in contact with the site creator with any questions I may have about the site.
        
        1. The footer contains links to the site creator's GitHub and Linkedin pages.
        2. Whichever link they click, it will be open up in a new tab to ensure the user can easily get back to the website.

-   #### Frequent User Goals

    1. As a Frequent User, I want to check to see if there are any newly added machines on the machine catalogue, as not all machines in the games are currently included.

        1. The user would already be comfortable with the website layout and can easily find the "Machine Catalogue" Page in the navigation bar.
        2. Here they would quickly see if any new machines had been added to the list. 

    2. As a Frequent User, I want to check to see if there are any new game releases planned.

        1. The user would already be comfortable with the website layout and can easily find the "About The Games" or "Game Developer History" Pages in the navigation bar. 
        2. Here they would find updates on any new game news. 

    3. As a Frequent User, I want to have more interaction with the community.
        
        1. The user would already be comfortable with the website layout and can easily find the "Sign Up" Page in the navigation bar.
        2. Here they would find updates on any developments within the community, such as a user creation and login section, or a chat function between users.  

### ***Further Testing***

-   The Website was tested on Google Chrome, Firefox, and Microsoft Edge browsers.

-   The website was viewed on a variety of devices such as Desktop up to 28 inch screen with 4k resolution, Laptop, Pixel 3a, Pixel 4, Samsung Galaxy Tab S5e.

-   A large amount of testing was done to ensure that all pages were linking correctly.

-   Friends and family members were asked to review the site and documentation to point out any bugs and/or user experience issues.

### ***Fixed Bugs***

- Initially `style.backgroundColor` was used on the Challenge mode of the piano to achieve a purple coloured piano key as it was played - see example `function twenty()` below. This was followed by a `clearKeyLights function`, resetting the `style.backgroundColor` to white and black respectively - see `function clearKeyLights` below. This however caused a bug when switching to Freestyle mode after having played Challenge mode: the purple colour no longer appeared when playing the notes. This was due to the `style.backgroundColor` taking precedence over the `.active` class used on Freestyle mode. The bug was fixed by applying an `.active` class on the Challenge as well - see `function nineteen()` example below. 
  - Key Colour Bug Add Colours:
  ![Key Colour Bug Add Colours](assets/images/bug-key-colors-add-colours.png)
  - Key Colour Bug Clear Colours:
  ![Key Colour Bug Clear Colours](assets/images/bug-key-colors-clear-colours.png)

### ***Known Bugs***

- The iframe containing the sheet music on the Sheet Music Page doesn't always load, requiring a hard refresh (ctrl + shift + R) - see example below. Chrome DevTools revealed the issue being that `<!DOCTYPE html>` hadn't been called and the site was therefore being loaded in Quirks Mode - see example below. However, `<!DOCTYPE html>` is present on all html pages, and this issue could therefore not be resolved. 
  - iframe Bug:
  ![iframe Bug](assets/images/bug-iframe.png)
  - iframe Bug Quirks Mode:
  ![iframe Bug Quirks Mode](assets/images/bug-iframe-quirks-mode.png)

## __Deployment__

### ***GitHub Pages***

The project was deployed to GitHub Pages using the following steps:

1. Log in to GitHub and locate the [PiaNotes GitHub Repository](https://github.com/AlexaH88/pianotes)
2. At the top of the Repository (not top of page), locate the "Settings" Button on the menu.
    - Alternatively Click [Here](https://raw.githubusercontent.com/) for a GIF demonstrating the process starting from Step 2.
3. Scroll down the Settings page until you locate the "GitHub Pages" Section.
4. Under "Source", click the dropdown called "None" and select "Master Branch".
5. The page will automatically refresh.
6. Scroll back down through the page to locate the now published site [link](https://alexah88.github.io/pianotes/) in the "GitHub Pages" section.

### ***Forking the GitHub Repository***

By forking the GitHub Repository we make a copy of the original repository on our GitHub account to view and/or make changes without affecting the original repository by using the following steps:

1. Log in to GitHub and locate the [PiaNotes GitHub Repository](https://github.com/AlexaH88/pianotes)
2. At the top of the Repository (not top of page) just above the "Settings" Button on the menu, locate the "Fork" Button.
3. You should now have a copy of the original repository in your GitHub account.

### ***Making a Local Clone***

1. Log in to GitHub and locate the [PiaNotes GitHub Repository](https://github.com/AlexaH88/pianotes)
2. Under the repository name, click "Clone or download".
3. To clone the repository using HTTPS, under "Clone with HTTPS", copy the link.
4. Open Git Bash
5. Change the current working directory to the location where you want the cloned directory to be made.
6. Type `git clone`, and then paste the URL you copied in Step 3.

```
$ git clone https://github.com/AlexaH88/pianotes
```

7. Press Enter. Your local clone will be created.

```
$ git clone https://github.com/AlexaH88/pianotes
> Cloning into `CI-Clone`...
> remote: Counting objects: 10, done.
> remote: Compressing objects: 100% (8/8), done.
> remove: Total 10 (delta 1), reused 10 (delta 1)
> Unpacking objects: 100% (10/10), done.
```

Click [Here](https://help.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository#cloning-a-repository-to-github-desktop) to retrieve pictures for some of the buttons and more detailed explanations of the above process.

## __Credits__

### ***Code***

- The following were used as references to help with writing the HTML, CSS and JavaScript code:
  - [Code Institute LMS](https://learn.codeinstitute.net/ci_program/diplomainsoftwaredevelopmentecommerce), in particular the [CI Love Maths Walkthrough](https://learn.codeinstitute.net/courses/course-v1:CodeInstitute+LM101+2021_T1/courseware/2d651bf3f23e48aeb9b9218871912b2e/78f3c10a937c4fe09640c7c0098d16bd/)
  - [W3Schools](https://www.w3schools.com/) 
  - [Stack Overflow](https://stackoverflow.com/)
  - [MDN Web Docs](https://developer.mozilla.org/en-US/)

- The virtual piano code was taken from [Web Dev Simplified's](https://www.youtube.com/channel/UCFbNIlppjAuEX4znoulh0Cw) [Build A Piano With JavaScript Tutorial](https://www.youtube.com/watch?v=vjco5yKZpU8) and adapted. 

- The game challenge code was taken from [Free Code Camp Org's](https://www.youtube.com/channel/UC8butISFwT-Wl7EV0hUK0BQ) [Simon Game JavaScript Tutorial for Beginners](https://www.youtube.com/watch?v=n_ec3eowFLQ) and adapted. 

- The CSS flexbox code was taken from [Stack Overflow](https://stackoverflow.com/), specifically from [this thread](https://stackoverflow.com/questions/643879/css-to-make-html-page-footer-stay-at-bottom-of-the-page-with-a-minimum-height-b).

- The code to use icons as list bullet points on the Instructions page was taken from [Font Awesome](https://fontawesome.com/), specifically [this page](https://fontawesome.com/docs/web/style/lists).

- The favicon code was taken from [W3Schools](https://www.w3schools.com/), specifically from [HTML Favicon](https://www.w3schools.com/html/html_favicon.asp) and adapted.

- The JavaScript media queries were taken from [CSS Tricks](https://css-tricks.com/), specifically [this article](https://css-tricks.com/working-with-javascript-media-queries/), and adapted. 

- The code for the hamburger menu on 800px width screens and smaller was taken from [W3 Schools](https://www.w3schools.com/), specifically [this section](https://www.w3schools.com/howto/tryit.asp?filename=tryhow_js_mobile_navbar), and adapted. 

- The code for the Simon game rules popup on the instructions page was taken from [W3 Schools](https://www.w3schools.com/), specifically [this aticle](https://www.w3schools.com/howto/tryit.asp?filename=tryhow_js_popup), and adapted. 

### ***Content***

- All text content was written by the site creator [Alexa Hendry](https://github.com/AlexaH88). 

### ***Media***

- The [piano graphic](https://www.canva.com/media/MAEYJcyVjO8) on the Instructions page was taken from graphic designer [vectortradition](https://www.canva.com/p/vectortradition/) via [Canva](https://www.canva.com/).

- The [mouse graphic](https://www.canva.com/media/MADHSKVmqUU) on the Instructions page was taken from graphic designer [BellafishPh](https://www.canva.cn/p/hnh-nh-ca-bellafish-ph/) via [Canva](https://www.canva.com/).

- The sheet music and corresponding audio on the Sheet Music page was taken from [Musescore](https://musescore.com/) with the individual songs credited as follows:
  - [The Entertainer - Scott Joplin](https://musescore.com/user/167019/scores/162108) by [rui.c.sousa.3](https://musescore.com/user/167019)
  - [Für Elise - Ludwig van Beethoven](https://musescore.com/user/19710/scores/33816) by [ClassicMan](https://musescore.com/classicman)
  - [Clair de Lune - Claude Debussy](https://musescore.com/user/19710/scores/58553) by [ClassicMan](https://musescore.com/classicman)
  - [Canon in D - Johann Pachelbel](https://musescore.com/user/1809056/scores/1019991) by [lemontart](https://musescore.com/user/1809056)
  - [Dance of the Sugar Plum Fairy - Pyotr Ilyich Tchaikovsky](https://musescore.com/user/3435661/scores/2899321) by [Nohpets](https://musescore.com/user/3435661)
  - [Greensleeves - Unknown Composer](https://musescore.com/user/35704259/scores/6340178) by [DominiqueMakowski](https://musescore.com/dominiquemakowski
  - [Happy Birthday - Patty & Mildred J. Hill](https://musescore.com/user/173585/scores/166951) by [wildpig](https://musescore.com/user/173585)

- The piano notes audio was recorded by the site creator [Alexa Hendry](https://github.com/AlexaH88) on [Ableton Live](https://www.ableton.com/en/live/) with the [Grand Piano](https://www.ableton.com/en/packs/grand-piano/) sound. 

### ***Acknowledgements***

Massive thanks to: 

- My mentor, [Darío Carrasquel](https://github.com/jeetkunecoder), for guiding me and giving me helpful feedback and advice. 

- My fellow Code Institute students and friends for their help, generous feedback, and incredible knowledge:
  - [Emanuel Silva](https://github.com/manni8436)
  - [Abi Harrison](https://github.com/Abibubble)
  - [Suzy Bennett](https://github.com/suzybee1987)
  - [Natalie Kate Alexander](https://github.com/natalie-kate)
  - [Dave Horrocks](https://github.com/DaveyJH)

- Tutor Support, Student Care and the Slack Community at [Code Institute](https://codeinstitute.net/global/) for their support.

- And last but not least, my fiancé [Antoine Masson](https://www.linkedin.com/in/antoine-masson-55b65094/) for helping me through the stressful moments and for supporting us financially while I make this big career change. 