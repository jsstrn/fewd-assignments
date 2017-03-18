#FEWD Week #4 Project: JavaScript Basics

---


###Description


The team from Relaxr is back...again! They want their page to be more interactive and asked you to add JavaScript to their source code. You've been given the HTML and CSS but will need to create a JavaScript file and add a few different pieces of interactivity:  Users should be able to click a link and have the remainder of the blog's content slide down and appear on the page, both on the main content column and the side bar; users should also be able hide the content when they are finished reading. See a detailed technical explanation below.

Student: Mak Mei Keen

Project URL: [https://schmaltz13.github.io/relaxr-blog-jquery/](https://schmaltz13.github.io/relaxr-blog-jquery/)

|                                                                                                                                                                                                                     |                                |                        |                          |
|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------|------------------------|--------------------------|
| Technical Requirements                                                                                                                                                                                              | Does Not Meet Expectations (0) | Meets Expectations (1) | Exceeds Expectations (2) |
| Use the ```$.ready()``` handler to delay your code from executing until all DOM assets have been loaded                                                                                                             |                                |           ✓            |                          |
| Select the appropriate DOM elements with CSS selectors upon a user's click using the ```$.click()``` handler                                                                                                        |                                |                        |           ✓              |
| Have the text in the ```div``` tag slide down along with a "Read Less" link in the blog post using,```$.slideDown()``` and ```$.show()```                                                                              |                                |                        |           ✓              |
| Hide the "Read More" link using ```$.hide()```                                                                                                                                                                      |                                |                        |             ✓            |
| Have the ```div``` slide up and hide the "Read Less" link using,```$.slideUp()``` and ```$.hide()```                                                                                                                   |                                |                        |            ✓             |
| Show the "Read More" link using ```$.show()```                                                                                                                                                                      |                                |                        |            ✓             |
| TOTAL: 11/12                                                                                                                                                                                                    |                                |                        |                          |

Note: Put your click functions into document ready. Eg.

```
$( document ).ready(function() {
    console.log( "Ready!" );
    $readmore.click(expand)
    $readless.click(collapse)
});
```

This makes sure that jQuery is loaded before running your JavaScript code.