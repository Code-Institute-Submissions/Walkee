# Walkee App Website
Deployed site: [https://sdgreen.github.io/first-milestone-project-walkee/](https://sdgreen.github.io/first-milestone-project-walkee/)
## Table of Contents
1. [Aim](#aim)
2. [UX](#ux)
3. [Features](#features)
4. [Technologies Used](#technologies-used)
5. [Testing](#testing)
6. [Deployment](#deployment)
7. [Credits](#credits)

---

## Aim
Walkee is an exciting new app that allows dog owners to easily meet other dog owners and arrange walks together.

Most dogs are brought singularly and don't often spend much time with other members of their species.
Whilst on walks they have the chance to meet other dogs but this isn't guaranteed and often only for a couple of minutes.
Loneliness in dogs leads to separation anxiety, flawed socialisation and ultimately poor mental health and behaviour.

Walkee aims to fix this issue by bringing dogs together for substantial amounts of time. You'll be able to improve their behavior, track physical health and hopefully make new friends too!

This website aims to easily educate interested dog owners, provide ample opportunity to download the app and follow the company on social media to improve brand awareness. 
It also acts as a login page for existing users who'd rather use the app in browser form.

## UX
The design of Walkee's website stems from analyzing the customer and business goals.

As a business Walkee's aims were simple:
* Get more downloads of the app.
* Educate prospective users easily. 
* Allow existing users to log on to the platform.
* Get more brand interaction with users through social media and increase our following.

This meant there should be a download or social link within 2 clicks maximum. Easily sign-posted information for prospective users. Some form of login functionality and many calls to download the app or follow Walkee's social in the copy.

Looking at other apps that rely on users phyically meeting/interacting through online platforms such as; [Tinder](https://tinder.com/?lang=en-GB), [Grindr](https://www.grindr.com/), [Geocaching](https://www.geocaching.com/play/mobile), [Uber](https://www.uber.com/a/join-new?utm_source=google&utm_medium=cpc-brand&utm_campaign=Search-google-brand_184_18_UK-London_d_all_acq_cpc_uk-en_Exact&adgroup_name=Pure-Brand-Misspelling&utm_term=%C3%BCber&kw=%C3%BCber&campaign_id=71700000039840326&cid=71700000039840326&adgroup_id=58700004296343639&adg_id=58700004296343639&kw_id=p35756579852&kwid=p35756579852&ad_id=321226171594&ext_id=&ran=9628064932952514583&lint_id=9045872&lphy_id=1006621&pos=1t1&dev=c&net=g&match=e&placement=&target=&gclid=Cj0KCQiAkKnyBRDwARIsALtxe7hZC-vqJ0M3a5wrei6L_GeJV9cSwGheH48uurLf7ndEasMCsR5Y0loaAjffEALw_wcB&gclsrc=aw.ds) and [Pokemon GO](https://www.pokemongo.com/en-gb/)
clearly less information on the home page is effective. Much like other websites in a B2C model, there are many emotive pictures and calls to action which heavily influenced Walkee's design.

Our customer aims were alot more utilitarian:
* Download the app
* Sign In/Sign up
* Learn more about the app

These helped influence the information architecture of the app. There needs to be clearly sign-posted information about how to achieve these goals and easy intuitive navigation which provides positive feedback.

### Target Demographic
As Walkee's target demographic is broad, dog owners over 16. As a result, the website has to feel friendly had inclusive to everyone.

This is achieved by:
* Using a gender-neutral palette that evokes the feel of autumnal park scenes.
* Having a very simple, almost linear website that even less tech-savvy users can control intuitively.
* Avoiding harsh lines where ever possible to give a friendly, soft feel to the website.
* Picking a fun font to represent the brand, dog walks are supposed to be enjoyed.

### User Stories
User stories have been used to shape the design of Walkee's website, below are the critical needs of the users and business owners:
* As a prospective user, I want to know more about the app so I can decide if I want it.
* As Walkee's owner, I want the key benefits of my app to be easily digestible, so customers don't have to spend much time deciding if they want the app.
* As a user, I want the sign-in page to be easy to find, so I can quickly log in.
* As Walkee's owner, I want the Brand to stand out, so it imbeds easily into customers consciences.
* As Walkee's owner, I want people to easily and quickly download the app, to increase our membership.
* As a user, I want the download links to be easy it find, so I can quickly download the app.
* As a visitor to the site, I want a minimal sign up form, so I can create an account quickly.

## Features
### Existing Features:
* #### Responsive Navbar: 
    This helps users to easily navigate the website and collapses on smaller devices keeping screen real estate to a minimum. The navbar isn't fixed so content is easily read, page heights are kept to a small so the navbar is never too far away.
* #### Clean footer with links to every page, download links, and social media accounts:
    This again makes navigation much easier within the site and provides quick links to everywhere a user might need to get too if the navbar is unseen.
* #### Call to action Jumbo-tron with responsive buttons:
    Quickly overviews the App and provides links to additional information and places to download the app.
* #### Responsive Copy:
    Information expands on both the home and about page, giving more information when appropriate. Excess text is cut out when on smaller screens so key benefits are easily read. 
* #### Dynamic Review Carousel:
    This helps maximise the positive buzz around the app, fitting more good feedback in a smaller area whilst making the website more dynamic.
* #### Data Validating Login form:
    An easy and clean form that also keeps passwords hidden and ensures both inputs are filled before logging on.
* #### Sign-Up Modal:
    This helps new users easily sign up on the same page. This is in keeping with convention and saves on webpages.

### Features Left to Implement
* #### Download and Social Media link functionality:
    Once Walkee exists on Twitter, Facebook, Instagram, Google Play and the App Store these links would direct the user to these external pages (via a new tab).
* #### Google Play and Apple badges:
    Once Walkee exists on Google Play and the App Store the site will be eligible to use the official badges, providing a more professional look. 
* #### Login functionality: 
    Currently this is just a static front-end component which can't actually log you on to the app. In future versions it would send you to your account page.
* #### Account Hub:
    The site should have an area where logged-in users can use a web-based version of the Walkee app.
* #### Sign Up Functionality:
    The signup form is currently just a front-end component that provides no function. In future releases, this would be able to store new user details and create accounts for them.
* #### Password Reset Button:
    In future releases a new button would appear after 1 unsuccessful login attempt which allows users to reset their password.
* #### Instagram Feed on community page:
    A feed from Walkee's Instagram account would be used to cover the background behind the link to Walkee's Instagram page giving the page a more dynamic feel.
* #### Contact Us Modal:
    A "Contact Us" modal in the footer would provide a better user experience, especially for people having trouble using the app.

## Technologies Used
* [HTML5](https://html.spec.whatwg.org/multipage/) - To create the structure of the page.
* [CSS3](https://www.w3.org/Style/CSS/Overview.en.html) - Used to style the website.
* [Bootstrap v4.3.1](https://getbootstrap.com/docs/4.3/getting-started/introduction/) - This framework was used to create a responsive mobile-first design and include functioning components.
* [JavaScript](https://www.javascript.com/) - Inculded with Bootstrap libraries to give components functionality.
* [Git](https://git-scm.com/) - Used for version control and tracking changes to the code whilst in development.
* [GitHub Pages](https://pages.github.com/) - Used to deploy the website.
* [Google Fonts](https://fonts.google.com/) - Used for Walkee's brand font [Fredoka One](https://fonts.google.com/specimen/Fredoka+One) and website fonts [Montserrat](https://fonts.google.com/specimen/Montserrat) for headings and [Lato](https://fonts.google.com/specimen/Lato) for content text.
* [Font Awesome](https://fo*ntawesome.com/) - This library provided the Icons used across the site.
* [Hover.css v2](https://ianlunn.github.io/Hover/#effects) - This library was used to give button a bounce effect aimed to increase ease of use.
* [Chrome DevTools](https://developers.google.com/web/tools/chrome-devtools) - Key for testing responsivness, trialing styles and 
## Testing
### Responsive Design Testing
### Browser testing
#### On Lenovo IdeaPad S340
* Tested on Microsoft edge (v44.18362.1.0)
  * Found that hex colors #ffffffdc not appearing on .downloadtron and background of of .benefits div. Had to convert to rgba() format.
* Google Chrome (v80.0.3987.100)
  * .downloadtron was overlapping header and footer due to being 500px at smaller widths (reduced)
* Firefox (v73.0)
  * Same as above
### Code Validation
* HTML5 code validated using [https://validator.w3.org/](https://validator.w3.org/)
* CSS3 code validated using [https://jigsaw.w3.org/css-validator/](https://jigsaw.w3.org/css-validator/)
### User Stories acheived
## Deployment
## Credits
### Media
Copyright free images taken from [Pxhere](https://pxhere.com/):
* [Forest Group](https://pxhere.com/en/photo/1066279) (file name: forest.png)
* [Dachshund](https://pxhere.com/en/photo/1029572) (file name: dasch2.png)
* [Labrador](https://pxhere.com/en/photo/714482) (file name:lab.png)
* [Dog in a scarf](https://pxhere.com/en/photo/832928) (file name: dogscarf.png)
* [Schnauzer](https://pxhere.com/en/photo/657538) (file name: schnauzer.png)
* [Man in sunglasses](https://pxhere.com/en/photo/1432871) (file name: man2.png)
* [Woman with leaf](https://pxhere.com/en/photo/1418706) (file name: woman1.png)
* [Two dogs in park](https://pxhere.com/en/photo/1425749) (file name: trees.png)

Copyright free images taken from [Needpix](https://www.needpix.com/):
* [Two dogs running](https://www.needpix.com/photo/1416632/stafford-dog-animal-pet-walking-playing-park) (file name: hounds.png)

Copyright free images taken from [PublicDomainPicture.net](https://www.publicdomainpictures.net/en/)
* [Two dogs walking in forest](https://www.publicdomainpictures.net/en/view-image.php?image=10244&picture=dogs-on-a-walk) (file name: dogswalking.png)
* [Man Walking Dogs](https://www.publicdomainpictures.net/en/view-image.php?image=221077&picture=dog-sitter) (file name: dogsitter.jpg)
Copyright free images taken from [Pexels](https://www.pexels.com)

* [Huskies in snow](https://www.pexels.com/photo/dog-in-snow-253308/) (file name: snowdogs.png)

Images provided by myself:

* [Schnauzer on sofa](https://sdgreen.github.io/first-milestone-project-walkee/assets/images/ozzy.jpg) (file name: ozzy.jpg)
* [Walkee logo](https://sdgreen.github.io/first-milestone-project-walkee/assets/images/logo.png) (file name: logo.png)
  * Created using [Logomakr](https://logomakr.com/)
* [Mock up of app on devices](https://sdgreen.github.io/first-milestone-project-walkee/assets/images/appondevice.png) (file name: appondevice.png)
  * Created using [Mockuphone](mockuphone.com)
* Favicon (file name: favicon.png)

## Code 
* Modal created from edited example modal from [Bootstrap](https://getbootstrap.com/docs/4.3/components/modal/)
* Collapsible Navbar created from edited example from [Bootstrap](https://getbootstrap.com/docs/4.3/components/collapse/)
* Carousel created from edited example from [Bootstrap](https://getbootstrap.com/docs/4.3/components/carousel/)
* Media Object created from edited example from [Bootstrap](https://getbootstrap.com/docs/4.3/components/media-object/)
* Responsive landscape breakpoints taken from [Responsivedesign.is](https://responsivedesign.is/develop/browser-feature-support/media-queries-for-common-device-breakpoints/)
* CSS prefixer used: [https://autoprefixer.github.io/](https://autoprefixer.github.io/)