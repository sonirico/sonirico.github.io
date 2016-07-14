---
layout: post
title:  "Met Jekyll. Sayonara, WordPress."
date:   2016-07-11 17:43:23 +0200
categories: blogging
tags: jekyll markdown github meta
---
Today I have just made an amazing discovery: **Github pages**. Well, they have been
there for long, hidden beneath my "just another git-scm webapp platform" prejuices
regarding GitHub. It turns out this Ruby based platform provides a *free* hosting 
service as a sibling repository of your projects. Rather metaphorical. 

This feature is even available for both, organizations and projects. You just 
have to create a new branch within your repo which, accordingly populated, will become more than
just a good-looking piece of HTML content. The how, lies on markdown and Jekyll.

**[Markdown][markdown-site]** is a powerful text-to-HTML conversion tool. Instead of writing large
and boring fragments of HTML code, users have to memorize certains formats to
write down along their content. On the other hand, [Jekyll][jekyll-docs] is a blog-aware Ruby-based 
static site generator. To summarize, it gets text files as input and generates
and entire folder-structured website.

Forget about databases and CMSs like [WordPress][wordpress-site] or [Joomla!][joomla-site]. Perhaps, they are well
suited for small and medium blogging platforms with standard numbers of concurrent
users, where content rapidly changes and extended features are required. Nevertheless, 
in regards to personal blogs, landing pages or even portfolios, maintaining both systems feels
out of the box somehow. So much effort for just a simple website which will be, 
lets say, updated twice a month? And what about outdated plugins and other security
concerns?

That is why I deicided -temporary, at least- to switch from WordPress to Jekyll 
as my regular blogging platform. As I mentioned above, you do not have to pay
a single penny for it. Just create a new repo following [these few steps][few-steps] and get
to work. The use of git is strongly encouraged since forking or cloning yourself
in order to develop your site, and push it to the remote when satisfied and repeat, 
is how this works. We developers, are supposed to constantly 
be learning new things -when not forced-, so if you are reading this post then 
it means I was successful. Oh, and nevermind upcoming grammar-spanished posts like
this. After all, English is not my mother tongue.
 

[jekyll-docs]: http://jekyllrb.com/docs/home "Jeyll official documentation"
[wordpress-site]: https://wordpress.org "WordPress organization"
[joomla-site]: https://joomla.org "Joomla organization"
[markdown-site]: https://daringfireball.net/projects/markdown "Markdown project page"
[few-steps]: https://pages.github.com/ "Github pages. Landing with quick-start"
