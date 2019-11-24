---
layout: post
title:  "Reflection"
date:   2019-11-20 09:59:36 -0600
categories: jekyll update
---

#### What do you think of pre-compiling your CSS?

* Thoughts, techniques and pros  

From an organisational point of view, it is advantageous, since you can work with separate files.
I get a better overview of my project this way.
As well is the readability better, especially compared to a bigger project using regular CSS.
Hand in hand will the code also be easier to maintain. 

For instance I've stored (declared and initiated) variables in minima.scss which I then have reused in base.scss and layout.scss. Now, I only need to change the varible in minima.scss if it needs to be changed.

Nesting also speaks for CSS pre-processors, the code is more structured as well as is it prevents redundancy.
Example in base.scss with the table.
Other pros with CSS pre-processora are the ability to define mixins and mathematical functions.

* Cons  

Debugging is harder with CSS pre-processors, due to incorrect match with code lines.  

As techniques develop, the use of CSS pre-processors is fading out. New HTTP protocols manages several separate files better than one complied file.   
New implemented teqchnique in CSS also accelerates the fade out of CSS pre-processors.

#### What type of projects are static site generators suitable for?

They are suitable for a more simple type of projects. Projects/sites with the intention to present information to the user/reader. Static sites are stored as simple files (html, css, templates) which are served by a web server, via HTTP request and back to the browser. 
A good example is the blog we are currently creating, with information about me and blog posts to read for whom finds my page on the web.

These sites differentiate from dynamic site, amongst other things, in the dynamics. With no real-time content nor user input (Disqus working around exists though). Obviously dynamic sites are more complicated overall.

Personally I enjoyed the creation of ssg, especially with the support for markdown language.

#### What is robots.txt and how have you configured it for your site?

It is a text file placed on a web server, that informs webcrawlers what files to access.
Or if they should access at all or everything.

I have allowed full access, with the exception for two folders. 

#### What is humans.txt and how have you configured it for your site?

This is also a text file, that is added to the project for knowing the people behind the website.
I have added myself as chef of this project with thanks to LNU for your support.

#### How did you implement comments to blog posts?



#### What is Open graph and how do you make use of it?

2010 Facebook created Open graph, which is a protocol that allows web pages to be represented as items in a social graph.
The purpose is to optimize links, i.e. highlight the main content of your website as well as control what you want to be displayed.

By adding relevant information, such as image, title, url and type, you have higher chance to interest users and clicking to your website.




