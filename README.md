# Billie Eilish Website

Stream One Project: User Centric Frontend Development - Milestone Project

This is a website is dedicated to American singer and a songwritter, Billie Eilish. This website promotes artist's new album, presents her pictures, audio and video clips, tour events, as well as allows its user to subscribe to email list and contact the artist.

This website consists of the following pages:

1. Home - page promotes recently released album and provides a user with link to purchase and / or stream it.

2. Media - page contains music albums embeded from Spotify and YouTube videos.

3. Photos - page contains artist's photo gallery in a form of collage.

4. Tour - page contains information about upcoming events and provides it's user with links to external websites of ticket vendors.

5. Contact - page contains a contact form that enables user to submit an enquiry.

6. Subscribe - page contains form that takes an email address information from a user that wishes to subscribe to the newsletter.

## Demo

Website demo is available [here](https://jbroks.github.io/Billie_Eilish_Website/ "Billie_Eilish_Website").

## UX

### UX Design

In my project I was aiming to achieve tidy and well structured design, while providing all essential information.

In order to create a stylish and modern look I used the following three colors in my design: off-white (`#f5f5f5`), black (`#010101`), and silver (`#acacac`). White-silver-black color scheme also harmonises well with artist's cover artwork and photos.

### Target Audience

### User Stories

### Mockups & Wireframes


## Features

### Existing Features

The navabar stays collapsed on mobile devices and displays with lower resolution.
Websites uses the buttons feature in Bootstrap.
Bootstrap forms were used to design contact us form and subscribe.
Arrow on title pages scrolls down to the next section.

### Features left to implement

In the future video carousel could be implemented in the media section. Alternatively the restriction could be made so only one video is played at the time.

Also modals for Subscribe and Contact Us form could be implemented to inform the user that their form was submitted. Modals would pop up after all data is validated and sent. Validation on forms could be enhanced to check e.g. for valid email domain etc.

In the fututre it would be useful to implement solution that would make scroll effect smoother.

## Technologies used

### Programming languages

- HTML - The project used **HTML** to define structure and layout of the web page;

- CSS - The project used **CSS** stylesheets to specify style of the web document elements;

### Libraries

- [Font Awesome](https://fontawesome.com/v4.7.0/) -

- [Google Fonts](https://fonts.google.com/) - **Google Fonts** library was used to set up font type for the document;

### Frameworks

- [Bootstrap](https://getbootstrap.com/) -

### Others

- [Gifox](https://gifox.io/) - Tool was used to record the gif presented in the demo secion of this README files;

- [Am I Responsive](http://ami.responsivedesign.is/#) - Online tool was used to display the project on various devices;

- [Figma](https://www.figma.com/) - Software was used to create a project mockup;

## Testing

Website was tested across different browsers, display sizes and devices to check its responsivness. While testing it was noticed that the heading in the new album section covers the person in the picture therefore the album title was moved to the bottom of container, and padding was adjusted accordingly.

Buttons and links were tested to ensure that they work correctly and are opened in a new page. Any broken links were fixed.

Forms were tested to ensure that validation checks work and to make sure that all fields are filled before clicking 'send' button. Email field was tested to check if it is possible to send the form without @ symbol. All required fields were tested to ensure that form cannot be send without all required information.

Scroll-down arrow was tested to ensure that it works properly on every title page. Bug was noticed while testing arrow, namely the navbar was covering the section title. In order to fix that padding was addjusted to make the navbar look good after scroll-down.
However, for the photo page this problem was left unresolved. It will have to be addressed in the future by applying an offset of some sort that would e.g. place the navbar at the bootom of a previous section.

Another issue related to images was the fact that I was unable to find a high quality image that could be used as a background photo for the main page and title section of the remaining pages. The main photo was replaced with a slightly better quality picture, however it still could be improved.

Finally, on some displays background photos are cropped due to use of 'cover' setting in the background-size property.

Video clips and embeded audio were tested to ensure that they play and full screen works correctly. While testing on mobile devices it was discovered that the second spotify iframe does not always load properly.

### Code validation

#### CSS

#### HTML

### Features testing

#### Feature 1

##### Bugs:

#### Feature 2

##### Bugs:

### Responsivness testing

### User stories testing

**User Story 1:**

- Solution:

## Deployment

The site was developed using Cloud9 and AWS Cloud 9. To keep records of different versions of all project files git version control system was used. 

In order to track the changes in the local repository the following steps were taken:

- command `git add 'filename'` - to update what will be committed;

- command `git commit` - to commit the changes.

Using `git push` command all changes from the local repository were pushed to the remote one on GitHub.


This dashboard project is hosted using GitHub pages, deployed directly from the `master` branch. 

To deploy my dashboard project from GitHub I followed these steps:

1. On GitHub website I logged onto my account and navigated to [my repository](https://github.com/JBroks/Billie_Eilish_Website);

2. Under my repository name, I clicked on **Settings** tab;

3. I scrolled down to the **GitHub Pages** section;

4. On the **Select source** drop-down menu I selected `master` as my GitHub Pages publishing source;

5. I clicked **Save**.

The deployed site will update automatically upon new commits to the `master` branch. It is important to remember that for the site to deploy correctly on GitHub pages, the landing page must be named `index.html`.

In order to clone my GitHub repository to your local one you should follow these steps:

1. On GitHub navigate to [my repository](https://github.com/JBroks/Billie_Eilish_Website);

2. Under the repository name, click **Clone or download**;

3. In the Clone with HTTPs section, copy the clone URL for the repository;

4. Go to IDE that you are using and open terminal;

5. Change the current working directory to the location where you want the cloned directory to be made;

6. Type `git clone` and then paste the URL you copied in Step 3;

```
$ git clone https://github.com/JBroks/Billie_Eilish_Website.git
```

7. Lastly press **Enter** and your local repository will be created.

## Credits

### Content

Tour information presents acctual events, this information was obtained from the official [website](https://site.billieeilish.com/ "Tour").

Privacy policy is linked to the acctual policy used by the artist. 

### Media

Main image used in the first section of every page (page title) was obtained from Pinterest website and can be viewed [here](https://i.pinimg.com/originals/6c/eb/99/6ceb996655ad9714d1c46dc64b938276.png "Main photo").

New album photo was obtained from the official Billie Eilish [website](https://site.billieeilish.com/ "New album photo").

All images in the photo gallery were obtained from the [Pinterest](https://www.pinterest.ie/maryiscoolbeans/bully-eyelash/ "Photos").

### Acknowledgements

Navbar and the footer was created using Bootstrap and instructions from the Code Institute course.

Code for the background image was obtained from [here](https://css-tricks.com/perfect-full-page-background-image/ "Background").

Hover effect on the navbar was taken from [here](https://codepen.io/maheshambure21/pen/QwXaRw "Stroke").

Outline effect to text was achieved by using [this](https://stackoverflow.com/questions/4919076/outline-effect-to-text "Hollow text") code.

Code for a scroll-down arrow was taken from [here](https://codepen.io/bitstarr/pen/XjaJGz "Arrow"). The use of the anchor for the arrow was suggested by my mentor Maranatha Ilesanmi.

Photo gallery idea was inspired by [this](https://www.w3schools.com/howto/howto_css_image_grid_responsive.asp "Photos gallery") code.

Many thanks to my mentor **Maranatha Ilesanmi** for support and advice throughout the project.

### Disclaimer

*This is for educational use.*

