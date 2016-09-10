---
layout: post
title: "git, running jekyll locally & rails"
date: 2016-09-10 11:51
tags: git jekyll rails
---
Today I spent a few hours tidying up my GitHub website. I got tired of having to commit and push my changes just to see my edits and so I decided to <a href="https://help.github.com/articles/setting-up-your-github-pages-site-locally-with-jekyll/">download Jekyll locally</a>. Now each time I make smaller edits, I can see the changes in real time. Then, when I am reasonabally satisfied, I can add my commit and push. 

First, I have to run the Jekyll server locally in Terminal with this command: 

    bundle exec jekyll serve

and then go to the following url to view my Jekyll website: <a href="http://localhost:4000">http://localhost:4000</a>.

I mentioned Git yesterday. Git is a free and open source distributed version control system designed to handle everything from small to very large projects with speed and efficiency. There's tons of information about Git on the web but I want to go over the steps again (for myself) on how to clone a repository. I will say that it is best to either work locally or work remotely on your project, but not both, otherwise you will have to do some pulling and pushing to sync things up. Once you create a remote repository (e.g., on GitHub or BitBucket) you can clone the repository. Once the repository is cloned, a local repository is automatically created by initializing a local repository and pulling the remote repository into the local one. 

    git clone https://github.com/user/repo.git
    # clone repository


