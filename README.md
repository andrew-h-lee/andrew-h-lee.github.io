Portfolio Website: Displaying My Work
============

#####Blog post
Create a Blog post by creating a file called `yyyy-mm-dd-name-of-post-like-this.markdown` in the `/_posts/blog/` directory with the following template:
```markdown
---
layout: post          #important: don't change this
title: "Name of post like this"
date: yyyy-mm-dd hh:mm:ss
author: Name
categories:
- blog                #important: leave this here
- category1
- category2
- ...
img: post01.jpg       #place image (850x450) with this name in /assets/img/blog/
thumb: thumb01.jpg    #place thumbnail (70x70) with this name in /assets/img/blog/thumbs/
---
This text will appear in the excerpt "post preview" on the Blog page that lists all the posts.
<!--more-->
This text will not be shown in the excerpt because it is after the excerpt separator.
```
#####Project post
Create a Project post to go in your Portfolio by creating a file called `yyyy-mm-dd-name-of-the-project.markdown` in the `/_posts/project/` directory with the following template:
```markdown
---
layout: project       #important: don't change this
title:  "Name of the project"
date: yyyy-mm-dd hh:mm:ss
author: Name
categories:
- project             #important: leave this here
img: portfolio_10.jpg #place image (600x450) with this name in /assets/img/project/
thumb: thumb02.jpg
carousel:
- single01.jpg        #place image (1280x600) with this name in /assets/img/project/carousel/
- single02.jpg  
- ...
client: Company XY
website: http://www.internet.com
---
####This is a heading
This is a regular paragraph. Write as much as you like.
```
---

####Publish
To publish with [GitHub Pages](https://pages.github.com/), simply create a branch called `gh-pages`in your repository. GitHub will build your site automatically and publish it at `http://yourusername.github.io/repositoryname/`.  
If there are problems with loading assets like CSS files and images, make sure that the `baseurl` in the `_config.yml`is set correctly (it should say `/repositoryname`).

#### Reference:
* [Jekyll](http://jekyllrb.com)
* [Blacktie](http://www.blacktie.co/)
* [Hexagon Buttons](https://github.com/shariarbd/CSS3-Hexagon-Buttons)
* [Solid Theme](http://www.blacktie.co/2014/05/solid-multipurpose-theme/)

