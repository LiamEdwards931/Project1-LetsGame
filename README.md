![CI logo](https://codeinstitute.s3.amazonaws.com/fullstack/ci_logo_small.png)

# LETS GAME

The purpose of Lets Game is to get people who love gaming to come together to make new friends.
Its intended audience are people who do not currently have people to play games with or are looking to branch out, they can do this by simply seeing when
and where there is a meetup.

see the live version [here](https://liamedwards931.github.io/Project1-LetsGame/)

![Lets Game website viewed on different screen sizes](readme/images/responsive-screenshot.png)

## Features

### Existing Features

- **Navigation Bar**

  - The navigation bar is consistent across both pages, has responsive styling and highlights when you are on your current page
the navigation bar has 4 links: home, about us, meetup and sign up, Allowing for easy navigation of the website.

  - There is no need to use the back button across all of the devices as the links take you to and from the different sections.

![screenshot of the navigation bar](readme/images/navbar-letsgame.png)

- **Index Page about us**
  - The about us section appears immediately and has strong visuals on the three main platforms to immediately give the viewer a context of the page.
    each of the logos has a small eyecatching heading to give a description on the intended purpose of the page.

![screenshot of the about us section](readme/images/aboutus%20screenshot.jpg)

- **Meetup times section**
  - The meet-up section is broken up into 3 different parts: Xbox, Playstation and PC - this is so it's very clear which meetup you should attend
    based on the type of platform you play.
  - The section gives you a welcome to each platform and some suggestions to prepare for the meetup such as having your network ID handy so you can continue to meet up after the event is over.

![screenshot of the meetup times section](readme/images/meetuptimes%20screenshot.jpg)

- **Footer**
  - The footer is fixed to the bottom of the screen and has a contrast to the rest of the site for importance.
  - it has 3 sections of navigation: Social media, Gaming platforms, Social gaming platforms. The social media is for the Lets Game updates and to keep in touch with other gamers. The Gaming platforms is so if the user doesn't have know their gaming ID they can access it through the link and finally the social gaming - this has discord for PC players, twitch and youtube so you can view each others channels if they have one.

![screenshot of the footer](readme/images/footer%20screenshot.png)

- **Sign up page**
  - This page will allow the user to sign up with the lets game community. The sign page has a form that requires the user to enter their first and last names, email address and the type of platform they are playing on.
  - The sign up form has "required" values set to it so users have to enter there credentials before they can submit the form.

![Screenshot of the signup page](readme/images/signupscreenshot.jpg)

### Future Features

- The website will have a running server that will take the user to a chatboard after they have signed up.

## Testing

- **HTML**
  - No errors returned when passing through [W3C Validator](https://validator.w3.org/nu/?doc=https%3A%2F%2Fliamedwards931.github.io%2FProject1-LetsGame%2F)

- **CSS**
  - No errors returned when passing through [jigsaw validator](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fliamedwards931.github.io%2FProject1-LetsGame%2F&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en)

- **Feature testing**
  - Tested all links - working as intended, all external links open in new tab with relevant aria-labels.
  - Media queries tested as thoroughly as I could, no errors from what I have tested.
  - Webpage is responsive to a minimum width of 320px
  - Devtool tested the webpage using different screen sizes and no errors from what I have tested.
  - Index page lines vertically when screen size changes allowing clear information.
  - No pixelation in images used.

## BUGS

### Index Page

- Fixed bugs
  - Navigation bar wouldn't respond when screen size changed.
  - Circle divs in about us section were too far to the left when screen size decreased.
  - Footer disappeared when content pushed it down on index page.
  - Meet up section overlapped when screen size decreased.
  - Links wouldn't connect to the section ID's
  - About-us section kept overlapping the meetup section
  
### Signup Page

- Fixed Bugs
  - Header pushed to the left when screen size decreased.
  - Form on submit sent you to a new page with a 404 error.
  - Form submit button was smaller than the text content.
  - Footer wouldn't stick to the bottom of the page.
  - Footer stuck half way up the page when screen size decreased.
  - Footer overlapped the sign up form when screen height decreased.
  - Labels on form didn't show up above the form input.

I had identified these bugs through testing the media queries on the devtools toolbar, and also running the code through the validator tools.
  
- **Unfixed Bugs**
  - Tested the website to the best of my ability and couldn't see any apparent bugs that needed fixing.

- **lighthouse score**

![Screenshot of website score on lighthouse](readme/images/lighthouse-score.png)
- lower score on performance due to the file size of the background images.
- Accesibility score is high due to the contrast of colors and the backgrounds set on containers to ensure good visibility for all content.
  
## Deployment

- This site was deployed through Github pages the steps to do so are as follows:
  - Git add . - in the codeanywhere terminal
  - Git commit -m"with message of what you are committing"
  - Git Push - Pushes the code to Git Hub
  - Go to repository of the website you are working on.
  - Go to the settings option.
  - Scroll down to the pages section on the left hand side.
  - Select the main branch to deploy.
  - Github will give you the live link for your webpage.
  - The live site can also be reached here: [Lets Game](https://liamedwards931.github.io/Project1-LetsGame/)

## Credits

- **Content**
  - The icons used in the Footer and the Meetup section are taken from [Font Awesome](https://fontawesome.com/kits)
  - Took guidance for box shadow CSS styling from [W3 Schools](https://www.w3schools.com/)

- **Media**
  - The background image used for the body on the index page is supplied by [Pixabay](https://pixabay.com/)
  - The background image used in the about-us section was taken from[FreePik](https://www.freepik.com/free-photo/cool-geometric-triangular-figure-neon-laser-light-great-backgrounds_9970519.htm#query=background%20gaming&position=2&from_view=search&track=ais)
  - The Xbox logo in the about-us section was taken from [Vecteezy](https://www.vecteezy.com)
  - The Playstation logo in the about us section was taken from [Pintrest](https://www.pinterest.co.uk/pin/598204763023781305/)
  - The PC logo in the about us section was taken from [Vecteezy](https://www.vecteezy.com/free-vector/pc-logo)

