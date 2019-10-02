# Billie Eilish Website

Stream One Project: User Centric Frontend Development - Milestone Project

![alt text](https://github.com/JBroks/Billie_Eilish_Website/blob/master/gif/billie.gif "Gif")

This is a website is dedicated to American singer and a songwriter, Billie Eilish. This website promotes artist's new album, presents her pictures, audio and video clips, tour events, as well as allows its user to subscribe to email list and contact the artist.

This website consists of the following pages:

1. Home - page promotes recently released album and provides a user with link to purchase and / or stream it.

2. Media - page contains music albums embedded from Spotify and YouTube videos.

3. Photos - page contains artist's photo gallery in a form of collage.

4. Tour - page contains information about upcoming events and provides it's user with links to external websites of ticket vendors.

5. Contact - page contains a contact form that enables user to submit an enquiry.

6. Subscribe - page contains form that takes an email address information from a user that wishes to subscribe to the newsletter.

## Demo

Website demo is available [here](https://jbroks.github.io/Billie_Eilish_Website/ "Billie_Eilish_Website").

## UX

### UX Design

In my project I was aiming to achieve tidy and well structured design, while providing all essential information.

In order to create a stylish and modern look I used the following three colors in my design: off-white (`#f5f5f5`), black (`#010101`), and silver (`#acacac`). White-silver-black color scheme also harmonizes well with artist's cover artwork and photos.

### Target Audience

This website aims to attract Billie Eilish's fans and people that would like to learn more about a total music output of the artist. It also provides means to contact the artist by any user who would like to e.g. invite her to participate / hire her for an event that they are organising.

The main objective of this project is to create a page that will provide an access to a useful information about the artist (creative work i.e. music and videos, photos, events, newsletter subscription) and enable its user to contact the artist and / or follow her on social media. The project promotes the artist and her work and inform its user about other sources that enable them to attain more information (i.e. social media, ticket vendors websites, links to purchase and stream music).

### User Stories

The following user stories were used to design this website:

**User Story 1:** As a user who does not know much about Billie Eilish I would like to check what sort of music she is making, so I can decide if that is something that suits my taste.

**User Story 2:** As a fan / user I would like to listen to her music and see some of her videos.

**User Story 3:** As a fan / user I would like to find her social media account details so I can follow her work.

**User Story 4:** As a fan / user I would like to get more information about her work and upcoming events on regular basis.

**User Story 5:** As a fan / user I would like to check some of her pictures to see what I can expect from events that she is taking part in and what sort of image she is creating.

**User Story 6:** As an event organiser I would like to be able to contact her to discuss possibility of her performing during my event.

**User Story 7:** As an event organiser I would like to be able to check some of her work to make sure that she is a kind of artist that would be suitable for my event.

**User Story 8:** As an event organiser I would like to be able to check some photos and videos from her past events to evaluate her performance and decide if I would like to hire her.

**User Story 9:** As a fan / user I would like to be able to contact her in order to communicate any of my queries, ideas etc.

**User Story 10:** As a fan / user I would like to learn about any upcoming events and how can I purchase tickets in order to see her performing live.

### Mockups & Wireframes

The following wireframes were created using **MockFlow WireframePro** to design the website layout options:

- [Mobile display](https://github.com/JBroks/Billie_Eilish_Website/blob/master/mockups/wireframes_mobile.pdf)

- [Medium display](https://github.com/JBroks/Billie_Eilish_Website/blob/master/mockups/wireframes_medium.pdf)

- [Desktop display](https://github.com/JBroks/Billie_Eilish_Website/blob/master/mockups/wireframes_desktop.pdf)

Additionally [this](https://github.com/JBroks/Billie_Eilish_Website/blob/master/mockups/website_mockup.pdf) mockup for a desktop display was created using **Figma**.

## Features

### Existing Features

The webpage consists of the following features:

- **Navbar** - The navbar stays collapsed on mobile devices and Font Awesome bar icon is used. The navbar contains links to associated pages i.e. Home, Media, Photos, Tour, Contact, Subscribe;

- **Buttons** - The project uses Bootstrap button features;

- **Down Arrow** - Arrow on each title pages scrolls down to the next section;

- **Social media icons** - The project uses Font Awesome icons for social media links;

- **IFrames** - iframes features were used to embed music from Spotify and YouTube videos;

- **Photo gallery** - Photo gallery contains artist's photos;

- **On Tour table** - On tour table provides information about event's date, venues, town / city and country, and button that redirects a user to ticket vendor website;

- **Contact Us form** - The project uses Bootstrap form features. The form requires to provide first and last name, email address, phone number and message;

- **Subscribe form** - The project uses Bootstrap form features. User provides his / her email address to subscribe;

- **Footer** - simple footer containing links to artist's social media accounts, links to Subscribe page and Privacy Policy, and copyrights.


### Features left to implement

In the future video carousel could be implemented in the media section. Alternatively, the restriction could be made so only one video is played at the time.

Also modals for Subscribe and Contact Us form could be implemented to inform the user that their form was submitted. Modals would pop up after all data is validated and sent. Validation on forms could be enhanced to check e.g. for valid email domain etc.

In the future it would be useful to implement solution that would make scroll effect smoother.

Another useful feature would be back-to-top button.

## Technologies used

### Programming languages

- **HTML** - The project used HTML to define structure and layout of the web page;

- **CSS** - The project used CSS stylesheets to specify style of the web document elements;

### Libraries

- [Font Awesome](https://fontawesome.com/v4.7.0/) - Font Awesome bars icon for menu on mobile devices was used in the project, as well as icons for social media links;

- [Google Fonts](https://fonts.google.com/) - Google Fonts library was used to set up font type for the document;

### Frameworks

- [Bootstrap](https://getbootstrap.com/) - The project used Bootstrap to create nice grid layout, and position elements within grids. Also elements such as navbar, buttons and forms were created using Bootstrap;

### Others

- [Gifox](https://gifox.io/) - Tool was used to record the gif presented in the demo section of this README files;

- [Am I Responsive](http://ami.responsivedesign.is/#) - Online tool was used to display the project on various devices;

- [Figma](https://www.figma.com/) - Software was used to create a project mockup;

- [MockFlow WireframePro](https://www.mockflow.com/) - Online tool that was used to create wireframes.

## Testing

### Code validation

#### CSS

CSS code was validated using the [W3C CSS Validation Service - Jigsaw](https://jigsaw.w3.org/css-validator/).

While validating CSS code the following warning appeared: "Imported style sheets are not checked in direct input and file upload modes". Warning was investigated and [this](https://stackoverflow.com/questions/25946111/importing-css-is-ending-up-with-an-error) Stack Overflow thread explained that it is just an information that imported style sheet will not be validated.

Also, the following warning appeared during the CSS validation:
```
144	.btn--buy	Same color for background-color and border-color
322	.btn-send	Same color for background-color and border-color
407	.btn-tour	Same color for background-color and border-color
```

This warning was ignored as these attributes were set up like this purposely.

#### HTML

HTML code was validated using the [W3C Markup Validation Service](https://validator.w3.org/).

All errors and warnings were addressed except the following: 

- Photos page warning

```
Section lacks heading. Consider using h2-h6 elements to add identifying headings to all sections.

From line 81, column 5; to line 81, column 25

 -->↩↩    <section id="photos">↩↩   
 ```

This warning was ignored as no heading is required.

### Features testing

#### Navbar

Navbar was tested to check if it correctly re-directs a user to appropriate page. 

To improve information architecture 'active' class was added to active navbar list item.

##### Bugs:

No bugs were left unresolved.

#### Buttons

All buttons and links were tested to ensure that they work correctly and are opened in a new page. 

##### Bugs:

Any broken links were amended appropriately to direct a user to the correct external website. In case where it was missing, attribute `target="_blank"` was added to the link to open the page in a new tab.

#### Down Arrow

Scroll-down arrow was tested to ensure that it works properly on every title page. 

##### Bugs:

Bug was noticed while testing arrow, namely the navbar was covering the section title. In order to fix that padding was adjusted to make the navbar look good after scroll-down.
However, for the photo page this problem was left unresolved. It will have to be addressed in the future by applying an offset of some sort that would e.g. place the navbar at the bottom of a previous section.

#### Social Media Icons

Links were tested to ensure that they work correctly and are opened in a new page. 

##### Bugs:

In case where it was missing, attribute `target="_blank"` was added to the link to open the page in a new tab.

#### IFrames

Video clips and embedded audio were tested to ensure that they play and full screen works correctly.

##### Bugs:

NO bugs identified.

#### Photo gallery

Photo gallery was created using bootstrap grid layout, therefor testing mainly focused on the responsiveness. Also, the code was checked to include ` alt` attribute for each photo.

##### Bugs:

In some cases pictures had to be rearrange slightly to provide a better visual finish for the end row (i.e. so the gap between end of each column and the footer was similar).

#### On Tour table

##### Bugs:

Paddings and margins were adjusted for different resolutions to provide a nice looking layout for the content.

#### Contact Us & Subscribe forms

Forms were tested to ensure that validation checks work and to make sure that all fields are filled before clicking 'send' button. Email field was tested to check if it is possible to send the form without @ symbol. All required fields were tested to ensure that form cannot be send without all required information.

##### Bugs:

No bugs were identified.

#### Footer

##### Bugs:

No bugs were identified.

### Responsiveness testing

This site was tested across multiple browsers (Chrome, Safari, Microsoft Edge, Mozilla Firefox, Opera) and on multiple mobile devices (iPad Mini, iPad, Sony Xperia) to ensure compatibility and responsiveness. 

Chrome developer tools were used during the development process to inspect responsiveness for the following devices:

- iPad Pro / iPad / iPad Mini (portrait & landscape);

- iPhone 5/SE (portrait & landscape);

- iPhone 6/7/8 (portrait & landscape);

- iPhone 6/7/8 Plus (portrait & landscape);

- iPhone X (portrait & landscape);

- Android (Pixel 2) (portrait & landscape).

Furthermore, [Responsinator](https://www.responsinator.com/) was used to test responsiveness of the final version of the project.

The website is fully responsive and working well on mobile devices.

#### Bugs

While testing it was noticed that the heading in the new album section covers the person in the picture therefore the album title was moved to the bottom of container, and padding was adjusted accordingly.

### User stories testing

**User Story 1:**

- Solution: Media section of the website provides two previous albums of the artist and various videos. Also, home page provides a link to stream the newly released album, and footer includes links to social media sites (e.g. Spotify, YouTube).

**User Story 2:**

- Solution: Media section of the website provides two previous albums of the artist and various videos. Also, home page provides a link to stream the newly released album, and footer includes links to social media sites (e.g. Spotify, YouTube).

**User Story 3:**

- Solution: Footer contains full set of links to artist's social media accounts.

**User Story 4:**

- Solution: Tour section of the website contains a list of upcoming events with detail information about venue and button that will re-direct user to external website of a ticket vendor. User can also subscribe to the newsletter to receive regular updates about upcoming events, new album releases etc.

**User Story 5:**

- Solution: Photos section of the website provides various images, and user can also click on the Instagram icon in the footer to see more photos of the artist on her social media account.

**User Story 6:**

- Solution: "Contact Us" form enables its user to contact the artist.

**User Story 7:**

- Solution: Media section of the website provides two previous albums of the artist and various videos. Also, home page provides a link to stream the newly released album, and footer includes links to social media sites (e.g. Spotify, YouTube).

**User Story 8:**

- Solution: Photos section of the website provides various images. User can also click on the Instagram and / or YouTube icon in the footer to see more photos and videos of the artist on her social media account.

**User Story 9:**

- Solution: "Contact Us" form enables its user to contact the artist.

**User Story 10:**

- Solution: Tour section of the website contains a list of upcoming events with detail information about venue and button that will re-direct user to external website of a ticket vendor.

### Unresolved bugs

On some displays background photos are cropped due to use of 'cover' setting in the background-size property.

Another issue related to images was the fact that I was unable to find a high-quality image that could be used as a background photo for the main page and title section of the remaining pages. The main photo was replaced with a slightly better-quality picture, however it still could be improved.

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

Tour information presents actual events, this information was obtained from the official [website](https://site.billieeilish.com/ "Tour").

Privacy policy is linked to the actual policy used by the artist. 

### Media

Main image used in the first section of every page (page title) was obtained from Pinterest website and can be viewed [here](https://i.pinimg.com/originals/6c/eb/99/6ceb996655ad9714d1c46dc64b938276.png "Main photo").

New album photo was obtained from the official Billie Eilish [website](https://site.billieeilish.com/ "New album photo").

All images in the photo gallery were obtained from the [Pinterest](https://www.pinterest.ie/maryiscoolbeans/bully-eyelash/ "Photos").

Favicon used for the project was download from [here](https://www.roblox.com/library/2310054681/blohsh "Favicon").

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

