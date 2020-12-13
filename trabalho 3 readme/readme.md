## Installing and configuring wordpress

### Installing

To install wordpress the computer, download the winrar and unzip it to a folder on the document root. 

Open wp-admin/install.php on the browser. It will help me config wp-config.php with the details of my database.

Since it didint start , i had to change the wp-config.php file manualy, by adding a myphp database that i created:

[firstconfig](imagem1.JPG)

Wordpress was installed, and to finish I just created an admin account.

### Making the website

After login, I had access to the following panel(already with plugins installed by me)

[adminpanel](imagem2.jpg)

The wordpress is very easy to work with, I did some experiences with the pages, but to make it more easy and intuitive I installed some plugins:

[plugins](imagem3.jpg)

#### Plugins

To build the website I added Starter Templates plugin:

[starterTemplate](imagem4.jpg)

This plugin takes one of the sites already made, so I can change it the way i want, it can save a lot of time. So i choose one of the Elementor websites, so I had to install the Elementor plugin, which is very good for editing the page. It also installed wp-forms to make user forms.

I also installed a plugin for the facebook, instagram and twitter feed to appear on the webpage.

And the last was a plugin for user login. 

I also installed a plugin for react js, in case i would use it, but i didn't.

#### General settings

In Presentation I did a bit of changings to the original copied webpage, changed the logo and the header titles:

[header](imagem5.jpg)

There is much more i could do, but for now i only changed the basic. 

#### Pages

In this section there are all the pages of the website:

[pages](imagem6.jpg)

Here, they can be added, deleted or modified, for example:

[pageedit](imagem7.jpg)

With Elementor I have all those options available, I just select them and add widget to add anything I want.

#### Header and footer

In the section we can change the header and footer, but for this website i manage to change the header on the general settings, so here is only the footer:

[footer](imagem8.jpg)

Again the footer is changed with Elementor, for this footer i added a logo with the icons of each social media bellow, and a contact form that allows visitors to contact the webmaster:

[footerSite](imagem9.jpg)

#### Social media feed

With the plugins for each social feed, all i had to do was connect them to my accounts and past the code on the page were i want the social feed: 

[socialfeed](imagem10.jpg)

Facebook had a problem, because it only works if I have a page or group to connect to, doesn't allow to show my feed, but for twitter and instagram worked perfectly.

#### Website 

So this is the homepage:

[homepage](imagem11.jpg)

The about page with the social feed:

[about](imagem12.jpg)

The education:

[education](imagem13.jpg)

The experience:

[experience](imagem14.jpg)

The user page:(Not finished)

[userpage](imagem15.jpg)

#### User register and login:

So I had some problems here, I used the plugin to create user registration and login:

[userplugin](imagem16.jpg)

This is the plugin page, it is the user overview. Firstly, i did one normal register to see how it was but i couldnt send the user to his page after the login. Secondly, i created another account with mail verification, but it didin't send any email to me, so it isn't working. I might need some help regarding this issue.

I also confirmed that the users are indeed in the databse and their password is protected:

[mydb](imagem17.jpg)

The plugin give us several options and forms for the register and login:

[forms](imagem18.jpg)

I created a page for the login as showned before and the register it is on the home page:

[registerforms](imagem19.jpg)

It shows error in case of weak password and etc.

So basically i can register users but can't log in with them, only with the admin DarkMx, I can login trough the site to my admin area of wordpress. 