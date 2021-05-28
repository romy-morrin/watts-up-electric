# Watts Up Electric
## Milestone Project 1 - User Centric Frontend Development

## Description

![Mock ups for Website](https://github.com/romy-morrin/watts-up-electric/raw/master/wireframes/mockups.png/ "Mock Ups for Website")

This is a website for Watts Up Electric, an electrical service based in Co Kildare, Ireland. The main objective of this website is to provide information for potential customers who need either household or commercial electrical services. The site consists of 4 main sections, a home section, a services section, an about section and a contact section. 

Check out Watts Up Electric [here](https://romy-morrin.github.io/watts-up-electric/).

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

Find my Wireframes for desktop, tablet and mobile [here](https://github.com/romy-morrin/watts-up-electric/tree/master/wireframes).

My wireframes are slightly different from the live site. 

* Desktop - 
Firstly, I decided to use a jumbotron and center it in the middle of the home page. I altered the text here too and added a larger callout button. 
Also, I decided to place the form on the left hand side of the contact section as I was creating the site I realised that this is the most important part of this section. 

* Mobile - 
I thought the second image in the services section may looked too crammed on a mobile screen. I decided to keep it after completing this section as it did not look crammed. 

### Surface

#### Images

I used [Adobe Stock](https://stock.adobe.com/) for the images used on the site. The business owner and I discussed what kind of hero image to use as a background for the home section. The business owner made it clear that they wanted an image that showed practicality (work tools) and one that had warm tones and colours. 

#### Colour

The grey tones of the background image in the home page are used across the site. I decided to match the jumbotron with the light grey color of the navigation menu. I picked a slightly darker grey color for the About section and matched the footer with this. The services section and contact section both have default white backgrounds as I believe this gives a nice contrast with the other grey backgrounds. The green used in the logo is replicated throughtout the site in the callout buttons which are in the home section and the services section. 

#### Typography

I used Google fonts "Quicksand" and paired it with "Roboto", however I decided not to use the "Roboto" font. I believe the "Quicksand" font matched the font of the logo and is easily readable while also adding a professional look to the overall site.

## Features

### Existing Features

#### Navigation Bar

The navigation bar used displays the 4 sections of the website labelled "Home, Services, About, Contact". Bootstrap 4.6 helped me construct the navigation bar. I also used Bootstrap's toggle function so that the nav bar changes to a hamburger menu when shown on a mobile device. I initially had the navigation links to the left hand side of the menu on desktop view and then decided to position them to the centre of the menu. This added to the sites accessiblity. The nav links have a slightly bolder font weight than other text on the site. This again adds readability and accessbility. When clicked on, each link will bring the user to the respective section. The nav-links change to a darker colour when the cursor hovers over them. The nav-bar also has a class of "fixed top" so that it follows the user as they scroll throught the page.

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

Other features that may be added to the site in the future include:

* Social Media links - 
At the time of completing this version of the site, the business owner does not have any social media sites related to the company. In the future, once these pages are established, social media links may be added to the site. They will be included in the footer. 

* A testimonial page - 
This would include client feedback and reviews which could be left on the company’s social media pages and then uploaded to the website. 

## Technologies Used
* HTML 5
* CSS3

* Bootstrap v4.6 - Used for grid layout, navigation bar and form features. 
* Google fonts - font style given across the site. 
* Fontawesome Icons - icons used in services sections. 

* Balsamiqu Wireframes

## Testing

By following the user stories, the site has been constructed and tested to meet all the users needs so far. 

##### *Navigation and Home Section* 
The user can clearly identify how to navigate the page by using the navigation links. The text for the navigation links was made bolder, bigger and given a darker font-color after testing so to add contrast to the rest of the page and make them stand out for the user. The nav links were also positioned to the center of the nav to add to the sites accessibility. 

After testing, the overall font size on the page was changed from 80px to 1.5rem.This change made the font-size slightly larger thus improving the readability of the site.

##### *Services Section*
When the user scrolls down to the next section, they can see the services provided by the company. There is also another “Get in touch” button displayed here if the user wants to contact the company after reading the services. After testing, the “get in touch” button was positioned directly below the lists of services and centered underneath the sentence “if your services needs are not listed above”. This gives more focus to the button and makes it stand out for the user. 

##### *About Section*
The user can scroll to the about section and read more information about the company. The user can also learn here that the company is registered with Safe Electric Ireland by seeing the Safe Electric logo displayed. The user can also see the locations the company operates in.

##### *Contact Section*
The user can then get in touch with the company by easily scrolling to the contact section. Here they can fill out the form. If they do not provide a first name, last name, valid email address and tick one of the services button, the user will be prompted to do so in order to complete the form. They will also be given the option to provide additional details for the company if they feel it is relevant. This section also provides the user with the company’s contact details here if they wish to contact the company directly. On desktop screens, the form and contact details are stacked beside each other. Before testing, this was the same for tablet devices. However, after testing, the display was changed on tablet devices so that the form stacks on top of the contact details. This improves the layout of this section on tablets.

Please find screenshots of sections after testing [in this folder](https://github.com/romy-morrin/watts-up-electric/tree/master/wireframes).

Testing was conducted across several browsers (Chrome, Firefox Mozilla, Safari) and across several devices (iPhone 11, iPhone 6S, iPad, Samsung Galaxy).

##### *Overflow issues*
When testing the site on smaller devices, the headings for each section were spilling out over the desired outlines of the site. In order to address this issue, I added a media query to my CSS code and targeted the font-size, margin and padding of the three sections (services, about & contact) so that they would no longer distort the display on smaller screens. 

##### *Background Image Issues*
When testing the site on my phone and tablet, the background image on the home page looked zoomed in and didn’t give the desired effect that it gave on my laptop. I added another media query to troubleshoot this issue. I added the same class I had previously used for the background image and edited one of the style properties, background-attachment, so that on tablet screen sizes and smaller, it would have a value of “scoll” rather than “fixed”. This resolved the issue. 


* Passed through HTML validator [here](https://validator.w3.org/) with no issues.
* Passed through CSS validator [here](https://jigsaw.w3.org/css-validator/) with no issues. 


## Version Control
Gitpod and Github were used for version control and there is only one master branch. 

## Deployment
The project was created in Gitpod and then pushed to Github as a repository. 

#### Adding and Commiting Files

To add files to the repository you will have to:
* Type "git add . " in the command line 
* Then type "git commit -m" followed by your commit message
* Then type "git push" to push your changes to send your new work to the repository. 

#### Deploying the site

To deploy the project you will have to:
* Login to Github
* Click the settings button when in the repository
* Scroll down to the pages section
* Under source, click the dropdown called "none" and change it to master branch
* The page will automatically refresh and display a url link to the website.

#### Cloning 

If you want to make a clone of the project you will have to:
* Login to Github and find your repository
* Under the repository name click on the button that says "clone or download". 
* If cloning with HTTPS, copy the link that says "Clone with HTTPS"
* Open Gitbash 
* change the working directory to the location you want the clone directory
* Type git clone and copy the url.

## Credits & Resources
#### *Logo*
The Watts Up Electric Logo was developed by Siobhan Bailey at [Chickadee Design](https://www.chickadeedesignbysmb.com/bio)

#### *CSS tricks*
I used a snippet of code and edited it from [CSS Tricks](https://css-tricks.com/perfect-full-page-background-image/) to help position the background image in home section.

#### *Adobe stock*
I used [Adobe Stock](https://stock.adobe.com/) for the images used on the site.

#### *Services/About Content*
The business owner supplied me with the content for these sections and I edited the content while developing the site. The business owner approved the edited version.

#### *Bootstrap*
I used and edited code from Bootstrap [documentation](https://getbootstrap.com/docs/4.6/getting-started/introduction/) for the navigation menu/hamburger menu, the jumbotron, the grid layout and  the form in the contact section. 

#### *Icons*
I used icons from [Font Awesome](https://fontawesome.com/)

#### *Font*
I used [Google Fonts](https://fonts.google.com/)

## Acknowledgements
I'd like to thank Luke Morrin, the owner of Watts Up Electric for his help in developing the site. I'd also like to thank Siobhan Bailey for providing the logo. Special thanks to my mentor Brian Macharia for his help and support throughout the process. 




