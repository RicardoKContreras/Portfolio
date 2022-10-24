# MyPortfolio


# AS AN employer
* I WANT to view a potential employee's deployed portfolio of work samples
* SO THAT I can review samples of their work and assess whether they're a good candidate for an open position

## Acceptance Criteria
* GIVEN I need to sample a potential employee's previous work:

    * WHEN I load their portfolio
    * THEN I am presented with the developer's name, a recent photo or avatar, and links to sections about them, their work, and how to contact them

    * WHEN I click one of the links in the navigation
    * THEN the UI scrolls to the corresponding section

    * WHEN I click on the link to the section about their work
    * THEN the UI scrolls to a section with titled images of the developer's applications

    * WHEN I am presented with the developer's first application
    * THEN that application's image should be larger in size than the others

    * WHEN I click on the images of the applications
    * THEN I am taken to that deployed application

    * WHEN I resize the page or view the site on various screens and devices
    * THEN I am presented with a responsive layout that adapts to my viewport


## Notes

* I created a responsive `viewport` by incorporating `flex` and best practices.

* I added my `name` and `avatar`

* I added  `google fonts` to my `HTML` and `CSS`

*  I made my `About Me`, `My Work`, and `Contact Me` navigation items redirect to the oppropriate sections

*  I set up images for `My Work` section and made them redirect to the application

* Added `placeholder` images for certain projects in development

* Added media query for sizes of a `tablet(980px-768px)` and a `phone(575px)`

* Added a little bit of `styling` for practice

* ![Site Photo](/assets/site-photo.png)
