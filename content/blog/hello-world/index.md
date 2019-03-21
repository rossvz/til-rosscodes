---
title: Today I Learned... Gatsby!
date: "2019-03-20"
description: Building this blog with a blazingly fast static site generator!
summary: A summary!
---

## The Great Gatsby

If you follow any of the prominent members of the React / JS community, there's a good chance you've heard about [Gatsby](https://www.gatsbyjs.org/). In their own words, Gatsby is `a blazingly fast static site generator for React`. Why is this important?

#### Blazingly Fast

I love the JavaScript ecosystem because it taught me about code, it let me build things, and launched my career as a software developer. 
However, modern JavaScript suffers from a multi-faceted problem: 
* more developers than ever are writing open-source JavaScript
* framework are becoming more full-featured
* a trend towards client-side-heavy-lifting apps

Unfortunately, a large number of software developers live in high-density, large-infrastructure cities, with access to high-speed internet and powerful computers and smartphones. This only masks the fact that websites are getting heavier and heavier to load. While it may be acceptable for a fully interactive web-based game to take a few seconds to load, loading a blog should be `blazingly fast`

#### Static Site Generator

Gatsby seems to strike a compromise between a completely static site and a dynamic JavaScript powered webapp. Traditional static sites are pure HTML, lightweight, but suffer from a lack of true interactivity. Gatsby allows the content to be king - statically rendered and generated, but in a dynamic "wrapper" that lets users build features into the site that are traditionally reserved for JS webapps.

#### Powered by React

React seems to have taken the JS community by storm, and I won't spend time here explaining it or its virtues, other than to point out the ability to tap into a rich ecosystem of plugins, node pacakges, and a framework philosophy that emphasizes separation of concerns, high performance, and predictable DOM updates.

<hr>

### TIL

I had heard about Gatsby for a while, and decided to spend some time diving into the framework today, as a result of needing a new blog. I was interested in Gatsby as a solution for this problem as Dan Abramov uses Gatsby for his personal web blog: [Overreacted.io](https://overreacted.io). Additionally, Dan has made [the repo for his blog open-sourced](https://github.com/gaearon/overreacted.io), so you can see how he builds everything.

I'm still early in the process of seeing what Gatsby can do. For now, here's what I've learned

* Many Gatsby blogs (including Dan's) don't use a separate CMS for blog content, but commit blog posts as `markdown` files along with code. I love that!

* Gatsby uses GraphQL to query for data on each page. For example, the twitter and Github links in the bio below are belong pulled dynamically from a GraphQL query in the `Bio.jsx` component! I plan to dive into GraphQL at some point... 
* Gatsby has a fantastic CLI to scaffold new projects, and many start templates you can use to get the tedious work out of the way. The "set up" for this blog took less than 5 minutes. [Check it out now!](https://www.gatsbyjs.org/tutorial/)