Hacker News Kansai
=========
This is the source code for the hnkansai.org website. It's a static site generated by [Middleman](http://http://middlemanapp.com/) and hosted on [GitHub Pages](http://pages.github.com/). 



Contributing
------------

If you want to contribute to the project, here's a guide to help you get started. 

1. Install and read up on [Middleman](http://http://middlemanapp.com/). If you are familiar with Ruby/Rails then you'll be up and running in no time.

2. Fork the repo and clone it locally. There are two branches, Source and Master. You'll want to do all of your work on the Source branch (or a new topic branch you create locally).

3. After you've cloned the repo locally, switch to the root of the project and run 
```
$ middleman build  
$ middleman
```   
Now you should be able to view the site locally at http://localhost:4567. Going forward, you will want to make all of your changes in the /source directory. Go wild in there. Important note: If you make changes directly in the /build directory they will be overwritten when the site is built. /source is your friend. /build is bad. 

4. When you are happy with your changes, commit and push to GitHub. 
```
$ git checkout source
$ git add -A
$ git commit -m "Some awesome changes to HN Kansai"
$ git push origin source
````
Now submit your pull request to the Source branch of this repo. Once it's been accepted, we'll rebuild the site manually to incorporate your changes. If you have any questions along the way, you can contact andrew@fajitanachos.com


Frameworks, APIs, and other cool things we used 
-----------------------------------------------

[Middleman](http://http://middlemanapp.com/)

[JQuery](http://jquery.com/)

[Twitter Bootstrap](http://getbootstrap.com/2.3.2/)

[Doorkeeper API](http://www.doorkeeperhq.com/developer/api)

[Flickr API](http://www.flickr.com/services/api/)

[Youtube API](https://developers.google.com/youtube/getting_started)

[Fancybox](http://fancyapps.com/fancybox/)

[Squaresend](https://squaresend.com/)


