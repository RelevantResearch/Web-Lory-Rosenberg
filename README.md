Ducor UpSkill HTML Template | Homepage
===========================

Welcome To Ducor UpSkill HTML Template | Homepage
--------------------------------------

Firstly, a huge thanks for purchasing this theme, your support is truly appreciated!

This document covers the installation and use of this theme and often reveals answers to common problems and issues - read this document thoroughly if you are experiencing any difficulties. If you have any questions that are beyond the scope of this document, feel free to email at [ducorteam@gmail.com](mailto:hmjubayed@gmail.com) Thank you so much!

Template Features
-----------------

Ducor UpSkill HTML Template | Homepage
===========================

Basic
-----

1.  After unzip the download pack, you'll found a Template Folder with all the files.
2.  You can view this Template in any browser, you can display or edit the Template without an internet connection.(May not wotrk fonts and google map).
3.  This section that will not work is the Contact Section which contains formspree.io form service for send messages.
4.  Now go to your github account and create repository (name like yourname.github.io). Push the content of the Template on your github repo.
5.  Once the files are done uploading go to yourname.github.io
6.  Enjoy


Contact Form
------------

This is a formspree.io for sending messages to your email, you should replace **form\_id** to your email to start receiving messages.

formspree.io create your own account

```html
<form action="[https://formspree.io/f/](https://formspree.io/f/){form_id}" method="POST">

  <input type="text" name="name">

  <input type="email" name="_replyto">

  <input type="submit" value="Send">

</form>
```

System Preparation
------------------

1.  To use this project, you'll need the following things installed on your machine.
2.  1\. \[Jekyll\] (http://jekyllrb.com/) - $ gem install jekyll bundler
3.  2\. \[NodeJS\] (http://nodejs.org) - use the installer.
4.  3\. \[GulpJS\] (https://github.com/gulpjs/gulp) - $ npm install -g gulp (mac users may need sudo)

Installation
------------

### Local Instalation

1.  1\. Inside the directory, run npm install .
2.  2\. Enjoy

### Development Mode

1.  This will give you file watching, browser synchronisation, auto-rebuild, CSS injecting etc etc.


$ gulp

1.  This will give you file watching, browser synchronisation, auto-rebuild, CSS injecting etc etc.

### Deploy with Gulp

1.  1\. You can easily deploy your site build to a gh-pages branch.
2.  2\. First, follow the instructions at \[gulp-gh-pages\](https://github.com/rowoot/gulp-gh-pages) to get your branch prepared for the deployment and to install the module.
3.  Then, in gulpfile.js you'll want to include something like the code below.
4.  gulp.src() needs to be the path to your final site folder, which by default will be _site. If you change the destination in your _config.yml file, be sure to reflect that in your gulpfile.

javascipt
var deploy = require("gulp-gh-pages");

gulp.task("deploy", ["jekyll-build"], function () {

    return gulp.src("./_site/**/*")

        .pipe(deploy());

});


Source and Credit
-----------------

*   [Pexels](http://www.pexels.com/)
*   [jQuery](http://jquery.com/)
*   [Bootstrap Framework](http://getbootstrap.com/)
*   [FontAwesome](http://fontawesome.io/)
*   [Codrops](http://www.codrops.com/)
*   [Bonzo](https://github.com/ded/bonzo/)
*   [ImagesLoaded](https://imagesloaded.desandro.com/)
*   [jquery.hoverdir.js](http://www.codrops.com/)
*   [Masonry PACKAGED](http://masonry.desandro.com/)


What's Included
---------------

After purchasing tunis template on themeforest.net with your envato account, go to your download page. You can choose to download tunis template only (Installable React template) or the entire tunis template.After extract the package you will find following this files:

![whats-included](img/included/1.png)

### You can get the following items after purchasing our template from themeforest[](#template-package)

*   **tunis** - An Installable React template zip file. this file you need to upload
*   **License** - This folder contains the terms and conditions of the license.
*   **Documentation** - This folder contains what you are reading now :)

React Installation
------------------

Please follow the instructions in the video to see how you can install React on your hosting:

1.  **For local host** -
    1.  Open you command prompt
    2.  npm install
    3.  npm run start

Change Site Title[](#change-site-title)
---------------------------------------

To change your Site title and Favicon open the tunis in your editor and go to the location by following screenshot which are given bellow.

1.  From the template options go to public

![go to Appearance -> Import Demo Data](img/basic-setting/favicon.png)

By folllowing this screenshot you can change your Site Title

Change Favicon[](#change-favicon)
---------------------------------

To change your Site Favicon by following screenshot

1.  From the template options go to publicimg

![go to Appearance -> Import Demo Data](img/basic-setting/title-and-favicon.png)

By folllowing this screenshot you can change your Favicon

Change Template Color[](#change-template-color)
-----------------------------------------------

To change your Site Primary Color by following screenshot

1.  From the template options go to assetesscss\_style.scss

![go to Appearance -> Import Demo Data](img/basic-setting/color.png)

By folllowing this screenshot you can change your Primary Color

Menu[](#header_title)
---------------------

To change Menu content by following this screenshot here.

1.  From the template options go to src viewsall-home-versionHomeDark.jsx

![Change Profile Image](img/theme-options/header.png)

Change Menu Content following the screenshot

Hero Section[](#hero_title)
---------------------------

To change Hero Section content by following this screenshot here.

1.  From the template options go to src componentssliderHero.jsx

![Change Profile Image](img/theme-options/slider.png)

Change Hero Section Content

Social Networks[](#social-networks)
-----------------------------------

Pul your social profile link here.

1.  From the template options go to src componentSocial.jsx

![Add your link here](img/theme-options/social_profile_1.png)

To change your Hero Content Social

About[](#about-1)
-----------------

To change about page image and content by following this screenshot here.

1.  From the template options go to src componentaboutAbout.jsx

![Add your link here](img/about/personal-info.png)

Change Personal Info Content following the screenshot

![Add your link here](img/about/achievements.png)

Change Achievements Content following the screenshot

![Add your link here](img/about/skills.png)

Change Skills Content following the screenshot

![Add your link here](img/about/experience.png)

Change Experience Content following the screenshot

![Add your link here](img/about/education.png)

Change Education Content following the screenshot

Portfolio[](#portfolio_page_title)
----------------------------------

To customize portfolio page. Please follow the steps:

1.  From the template options go to src componentportfolioPortfolio.jsx

![Portfolio Single Page Setting 1](img/portfolio/1.png)

Portfolio Page Content Customization follow the screenshot

![Portfolio Single Page Setting 1](img/portfolio/popup/1.png)

Portfolio Details Popup Content Customization follow the screenshot

How to send mail throught contact form[](#blog_archive_title)
-------------------------------------------------------------

Send email from React without backend ( [**Email js Official Website**](https://www.emailjs.com/docs/examples/reactjs/)) and follow bellow screenshot here and also follow this video ( [**Youtube**](https://youtu.be/t1_kviNJsy4))

1.  From the template options go to src componentsContact.jsx

![Change Blog Archive Setting](img/theme-options/contact-form.png)

Change Contact Form Information

1.  Change Address Conent the template options go to src componentsAddress.jsx

![Change Blog Archive Setting](img/theme-options/address.png)

Change Your Adreess follow this

Blog[](#blog_archive_title)
---------------------------

To change Blog Content and setting you can change by following this screenshot here.

1.  From the template options go to src componentsblogBlog.jsx

![Change Blog Archive Setting](img/theme-options/blog_archive.png)

Change all home page Blog Content

![Change Blog Archive Setting](img/theme-options/blog-popup.png)

Change Blog Popup Content from this

Change Log[](#changelog_title)
------------------------------

**[ducorteam Team](https://themeforest.net/user/ducorteam)** never stops Improving, bug fixes, and improvements. See What's New. We recommend you to read the changelog for every update.

###### 2022 Aug 26

Init Release

1.0.0

New1) Template Release

###### Support? [ducorteam@gmail.com](mailto:ducorteam@gmail.com)

If you like our product. [Please Rate Us](https://themeforest.net/downloads)