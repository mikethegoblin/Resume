---
title: Introduction To Gatsby
subtitle: 

# Summary for listings and search engines
summary: Gatsby is a React based, GraphQL powered static site generator. It is fast, secure, scalable, and friendly to developers. This post is a brief intorduction to Gatsby.

# Link this post with a project
projects: []

# Date published
date: "2021-12-29T22:30:00Z"

# Date updated
lastmod: "2021-12-29T23:00:00Z"

# Is this an unpublished draft?
draft: false

# Show this page in the Featured widget?
featured: false

# Featured image
# Place an image named `featured.jpg/png` in this page's folder and customize its options here.
image:
  caption: ''
  focal_point: ""
  placement: 2
  preview_only: false

authors:
- admin

tags:
- frontend

categories:
- frontend
---
### What is Gatsby
In simple words, Gatsby is a React-based, GraphQL powered, static site generator. So what is a static site generator? A static site generator is a software application that creates HTML pages from templates or components and a given content source. In short, static site generators reduce site complexity. Because your site is static, all the HTML pages can be pre-generated and deployed to a server so that whenever the server receives a request, it responds with a pre-rendered HTML. This significantly improves speed and reliability. 

Because Gatsby uses GraphQL, it can get data from almost anywhere (markdown file, database, csv file). Gatsby will pull the data from our preferred data source and generate our site from our data. As mentioned above, Gatsby is built with React, so we can use React for templating and CSS for styling, which makes the developing process really easy if you already know React.

### Why Gatsby?
In short, we use Gatsby for its speed, security and developer experience. One of the most noticeable advantage of a static site generator is speed. Its performance is way better than the other database-driven content management systems such as WordPress. Static Site Generators generate HTML pages during the build process as opposed to retrieving data from database and merging it with template files when the server receives a request for a particular URL. Because of the static nature of Gatsby, it is essentially more secure. All we have on a server is a bunch of HTML files, so there's no database to hack and there will be no user information stored on the server with the Gatsby site. In this case, hackers can only do a limited damage to our site. Using a Static Site Generator, you don't have to worry about database-toppling traffic spikes, and you don't need to manage database server software or backups. These all smoothes the whole developer experience. 

### Installation
Gatsby has a CLI tool that we can use to run command in our terminal. This CLI tool can be installed using `npm` by running `npm install -g gatsby-cli`

### How do we use Gatsby
We build our site using React framework, and Gatsby helps us generate the contents of our site. The output of Gatsby will be a Gatsby static site which contains the HTML, CSS, Javascript files as well as all the images our website needs.