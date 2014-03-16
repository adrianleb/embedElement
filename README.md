embedElement
============
the universal control remote of embeding media on the web.

# Introduction
embedElement is a polymer element for easily embedding dozens of different media providers on your website.
Its a simple HTML element with a "url" attribute, from there the tag itself resolves the right embed code, some of the benefits:
- no hassle embeds, simply copy the url of the track from the provider site, add it to afreshly created tag.
- 100% original embeds, embedElement doesn't inforce an UI, so what you get the same embed others would get from the same provider.
- normalized dimensions, the embed will try to fit, if not will stick to the boundaries of the element, default dimensions: 400px x 300px

example:
```html
<embed-element url="http://www.youtube.com/watch?v=nlBC56kDu5E">Hello Youtube</embed-element><!-- A Youtube embed-->
<embed-element url="http://vimeo.com/69986655">Hello Vimeo</embed-element><!-- A Vimeo embed-->
<embed-element url="https://soundcloud.com/hnny/music-for-listening-vol-7">Hello Soundcloud</embed-element><!-- A Soundcloud embed-->

```

# Providers

- Youtube
- Soundcloud
- Vimeo
- Hulu
- CollegeHumor
- Jest
- Slideshare
- rdio
- dailymotion
- justin.tv
- Shoudio
- SpeakerDeck
- Kickstarter
- FunnyOrDie

# How to run
- Clone repository
- Install depedensies with `bower`
- run a simple http server of choice

#TODO
- stable jsonp proxy
- more providers

