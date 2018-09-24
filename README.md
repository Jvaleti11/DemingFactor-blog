# What is this?

This blog site servers static assets for better performance than a databased backed CMS like Wordpress.
The underlying site is built with a specific flavor of Jekyll called Github Pages.
Technically we're using the github-pages gem which extends on jekyll. 

By deploying to github pages we don't need to build the site (see Building below)

ref: https://help.github.com/articles/setting-up-your-github-pages-site-locally-with-jekyll/

# How do I add new pages/content/articles?

The code driven approach is to add posts directly under _posts and follow the date format in the name.

The human friendly approach is to login to our account on forestry.io and that provides a UI for making articles and pages for non-coders. Foresty has github commit access and essentially adds the pages into the git repo.

# Installation

1. git clone https://github.com/evolve2k/blog.demingfactor.com && cd blog.demingfactor.com
2. bundle install

# Start the local development server

    $ bundle exec jekyll serve

    Open the browser to localhost:4000

# Building

Building the jekyll code is not usually required as github pages handles building the pages itself.

