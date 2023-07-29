# TESTING
![](documentation/mainresp.png)

## Compatibility

To confirm correct functionality, responsiveness and appearance:

+ The site has been tested on the following browsers: Chrome, Firefox, Safari.

    - Chrome:

    ![Chrome](documentation/main_google.png)
    ![Chrome 2](documentation/main2_google.png)
    - FireFox:

    ![FireFox](documentation/main_firefox.png)
    ![FireFox 2](documentation/main2_firefox.png)

    - Safari:

    ![Safari](documentation/main_safari.png)

    ![Safari 2](documentation/main2_safari.png)

---
## Responsiveness

+ Here's how the full pages of the website look like:
(checked with the GoFullSize extension in Chrome)

   - ![Home page](documentation/homefull.png)

   - ![Gallery page](documentation/galleryfull.png)

   - ![Contact us page](documentation/contactfull.png)

   - ![Response page](documentation/responsefull.png)

+ The website was checked with [Responsive Website Design Tester](https://responsivedesignchecker.com/).

- Desktop Screen:

![Desktop](documentation/desktop11.gif)

 - Tablet Screen:

 ![Tablet](documentation/tablet11.gif)

  - Mobile Screen:

  ![Mobile ](documentation/phone11.gif)

+ The functionality of the links in the website was checked as well by different users.

## Manual testing

| feature | action | expected result | tested | passed | comments |
| --- | --- | --- | --- | --- | --- |
| Navbar | | | | | |
| Home | Click on the "Home" link | The user is redirected to the main page | Yes | Yes | - |
| Gallery | Click on the "Gallery" link | The user is redirected to the gallery page | Yes | Yes | - |
| Contact | Click on the "Contact" link | The user is redirected to the contact page | Yes | Yes | - |
| Footer | | | | | |
| Instagram icon in the footer | Click on the Instagram icon | The user is redirected to the Instagram page | Yes | Yes | - |
| Facebook icon in the footer | Click on the Facebook icon | The user is redirected to the Facebook page | Yes | Yes | - |
| Twitter icon in the footer | Click on the Twitter icon | The user is redirected to the Twitter page | Yes | Yes | - |
| YouTube icon in the footer | Click on the YouTube icon | The user is redirected to the YouTube page | Yes | Yes | - |
| Home page | | | | | |
| "Contact Us" button in Header | Click on the "Contact Us" button | The user is redirected to the contact page | Yes | Yes | - |
| Gallery page | | | | | |
| "Contact Us" button in header  | Click on the "Contact Us" button | The user is redirected to the contact page | Yes | Yes | - |
| "Contact Us" button in Call to action section | Click on the "Contact Us" button | The user is redirected to the contact page | Yes | Yes | - |
| Contact page | | | | | |
| First name input | Enter the first name | The first name is entered | Yes | Yes | If user doesn't enter the first name, the error message appears |
| Last name input | Enter the last name | The last name is entered | Yes | Yes | If user doesn't enter the last name, the error message appears |
| Email input | Enter the email | The email is entered | Yes | Yes | If user doesn't enter the email, the error message appears. If user enters not valid email, the error message appears |
| Phone number input | Enter the phone number | Phone number is entered (or not)  |Yes | Yes | If user doesn't enter the number would be no error mesage 
| "Submit" button | Click on the "Submit" button | The user is redirected to the response page | Yes | Yes | - |
| Response page | | | | | |
| Response message | The user will be automatically redirected to the home page after 10 seconds | The user is redirected to the home page | Yes | Yes | - |


---
## Validator testing
+ ### HTML
  #### Home Page
    - No errors or warnings were detected when passing through the official W3C validator.

       ![Home Page HTML Validator](documentation/validator1.png)
    
  #### Gallery Page
   - No errors or warnings were detected when passing through the official W3C validator.

    ![Gallery Page HTML Validator](documentation/validator2.png)

  #### Contact Page
    - No errors or warnings were detected when passing through the official W3C validator.

    ![Contact Page HTML Validator](documentation/validator3.png)

  #### Response Page
    - No errors or warnings were detected when passing through the official W3C validator.

    ![Response Page HTML Validator](documentation/validator4.png)
    
+ ### CSS

 - No errors or warnings were found when passing through the official W3C (Jigsaw) validator.
    
    ![CSS Validator](documentation/cssvalidator.png)


+ ## LightHouse report

    - Using lighthouse in devtools, I made sure the site works well, is accessible, and the colors and fonts chosen are readable.
    
  ### Home page

![Home Page Lighthouse](documentation/image.png)

 ### Gallery page

![Gallery Page Lighthouse](documentation/image1.png)

 ### Contact page

![Contact Us Page Lighthouse](documentation/image2.png)

---
​
## Bugs
+ ### Solved bugs
    1. In Contact Us page I accidentally put type-text in the email form.
  *Solutions:* Fixed to type-email.
    2. I used a container several times when I didn't need it. 
    *Solution:* remove unnecessary containers.
    3. Used float and margin, which made the page deform when resizing. 
    *Solution:* almost all float and margin were replaced, which made the page more responsive.

 ---
+ ### Unsolved bugs
    - When I commit it's like it's not in my name, but I can't do anything about that unfortunately.
    ---