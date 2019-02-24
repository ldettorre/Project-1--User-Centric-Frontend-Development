# Luca D'Ettorre Portfolio
A User-Centric Frontend Development Project.

Welcome to my online portfolio. The purpose of this site is to display my use of Frontend technologies for my User-Centric Frontend Development Project with Code Institute. This online space also allows me the opportunity to briefly inform visitors about my current skill set, showcase my recent projects to potential employers and clients aswell as provide access to my most current CV and links to frequently used online platforms.

Click [here](https://ldettorre.github.io/portfolio/) to view my portfolio site live.


## UI & UX 

I wanted to achieve a consistent flow of content both on larger desktop resolutions and narrower mobile screens. This was accomplished by using a single page format with multiple sections as opposed to seperate pages to load. In relation the site theme, I was inspired by the simplicity of the Apple Macbook but wanted to add a dash of colour through the use of the landing image, progress bars in the Skill section and the natural colors of the project's thumbnails. There was also no template used for this project.

As for site users, I wanted to efficiently brief recruiters on my current skill set and ability with my most frequently used technologies. Should the user be a potential client or employer they can see live versions of my work as the thumbnails act as links to the respective live sites. Should any of these users also work with code, they can also access my GitHub repositories to each project. There has also been links added to my frequently used online social networking platforms and to a downloadable PDF of my CV.


## Technologies used for this project
* HTML
* CSS
* Bootstrap Version 3.3.7
* Javascript
* FontAwesome
* Google Fonts 
* Balsamiq for wiregframing and mock-ups.


## Features

### Existing Features
* Responsive layout and navigation bar.
* Automatic smooth scrolling to the chosen section. This code has been copied from [hschafer2017](https://github.com/hschafer2017/HSCHAFER-Portfolio/blob/master/assets/js/index.js) on Github.
* Fully functioning and accurate links to 
    * Deployed Projects.
    * GitHub Repositories.
    * Social networking platforms.  
    * Current C.V. in PDF format. 

### Future Features

###### Contact Me
At the moment in the "Contact" section, there is  placeholder for a form to be submitted. I previously used the 'href="mailto:'feature however it has been removed as Apple hardware does not use the same email app that is default in Windows. This results in an error showing and I decided best to leave it solely as a placeholder for future updates.

###### Blogging
Beyond the projects being showcased there is not much else creating a need or desire to return. I would like to include a blog aspect to the site however I will using a framework such as Flask or Django for this.

###### Donations
With a framework upgrade to Django it would allow me to create a donation app where users can donate towards the likes of a cup of coffee.

###### Styling
I'd like to make the site itself alot more 'alive' through the use of Javascript and have the contact be more active on the page in response to the users actions. The imagery of the site will also be updated to something more consistent as opposed to being a mix of photos from different sites as it is now.



## Testing

### Responsiveness
Through out the development of this site I have been using Chrome DevTools, Firefox Developer Tools and [ResponsiveDesignChecker](https://responsivedesignchecker.com/) to test responsiveness. As I had some issues with Chrome DevTools during testing, I wanted to ensure some form of coverage by incorporating other tools as well as some physical hardware. The aforementioned tools were beneficial in simualting a multitude of resloutions I did not have access to in physical form, for example, that used for Apple hardware.

With regards to physical hardware, the site was tested on a number of different Samsung Galaxy smartphones using Samsung's browser as well as Chrome, Dell and Asus laptops and also screen size and resoloutions ranging from 24 inch 1080p monitors up to 75 inch panels at 4k. 

At the smaller resoloution widths less than 300 pixels the site develops an issue with the landing text breaking out of the image space. In Chrome DevTools there is also white space along the right hand side of the page that increases as the you go below the 300 pixel width. However, from 300 pixel width and above the site performs as expected.

### User Interaction
The following has also been manually tested.
* All navigation bar buttons bring the user to the correct section of the site.
* All project thumbnails open up a new tab through the use of target="_blank" and load the appropriate project .
* The FontAwesome icons link to the appropriate projects live site and GitHub repository.
* The navbar buttons change to a single dropdown option when below 768 pixel width.
* Upon clicking the CV button, a new tab opens with the CV to view and download.
* The hover feature to display more information about the projects is functioning as intended. For desktop users you hover over the thumbnail with your mouse. For touchscreen users you hold a tap and the information appears in similar fashion.


## User Stories
All the following objectives are catered for on this portfolio site.
* As the site owner - I want a space to tell people a little about myself,  show off my creative skill set, showcase projects of my choosing and give people different mediums to contact me through.
* As a recruiter/employer - I want to learn about an individuals background and skills without having to do excessive heavy reading. I also want to easily be able to see their work in action without having to ask for permission.
* As a recruiter/employer - I want to know how can I connect with them.
* As a recruiter/employer - I want access to a CV for further review.


## Deployment
I have hosted this site on GitHub Pages and deployed it from the master branch.

In order to run this yourself, enter `git clone https://github.com/ldettorre/portfolio.git` into your terminal.

## Credits

### Content
All content in the "About Me/À Propos" and "Work/Travail" sections in this portfolio site were written by me. 

### Media
I sourced photos, fonts and icons for this site from 
* [Pexels.com](https://www.pexels.com/)
* [Pixabay.com](https://pixabay.com/en/)
* [Google Fonts](https://fonts.google.com/)
* [Font Awesome](https://fontawesome.com/)

### Acknowledgements
I would like to credit the automatic smooth scrolling feature to [hschafer2017](https://github.com/hschafer2017/HSCHAFER-Portfolio/blob/master/assets/js/index.js) on Github. 

Also credit to [mparkcode](https://github.com/mparkcode) for helping me with a bug I had regarding my profile photo. Initially the photo caused y-axis scrolling when using width="px" however he advised to use a width="%" and it fixed the issue.



