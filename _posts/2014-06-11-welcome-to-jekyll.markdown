---
layout: post
title:  "Don't Tell Me How To Live My Life, Jekyll!"
date:   2014-06-11 22:43:01
categories: jekyll update ruby gem rvm musings
---

I've set up an initial Jekyll post to be hosted on GitHub and am pleasently surprised how easy it was to get this set up.

One minor complaint I do have is with the Ruby installation.  After my intial installation using `apt` I wasn't able to install gem packages without `sudo`.

After remembering about `rvm` it was super easy.  What surprised me was that it wasn't more promenent on the Ruby homepage.  The initial install was using some odd default Ruby folders.

Since Jekyll offers "powerful support for code snippets" I suppose I should add one for previewing later:

{% highlight javascript %}
setTimeout(function() { console.log("Knock knock..."); }, 0);
setTimeout(function() { console.log("Who's there?");   }, 100);

setTimeout(function() { console.log("Banana?")         }, 300);
setTimeout(function() { console.log("NOT TODAY STEVE!")}, 1000);
{% endhighlight %}

I guess that's about it.  I did hear the news about [Intel adding JavaScript bindings for SIMD](https://01.org/blogs/tlcounts/2014/bringing-simd-javascript) which was pretty cool.  One step closer to being [close to the metal!](https://www.destroyallsoftware.com/talks/the-birth-and-death-of-javascript)

[jekyll-gh]: https://github.com/mojombo/jekyll
[jekyll]:    http://jekyllrb.com
