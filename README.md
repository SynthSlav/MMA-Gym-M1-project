# Vagabond MMA Website
A modern, responsive website for Vagabond MMA, showcasing its unique features, classes, and services. Built with HTML, CSS, and Bootstrap, the website aims to attract potential members and provide a seamless browsing experience.
## Table of Contents
- [Overview](#overview)
- [Wireframe](#wireframe)
- [Colour Scheme](#palette)
- [Features](#features)
- [Testing](#testing)
- [Deployment](#deployment)
- [Credits](#credits)
- [Screenshots](#screenshots)

- ## Overview
Vagabond MMA is a responsive and performance-optimized website designed for an MMA gym. The project showcases a structured and user-friendly interface, providing essential information about the gym’s classes, coaches, schedule, and contact details.

The website is built with modern web technologies (HTML5/CSS/Bootstrap5), ensuring fast load times, mobile responsiveness, and SEO optimization. It includes key features such as an embedded promotional video, dynamic class schedules, and an intuitive navigation system to enhance user experience.

This is a web development project built with accessibility, performance and maintainability in mind.
--------------
## Wireframe
<br>
<details>
<summary><strong>Home Page Wireframe</strong> (Click to open)</summary>
<img src="assets/media/wireframe.png">
</details>
<br>

## Colour Scheme
__These are the following colours used in my project__
<br>
<details>
<summary><strong>Colour Scheme Palette</strong> (Click to open)</summary>
<img src="assets/media/palette.png" style="width:600px height:600px">
</details>
<br>

## Features

### Existing Features

__Navigation Bar__
  - The navigation bar is present on all pages of the Vagabond MMA Project
  - It is positioned at the top of the of every page, encouraging intuitive and easy navigation for all important sections like (Home, Classes, Contact etc.)
  - Designed with intended responsiveness, the nav bar is adapting to all screen sizes, featuring a hamburger collapsable menu on smaller screen sizes for a better and cleaner UX.

![navbar](assets/media/navbar-snippet.jpg)

__Landing/Hero Sections__
- __Home, Classes, About and Coaches__
   - The Home landing page features a quick introduction accompanied by a promo video, followed by brief sections showcasing the pages contents accompanied with a quick access link for intuitive and easy navigation.

<br>
<details>
<summary><strong>Class and Schedule Story Image</strong> (Click to open)</summary>
<img src="assets/media/class&schedule-story.jpg">
</details>
<br>

  - The Classes Page features a hero landing paralax image accompanied with text representing navigation coordination. This is all followed by classes content card sections that provide visual engagement with pictures and encourages the user to click on them for extra info pertaining them. Beneath it is the final section containing a link targeting the contact section where the sign up form is located.

  - The About section also features a hero landing paralax image accompanied with text to represent navigation. This is followed by a short double paragraph (single for sm screens) introduction, a double image section (single for sm screens) and a small testimony section (urther development can be made to transform the testimonial section into a carousel slider once more testimonials are created).

<br>
<details>
<summary><strong>Coaches Story Image</strong> (Click to open)</summary>
<img src="assets/media/coaches-story.jpg">
</details>
<br>

  - The Coaches page has a matching hero landing design as the other two, a quick introductory text to entice the user into checking the range of coaches in the team. This is followed by a responsive row of columns that contains the coaches image, title, and brief description of their expertise. And beneath it all a final section containing the link for contact/sign up page.

- __Timetable and Contact Us__
  - Compared to the previous pages, these two contain a simple landing hero that does not contain media or effects, its purpose its to simply inform the user of the current page he is on.

__(for UX story look up Classes section)__

  - The Timetable/Schedule page contains a single table presenting the schedule information, color coded for navigation (the table is not made to fully be responsive due to the sheer amount of content it has). For consistency and encouragement the pages final section is the same contact us/form link.

<br>
<details>
<summary><strong>Contact Story Image</strong> (Click to open)</summary>
<img src="assets/media/contact-story.jpg">
</details>

  - The Contact us page also has a simplistic landing/hero section in the top. It is followed by 2 coulmn section (1 col for sm screens) that features a Free trial sign up form with validation required (upon submitting the user is redirected to a success page to confirm form submission). The same section  also provide crucial info for the user when engaging the page. In the final section there is a GoogleMaps iframe showing the address of the MMA Gym.
 
 - __Footer__
   - The footer section is present on all pages, and its comprised of 2 responsive layout rows.
   - The first row contains a quick  navigation links through the page.
   - The second row contains social media icons for better UX.
<br>
<details>
<summary><strong>Footer Image (smaller screens)</strong> (Click to open)</summary>
<img src="assets/media/footer-snippet.jpg">
</details>

 - __Features left to implement/Design changes__
   - Table containing schedule info can be presented in a different media/style. Or removed and incorporated as a downloadable PDF/JPG.
   - Form completion can involve JS to ensure data processing, and be presented with a Modal.
   - Testimonials section can be restyled into a carousel slider to improve UX.


## Testing
The testing done for this project are as follows:
- HTML Validator
- CSS Validator
- Lighthouse
<!-- List of info/images to explain validators/lighthouse -->
### Validator testing and Lighthouse
- [HTML Validator](https://validator.w3.org/) Showed few errors when passed initially but they were fixed. Only warning and info tags remain (nothing that impedes UX/Styles)
- [CSS Validator](https://jigsaw.w3.org/css-validator/) Showed no errors at all when passed with direct input.
<br>
<details>
<summary><strong>CSS Jigsaw snippet</strong> (Click to open)</summary>
<img src="assets/media/jigsaw-snippet.jpg">
</details>

- [Lighthouse](https://developer.chrome.com/docs/lighthouse/overview) Has shown varied results due to factors like internet speed, images, http ports, cdn links and so on. When tested on higher net speed the performance scores are high. Accesibility and Best Practices also have a decent score.
  - [More details in screenshot section](#screenshots)
### Bugs/Style issues

- HR tag presented errors in validator, so style change was done using border-top
- Coach card No3 text is covering the footer line separator (future style changes might sort this)
- Contact columns have different height at certain small gap in screen width (looking for a fix)
- Google maps iframes has an odd invisible margin probably due googles own iframe code (needs fixing  but doesnt impair design much)
  - These bugs and styling discrepancies can/will be fixed in the future
  - For more detailed info check [Bug Screenshots](#screenshots)

## Deployment
- __The site was deployed to GitHub pages__
- The site was deployed to GitHub pages. The steps to deploy are as follows: 
  - In the GitHub repository, navigate to the Settings tab 
  - From the source section drop-down menu, select the Master Branch
  - Once the master branch has been selected, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment. 
- The live link for the project repo: [Vagabond MMA Milestone 1 repository](https://github.com/SynthSlav/MMA-Gym-M1-project.git)
- The live deployed version of the project [Vagabond MMA Milestone 1 deployed](https://synthslav.github.io/MMA-Gym-M1-project/)

## Credits
  - Font imports are taken from Google Font.
  - Images are taken from various sources on Google Images.
  - Home landing video promo is taken from youtube channel Golden Core Studio.[Video Link](https://www.youtube.com/watch?v=G7jcZwFlO_o)
  - Map section code taken from Google Maps.
  - Icons for footer and Classes cards were taken from Font Awesome.
  - Icons for the page tab (and previously navbar logo) were generated using Favicon and their guide.

## Screenshots
### __Lighthouse screenshot snippets__
<details>
<summary><strong>Home Lighthouse Scores</strong> (Click to open)</summary>
<img src="assets/media/home-light-mobile.jpg">
</details>
<details>
<summary><strong>About Lighthouse Scores</strong> (Click to open)</summary>
<img src="assets/media/about-light-mobile.jpg">
</details>
<details>
<summary><strong>Classes Lighthouse Scores</strong> (Click to open)</summary>
<img src="assets/media/classes-light-mobile2.jpg">
</details>
<details>
<summary><strong>Coaches Lighthouse Scores</strong> (Click to open)</summary>
<img src="assets/media/coaches-light-mobile.jpg">
</details>
<details>
<summary><strong>Timetable/Schedule Lighthouse Scores</strong> (Click to open)</summary>
<img src="assets/media/schedule-light-mobile.jpg">
</details>
<details>
<summary><strong>Contact Us Lighthouse Scores</strong> (Click to open)</summary>
<img src="assets/media/contact-light-mobile.jpg">
</details>
<details>
<summary><strong>Success Lighthouse Scores</strong> (Click to open)</summary>
<img src="assets/media/success-lighthouse-deployed.jpg">
</details>
<br>

__Note: The listed lighthouse tests are done on mobile__
- For the desktop tests reffer to the media folder under the names: example(home-lighthouse-deployed.jpg) 
### __Bug/Style issues__
<details>
<summary><strong>Contacts column bug/styling issue</strong> (Click to open)</summary>
<img src="assets/media/contact-column-bug.jpg">
</details>
<details>
<summary><strong>Cooach card3 bug/styling issue</strong> (Click to open)</summary>
<img src="assets/media/coachcard-bug.jpg">
</details>
<details>
<summary><strong>Google Maps bug/styling issue</strong> (Click to open)</summary>
<img src="assets/media/gmap-bug.jpg">
</details>