# The Monkees

Milestone Project 1: User-Centric Frontend Development - Code Institute

This is a website is for the fans of the famous rock band "The Monkees". It allows them to watch their videos, listen to their musics, check out their tour dates and the possibility to contact the band to perfom to their party (chrismas party, birthday or Wedding).

## **Demo**

A live demo can be found [here](https://comanezz.github.io/the_monkees/index.html).

## UX
 
Use this section to provide insight into your UX process, focusing on who this website is for, what it is that they want to achieve and how your project is the best way to help them achieve these things.

**The primary target audiences are their fans or people who already know the rock band.** 

#### User Stories:

- As a user type, I want to perform an action, so that I can achieve a goal.
- As a new visitor, I want to see what the site show
- As a fan I want to hear music or watch videos of The Monkees
- As a fan or client I want to book an event (party, weddings, christmas)
- As a fan I want to check out the tour dates
- As a fan I want to buy a ticket for a tour

#### This project is the best way to achieve these things because:

- This website is easy to navigate
- There is no overloading information

##### Wireframes

- [Mobile view](https://github.com/comanezz/the_monkees/blob/master/assets/wireframe/balsamic-mobile-monkees.pdf)
- [Desktop view](https://github.com/comanezz/the_monkees/blob/master/assets/wireframe/desktop-wireframe-monkees%20(1).pdf)

## Features

Each page has a responsive **navbar** with a highlighted button **"Book an event"**  (right side) to catch the eye of the user. 
The **logo** (top left) is bigger than the navbar.
Each page has a footer with **Social Media Icons** linking to the social media pages of the Rock Band.

**Home**

The Home page uses a carousel with 3 pictures switching alone or can be switch manually. 
There is no big title of the band's name on this page because we can clearly see written "The Monkees" on the logo and in the main pictures. 

Each rectangle includes an image and a title which are clickable. The user has multiple choice to navigate in the website by selecting one of the clickable rectangle under the pictures.

**Videos**

The Video page features 3 embed Youtube video.

**Music**

The Music page features:
 - 4 images cover
 - 3 lyrics button
 - 1 Spotify player. 

 The images are used above the audio player and the lyrics buttons. Each audio has a different song which is related to the image and the lyrics. 


**Tour**

The Tour page features an image (representing the person who will perform in this next event), a table showing the date and location and 3 tickets button. A table has been used because it was the easiest way to align the ticket buttons besides the location content. 

**Book an Event**

The Book an Event page features a contact form requesting an email, type of event, date, location and additional information. 
Bottom of the form there is a send button. 
 
### Existing Features
- Feature 1 - allows users X to achieve Y, by having them fill out Z
- Footer Social Icons.

For some/all of your features, you may choose to reference the specific project files that implement them, although this is entirely optional.

In addition, you may also use this section to discuss plans for additional features to be implemented in the future:

### Features Left to Implement
- I would like to make the form working being able to receive the information sent by the customer. 

## Technologies Used

- **HTML5**
- **CSS3**
- [Bootstrap Framework](https://getbootstrap.com/)
  - The project uses **Bootstrap4** to simplify the structure of the website and to build a responsive website .
- [Font Awesome 4.7](https://fontawesome.com/v4.7.0/)
    - The project uses **Font Awesome** to provide icons.
- [Google Fonts](https://fonts.google.com/)
  - The project uses **Google Fonts** to style the website fonts.
- **Javascript libraries** used for the responsive navbar, carousel and modal.
    - [Popper.js](https://popper.js.org/)
    - [JQuery](https://jquery.com)
- **IDE** used to develop the website: writting, debugging and running the code.
  - [Cloud9 IDE](https://aws.amazon.com/cloud9/?origin=c9io)
  - [Visual Studio Code](https://code.visualstudio.com/)


## Testing

[W3C CSS Validation Service](https://jigsaw.w3.org/css-validator/) and [W3C Markup Validation Service](https://validator.w3.org/) has been used to check the validity of the website code.

- **As a fan I want to navigate to the website and see what I can find**
  - The navbar stays always at the top of the page
  - The user can navigate through the button in the nav. They work correctly
  - The logo in the nav always bring back the user to the home.page if he clicks on it.

For any scenarios that have not been automated, test the user stories manually and provide as much detail as is relevant. A particularly useful form for describing your testing process is via scenarios, such as:

1. Contact form:
    1. Go to the "Book an Event" page
    2. Try to submit the empty form and verify that an error message about the required fields appears
    3. Try to submit the form with an invalid email address and verify that a relevant error message appears
    4. Try to submit the form with all inputs valid and verify that a success message appears.

In addition, you should mention in this section how your project looks and works on different browsers and screen sizes.

You should also mention in this section any interesting bugs or problems you discovered during your testing, even if you haven't addressed them yet.

If this section grows too long, you may want to split it off into a separate file and link to it from here.

## Deployment

**This website is hosted using GitHub pages, the deployment steps were:**

1. Log into GitHub.
2. Navigate to my GitHub Pages site's repository: **the_monkees**.
3. Under the repository name, **click Settings**.
4. Scroll down to the GitHub Pages section.
5. Under Source click the drop-down button named None and select Master Branch.
6. The page is automatically refreshed, the website is now deployed.
7. Scroll back down to the GitHub Pages section to retrieve the link to the deployed website.

The deployed site will update automatically upon new commits to the master branch. In order for the site to deploy correctly on GitHub pages, the landing page is named index.html.

**To run locally, you can clone this repository directly into the editor of your choice by following these steps:**

1. On GitHub, navigate to the main page of the repository.
2. Under the repository name, click **Clone or download**.
3. In the Clone with HTTPs section, copy the clone URL for the repository.
4. Open the terminal.
5. Type `git clone`, and then paste the URL you copied in Step 3.
``` console
$ git clone https://github.com/USERNAME/REPOSITORY
```
6.Press **Enter**. Your local clone will be created.

To cut ties with this GitHub repository, type `git remote rm origin` into the terminal.

## Credits

### Content

- All the lyrics for the Music page were taken from [Genius.com](https://genius.com/) and [Azlyrics.com](https://search.azlyrics.com/)
- The dates and locations for the Tour page were taken from [Songkick.com](https://www.songkick.com/artists/485568-monkees/gigography) and [viagogo.ie](https://www.viagogo.ie/Concert-Tickets/Rock-and-Pop/The-Monkees-Tickets)
- The text for the Book Event page was written by me.

### Media

- The logo was taken from Google Images.
- Some photos were taken from [Pexels](https://www.pexels.com/), and some were taken from Google Images.
- Some videos were taken from [Youtube](https://www.youtube.com/results?search_query=themonkees).

### Acknowledgements

- I received inspiration for this project from:
  - [ACDC](https://www.acdc.com/) for the Home page and [Rolling Stones](https://www.rollingstones.com/live/) for the underline hover in the Navbar. 

**This is for educational use.**