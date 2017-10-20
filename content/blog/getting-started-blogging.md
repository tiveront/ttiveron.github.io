+++
date = "2016-06-22T23:46:35-04:00"
title = "Thomas's First Tech Blog Post"
subtitle = "About Blogs"
type = "post"
categories = ["Opinion"]
tags = ["Hugo"]
+++

## So I've started my blog!
# ...
## ...
### ...

Now for the content, hold onto your seats people.

As a big podcast fan ([check out my PlayerFM channel](https://player.fm/ttiveron/fm "Thomas's PlayerFM Channel")),
I often heard the benefits of sharing your knowledge from many people, such as [Scott Hanselman](https://twitter.com/shanselman), and [Jon Sonmez](https://twitter.com/jsonmez).
They preach that sharing your journey will not only help you retain what you are learning, create an excellent portfolio, but you may also help/inspire someone else to tackle new challenges.

So I decided to leap and started this blog a little over a month ago, but like anyone who likes to tinker with technology, I took the long road.

### Domains, Hosting, Servers, CMS, Oh WOW

The first technical challenge which will siphon hours of Google research is where will your blog live??

I knew I wanted my own domain and settled on [Namecheap](https://www.namecheap.com/ "Namescheap") because they had the best value for domain registration and email hosting.
Some services offer many more features, but seeing as I will not be requiring a lot of features for this simple blog, Namecheap's offering was perfect.

Following my domain purchase and email setup, I stared down the barrel of hosting options and blogging platforms.

I reviewed hosting with Dreamhost, Digital Ocean, and a few others. I reviewed VPS options like Azure, and Linode (wouldn't it be fun to admin a Linux server!).
And I considered your classic WordPress, and the new blogging focused Ghost platforms.
But at the end of the day, I didn't really want to have to start paying for a hosting subscription at the start, and then I stumbled upon [Github Pages](https://pages.github.com/ "Github Pages").

### Github Pages and Static Site Generators

Github Pages will serve the content in a Github repository as a website, with the catch that everything in the repository has to be static.
So while you could create the content and HTML of each page, you can use a static site generator to take care of the HTML for you!

Now here is where the real fun begins, choosing a static site generator.
[StaticGen](https://www.staticgen.com/ "StaticGen") tracks the top Open-Source static site generators and their list contains well over 100!

[Hexo.io](https://hexo.io/ "Hexo") was my first static generator. I chose Hexo, because it ranked high on the  list of generators and runs a node.js server.
I do not have much experience with JavaScript, but I felt that if I needed to code something to go along with node.js it would be good experience.
Unfortunately, my love of Hexo was short lived. They have great tutorials, and I was able to get my site up very quickly, but when I wanted to dig into the theme and make some changes things got tricky.
Hexo themes use either the template language EmbeddedJavaScript (EJS) or Swig, and I'm currently not interested in learning either of these.
Thus, while I was able to get my Hexo site up and running smoothly, I didn't want to tackle their foreign templating language just to make theme changes.

So I moved onto the next generator.

Seeing that some experience with the underlying language may be advantageous I decided to try [Wyam.io](http://wyam.io/ "Wyam") next.
Wyam is a static *content* generator written entirely in .NET, and allows for templating in Markdown and Razor. I used Wyam for a couple of days before deciding it was too complex.
Wyam is a lot more than just a static site (simple blog) generator. Wyam is used by chaining together flexible modules to produce your end product,
and while you can create a website this way it seemed like overkill (to me).

Finally, I stumbled upon [goHugo.io](http://gohugo.io/ "Hugo") (another .io)!
Hugo is very similar to Hexo. Both have great documentation, easy setup guides, and awesome themes.
Hugo was different for me because the entire application is written in Go. While Go is vastly less popular than JavaScript, I have been trying to find time to use Go all year.
Hugo's themes use Go templating and they have a great primer in their documentation. So far the minor changes I have wanted to make have been pretty simple.
It feels more like I'm making simple HTML changes, with the power of Go objects and conditionals.
Finally, another important aspect to me was that with Hugo you create your content in Markdown files.

There you have it, a short summary of the meandering trail I took to get here.

If you have any questions about my choices feel free to reach out to me with any of the links below.

Thanks for reading,

Thomas
