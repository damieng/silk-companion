silk-companion
===============

[![NPM version](https://img.shields.io/npm/v/silk-companion.svg)](https://www.npmjs.org/package/silk-companion)
[![Bower version](https://img.shields.io/bower/v/silk-companion.svg)](http://bower.io/search/?q=silk-companion)
[![Packagist version](https://img.shields.io/packagist/v/damieng/silk-companion.svg)](https://packagist.org/packages/damieng/silk-companion)







About
----------


Silk companion icon set #1 - "More Silk!"
Last updated: 19 November 2007

_________________________________________
Damien Guard
http://damieng.com/creative/icons/silk-companion-1-icons

Packaging by T1st3
https://github.com/T1st3
_________________________________________


This work is licensed under a
Creative Commons Attribution 2.5 License.
[ http://creativecommons.org/licenses/by/2.5/ ]

The FamFamFam Silk icon set is a very large,
consistent set of well-drawn icons that has
proven to be popular with both applications
and web sites.

On a number of occasions I have found myself
wanting more icons in the same style. This 
companion set represents what I needed but also
what I felt like adding.

Some are new icons in the same style, some are
alternative sizes/colours of the existing icons
and some are new compositions of the elements.

Any questions about this companion set please
contact damieng@gmail.com.



The Original Silk readme this work is based upon:


Silk icon set 1.3

_________________________________________
Mark James
http://www.famfamfam.com/lab/icons/silk/
_________________________________________

This work is licensed under a
Creative Commons Attribution 2.5 License.
[ http://creativecommons.org/licenses/by/2.5/ ]

This means you may use it for any purpose,
and make any changes you like.
All I ask is that you include a link back
to this page in your credits.

Are you using this icon set? Send me an email
(including a link or picture if available) to
mjames@gmail.com

Any other questions about this icon set please
contact mjames@gmail.com



CSS spritesheets
----------

You can insert the icons directly into your HTML with a common IMG tag:

```
    <img alt="Connect" src="dist/png/folder_connect.png" width="16" height="16">
```


In addition to the icons by themselves, this project also ships a CSS spritesheet for the icon-pack. This spritesheet allows to load the entire icon-pack in just 1 image, and thus reduce HTTP calls.

This is what it actually looks:

![Spritesheet](https://raw.githubusercontent.com/damieng/silk-companion/master/dist/sprite/silk-companion.png)


All the positioning of the icons inside this alone image is made through CSS, which allows you to just add block-type tags with the proper class and get the same result:

```
    <div class="silk-companion folder_connect"></div>
```

Just remember to add the CSS stylesheet to the HEAD of your HTML page!




About the rest (all this repository but the icons)
----------

All the content of this repository (excepted the icon pack) 
is licensed under the [MIT license](http://opensource.org/licenses/MIT).

Though, it is just composed a few trivial json files and a Readme.



Get the package
----------

**NPM**

Get it with:

```
npm install silk-companion
```


**Bower**

Get it with:

```
bower install silk-companion
```


**Composer / Packagist**

[silk-companion on Packagist](https://packagist.org/packages/damieng/silk-companion)




Dev dependencies and build status
----------

[![Dependency Status](https://img.shields.io/david/dev/damieng/silk-companion.svg)](https://david-dm.org/damieng/silk-companion)
[![Build Status](https://img.shields.io/travis/damieng/silk-companion.svg)](https://travis-ci.org/damieng/silk-companion)



