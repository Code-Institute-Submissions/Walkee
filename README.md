prefixer used: https://autoprefixer.github.io/
https://responsivedesign.is/develop/browser-feature-support/media-queries-for-common-device-breakpoints/

http://www.responsinator.com/?url=sdgreen.github.io%2Ffirst-milestone-project-walkee%2Findex.html
http://www.responsinator.com/?url=sdgreen.github.io%2Ffirst-milestone-project-walkee%2Fabout.html
http://www.responsinator.com/?url=sdgreen.github.io%2Ffirst-milestone-project-walkee%2Fcommunity.html
http://www.responsinator.com/?url=sdgreen.github.io%2Ffirst-milestone-project-walkee%2Fdownload.html
- One thing I would change on future releases would be the bottom margin on the download call-outt on landscape devices to make them smaller
http://www.responsinator.com/?url=sdgreen.github.io%2Ffirst-milestone-project-walkee%2Flogin.html

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
The design of Walkee's website stems from analysing the customer and business goals.

As a business Walkee's aims were simple:
* Get more downloads of the app
* Educate propective users easily 
* Allow existing users to log on to the platform
* Get more brand interaction with users through social media

This meant their always has to be a download or social link within 2 clicks maximum. Easily sign-posted information for propective users. Some form of login functionality and lots of calls to get the app or follow Walkee's social in the copy.

Looking at apps which follow in the same vein of people meeting in the physical world through online apps like [Tinder](https://tinder.com/?lang=en-GB), [Grindr](https://www.grindr.com/), [Geocaching](https://www.geocaching.com/play/mobile), [Uber](https://www.uber.com/a/join-new?utm_source=google&utm_medium=cpc-brand&utm_campaign=Search-google-brand_184_18_UK-London_d_all_acq_cpc_uk-en_Exact&adgroup_name=Pure-Brand-Misspelling&utm_term=%C3%BCber&kw=%C3%BCber&campaign_id=71700000039840326&cid=71700000039840326&adgroup_id=58700004296343639&adg_id=58700004296343639&kw_id=p35756579852&kwid=p35756579852&ad_id=321226171594&ext_id=&ran=9628064932952514583&lint_id=9045872&lphy_id=1006621&pos=1t1&dev=c&net=g&match=e&placement=&target=&gclid=Cj0KCQiAkKnyBRDwARIsALtxe7hZC-vqJ0M3a5wrei6L_GeJV9cSwGheH48uurLf7ndEasMCsR5Y0loaAjffEALw_wcB&gclsrc=aw.ds) and [Pokemon GO](https://www.pokemongo.com/en-gb/) it was clear that less infomation on the home page is more. Instead much like other websites in a B2C model there was lots of emotive pictures and calls to action which heavily infulcend walkee's design.

Our customer aims were alot more utilitarian:
* Download the app
* Sign In/Sign up
* Learn more about the app

These helped influcnece the information achiecture of the app. There needed to be a clearly sign-posted information about how to acheieve these goals and easy infuituve naviagtion which provides positive feedback when you click on a link.

### Target Demographic
As Walkee's target demographic is broad (general dog owners over 16) the website had to feel friendly had inclusive to everyone.

This is acheived by:
* Using a gender neutral palette that evoke the feel of autumn dog walk
* Having a very simple, almost linear website that even less tech savvy users can control
* Avoiding harsh lines where ever possible to give a friendly feel to the website
* Picking a more fun font to represent the brand, dog walks are supposed to be enjoyed.
### User Stories
Here are the user stories that shaped the design of Walkee's website:
* As a prosective user, I want to know more about the app so I can decided if I want it.
* As the business owner, I want the key benifits of my app to be easily digestable, so customers don't have too much time to decide if they want to get the app.
* As a user, I want the login to be easy to find, so it's easy to login.
* As Walkee's owner, I want the Brand to stand out, so it imbeds easily into customers consciences.
* As Walkee's owner, I want people to easily download the app, too increase our membership.
* As a user, I want to find download links to be easy it find, so I can quickly download the app.#
* As a visitor to the site, I want a sign up form, so I can create an account quickly.
## Features
### Existing Features
* #### Responsive Navbar: 
    This helps users to easily navigate the website and collapses on smaller devices so not too much screen real estate is used up. The nav bar isn't fixed so content is easily read, page heights kept to a minimum so the navbar is never too far away.
* #### Clean footer with links quick links to everypage, download links and social media accounts:
    This again makes navigation much easier within the site and provides quick links to everywhere a user might need to get too if the navbar is unseen
* #### Call to action Jumbo-tron with responsive buttons:
    Quickly overviews the App and provides quick links to addition information and places to download from
* #### Responsive Copy:
    Information expands on both the home and about page to cut text when on smaller screens & make it more digestable
* #### Dynamic Reviews Carousel:
    This helps maximise the positive buzz around the app, fitting more good feedback in a smaller area whilst making the website more dynamic.
* #### Data Validating Login orm:
    A easy and clean form which will also hides password infomation and ensures both inputs are filled
* #### Sign-Up Modal:
    This helps new users easily sign up without creating more pages

### Features Left to Implement
* #### Download and Socail Media link functionality:
    Once Walkee exists on Twitter, Facebook, Instagram, Google Play and the App Store these links would be added to their buttons
* #### Login functionality: 
    Currently this is just a static front-end component which can't actually log you on to the app. In future versions it would actually send you to your account page.
* #### Account Hub:
    The site should have an area where logged in users could use a web based version of the Walkee app.
* #### Sign Up Functionality:
    The sign up form is currently just a front-end component which provides no fuction. In future releases this would be able to store new user details and create an account for them.
* #### Password Reset Button:
    In furture releases a new button would appear after 1 unsuccessful login attempt which allows users to reset their password.
* #### Instagram Feed on comminty page:
    A feed from Walkee's instagram would be used to cover the background behind the link to Walkee's instagram page.
* #### Contact Us Modal:
    A "Contact Us" modal in the footer would provide a better user expericence, especially for people having trouble using the app.
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
### Code Validation
### User Stories acheived
## Deployment
## Credits
### Media
Copyright free images taken from [Pxhere](https://pxhere.com/):
* [Forest Group](https://pxhere.com/en/photo/1066279) (file name: forest.png)
* [Dachshund](https://pxhere.com/en/photo/1029572) (file name: dasch2.png)
* [Labrador](https://pxhere.com/en/photo/714482) (file name:lab.png)
* [Dog in a scarf](https://pxhere.com/en/photo/832928) (fike name: dogscarf.png)
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
* Lanscape breakpoints taken from [Responsivedesign.is](https://responsivedesign.is/develop/browser-feature-support/media-queries-for-common-device-breakpoints/)