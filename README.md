# Legend Of The Greek Gods

![Final project image home page](assets/images/responsiveimages.jpg)

![GitHub last commit](https://img.shields.io/github/last-commit/manni8436/Legend-of-the-Greek-Gods?color=green&style=for-the-badge)
![GitHub contributors](https://img.shields.io/github/contributors/manni8436/Legend-of-the-Greek-Gods?color=red&style=for-the-badge)
![GitHub language count](https://img.shields.io/github/languages/count/manni8436/Legend-of-the-Greek-Gods?color=blue&style=for-the-badge)
![GitHub top language](https://img.shields.io/github/languages/top/manni8436/Legend-of-the-Greek-Gods?color=yellow&style=for-the-badge)

Visit the deployed site: [Legend of the Greek Gods](https://manni8436.github.io/Legend-of-the-Greek-Gods/)

## INITIAL DESIGN

My initial idea for this project was to create an informative website about the Greek Gods. My target audience is anyone interested in Greek Mythology, this can cover a huge spectrum of ages, genders and interest levels. This ranges from children who want to learn about the Greek Gods, to anyone who wants to use the site for projects, to those who just want to read something fun and interesting.

* The main features that I wanted to include are:

* Easy to use navigation menu.
* Easy to read information.
* A black and gold colour scheme that stands out, but is not overwhelming.

## CONTENTS

* [User Experience](#user-experience)
  * [User Stories](#user-stories)
* [Design](#design)
  * [Colour Scheme](#colour-scheme)
* [Wireframes](#wireframes)
* [Technologies Used](#technologies-used)
  * [Languages Used](#languages-used)
  * [Programs Used](#programs-used)
* [Deployment](#deployment)
  * [Initial Deployment](#initial-deployment)
  * [How To Fork A Repository](#how-to-fork-a-repository)
  * [How To Clone A Repository](#how-to-clone-a-repository)
  * [How To Make A Local Clone](#how-to-make-a-local-clone)
* [Testing](#testing)
  * [Code Validators](#code-validators)
* [Content](#content)
  * [Images](#images)
  * [Text Content](#text-content)
* [Acknowledgments](#acknowledgments)

## USER EXPERIENCE

The structure of the site was designed to be simple and easy to use and have a good content balance to not overload the user and give them enough information to not leave them lost or needing more knowledge.

* The website is for the following user types:

* Users that have no previous knowledge of the stories, history, or characters and see what they used to look like.
* Users with basic knowledge of Greek history, who were looking for more information and to increase their knowledge base.
* Users who have good knowledge of Greek history but want to refresh their knowledge and do some research or even just enjoy reading about the history of all the gods.

## USER STORIES

### CLIENT GOALS

* The site needs to be easily accessible.
* The navigation menu needs to be simple to use on a range of devices, including desktop, tablet and mobile.
* Maneuvering around the site should be straightforward.
* The site should be informative and all the text should be easy to read.
* The images should be clear and not stretched or squashed.

#### FIRST TIME VISITORS

* I want it to be easy to understand how to navigate throughout the site.
* I want the content to be easily read and understandable.

#### RETURNING USER

* To gather information for projects.
* To recommend the site to friends and family.
* To get in contact with us

## DESIGN

### COLOUR SCHEME

My overall color scheme used throughout the site was gold and slightly off-black.

![Site Colour Theme](/assets/docs/colourtheme.png)

I chose these colours for my theme to represent the high status of the gods, which have been known to use gold in clothes, buildings, money and plenty of other items, I chose the off-black color to make the gold color stand out on the site.

 I also used white text in the forms section on the [Contact Us](https://manni8436.github.io/Legend-of-the-Greek-Gods/contactus.html) page.

## WIREFRAMES

[Here are my wireframes for desktop, mobile and tablet for this project](assets/wireframes/MSProject1Wireframes.pdf)

## FEATURES

I have used the following features in this project:

* Hover
* Tells the user the location of the mouse whilst navigating the menu.
* Helps the user not lose their place.

* Contact Form
* Form validation requests the user to input the correct information in the input fields.
* Avoids the user accidentally sending blank or incomplete forms.

## SOLVED BUGS

|  Bug Encountered         | Bug Solution |
| :----------------------: | :-------------: |
| None of the background images would fit on the screen properly, especially on the home page as the top of the image was getting cut off. | To fix this issue, I changed the `background-position` from `background-position: center center;` to `background-position: top center;`|
| While running my code through W3C validators, I was given an error of `duplicate attribute class`.| After closer inspection. I added `img-fluid` and `d-block w-100` into one `class=" "` rather than splitting it between multiple `class=" "`, After checked all pages through the W3C validator, there were not further errors shown. |

## TECHNOLOGIES USED

### LANGUAGES

![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)

### VERSION CONTROL

![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)
![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)
![Gitpod](https://img.shields.io/badge/gitpod-f06611.svg?style=for-the-badge&logo=gitpod&logoColor=white)

### FRAMESWORKS & LIBRARIES

![Bootstrap](https://img.shields.io/badge/bootstrap-%238511FA.svg?style=for-the-badge&logo=bootstrap&logoColor=white)

### BROWSERS

![Firefox](https://img.shields.io/badge/Firefox-FF7139?style=for-the-badge&logo=Firefox-Browser&logoColor=white)
![Google Chrome](https://img.shields.io/badge/Google%20Chrome-4285F4?style=for-the-badge&logo=GoogleChrome&logoColor=white)
![Edge](https://img.shields.io/badge/Edge-0078D7?style=for-the-badge&logo=Microsoft-edge&logoColor=white)
![Safari](https://img.shields.io/badge/Safari-000000?style=for-the-badge&logo=Safari&logoColor=white)

### WIREFRAMING

![Balsamiq](https://img.shields.io/badge/Balsamiq%20-%23A60000.svg?&style=for-the-badge&logo=Balsamiq&logoColor=FFFFFF)

### SITE DEPLOYMENT

![GitHub Pages](https://img.shields.io/badge/github%20pages-121013?style=for-the-badge&logo=github&logoColor=white)

## DEPLOYMENT

### INITIAL DEPLOYMENT

This site was deployed using GitHub Pages with the following steps below:

1. Login or Sign Up to [GitHub](www.github.com).
2. Create a new repository named "Legend-of-the-Greek-Gods".
3. Once created, click on "Settings" on the navigation bar under the repository title.
4. Click on "Pages", on the left-hand side below Secrets.
5. Under "Source", choose which branch you wish to deploy, In most cases, it will be "main".
6. Choose which folder to deploy from, generally from "/root".
7. Click "Save", then wait for it to be deployed. It may take some time for the page to be fully deployed.
8. The URL will be displayed above the "source" section in GitHub Pages.

### HOW TO FORK A REPOSITORY

If you need to make a copy of a repository:

1. Login or Sign Up to [GitHub](www.github.com).
2. On GitHub, go to [manni8436/Legend-of-the-Greek-Gods](manni8436/Legend-of-the-Greek-Gods).
3. In the top right corner, click "Fork".

### HOW TO CLONE A REPOSITORY

If you need to make a clone:

1. Login to [GitHub](www.github.com).
2. Fork the repository manni8436/Legend-of-the-Greek-Gods using the steps above in [How To Fork a Repository](#how-to-fork-a-repository).
3. Above the file list, click "Code".
4. Choose if you want to close using HTTPS, SSH or GitHub CLI, then click the copy button to the right.
5. Open Git Bash.
6. Change the directory to where you want your clone to go.
7. Type git clone and then paste the URL you copied in step 4.
8. Press Enter to create your clone.

### HOW TO MAKE A LOCAL CLONE

If you need to make a local clone:

1. Login to [GitHub](www.github.com).
2. Under the repository name, above the list of files, click "Code".
3. Here you can either Clone or Download the repository.
4. You should close the repository using HTTPS, clicking on the icon to copy the link.
5. Open Git Bash.
6. Change the current working directory to the new location, where you want the cloned directory to be.
7. Type git clone and then paste the URL you copied in step 4.
8. Press Enter, and your local clone will be created.

## TESTING

### CODE VALIDATORS

The W3C Markup and CSS Validators were used to validate my project to make sure there were no errors within the site.

|  Code validated         | Website Page          | Validator Results |
| :---------------------: | :-------------------: | :---------------: |
| ![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)|![Home Page Image](/assets/docs/homepage.png)|![HTML Validator Image](/assets/docs/homepagevalidator.png) |
| ![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)|![Big Three Image](/assets/docs/bigthree.png)|![HTML Validator Image](/assets/docs/bigthreevalidator.png) |
| ![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)|![Lesser known Image](/assets/docs/lesserknown.png)|![HTML Validator Image](/assets/docs/lesserknowngodsvalidator.png) |
| ![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)|![History Image](/assets/docs/history.png)|![HTML Validator Image](/assets/docs/historyvalidator.png) |
| ![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)|![Contact Us Image](/assets/docs/contactus.png)|![HTML Validator Image](/assets/docs/contactusvalidator.png) |

|  Code validated         | Validator Results |
| :---------------------: |:---------------: |
| ![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)|![CCS Validator Image](/assets/docs/cssvalidator.png) |

### FULL TESTING

[Click Here](testing.md) to view the full testing steps that were completed on every device and browser.

### LIGHTHOUSE

I have tested my website on both desktop and mobile, Overall I am pleased with the results however there is still room for improvement, by reviewing and possibly removing any unused code, eliminating render-blocking resources and using next-gen image formats like `WebP` and `AVIF`. With this feedback, I will look into improving my lighthouse scores, in particular on mobile.

### DESKTOP

| Lighthouse Results |
| :----------------: |
|![Home Page Lighthouse](/assets/docs/desktophomepagelighthouse.png)|
|![Big Three Page Lighthouse](/assets/docs/desktopbigthreelighthouse.png) |
|![Lesser Known Page Lighthouse](/assets/docs/desktoplesserknownlighthouse.png) |
|![History Page Lighthouse](/assets/docs/desktophistorylighthouse.png) |
|![Contact Us Page Lighthouse](/assets/docs/desktopcontactuslighthouse.png) |

### MOBILE

| Lighthouse Results |
| :----------------: |
|![Home Page Lighthouse](/assets/docs/mobilehomepagelighthouse.png)|
|![Big Three Page Lighthouse](/assets/docs/mobilebigthreelighthouse.png) |
|![Lesser Known Page Lighthouse](/assets/docs/mobilelesserknownlighthouse.png) |
|![History Page Lighthouse](/assets/docs/mobilehistorylighthouse.png) |
|![Contact Us Page Lighthouse](/assets/docs/mobilecontactuslighthouse.png) |

#### Performance

* I was very happy with my initial lighthouse scores.
* The issues reducing my performance scores are that I have a lot of images, including background images on all pages and also a huge amount of content on four pages.
* My mobile scores are lower due to the scaling down of images and text for use on mobile.

#### Accessibility

* While writing my code, I was careful to ensure that it was fully accessible.
* Every image has the relevant alt text applied to it.
* All text has good visibility on the background I chose.

#### Best Practices

* All images are shown in the correct aspect ratio, so as not to look stretched or pixelated.

#### SEO

* I ensured the site had all the relevant meta tags needed.
* All font sizes are legible on all screen sizes.

## CONTENT

### IMAGES

Images for this project have been provided mainly by Wikipedia and Pinterest, A full list has been provided below.

The three images below was to depiction of the three main Gods in Greek Mythology.

|  Zeus    | Poseidon | Hades |
| :------: | :------: | :----:|
| [![Zeus](/assets/images/zeusstatue.jpg)](https://en.wikipedia.org/wiki/Zeus) |  [![Poseidon](/assets/images/poseidonstatue.jpg)](https://en.wikipedia.org/wiki/Poseidon) | [![Hades](/assets/images/hadesstatue.jpg)](https://en.wikipedia.org/wiki/Hades) |

|  Background Images    | Lesser Known Gods Images and Carousel Images |
| :-------------------: | :------------------------------------------: |
| <table><tr><th>Home Page</th><th>[Zeus](https://wallpaperaccess.com/zeus)</th></tr><tr><th>Big Three Page</th><th>[Poseidon](https://omniversal-battlefield.fandom.com/wiki/Poseidon_(Greek_Mythology)?file=Poseidon.jpg)</th></tr><tr><th>Lesser Known Gods Page</th><th>[Hades](https://www.artstation.com/artwork/1YzOK)</th></tr><tr><th>History Page</th><th>[Athena](https://www.pinterest.co.uk/pin/434245589082196360/)</th></tr><tr><th>Contact Us Page</th><th>[Hermes](https://www.ancient-origins.net/myths-legends-europe/hermes-0011776)</th></tr></table> | <table><tr><th>[Atlas](https://en.wikipedia.org/wiki/Atlas_(mythology))</th><th>[Mount Olympus](https://www.pinterest.co.uk/pin/111182684540958323/)</th></tr><tr><th>[Heracles](https://en.wikipedia.org/wiki/Heracles)</th><th>[Temple of Zeus](https://en.wikipedia.org/wiki/Temple_of_Olympian_Zeus,_Athens#History)</th></tr><tr><th>[Amphitrite](https://www.pinterest.com/pin/423831014921428350/)</th><th>[Temple of Poseidon](https://en.wikipedia.org/wiki/Temple_of_Poseidon,_Sounion)</th></tr><tr><th>[Asclepius](https://en.wikipedia.org/wiki/Asclepius)</th><th>[Parthenon](https://www.visionpubl.com/en/cities/athens/parthenon-facts-history/)</th></tr><tr><th>[Pan](https://www.pinterest.co.uk/pin/410109109794860381/)</th><th>[Ancient Olympia Stadium](https://yallatoursblog.com/2014/01/27/faster-higher-stronger-in-ancient-olympia/)</th></tr><tr><th>[Nike](https://www.pinterest.co.uk/pin/111182684540958323/)</th></tr></table>|

### TEXT CONTENT

* Text content on all Pages was copied and/or amended from the following sites:  
  
|  Text Used               | on Website               |
| :----------------------: | :----------------------: |
| <table><tr><th>[Parthenon](https://www.visionpubl.com/en/cities/athens/parthenon-facts-history/)</th><th>[Ancient Olympia](https://yallatoursblog.com/2014/01/27/faster-higher-stronger-in-ancient-olympia/)</th></tr><tr><th>[Acropolis of Athens](https://en.wikipedia.org/wiki/Acropolis_of_Athens#History)</th><th>[Temple of Hera, Olympia](https://en.wikipedia.org/wiki/Temple_of_Hera,_Olympia)</th></tr><tr><th>[The second link for the Temple of Hera, Olympia](https://www.greeka.com/peloponnese/olympia/sightseeing/temple-hera/)</th><th>[Heracles and The Twelve Labors](https://www.history.com/.amp/topics/ancient-history/greek-mythology)</th></tr><tr><th>[Zeus](https://en.wikipedia.org/wiki/Zeus)</th><th>[Poseidon](https://en.wikipedia.org/wiki/Poseidon)</th></tr></table> | <table><tr><th>[Hades](https://en.wikipedia.org/wiki/Hades)</th><th>[Atlas](https://en.wikipedia.org/wiki/Atlas_(mythology))</th></tr><tr><th>[Atlas](https://en.wikipedia.org/wiki/Atlas_(mythology))</th><th>[Hercules/Heracles](https://en.wikipedia.org/wiki/Hercules#Mythology)</th></tr><tr><th>[Amphitrite](https://en.wikipedia.org/wiki/Amphitrite#Mythology)</th><th>[Pan](https://www.pinterest.co.uk/pin/410109109794860381/)</th></tr><tr><th>[Nike](https://en.wikipedia.org/wiki/Nike_(mythology))</th></table>|

## ACKNOWLEDGMENTS

I would like to give a big thanks to [Chris Quinn](https://github.com/10xOXR) for all his help, effort, guidance
and patience he has provided during this project.

I would also like to thank [Abi Harrison](https://github.com/Abibubble) for all her support, and advice and for explaining things to me when I did not understand.
