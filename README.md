# hexo-theme-lightTae

Hexo theme based on Light. I will update it from time to time. You can see the style on this [Demo]().

## Install

Execute the following command and modify `theme` in `_config.yml` to `lightTae`.

```
git clone https://github.com/DavorWade/hexo-theme-lightTae.git themes/lightTae
```

## Update

Execute the following command to update Light.

```
cd themes/lightTae
git pull
```

## Config

Default config:

``` yaml
menu:
  Home:
  Archives: archives
  About: about

widgets:
- search
- category
- tagcloud

excerpt_link: Read More

twitter:
  username:
  show_replies: false
  tweet_count: 5

addthis:
  enable: true
  pubid:
  facebook: true
  twitter: true
  google: true
  pinterest: true

fancybox: true

google_analytics:
rss: /atom.xml

comment_provider: disqus
# Facebook comment
facebook:
  appid: 123456789012345
  comment_count: 5
  comment_width: 840
  comment_colorscheme: light
```

- **menu** - Main navigation menu
- **widget** - Widgets displaying in sidebar
- **excerpt_link** - "Read More" link text at the bottom of excerpted articles
- **twitter** - Twitter widget config
  - **username** - Twitter username
  - **show_replies** - Enable displaying replies
  - **tweet_count** - Tweets display in widget
- **addthis** - Share buttons at the buttom of articles (Powered by [AddThis])
  - **enable** - Enable share buttons
  - **pubid** - Profile ID of [AddThis]
  - **facebook** - Enable Facebook button
  - **twitter** - Enable Twitter button
  - **google** - Enable Google+ button
  - **pinterest** - Enable Pinterest button
- **fancybox** - Enable [Fancybox]
- **google_analytics** - Google Analytics ID
- **rss** - RSS subscription link (change if using Feedburner)

## Features

1. Change quote style.
2. Add pagnition of Archives, Categories and Tags.
3. Add "fork me on Github".
4. Add "About" page.
5. 