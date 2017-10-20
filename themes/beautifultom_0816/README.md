# beautifultom - A port of Beautiful Jekyll/Hugo Theme

![beautiful tom Screenshot] (https://github.com/ttiveron/beautifultom/blob/master/images/home.jpg)

# BUT ... this is where the similarity ends

## Installation

    $ mkdir themes
    $ cd themes
    $ git clone https://github.com/ttiveron/beautifultom.git beautifultom

See [the Hugo documentation](http://gohugo.io/themes/installing/) for more information.

### UpForGrabs

I'm not very good at HTML and CSS are you? The url to the octocat image in the css is hard coded! I would love for this to pass through from the HTML, where it can be set by Go Templating (I tried see /layouts/partials/nav.html). Maybe the CSS has to be update by JS? If you are a front-end wizard [or novice wizard :) ] I'd love you help!

## Extra Features - Will be expanding on all these shortly!
1. Favicon
  - the location can be set in the config.toml and will be used now
2. Colors!
3. Shape options for you portrait
  - updated to be a hexagon, will be add others
4. Expanding header and footers
  - this functionality is now working
5. Blogs, Pages, Sections!
  - Sections! If you set your blog categories, these pages will index blogs. Currently the value is hard coded in the template. Will be updating the Go Tempalating to grab the url and use this to filter posts.

### Responsive

This theme is designed to look great on both large-screen and small-screen (mobile) devices.

### Syntax highlighting

This theme has support for `highlight` shortcode (with Pygments),
see [the Hugo documentation](http://gohugo.io/extras/highlighting/) for more information.

To use this feature install Pygments (`pip install Pygments`) and add `pygmentsuseclasses = true` to your `config.toml`.

### Disqus support

To use this feature, uncomment and fill out the `disqusShortname` parameter in `config.toml`.

### Google Analytics

To add Google Analytics, simply sign up to [Google Analytics](http://www.google.com/analytics/) to obtain your Google Tracking ID, and add this tracking ID to the `googleAnalytics` parameter in `config.toml`.

## About

This is a serious rework of the Jekyll theme port [Beautiful Jekyll](http://deanattali.com/beautiful-jekyll/) by [Thomas Tiveron](http://tiveron.ca/page/aboutme). It supports most of the features of the original theme.

## License

MIT Licensed, see
 [My LICENSE](https://github.com/ttiveron/beautifultom/blob/master/LICENSE)

 [Port's LICENSE](https://github.com/daattali/beautiful-jekyll/blob/master/LICENSE)
 
 [Theme's LICENSE](https://github.com/halogenica/Hugo-BeautifulHugo/blob/master/LICENSE)
