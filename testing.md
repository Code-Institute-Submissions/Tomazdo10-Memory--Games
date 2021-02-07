# Testing
--------------------------------------------------------------------------
[Click here to get back to Readme.md file](Readme.md).

## Table Of Contents :
---------------------------------------------
 * [W3C Validator](https://validator.w3.org/nu/#textarea)
 * [DevTools](DevTools:)

 * Site Testing
   
   * [User stories from user experience - UX Section]()

      * First time user goals


   * [User Testing]()

      * User review

    * [Further Testing]()
------------------------------------------------------------

Testing this site was conducted using various methods to identify any bugs
 throughout the site. I've use the automatic testing in form of the 
 W3C Validator for HTML code, CSS code and JSHint for java script code.

 ## W3C Validators:
 -------------------------------------------------------------------
 The W3C Markup validator and W3C CSS validator services where used to check the validity on codes,
 in all pages and to make shore there where no syntax errors in the project. Both the HTML and
 CSS where run true this validator regulary when building the projet so no major bugs where found 
 in the end of the finished project.

  * [W3C Markup Validator](https://validator.w3.org/)
  * [W3C CSS Validator](https://jigsaw.w3.org/css-validator/)
-------------------------------------------------------------------------------------  

## JSHint Validator:
----------------------------------------------------------------------------------
The JSHint Validator was used to check the validity of the JS code to increase the code quality
and check or detect for any potencial bugs.It pointed out any issues and warnings that i could
easily rectify. It was detected few warnings in my JS code and the biggest issue was the about
'template literal syntax', that is only available in ES6. I've done some resarch and found out in
[stack overflow](https://stackoverflow.com/) from other coders that they put in on the top of the 
JS code in the root (/*jshint esversion: 6 */) this syntax and no errors where shown anymore for 
'template literal syntax'.

* [JSHint](https://jshint.com/)
------------------------------------------------------------------------------------------------

## DevTools:
-------------------------------------------------------------------------------------------
Google Chrome DevTools was used for rigorous testing of the site. It was used for varied different reasons.

* It reveald the issue withe canvas in JS that was not properly responsive  with the smaller screens, such 
   as mobile phones or tablets. So i had to set up the media screen properly in the CSS code.

* The background image which i was using before it was to blurry when I've streched it over the screen, 
   so i had find anothe one which i got it from [Unsplash.com](https://unsplash.com/) where you can find 
   high quality images for free download and usage for programs.

* I did regular check on a website in the server, when click the right button on the mouse and chose 
  inspect option it will open you the toolbar where you can adjusting the website directly and see the 
  actual changes you are making when chanching the code, there I chose the option (lighthouse), where 
  it calculate you the Performance, Accessibility, Best Practice and SEO which ensure you page is optimized 
  for search engine results ranking. 

* Debugging

   *  Highlighted incorrect use of styling and/or Bootstrap.
   *  All of these issues were addressed using media queires to alter sizes, 
      positioning and background  across the various screen sizes.

## Site Testing
--------------------------------------------------------------------------------------
#### User Stories from user expirience (UX-Section)

 * User goals
   
   * As a user i want to be able to navigate true the website comfortably
     and securely.

     * When the site is first loaded main image and the title is seen clearly
       and easily readable. Users should feel comfortable whith the suplicity
       of the site.

     * A main image should give the user what to expect when entering the game.

     * When scrool down the page it will provide you some more info about the 
       tetris game what is it about and some history of it.

     * When arriving to the bottom of the page there would be the tetris game 
       which you can start playing and have some fun and relax. 

     * Right above the tetris game you will found the instructions how to play 
       the game, which buttons to use and on the right site of the instruction 
       buttons is the score showing and next to it mute button, where you can 
       mute the sound if you want to play in quiet.
       
-------------------------------------------------------------------------------------

### User Testing

Once the project was nearly finished and debugged I've sent it out to be reviewed.

#### User Review:

My project was sent to my friends and famaly members to test and review the site if
it's fully function and if the game is workng properly on every device. I received the
feedback from people of different ages and professions and they notfyed me of any bugs 
or issues of user experience. The general reviewes where positive about the game and 
colorful tetrominos and nice background images with the chosen colors of the background
text box. The structure was complemented with the site uncluttered design.

### Further Testing

The website was tested on Google Chrome Mozzila Firefox, Safari browsers and Internet Explorer. 
It was viewed on a range of different devices  such as desktop, laptops and all sorts of different 
mobile phones such as iPhone 5s samsung galaxy S10-S20 Huawei p30 PRO. Extensive testing was carried out to make 
 sure the links were working correctly, and that the tetris game is loading correctly.

