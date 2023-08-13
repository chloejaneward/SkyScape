# SkyScape

SkyScape is a website for a fictional aerial arts studio. The business operates like a gym and has classes scheduled weekly for aerial hoop, silks and trapeze. The website has a dual purpose; to advertise classes to new customers, and to inform current customers of class times. It will also provide information on how to get in touch with the business owners.

Here is a link to the deployed site:

## UX: User Experience

### User stories

First time visitors to the site want to learn:

* The purpose of the site
* More about the business and where they are based
* How to easily navigate the website at first glance
* The cost of joining the aerial classes
* The schedule of classes and a brief explanation of the classes.

Returning or frequent visitors to the site want to:

* Find information about scheduled classes easily
* Find out how to get in touch with the business owners.

### Scope

*	A navigation bar for easy navigation of the site,

*	Simple home page that explains what type of aerial apparatus the studio covers,
*	Schedule of studio classes along with the price of classes,
*	Easy to access contact information and space for site visitors to send a message to the business owners,
*	Social media links located in the footer.

### Structure

#### Header bar, present on each page–

Logo and business name ‘SkyScape’ on left side

Navigation links to the right (home, class schedule, contact), that condenses down to hamburger menu for mobile devices

Footer, present on each page, stack on top of each other for mobile devices –
	Address
	Phone number
	Social media links (Facebook, Twitter, Instagram)

#### Home or landing page –

Header

Business name, tagline, and basic introduction to the business

Link to schedule

Photos and hover over function to explain the three types of apparatus available

Mobile devices have background image and no information about different apparatus types

#### Schedule –

Header

Columns for three types of classes, including a photo of each to illustrate. List of class times and prices. Mobile devices have background image and schedule stacked above one another.

#### Contact –

Header

Decorative photo for illustrative purposes

Contact form

Mobile version has background image and form overlay.

### Wireframes

Wireframes were created using [Figma](https://www.figma.com)

Home/Landing page:
![SkyScape (1)](https://github.com/chloejaneward/SkyScape/assets/131905887/5a0b8ae5-b753-415c-bc82-8ddde54e5090)

Class schedule page:
![SkyScape - Schedule (1)](https://github.com/chloejaneward/SkyScape/assets/131905887/a529d3a7-8ed7-4f4f-a603-223c620a115c)

Contact page:
![SkyScape - Contact](https://github.com/chloejaneward/SkyScape/assets/131905887/cde90927-99df-4a27-9cad-b384efee94ee)

### Surface

#### Design

The theme will be based on pastel sky, pink and light blue tones in background to illustrate the SkyScape theme and the elegant nature of aerial arts. Also in line with the fact that aerial arts are done in the air.

#### Colours

Colours for the site have taken inspiration from a pastel night sky, with light hues of purple and pinks.

A colour scheme has been chosen by using [Coolors.co](https://coolors.co/8783d1-aa9aba-bfa4a4-d1abad-e3b9bc)

#### Fonts

Fonts were decided by using [FontJoy](https://fontjoy.com/#)

Fonts chosen were:

Headings and titles - Montserrat Alternates
General text - Abhaya Libre
Back-up font - sans-serif

#### Images

All images chosen will have a light colour tone and will follow a similar colour theme.

Mobile background image is purposefully elegant, with light coloured silk that evokes a feeling of relaxation and elegance.

## Resources & Technologies Used

### Languages used

* HTML
* CSS

### Frameworks used

* [Bootstrap](https://getbootstrap.com/docs/4.4/getting-started/introduction/) - Bootstrap was used to help make the site more responsible, and to ensure we were creating a mobile-first UXD.

* [Google Fonts](https://fonts.google.com/) - Fonts were imported from Google, with [FontJoy](https://fontjoy.com/#) helping to ensure suitable font pairings.
* [Font Awesome](https://fontawesome.com/) - Icons for social links in the footer, which is good UX as users will recognise these icons.
* [Figma](https://www.figma.com) - Used for creating Wireframes.
* [Unsplash](https://unsplash.com/) - 2 of the images were downloaded free from Unsplash for the index.html page.
* [Pixabay](https://pixabay.com/) - 1 image was downloaded free from Pixabay for the home page.
* Git - Both GitHub and Git were used for storing the code, and for version control.
* [HTML Formatter](https://www.freeformatter.com/html-formatter.html) - HTML Formatter was used to ensure HTML was formatted neatly, and to remove unecessary spaces.

## Testing

### Code Validators & Lighthouse

I used a [HTML Validator](https://validator.w3.org/) to test the code, here are the errors that appeared and were corrected:

* Using the element 'a' as a descendent of the button element. Fixed by changing the elements to 'a' then using the class to format as a button with Bootstrap.
![Error1](documentation/error-1-buttonlink.png)
  
* Align attribute on an img element, should use CSS instead. Fixed by removing the align element as was obsolete.
![Error2](documentation/error-2-imgalign.png)

* Warning: Only to use h1 headings for top-level headings, when it was being used for the business name in the nav bar. Changed to p element.

I used a [CSS Validator](https://jigsaw.w3.org/css-validator/) to test the CSS Code, here is the error that appeared and was corrected:

* I accidentally gave an element a padding of 'auto' which isn't a suitable value. This was accidentally transfered from an old margin styling. Fixed by removing the padding style.
![Error3](documentation/error-3-paddingauto.png)

I used Lighthouse in Google Chrome Developer Tools to test accessibility:
![Lighthouse](documentation/lighthouse.png)

### Testing User Stories as outlined in 'UX: User Experience'

We decided that first time visitors to the site wanted to learn:

* The purpose of the site:
  * This was achieved by creating a simple home landing page, with visual representation of the aerial apparatus that the studio offers. There's also simple text to explain what the studio offers.
    ![Landing page](documentation/Landing%20page.png)
    ![Landing page mobile](documentation/Landing%20page%20mobile.png)

* More about the business and where they are based
  * The studio's address is always visible in the footer bar.
    ![Footer bar address](documentation/Footer%20Address.png)

* How to easily navigate the website at first glance
  * There is a navigation bar at the top of each page, with simple page names. When you hover over the links, they change to a lighter shade of grey to show they are interactive/links. You can also navigate back to the home pageby clicking on the business name on the left side of the nav bar.
![nav bar](/documentationnav%20bar.png)

* The cost of joining the aerial classes
  * The price is found on the schedule page. However, considering this is one of the main pieces of information a customer may want, I decided to use the strong element to wrap the prices and make them bold. This will make sure this key information stands out to customers.
  ![price](documentation/price-list.png)

* Find information about scheduled classes easily
  * There is a dedicated page for the class schedule. This is linked in the nav bar, but is also linked from the home page of the website so it is easily found. There is a clear table which outlines the different classes, days and times.
  ![schedule](documentation/schedule.png)

* Find out how to get in touch with the business owners.
  * There is a page dedicated to contact the business owners. This is linked on the nav bar, as well as linked through the schedule page as customers are required to contact the business to book classes. The footer also has a contact number and social media links.  
![contact](documentation/contact-page.png)

### Additional tests

* I tested how responsive the site was using Google Chrome Developer tools to change the screen size;
  * I noticed that below the width of 358px the nav bar does not stay inline, and seperates onto different lines. It is still functional but may not provide the best UX on smaller devices below 358px.
  * I also noticed that on tablet sized devices, there are blank white spaces at the bottom of pages as well as to the right of the page, which isn't great UX.
* I made a slight design change to the footer colour, as I felt the site flowed better if the footer was a darker shade of the header colour as opposed to a different pink.

## Finished Site

### Desktop view

Note: In order to get a screenshot of the site pages, I zoomed out on the browser to get the whole page in one shot. This means text looks quite small.

![Desktop View](documentation/Desktop%20view.png)

### Tablet View

![Tablet View](documentation/Tablet%20View.png)

### Mobile View

![Mobile View](documentation/Mobile%20View.png)

## Deployment

Deployment guide.