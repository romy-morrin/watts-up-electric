# Watts Up Electric
## Milestone Project 1 - User Centric Frontend Development

## Description

![Mock ups for Website](https://github.com/romy-morrin/watts-up-electric/raw/master/wireframes/mockups.png/ "Mock Ups for Website")

This is a website for Watts Up Electric, an electrical service based in Co Kildare, Ireland. The main objective of this website is to provide information for potential customers who need either household or commercial electrical services. The site consists of 4 main sections, a home section, a services section, an about section and a contact section. 

Check out Watts Up Electric [here](https://romy-morrin.github.io/watts-up-electric/)

## UX Design

### User Stories

#### Customer
As a potential client, I want to use a website that clearly shows me what services the company has to offer. I would also like to know some of the company’s history. I also want easy directions as to how to contact the company either by phone or email or by submitting a form. I want to see that this electrician covers the area that I live in. If I am looking for an electrical service in the Rep. of Ireland, I want to see that the electrician is registered with Safe Electric and that this is visible by the Safe Electric logo. 


#### Business Owner 

As a business owner, I want my website to clearly show the services I can provide to potential customers and my company’s history. I also want it to be easy for customers to contact my business either by phone or email or by submitting a form. I want it to be easy for customers to give me their location so that I can confirm whether it is possible to do work there. I want customers to see that I am a registered electrician with Safe Electric. 

### Strategy

When designing the website, my main objectivce was to keep the layout as simple as possible while providing all the necessary information. Completing the user stories was a great way to prioritise the content need to contruct the main sections of the site.

### Scope
When meeting with the business owner, we discussed what information was fundamental to the website. We discussed the services that needed to be listed, the informtation needed to give a brief history of the company and the best methods for potential customers to contact the company. I spoke with family members and friends who would be potential customers and what they thought would be necessary in an electricians website if they ever needed one. Most said that they would want an easy, accessible website that would show them the services provided and a simple way of getting in contact with the company. 

### Structure
Having this information, I was then able to structure the website in a way that prioritised the necessary information. It was clear that at least 3 sections were needed to display all of the information required.  It was established at this stage in the design process that the structure would have to be accessible, simple and coherent. 

### Skeleton

It is a one page scrolling website with 4 main sections:

* Home section
* Services section
* About section
* Contact section

Find my Wireframes for desktop, tablet and mobile [here](https://github.com/romy-morrin/watts-up-electric/tree/master/wireframes)

My wireframes are slightly different from the live site. 

* Desktop - 
Firstly, I decided to use a jumbotron and center it in the middle of the home page. I altered the text here too and added a larger callout button. 
Also, I decided to place the form on the left hand side of the contact section as I was creating the site I realised that this is the most important part of this section. 

* Mobile - 
I thought the second image in the services section may looked too crammed on a mobile screen. I decided to keep it after completing this section as it did not look crammed. 

### Surface

#### Images

I used [Adobe Stock](https://stock.adobe.com/)for the images used on the site. The business owner and I discussed what kind of hero image to use as a background for the home section. The business owner made it clear that they wanted an image that showed practicality (work tools) and one that had warm tones and colours. I looked around on websites for free images but unfortunately couldn't find any so I decided to use this one from Adobe. 

#### Colour

The grey tones of the background image in the home page are used across the site. I decided the match the jumbotron with the light grey color of the navigation menu. I picked a slightly darker grey color for the About section and matched the footer with this. The services section and contact section both have default white backgrounds as I believe this gives a nice contrast with the other grey backgrounds. The green used in the logo is replicated throughtout the site in the callout buttons which are in the home section and the services section. 

#### Typography

I used Google fonts "Quicksand" and paired it with "Roboto", however I decided not to use the "Roboto" font. I believe the "Quicksand" font matched the font of the logo and is easily readable while also adding a professional look to the overall site.

## Features

### Existing Features

#### Navigation Bar

The navigation bar used displays the 4 sections of the website labelled "Home, Services, About, Contact". Bootstrap 4.6 helped me construct the navigation bar. I also used Bootstrap's toggle function so that the nav bar changes to a hamburger menu when shown on a mobile device. I initially had the navigation links to the left hand side of the menu on desktop view and then decided to position them to the centre of the menu. This added to the sites accessiblity. The nav links have a slightly bolder font weight than other text on the site. This again adds readability and accessbility. When clicked on, each link will bring the user to the respective section. The nav-links change to a darker colour when the cursor hovers over them. 

#### Home Section
The home section features a background image and a jumbotron. The background image has a background-attachment property with a value of fixed on desktop devices which gives a nice effect when scrolling through the site. The background image is position to the bottom left so as to show the tools and other objects in the image. I used a snippet of code from CSS Tricks [here](https://css-tricks.com/perfect-full-page-background-image/) to help position the background image correctly.I used Bootstrap components to create the jumbotron. I gave the jumbotron the same background color as the navigation bar so to show consistency in style across the home page. I positioned it to the centre of the home section and placed the Watts Up Electric logo at the top of the jumbotron with text and a callout button underneath it which directs the user to the contact section. 

#### Services Section
The services section displays the services that the company can provide and these are divided into two sections; household and commercial. I used font-awesome lightning bolt icons to both lists of services. I also added icons to both headings as I think the icons add to the sites visibility. There are two images in this section, both stacked on top of each other beside the lists of services. These images were also from [Adobe Stock](https://stock.adobe.com/).

#### About Section
The about section displays a brief outline of the company's history and it's mission. It gives the user the company's location and the areas it covers. It also displays the Safe Electric Logo which indicates to the user that the company is registered with Safe Electric Ireland. 

#### Contact Section
The contact section displays several different methods of contacting the company. The user can fill out a form. Here they will give their name, email address, whether they want household or commercial services or other and they can also give any additional information they fill is relevant. The user is also provided with the company's email, phone and address to contact Watts Electric directly if they wish to do so. 

#### Footer
The footer displays the name of the company, which is positioned to the center of the footer. The footer also has the same background colour as the about section which adds consistency to the overall layout. 

### Features left to implement

This site will continue to be developed in the future. Other feautures that 

Testimonial page, social media links added to footer, functioning form in contact section, 

## Technologies Used
### Languages
* HTML 5
* CSS3
* JQuery - Used this bootstrap feature to implement the hamburger menu for the navigation bar when on a mobile device.

### Integration
* Bootstrap v4.6 - Used for grid layout, navigation bar and form features. 
* Google fonts - font style given across the site. 
* Fontawesome Icons - icons used in services sections. 

### Other
Balsamiqu Wireframes - Used to create wireframes for the site. 

## Testing

* Passed through HTML validator [here](https://validator.w3.org/) with no issues.
* Passed through CSS validator [here](https://jigsaw.w3.org/css-validator/) with no issues. 


## Version Control

## Deployment
Github pages

## Credits
Logo, CSS tricks, Adobe stock, Bootstrap for form and nav, 

## Resources
W3schools, Code Intsitute tutorials, 

## Acknowledgements
Thanks to company owner, friends and family, Brian mentor




