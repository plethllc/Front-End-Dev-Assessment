# Front-End Development Assessment
## Contents
* Overview
* Responsive Web Design and Development
* Optimization
* UX and Content Choreography
* Completion

## Overview
Using HTML/CSS/JS best practices, please attempt to complete each of the tasks in the following assessment. 

Feel free to use any tools available on the internet or pre-existing code you may already have (this includes LESS/SaSS, javascript libraries/frameworks and any html/css frameworks you wish). Using a CSS preprocessor is strongly encouraged.

You may use the development platform (PHP, WordPress, plain HTML) of your choice and any IDE you wish (Visual Studio, Textmate, Notepad). Please save your code locally.  If you have questions, please don’t hesitate to contact your test administrator (travis@pleth.com). 

Prioritize the responsive portion of the work.

Please be prepared to save and turn in your work by noon on the following day. Try to get all tasks done, but, if you don’t finish, that’s OK. After you turn in your initial work, you are free to spend as much time as you like finishing the test at which point you can turn in a new zip file. You have 24 hours to complete the assessment, though it is encouraged that you send in the assessment as soon as you've completed it. 

See the **Completion** section for instructions on how to submit your work.

### Focal Points

1. Solve responsive web design layout issues with industry-standard best-practices
2. Be cross-browser compatible (IE9, 10, Chrome, FF, Mac Safari)
3. Write accessible, semantically correct HTML
4. Create clean, readable, and maintainable CSS
5. Keep it simple.

## Responsive Web Design and Development

In the following section be careful but please don’t worry about matching the design in a pixel perfect manner; how you solve responsive layout problems is much more important. Please focus on the three tenants of Responsive Web Development: a flexible grid, flexible imagery, and proper use of media queries. Please remember that you need to be cross browser compatible as much as possible (IE9, 10, Chrome, FF).  

1. Please examine all folders and files labeled “responsive”. 
2. At [http://preview.pleth.com/fe-dev-2015](http://preview.pleth.com/fe-dev-2015) you will find various mockups, linked in the top right corner of the page. Together, these designs make up a simplified version of the Pleth homepage.
3. Please use the HTML page called “responsive.html”.
4. Your goal is to create a single, fully responsive page. See the linked mockups for the content choreography. Please use the following breakpoints:
    * Resolution < 480px = Mobile
    * Resolution < 800px = Tablet
    * Resolution > 1140px = Desktop
5. Other images you may need are found in the /assets/images/responsive folder.
6. All copy and menu items should be **"museo", sans-serif** system fonts. Typekit is enabled for **localhost**, so you'll need to use an apache stack (XAMPP, MAMP, LAMP).
7. Typekit embed code is:

```
    <script src="//use.typekit.net/tvs5dgh.js"></script>
    <script>try{Typekit.load();}catch(e){}</script>
```

8. In /responsive/img you’ll find slide-1.jpg and slide-2.jpg. Create a simple banner infinite scrolling rotator with using those two images in the main hero banner area of the page. The rotator must have previous and next buttons on desktop and swipe-capable left and right on mobile.  Keep the rotator functioning as you change resolution. You may use anything from the web (plugins, etc.) or write your own code.
9. If you have time left, optimize the code and assets for responsive web design, such as with the image of your choice or Grunt.

## Optimization

Create a text file called “Optimization.txt” in the root directory.  Describe any ways you may further optimize the responsive HTML page, even though you might not have had time while completing the exercises.

## Completion
Please take all files used in the assessment, even if uncompleted, zip them up, and email to **travis@pleth.com**. If you use a CMS such as WordPress or Drupal, include an export of the database in the zip file as a .sql file and any credentials used to login to the site.