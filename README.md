# Lagom+
[![Live Demo](https://img.shields.io/badge/view-live--demo-blue.svg?style=flat-square)](http://fngryboi.github.io)

A theme I use on my personal blog over on https://fngryboi.github.io that is basically an extended version of the original theme found here: https://github.com/swanson/lagom

1. Browser Adress Bar Theme Color with a browser theme color variable located in `_data/theme.yml`, more info found [here](http://stackoverflow.com/questions/26960703/how-to-change-the-color-of-header-bar-and-address-bar-in-newest-android-chrome-v/). Most visible in the mobile screenshot below
2. Implemented [TwitchCleverEmbed](https://github.com/fngryboi/TwitchCleverEmbed), with a boolean (show_twitchtv_player) to toggle whether you want to embed the twitch stream or not when the user is live (twitchtv must have a username set in data/theme.yml).
3. Implemented [FitVids.js](https://fitvidsjs.com) for responsive videos and made all images go 100% wide inside .content
4. Added a dark theme, which you can toggle in data/theme.yml - with it's own syntax theme as well. The original theme can be found [here](http://github.com/jwarby/jekyll-pygments-themes/blob/master/monokai.css).
5. Added Youtube as a social link (go to Youtube.com > My channel and copy your unique string right after "https://www.youtube.com/channel/" in the url.

Easiest way to get this website is to fork this project and rename it to `<yourgithubusername>.github.io`, setup your personal information in `_layout/sidebar.html`, `_data/theme.yml` and log in with http://prose.io and head to the `_posts` directory to start making posts.

With the dark theme enabled and Twitch stream enabled it would look something like this when the user is streaming on Twitch.tv, you can of course customize the pink and blue inside the data/theme.yml. Pink is the theme color, and blue is the browser color.

![An idea what it looks like on PC](http://i.imgur.com/3qZR1EB.png)
![On mobile, Twitch gets embedded here as well](http://i.imgur.com/Dw7zXte.png?1)

# Lagom

> #### *Lagom* is a Swedish word with no direct English equivalent, meaning "just the right amount"

Lagom, a [Jekyll][j] blog theme with just the right amount of style. 

Extracted lovingly from [http://mdswanson.com][mds] for your enjoyment!



* Responsive, based on [Skeleton][skeleton]
* [Font Awesome][font-awesome] for icons
* Open Sans from [Google web fonts][gfonts]
* Built-in Atom feed

[![Live Demo](https://img.shields.io/badge/view-live--demo-blue.svg?style=flat-square)](http://lagom.mdswanson.com/)

## Action Shots
![](http://i.imgur.com/Pmzk4j1.png)
![](http://i.imgur.com/CT2Xvug.png)
![](http://i.imgur.com/XisjqW1.jpg)

## Installation

- [Fork this repository][fork]
- Clone it: `git clone https://github.com/YOUR-USER/lagom`
- Install the [GitHub Pages gem][pages] (includes Jekyll): `bundle install`
- Run the jekyll server: `jekyll serve`

You should have a server up and running locally at <http://localhost:4000>.

## Customization

Next you'll want to change a few things. Most of them can be changed directly in
[theme.yml][config]. That's where you can add your social links, change the accent
color, stuff like that.

There's a few other places that you'll want to change, too:

- [CNAME][cname]: If you're using this on GitHub Pages with a custom domain name, 
  you'll want to change this to be the domain you're going to use. All that should 
  be in here is a domain name on the first line and nothing else (like: `example.com`).
- [favicon.png][favicon]: This is the icon in your browser's address bar. You should 
  change it to whatever you'd like.
- [logo.png][logo]: A square-ish image that appears in the upper-left corner

## Deployment

You should deploy with [GitHub Pages][pages] - it's just easier.

All you should have to do is rename your repository on GitHub to be
`username.github.io`. Since everything is on the `gh-pages` branch, you
should be able to see your new site at <http://username.github.io>.

## Licensing

[MIT](https://github.com/swanson/lagom/blob/master/LICENSE) with no
added caveats, so feel free to use this on your site without linking back to
me or using a disclaimer or anything silly like that.

## Contact
I'd love to hear from you at [@_swanson][twitter]. Feel free to open issues if you
run into trouble or have suggestions. Pull Requests always welcome.

[j]: http://jekyllrb.com/
[mds]: http://mdswanson.com
[skeleton]: http://www.getskeleton.com/
[font-awesome]: http://fortawesome.github.io/Font-Awesome/
[gfonts]: http://www.google.com/fonts/specimen/Open+Sans
[fork]: https://github.com/swanson/lagom/fork
[config]: https://github.com/swanson/lagom/blob/master/_data/theme.yml
[cname]: https://github.com/swanson/lagom/blob/master/CNAME
[favicon]: https://github.com/swanson/lagom/blob/master/favicon.png
[logo]: https://github.com/swanson/lagom/blob/master/logo.png
[pages]: http://pages.github.com
[twitter]: https://twitter.com/_swanson
[pages]: https://github.com/github/pages-gem
