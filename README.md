# Zola with Yoga!

*Zola with Yoga* is an online yoga studio where you can relax, unwind and reset after a long day of work / school and feel refreshed for the next day. **Zola**, a word that derives from a South African language (Zulu) meaning *'calm'* or *'peacful'*, puts an emphasis on the energy the site will bring to the customers. People are so busy in such a way that they no longer have time to go to fitness studios. This site hopes to help people interested in doing yoga but do not have time to travel to the actual studio. This site also hopes to accomplish a more calm and joyful society without having to pay more for transport. The target market is young and old adults, who wish to live a positive and stressless life. Customers who wish to keep fit but cannot afford to go to a studio. Customers can also purchase Yoga equipment on the website's online shop. 

![Responsive screens](README.md_docs/responsive-screens.png)

## Features

#### Navigation Bar
- The navigation bar is set to make it easy for the user to get to the right page with just a click. 
- This section is found on all pages for the convinience of the user. The user will not have to click on the back button to return to a page.
- When a user is on a certain page, there is a borderline below the name of the page which helps them see which page they are on at that time.
- By clicking the on the logo, a user can easily return to the home page.
- The slogan lets the user know that they can do yoga at their homes. Please see image below:

![Nav bar features](README.md_docs/nav-bar-feature.png)

#### The Home page image
- The home page image is put as background image. The image shows a woman sitting in a position that shows she is doing yoga. She is located in her living room. Which illustrates the setting of the sessions.
- On top of the background image is a welcome message for users to have an idea of what exactly the site entails.
- The home page welcomes a user to the yoga studio which is held online. The user will be expected to read the welcome message then sign up for yoga if they are interested. Please see below image:

![Hero image feature](README.md_docs/hero-image-feature.png)

#### The Footer
- The footer shows the user the accessible social media platforms to visit in order to connect with us and to get more information about the site.
- On Instagram and Tiktok, that is where the users can have a glimpse of what the website contains with short videos of what takes place at each session. On WhatsApp that is where they can connect with employees and ask questions. Please see image below:

![Footer feature](README.md_docs/footer-feature.png)

#### The Shop page
- This page consists of a variety of products and equipments which users can purchase so they are prepared for yoga.
- On this section, users do not have to be members in order to purchase the goods. Please see image below:

![Shopping feature](README.md_docs/shopping-feature.png)

#### The Sign Up page
- This page has a form where customers can signup to become members of the studio.
- Once the form is completed, a submit button should be clicked. This button will take the user to a 'congratulations' page which shows the signup was successful.
- Terms of the website have been added so users are not blind sided when it comes to the product being sold.

![Signup feature](./README.md_docs/signup-feature.png)

#### The Bookings page
- This page consists of a fieldset which requires the age of the member as well as any information regarding their health. This is to help the instructor to prepare yoga moves which are suitable for the customer's age and health. 
- It also consists of the booking times as well as the preferred instructors and preferred settings.
- Our Studio has well trained and professional instructors who are more than willing to assist our customers to have the full experience as they wish. It contains of group and private sessions, where as in a private session it is just the customer and their chosen instructor.
- The instructors speak 4 different languages namely: English, Chinese, French and German.

![Bookings feature](./README.md_docs/bookings-feature.png)

<!-- Forms on signup and bookings pages with defensive design-->
#### My Signup Page Feature

- A required feature is added on the form so all fields are completed in order for the the submit button to work.
- The submit button has a defensive feature that requires all fields to be completed. The below screenshot has a pop up error that requests the user to fill the required sections.

<!-- Input fields -->
![Incomplete form](./README.md_docs/uncompleted-form-testing.png)

- When the email inserted does not have the correct symbols for an email, the defensive design inserted will cause the below error to pop up. This is how the user will see that they have inserted something incorrectly.

![Incorrect email](./README.md_docs/incorrect-email-testing.png)

<!-- Checkbox -->
- When the checkbox has not been clicked, the form will not be submitted, as seen on the screenprint below:

![Unchecked checkbox](./README.md_docs/unchecked-checkbox-testing.png)

- A checkbox should be checked once the terms and conditions have been read and understood by the user. Below is a screen shot of the terms.

![Checked checkbox](./README.md_docs/checked-checkbox-testing.png)

- Once the form is completed, a submit button should be clicked. This button will take the user to a Code Institute 'congratulations' page which shows the signup was successful. Please see below screenshot: 

![Congratulations signup](./README.md_docs/congratulations-testing.png)

<!-- Book a Session -->
#### My Bookings Page Feature
<!-- Age -->
- The below screenshot shows the drop down where members would have to select their age group.

![Age group](./README.md_docs/age-group-testing.png)

<!-- Health issues -->
- The radio button used on Zola with Yoga site forces a user to select one option, no multiple options can be selected at once. The below screenshot shows a selected answer to the health question. If the answer is yes, members would be required to complete the below textarea to specify what the health issue is to help the instructor to prepare suitable exercises.

![Health response](./README.md_docs/response-testing.png)

<!-- Yoga Instructors-->
- A user cannot add instructors outside of the 5 names in the Zola with Yoga site. The user cannot add new time slots which are not on our scope. Below is the screenshot of the table where users can book their sessions.

![Booking sessions](./README.md_docs/booking-sessions-testing.png)

- The 'Let's do Yoga!' button has a defensive feature that requires all fields to be completed. Please see screen shot below.

![Radio response](./README.md_docs/radio-response-testing.png)

<!-- Submit and do Yoga with us! -->
- When the 'Let's do yoga!' button is clicked, the user will be taken to another screen which shows that the member can start doing yoga.
- For now this button will take the user to a Code Institute 'congratulations' page which shows the signup was successful. Please see screenshot below.

![Congratulations booking](./README.md_docs/successful-booking-testing.png)

### Features Left to Implement
* I would like to  implement a feature that would allow a user to view the prices of the purchaseable goods by just hovering over an image.
* When booking a session, customers should be able to choose a preferred language from the 4 spoken by the instructors.

## Testing
I have conducted manual testing, defensive design testing, HTML and CSS validation and lastly included Dev Ops tools to test for Performance, Accessibility, Best Practices and SEO.

### Manual Testing

<!-- Favicon -->
#### My Favicon Bug Fixing
- The favicon gave me an issue as the files did not want to upload on my file explorer. The below screenshot would appear.

![Favicon error message](README.md_docs/favicon-error-message-testing.png)

- I then realised that the file name could be an issue as it would not allow the upload. I then renamed the file from "favicon-32x32" to "favicon-png.png", then it worked. On this section I used an emoji of a woman in Lotus Position which looks like a yoga position.

![Favicon current](./README.md_docs/favicon-current-testing.png)


#### My Home Page Bug Fixing
- At first, I wanted the booking session table to be on the home page with a background image of a woman sitting in a lotus position, where a user can book sessions with the Yoga instructors. The table appeared to have a background image that was meant for the whole screen and the image below the table was not covering the whole screen. Through consultation with a tutor, I noticed that the image was being called on both CSS and HTML, hence why the home page had two images. See screen print below.

![First home image](README.md_docs/first-home-img-testing.png)

- I then removed the image which was called on the html page and also decided to remove the table from the home page. Now the background image is covering the whole screen and includes a welcome message for the users. Please see the below screenshot.

![Home page after](README.md_docs/home-page-after-testing.png)

- I had another issue of nesting the background image class and welcome message class in a div element. Which ever style I gave to the welcome message was affecting the background image. Please see result below.

<!-- Background image -->
![Background image before](README.md_docs/background-image-before-testing.png)

- I seperated the classes in order to style them individually. I then applied the welcome message class to just the text. The below was the result.

![Background image after](./README.md_docs/background-image-after-testing.png)

- Without a background color, editing the welcome message on different screen sizes was difficult, because the larger the screen became, the less visible it would be. Please see screen below.

<!-- Welcome message -->
![Welcome message without background](README.md_docs/welcome-mess-nobackground-testing.png)

- After research and consultation, I added a background-color and made it transparent for a better user experience. I had also added a height to the background-color, which made it difficult for the welcome message to fit. Please see screen below.

![Welcome message with height styling](README.md_docs/welcome-mess-withheight-testing.png)
 
- Seeing that adding a height on the welcome message made it difficult to edit on difference screen sizes, I then removed it. This made the welcome message of Zola with Yoga to fit perfectly inside the border and made it easy to edit for all screen sizes. Please see screenshot below.

![Welcome message after](README.md_docs/welcome-mess-now-testing.png)


<!-- My shop pages images-->
#### My Shop Page Bug Fixing
The below screen shows what the shop screen looked before I added the correct styling. The ugly spaces make the page look unappealing.

![Shop page before](./README.md_docs/shop-page-before-testing.png)

I had used grid to style the images, but they were not performing accordingly. By using the following site, I managed to beautify the images also the positioning: [CSS Grid](https://medium.com/@Kamran1819G/responsive-masonry-image-gallery-using-a-css-grid-1a1f2711eae7). The below screenshot shows what the page looks like now.

![Shop page now](./README.md_docs/shop-page-now-testing.png)


<!-- Navigation bar issues -->
#### My Navigation Bar Bug Fixing
- The navigation bar gave me problems a couple of times. The menu, slogan and logo could not be positioned inline for larger screens. Please see below screenshot. 

![Navbar before](README.md_docs/navbar-before-testing.png)

- For small devices I wanted to use the toggle effect as shown on the Love Running Walkthrough Project. My toggle icon would not appear, instead the nav bar would go under the logo. On html, the width was set to 100% which was pushing the hamburger icon down. 

![Toggle issue 1](README.md_docs/toggle-issue1-testing.png)

- I had wrapped the logo, nav-bar and toggle within an anchor which caused the menu not to drop down when burger icon is clicked. 

![Toggle issue 2](README.md_docs/toggle-issue2-testing.png)

- After research and consultation, I then removed the nav-bar and toggle html from the anchor. This resulted in the navigation bar menu to drop down when burger icon was clicked. The menu of Zola with Yoga now appears below the navigation section when hamburger icon is clicked. The below screenshot shows the result.

![Toggle results](README.md_docs/toggle-result-testing.png)

- The navigation section looks great on larger devices as well. Please see screenshot below.

![Navigation menu](./README.md_docs/navigation-menu-testing.png)

<!-- What website looks like on all devices -->
#### Background Images Bug Fixing
- My project fits on all screens the way I had intended. Although at first it was an issue as there was unwanted space on the side. After consultating the tutors, I realised that the reason for the space is the navigation width which was set to 100% and positioned to left with another 70% which added the unwanted space. I then removed the width on larger devices as the effect was affecting only them. Please see below screen.

![Unwanted space](./README.md_docs/unwanted-space-home-testing.png)

- Now there is no space, the background images cover the whole screen.

![Fitted screen](./README.md_docs/fitting-4by4-testing.png)

### Validator Testing
The below are the validator tests for CSS, Lighthouse and HTML.

* HTML
    ##### Errors
    - Six errors were found on my HTML code.
    - Five of the errors were referring to bookings table where member's personal details are needed.
    - Some fields of the form should not have a 'required' attribute. Please see screenprint below:    

    ![HTML error](README.md_docs/html-error-validation.png)

    - The one last error was referring to the label element that did not have an input element on the bookings form. Labels and inputs go together. Please see screen shot below:

    ![Form error](./README.md_docs/form-error-validation.png)

    - After consultation I then changed the label to a paragraph, which illuminated the error. Please see below screen shot which shows that there are no longer errors on HTML:

    ![No error on HTML](./README.md_docs/clear-errors-html-validation.png)

    ##### Warnings
    - A warning was found: Section lacks heading. A heading is supposed to be added on the section element or turn the section into a div rather [Validator W3 html](https://validator.w3.org/nu/#textarea)

    ![Warning 1](README.md_docs/warning1-validation.png)

    - HTML is now clear of errors and warnings.

* CSS
    <!-- Styling -->
    - An error on the nav bar referring to adding space in between the letters. A pixel unit should have been added in order for the spacing to take action. Please see screenprint below:
    
    ![CSS error](README.md_docs/css-error-validation.png)

    - After carefully fixing the errors, there appears to be no errors remaining [Validator W3 css](https://jigsaw.w3.org/css-validator/validator). 

    ![CSS clear of errors](README.md_docs/css-noerrors-validation.png)

* Lighthouse
    <!-- Lighthouse results -->
    - All images used on this project are set as background images, hence why the forms are blocking the women in the background. Just like any other background with content on top of it.
    - The Zola with Yoga site could not pass all the lighthouse tests. That was due to having large images, which were taking up a lot of space which caused uploading of the site to take long. Please see below screenshot:
    
    ![Lighthouse results](./README.md_docs/lighthouse-results-validator.png)

        + Performance = 41%
        + Accessibility = 96%
        + Best Practice = 100%
        + SEO = 100%

    ![Lighthouse failed results](./README.md_docs/lighthouse-failed-result-validator.png)

    - After consultation and research, I managed to reduce the images used on the site which definitely gave incredible results on the Lighthouse Results:
        + Performance = 92%
        + Accessibility = 100%
        + Best Practice = 100%
        + SEO = 100%
    - Please also see below screenshot taken for one of the pages:

    ![Lighthouse final result](./README.md_docs/lighthouse-final-result-validation.png)

### Unfixed Bugs
* On the signup form, the first and last name areas should only accept alphabets/ text. However it also accepts numbers. In future, I would like to exclude the possibility that user can put numbers.
  

## Deployment
* This site was deployed to GitHub pages. The steps are as follows:
    - In the GitHub repository, navigate to the Settings tab
    - Under General section, select Pages
    - From the source section, click drop down to select Deploy from branch 
    - Under Branch, select main, file/root and save  
    - Once the save button is clicked, wait a couple of minutes to refresh the page
    - After refreshing, the code page will appear and show that deployemnt was successful.

The live link can be found here - https://hlomphosibeko.github.io/Zola-with-Yoga/

## Credits
### Content 
* The quote used on the bookings page is taken from this site: [Tegan by yoga]https://www.teganbyoga.com/post/best-yoga-quotes
* The terms and conditions used on the sign up page are taken from this site: [Terms and conditions](https://yogauonline.com/terms-and-conditions/)
* I struggled with getting my footer to stick to the bottom of the page, this site helped me: [Footer](https://www.w3schools.com/howto/tryit.asp?filename=tryhow_css_fixed_footer)
* The style for the submit button found on the sign up and bookings page was found in this site: [Signup W3School](https://www.w3schools.com/css/tryit.asp?filename=trycss_buttons_animate3)
* The position of which the images on the shop page are placed is found on this website: [Grid container](https://www.shecodes.io/athena/22284-how-to-scale-images-with-different-sizes-in-a-css-grid#:~:text=If%20your%20pictures%20have%20different,resized%20to%20fit%20its%20container.)
* Alan, a tutor at CI, assisted me with the Favicon.
* [Navigator](https://stackoverflow.com/questions/42095405/logo-and-navigation-bar-inline#:~:text=You%20could%20also%20simply%20put,align%20to%20center%20things%20horizontally.) 
* Roo, a tutor assisted with getting the shop page to have the grid look.
* Sean, a tutor assisted with removing the space on the side of the page which was caused by the width.
* Rebecca, a tutor helped me the issue with the background image that was applied on both CSS and HTML.
* Moritz, a mentor assisted with the transparent background color for the welcome message and the forms.

### Media
* The images used on this website are taken from various sites: [Yoga Images](https://www.pexels.com/search/yoga/) , [Yoga incense](https://www.pexels.com/search/incense/)
* The logo image used is taken from this site: [Yoga Logo](https://www.canva.com/design/play?type=TAB7AVEOUWQ&category=tACZCvjI6mE&locale=de-DE)
* Oisin, a Tutor from Code Institute provided a guide on how to compress images, which was found on this site: [TinyJPG](https://tinyjpg.com/)
* The favicon was found on this site: [Favicon](https://favicon.io/emoji-favicons/woman-in-lotus-position)
* Roman, a tutor at CI, advised that I can resize images with a default setting for Windows devices.