# Laxus and Thiosymbion

(Developer: Gabriela Fabiola Paredes Rojas)

![Responsice Mockup](https://github.com/lucyrush/readme-template/blob/master/media/love_running_mockup.png)

Symbiosis is defined as "the living together of differently named organisms" (de Bary, 1879). This website provides information on an extraordinary symbiotic example, the one involving the free-living marine nematode *Laxus oneistus* and its inseparable bacterial partner, *Candidatus* Thiosymbion oneisti. 

+ Throughout this documentation, they will be referred as *Laxus* and Thiosymbion. respectively.

+ The site can be accessed via this [link](https://paredesgab.github.io/PP1-project-portfolio-1/)

## Project Goals

### User Goals

+ Find clear, fun and engaging information about this marine symbiosis.
+ Understand or learn about the unique relationship between *Laxus* and Thiosymbion. 
+ Explore the "cool factor" of symbiosis through this example.
+ Leave with a new appreciation for the surprising, complex relationships that exist even in the smallest corners of the ocean.

### Business Owner Goals

+ My primary goal is **science communication**. Namely:

  + Inform, raise awareness and public outreach about the existance of this fascinating but little-known nematode-bacterium symbiosis.  
  + Communicate key scientific findings of the *Laxus*-Thiosymbion partnership in a simple way.

+ In addition:
  + Spark interest in further scientific study of this fascinating symbiotic system. 
  + Generate public engagement to build a network of people excited about marine symbioses.

## User Experience

### Target audience

+ General public interested in life, nature or biology.
+ Environmental advocates, because global warming and/or human impact have also an effect on marine meiofauna.
+ Students, teachers or marine science enthusiasts studying marine biology, ecology, nematology, or microbiology. 
+ Researchers, scientists.

### User expectations

+ Accessible site.
+ Fast access to content.
+ Understand clearly the purpose of the site.
+ Have relevant content that keeps the user engaged.
+ Easy and intuitive navigation, overall a smooth experience.
+ Mobile-friendly, but generally a responsive design that works well on all devices.

### User stories

+ **As a first-time user, I want to:**

  + Easily navigate the website and find the content interesting.
  + Be surprised to discover that drastically different organisms in nature might depend on each other for survival.
  + Find this, otherwise niche topic, entertaining and easy to understand. 
  + Find useful information about this symbiosis, so I can compare it with my research system. 
  + Visit the social media platforms to see what activity is going on around this topic.

+ **As a returning user, I want to:**

  + Discover the latest key findings or new research on the *Laxus*-Thiosymbion symbiosis. 
  + Connect with scientists working on marine symbiosis, so they can share their insights in schools, museums, or to establish a scientific collaboration.
  + See if other symbiotic systems are featured on the site.

+ **As the business ownser user, I want:**

  + Pass on my love for this system that was my workhorse for many years. 
  + Highlight the key discoveries I made during my Ph.D. research (Paredes et al., 2021, 2022).
  + Keep the website updated with the latest research on this symbiosis. 
  + Know if the visitors found the content interesting and if it was easy to understand. 
  + Know what other symbiosis-related content my users want to see. For example, testimonial from scientists, or the process of collecting the nematodes from sand, etc. 

## Features 

### Navigation Bar

![NavBar desktop](documentation/navbar_desktop.png)

  + It is positioned at the top of the page, and across all pages of the website. 
  + It is clear and easy to navigate.
  + It contains the "Laxus and Thiosymbion" logo on the left.
  + It contains the following four navigation links on the right:

    + **HOME:** Takes you to the home page where users can learn about the *Laxus*-Thiosymbion symbiosis.

    + **LAXUS:** Takes you to the page that features the nematode *Laxus oneistus* and what it might be providing to its bacterial partner.

    + **THIOSYMBION:** Takes you to the page describing the bacterium *Candidatus* Thiosymbion oneisti and what it might provide to its nematode host.

    + **CONTACT:** Takes you to the contact form to sign up for a newsletter with symbiosis stories.

  + All four navigation links have a hover effect.

  + In addition, the navigation bar is responsive:

    + **On mobile devices:**
        
      + The navbar features the logo on the left, with a hamburger menu from Font Awesome on the right.

    ![NavBar Mobile Closed](documentation/navbar_mobile_closed.png)

      + When clicked, the hamburger menu reveals a drop-down with the navigation links displayed in the same order as described above, and they have Laxus as bullet points.

    ![NavBar Mobile Open](documentation/navbar_mobile_open.png)

    + **On tablets and larger screens** 
      + The logo remains on the left, the hamburger disappears and instead you see all the navigation links spaceously distributed on the right.

    ![NavBar Tablets and Up](documentation/navbar_tablets.png)
       
---
### HOME page

  * It presents the symbiosis of *Laxus* and Thiosymbion.
  * It intends to make the topic of symbiosis easy to understand, by:
    * Presenting it as a love story - it is after all, a relationship.
    * Using the analogy of wearing a winter coat, so to make it clearer that the bacteria live on the surface. 
  * It highlights the extraordinary features of this partnership, including fun facts to make the content more interactive.
  * It also introduces the social media channels.
  * The home page is responsive.

  ![Home Page](documentation/home_page.png)

#### Hero section

- The hero section is placed on the top of the home page.
- The intention was to make it simple but yet impactful - here the black background allows the single nematode picture to shine.
 - The title of the website (h2) "A extraordinary symbiosis" is next to the image and it has a yelloish/white color, same as the bacterials symbiont.  
 - This background image as well as the title position and font-size was made responsive across all devices. 

![Hero Section](documentation/hero_section.png)

#### Love story section

- This section aims to introduce the symbiosis in a fun and simplified way.
  
- It contains: a title (h3), an intro text explaining the website's theme, a video of moving worms, and a video caption. 

- The "love story" title is an analogy representing symbiosis as a partnership.

- The text is written to engage all audiences, for example, using the analogy of a winter coat in Caribbean heat to help users imagine life as this nematode.  

- The video, shows several *Laxus oneistus* in motion, and the caption, highlights their resemblance with rice noodles but, in fact, the whiteness is the bacteria on the surface. 

- This section was made responsive, and from Tablets up flex box with flex direction row was used. 
    
![Highlights Section](documentation/main_cons.png)

#### Extraordinary section

- As the title suggests, this section aims to highlight extraordinary features of this symbiosis. 
    
- Three key features have been selected and displayed using the HTML class attribute "feature1.
    
- They allow the user to see information about its habitat, reasons of being together and more importantly, the uniqueness of this symbiosis, 

- To make it more interactive, each feature card has a "fun fact" that is highlighted in bold and next to a star from Font Awesome. 

- These features are in fact seminal findings of the Laxus*-Thiosymbion research. As such, they will likely remain as the site is updated, but more features will be added as new research emerges.

- This section was made responsive. Namely:
  - The title (h3) increases in font size.
  - In mobiles: the figure is placed on top of the text, forming a column. 
  - In tablets, the figure and text were placed next to each other(in a row). This was achieved because their container (class feature1) was set to display property: flex.
  - In Laptops and Up, this display propery was set to column, to have the features next to each other. 
​
![Highlights Section](documentation/main_cons.png)

#### Footer

- The footer section is present across all pages from this website.
- The footer section contains links to the relevant social media sites that feature *Laxus* and Thiosymbion.
- The links will open to a new tab to allow easy navigation for the user. 
- The footer adds value by encouraging users to stay connected through social media.
- The footer is responsive, with increasing font sizing and padding as the screen width increases.
​
![Footer](documentation/footer.png)

---
### LAXUS page

- This page provides the user with more information about the nematode.

- It contains three sections, from top to bottom:

  - First: The **Hero Laxus section** - which uses the same style as the hero section from the home page. This section is responsive, and its height increases as the device screen width increases. 

  - Second: The **Laxus introduction section** - which uses the same style as the love story section from the home page. This section is responsive.

  - Third: The **What Laxus gives to Thiosymbion section** -which is a research study conducted by the developer in 2022. A summary of the main findings of the article is presented, as well as a nutritional model of the interaction of *Laxus* with its bacteria. The study is also linked to the website, and this section is responsive.  

  ![Footer](documentation/footer.png)

---
### THIOSYMBION page

- This page provides the user with more information about the bacteria.

- Intentionally, it has the same style and responsiveness as the Laxus page, from top to bottom:

  - First: The **Hero Thiosymbion section**.

  - Second: The **Thiosymbion introduction section**.

  - Third: The **What Thiosymbion gives to Laxus section** -which is a research study conducted by the developer in 2021. A summary of the main findings of the article is presented, as well as a nutritional model of the interaction of Thiosymbion with the nematode. The study is also linked to the website, and this section is responsive.  

  ![Thiosymbion](documentation/footer.png)

---
### NEWSLETTER page

  - This page will allow the user to subscribe to a newsletter to stay updated on new content, discoveries, or tips related to the *Laxus*-Thiosymbion symbiosis or other "love stories".

  - To subscribe to the newsletter The user is required to provide their name, email address, feedback,  choose which system is of their interest, and click on the subscribe button. 

  - The subscribe button has a hover effect animation. 

  - This section is responsive, and the resize property of the textarea was disabled by setting it to: none.

![Newsletter](documentation/footer.png)

---
### SUCCESSFUL page

  - After successful subscription the user is redirected to this page.

  - The user is thanked for subscribing, and there is a quote from one of the foremost symbiosis researchers, Lynn Margulis, that highlights the power of teaming up. 

  - This page is responsive, and has a "Return to Home page" button to keep the user in the website. 

---
### Features Left to Implement

- Make the hamburger icon responsive. 

- Use CSS roots to declare global CSS variables and and apply them across the entire project for consistent styling.

- Update the extraordinary section with new research. 

- Add a carousel to the "Love story" section, and to the "Laxus and Thiosymbion introduction sections", respectively; so that more media can be displayed. 

- And/or, add a gallery section, showing nematode pictures, researchers in action, the island in Belize from where they are collected, etc., and use CSS grid to organize it.

- Add a "References" page, that lists all publications related to the *Laxus*-Thiosymbion association.

---
## Languages
- HTML
- CSS

---
## Technologies used
- Balsamiq: to create the wireframes.
- Google Fonts
- [Font Awesome](https://fontawesome.com/): For the hamburger, star, and social media icons.
- Gitpod
- GitHub
- TinyPNG to compress the images.
- MDN Web Docs resource to read more about CSS properties.
- VEED video editor, to compress and edit the video.
- color-hex to get the rgb color information.
- Chrome DevTools.
- Lighthouse from Chrome DevTools.
- W3C HTML and CSS Validation Services. 
- DeepL write, to spot spelling mistakes in the text. 

## Testing 

In this section, you need to convince the assessor that you have conducted enough testing to legitimately believe that the site works well. Essentially, in this part you will want to go over all of your project’s features and ensure that they all work as intended, with the project providing an easy and straightforward way for the users to achieve their goals.

In addition, you should mention in this section how your project looks and works on different browsers and screen sizes.

You should also mention in this section any interesting bugs or problems you discovered during your testing, even if you haven't addressed them yet.

If this section grows too long, you may want to split it off into a separate file and link to it from here.


### Validator Testing 

- HTML
  - No errors were returned when passing through the official [W3C validator](https://validator.w3.org/nu/?doc=https%3A%2F%2Fcode-institute-org.github.io%2Flove-running-2.0%2Findex.html)
- CSS
  - No errors were found when passing through the official [(Jigsaw) validator](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fvalidator.w3.org%2Fnu%2F%3Fdoc%3Dhttps%253A%252F%252Fcode-institute-org.github.io%252Flove-running-2.0%252Findex.html&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en#css)

### Unfixed Bugs

You will need to mention unfixed bugs and why they were not fixed. This section should include shortcomings of the frameworks or technologies used. Although time can be a big variable to consider, paucity of time and difficulty understanding implementation is not a valid reason to leave bugs unfixed. 

## Deployment

This section should describe the process you went through to deploy the project to a hosting platform (e.g. GitHub) 

- The site was deployed to GitHub pages. The steps to deploy are as follows: 
  - In the GitHub repository, navigate to the Settings tab 
  - From the source section drop-down menu, select the Master Branch
  - Once the master branch has been selected, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment. 

The live link can be found here - https://code-institute-org.github.io/love-running-2.0/index.html 


## Credits 

### Content 

- The Code institute ci-full-template was used to create the GitHub repository of the Laxus & Thiosymbion website.

- All content was written by the developer but checked with DeepL Write for spelling mistakes. 

- Inspiration to add the small Laxus bullet points is from the youttube channel "Six Minutes. Smarter."

- MDN Web Docs showed me different ways to use the backgroun-position property.

- ReadMe was inspired and guided by the ReadMe documents of my mentor Iuliia Konovalova, of my cohort Kamil Wojciechowski, and of the love running project. 

- Stack Overflow solutions were a game changer, for example the one "How to use the "required" attribute with a "radio" input field" 

### Media

- The photos used on the home and sign up page are from This Open Source site
- The images used for the gallery page were taken from this other open source site


Congratulations on completing your Readme, you have made another big stride in the direction of being a developer! 

## Acknowledgments

- I want to thank my mentor Iuliia Konovalova for her valuable feedback. 
- Thank you to my brother Brando, who new long before myself that I love to code. Your piano background [Brando PR](https://www.youtube.com/@BrandoPR) accompanied me along this project. 
- 