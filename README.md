# Zarathustra

![Ghost version](https://img.shields.io/badge/Ghost-0.7.x-brightgreen.svg?style=flat-square)
[![Donate](https://img.shields.io/badge/donate-paypal-003087.svg?style=flat-square)](https://www.paypal.me/andreatarquini/5)

> A simple theme for Ghost made for geeks, hackers and developers (forked from Casper).

[<img src="http://i.imgur.com/SjCzgwp.jpg">](https://blog.prestonbernstein.com)

***Do you like my theme? Do you want new features?***  
Great, we can discuss. Open an issue. Some :coffee::coffee::coffee::coffee: offered with [Paypal](https://www.paypal.me/andreatarquini/5) are appreciated.

## Intro
**Zarathustra** is a very simple fork of the Ghost theme [Odin](https://github.com/ferdythebull/odin).
Zarathustra extends the Ghost theme Odin, adding some nice features very useful for developers such as syntax
highlight, comments and big social sharing features. I created this theme to customize Odin for my own personal website. Some things I plan to add are static page support, as well as adding in pixi.js and midi support.



### Features
* Casper minimalistic and clean style (without right side menu)
* Works with Ghost 0.7+
* Fully responsive (for mobiles and tablets)
* Home Page Navigation Menu Buttons
* Google Analytics (easily configurable by code injection in the admin area)
* [Disqus](https://disqus.com) comments (easily configurable by code injection in the admin area)
* [Prism](http://prismjs.com/) Syntax Highlight (all languages supported)
* [RRSSB](https://github.com/kni-labs/rrssb) Extraordinary Social Sharing Buttons
* [Font Awesome](http://fontawesome.io) home page Social Link Icons (easily configurable by code injection in the admin area)

### Demo
I've created and I use this theme for my personal website at [prestonbernstein.com](https://prestonbernstein.com).

## Installation
Installation is the same as other themes, so clone or download the content of this repo inside your Ghost `content/themes/` folder.

```
# for example
$ cd /your-ghost-root-directory
$ git clone https://github.com/ferdythebull/zarathustra.git content/themes/zarathustra
```

Restart Ghost and select Zarathustra theme from your Admin Area.

## Configuration
No need to configure ***Prism*** or ***RRSSB*** buttons.

To add Homepage Navigation Menu Buttons simply add the links in your Navigation Admin Area. They may be useful for static pages (*AboutMe* for example) or for shortcut to your (best) post tags.  

Zarathustra comes with a default ***favicon*** generated with [Real Favicon Generator](http://realfavicongenerator.net). If you want to add your *favicon* you can generate your own (with [Real Favicon Generator](http://realfavicongenerator.net)) and place downloaded files inside the ***assets/img/favicons*** Zarathustra directory.

***Disqus*** comments, ***Google Analytics***  and ***Font Awesome Home Page Social Link Icons*** are disabled by default, but they are easily configurable with *Blog Header Code Injection* inside your Ghost Admin Area.

```html
<script>
// to enable Google Analytics
var ga_id = 'YOUR-UA-ID_HERE';

// to enable Disqus
var disqus_shortname = 'YOUR_DISQUS_SHORTNAME'


// to enable Social Link Icons add the social_link object
// with the pair key/value -> social_network/link
// NB: the key is used to include the right icon from Font Awesome
// (you can include any Font Awesome icon)

// Example1: default social network icons
var social_link = {
    'twitter': 'https://twitter.com/prestonbernstein',
    'linkedin': 'https://it.linkedin.com/in/prestonbernstein',
    'github': 'https://github.com/ferdythebull',
    'rss':'https://blog.prestonbernstein.com/rss/'
    // you can add more icons
}

// Example2: squared social network icons
var social_link = {
    'twitter-square': 'https://twitter.com/prestonbernstein',
    'linkedin-square': 'https://it.linkedin.com/in/prestonbernstein',
    'github-square': 'https://github.com/ferdythebull',
    'rss':'https://blog.prestonbernstein.com/rss/'
    // you can add more icons
}

</script>


```


## Copyright & License

Released under the MIT License.
Copyright (c) 2016 [Preston Bernstein](https://blog.prestonbernstein.com)
Copyright (c) 2016 [@h4ton](https://twitter.com/h4t0n) (for Odin theme substantial portions of code)
