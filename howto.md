---
layout: page
title: How to
permalink: /howto/
tags: howto
---

This site uses [Jekyll](https://jekyllrb.com/) to create static web pages from simple [markdown](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) files. This way of managing content has many advantages over traditional content management systems such as [Wordpress]() or [Drupal]() including:

1. Ability to edit content offline using simple text editors
2. No need for databases or dynamic content
5. Faster page loads
3. Integration with version control systems
4. Easier collaboration with groups

Even better, Jekyll is [integrated](https://help.github.com/articles/using-jekyll-as-a-static-site-generator-with-github-pages/) with [Github Pages](https://pages.github.com/). This allows content pushed to a special repositiory to be automatically converted to static pages, and hosted for free directly from the associated github.io address. This method of blogging has become popular with software developers because it integrates directly within their existing version control workflow. Instead of going through a separate online interface to generate content, blog posts can be mainted offline as simple markdown-formatted text files, and pushed to the web using the Github interface.

While this is ultimately a fairly easy and straight forward method for maintaining a blog, it does require a bit of setup to be able to work on the contant remotely and preview blog posts before they are published online. The following are step by step instructions on how to set up the necessary requirements to create and preview content on your local machine, as well as how to submit the content to have it featured on the blog.

### 1. Set up Github

In order to edit and submit content, you will have to set up a Github account and 'fork' the website's repository. To get started, go to [https://github.com/](https://github.com/) and sign up for a free account:

![GitHub account](/images/github01.png)

Then go to: [https://github.com/the-living/the-living.github.io](https://github.com/the-living/the-living.github.io). This is the main repository for the research blog. All contributions to the blog have to follow this basic process:

1. Fork blog repository
2. Create new post in _drafts/ folder and add any referenced images into the images/ folder
3. Submit pull request to incorporate changes into the blog

To start contributing to the blog, you need to 'fork' the main repository into your account. This creates your own personal version of the repository and allows you to make changes and contributions without worrying about effecting the main project. To fork the site, click the 'fork' button in the top-right corner:

![GitHub forking](/images/github02.png)