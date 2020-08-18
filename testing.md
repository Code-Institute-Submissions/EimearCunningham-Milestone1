# Testing
## Validation Services
The [W3C Markup Validation Service](https://validator.w3.org/) and the [W3C CSS Validation Service](https://jigsaw.w3.org/css-validator/) was used to validate all HTML5 and CSS3 code.

### Errors / Warnings found by W3C Markup Validation Service:
- "Error: No p element in scope but a p end tag seen." This error appeared 3 times - 
Once per every paragraph in the Work Experience Timeline (Code taken from Bootsnipp).
I realised that this error was occuring because a H4 element was being placed **inside** a paragraph element. I fixed this by simply moving the H4 element outside the Paragraph element.

### Errors / Warnings found by W3C CSS Validation Service:
- No Errors found.
- Warnings: Ignored as these extensions are needed for different browsers.
    - -moz-transition is an unknown vendor extension
	- -webkit-transition is an unknown vendor extension
	- -o-transition is an unknown vendor extension
	- -moz-transition is an unknown vendor extension
    - -webkit-transition is an unknown vendor extension
	- -o-transition is an unknown vendor extension
        
## Testing User Stories 

1. As a recruiter, I want to learn more about this candidate, 
including their skills.
    * Upon entering the site, the user can clearly see the "About Me" paragraph, a headshot image and my list of skills.
    * The "About Me" paragraph is visible at the top of the page on all device sizes.
    * The user can always easily navigate back to the "About Me" section, using the link in the navigation bar, which is fixed to the top of the page.

2. As a recruiter, I want to view projects that this candidate 
has worked on to get a feel for their work.
    * The "Projects" section can be accessed easily in two ways - Either by scrolling past the "About Me" section,
    or by selecting the "Projects" link from the navigation bar.
    * The projects section provides an album with pictures of three projects, including links to view these projects on GitHub.

3. As a recruiter, I want to view the candidates relevant work 
experience.
    * The "Work Experience" section is located directly underneath the "Projects" section and can be found by scrolling to the section. It is 
    also accesable through the navigation bar.
    * The section contains an easy to read timeline of my most recent work experince.

4. As a recruiter, I want to be able to easily see how I can contact 
the candidate should I wish to get in touch.
    * There are 2 links on the page to access the "Contact Me" section - One in the navigation bar, and an inline link in the "About Me paragraph. Both of these links lead to 
    a contact form which requests the users name, email address and message.
    * The footer is located directly underneath the contact form, and contains further contact details such as phone, email address and links to my social media platforms.

5. As a recruiter, I want to be able to download the candidate’s CV in PDF format.
    * There are 2 places where the user can download my CV from on the site - One is located in the "About Me" section at the top of the page, and the second is located in the page footer.
    This will save the user from scrolling back to the top of the page to retrieve my CV.

## Manual testing of all elements and functionality 

1. Navigation bar
    * Ensure that the navigation menu items change from inline to a dropdown menu when screen size is changed from desktop to tablet, and stays this way for mobile screen size.
    * Click on burger icon when screen size is reduced. Make sure that menu drops down and that all links are working.
    * Click on each menu item and make sure it links to the correct section. Repeat this for each screen size.
    * Click on the header logo (my name and title) and ensure it links to the top of the page, as the user would expect.
    * Ensure that the navigation bar is fixed to the top of the page when users scroll. Test this on all device sizes.
    * Hover over each navigation item and ensure that there is a color change and that each item expands.

2. About Me Section
    * Click the "get in touch" link in the About Me paragraph to make sure it links to the Contact Me Section.
    * Click the "download CV" item and check that my CV opens in a new tab.
    * Hover over each list item under "my skills" and ensure that they expand as expected.
    * Reduce screen to tablet size and make sure that layout changes so that each column takes up the full width. Ensure that this stays the same for mobile screen size.

3. Projects Section 
    * Click each of the three "view" buttons to make sure they open my GitHub profile in a separate tab. Repear for all screen sizes.
    * Hover over each of the three "view" buttons to check that they change color in the hover state.
    * Reduce screen size to tablet size and check that projects display vertically instead of in a row of three. Make sure the display stays this way for mobile.

4. Work Experience Section  
    * Reduce screen size to medium and check that the timeline layout changes accordingly. (Line to left with all 3 experience divs to right)
    * Reduce screen size to mobile to ensure that the layout stays the same as tablet size mentioned above.

5. Contact Me Section
    * Try submitting the form with empty fields to make sure the user cannot submit without filling in each required field.
    * Try submitting the form without using "@" in the email input to ensure the user will be told that this is not a valid email address.
    * Hover over the "Submit" button to check that the color changes.

6. Pager footer 
    * Hover over social icons to check that a color change and transition take place.
    * Click on each social icon to ensure that the page opens in a new tab.
    * Hover over the "download" icon to check that the same color change and transition take place, as the social icons.
    * Click on the "download " icon to ensure it opens my CV in a separate tab.
    * Reduce the screen size to mobile and check that the Download CV column is hidden at this size.
    
