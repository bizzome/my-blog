---
title: The day I started
date: "2024-07-28T13:05:00.000Z"
description: "When I realized that I'm not so good."
---

# Been a better professional
#### When I realized that I'm not as awesome as I thought.

This post has two titles because my mind is in chaos.
I realized that I am not a good professional. I'm a developer and work making things on the web but... not really.

For the past few months (maybe years), I've been stuck in the same place and haven't updated my knowledge for quite a while.
It doesn't seem like I have made any progress in my career or learning experiences.
Now I feel an urge to create a really good project that helps me reach the next level of knowledge and regain confidence in my work.

The idea I had was to create a blog to write about my experiences and perhaps get involved in something new and exciting.
This blog should be about my thoughts on the process, what I have learned, and what I still need to learn.

What will be my steps through this new learning path?

To have an online blog, there are some questions that need to be answered:
- How do I make a blog?
- How to deploy it in cloud?
- What are the steps of CI/CD that needs to be done?


First, I will use Gatsby (Node.js) as my starter pack on the front-end side.
For the cloud, I need to learn more about AWS deployment steps, and for CI/CD, I will look for information on GitHub Actions.

# How do I make a blog?

I believe it would be nice to have any idea about if anything is going to work before start it. But the truth is that we can't be really sure if things will happen as we expect unless we try.

It seems to me that with blogs, the key is to write in a consistent way over a long period of time every day or week at least.

Thing is that... I'm not that diciplined.
First of all, I don't even know how to write in english properly.
So, how do I do it?

Looking for answers to this question, I dicovered that it's completely normal to feel uncertain about writing in a second language, but the good news is that practice and persistence can make a huge difference. The same applies to having a blog.

It needs to be something I will do to train my dicipline and consistency.

<b><i>So, what about the HOW?</i></b>

I think that we need to talk about tools we need in order to make this idea concrete. So in that section we will talk about this framework I found called [Gatsby](https://www.gatsbyjs.com/).

## Creating a Blog with Gatsby.js

Gastby.js is a framework built on Node.js that is really powerful and helps people to start projects in seconds. It leverages React to create fast, static websites and apps and it is very popular for building blogs thanks to its ease of use.

### Setting Up Your Blog

<b>Step 1: Install Gatsby CLI</b>

First, you need to install the Gatsby CLI globally on your machine. This will you set up new Gatsby projects.

```bash
npm install -g gatsby-cli
```

<b>Step 2: Create a New Gatsby Site</b>

With the CLI installed, create a new Gatsby project using the blog starter template.

```bash
gatsby new my-gatsby-blog https://github.com/gatsbyjs/gatsby-starter-blog
```


<b>Step 3: Run Your Site Locally</b>

Navigate to your project folder and start the development server:

```bash
cd my-blog
gatsby develop
```

Your blog will be available at http://localhost:8000. This environment lets you see changes in real-time as you edit your files.

<i>(after this point I used GPT to help me, because why not)</i>

<b>Step 4: Customize Your Blog</b>

<b>Add New Posts:</b> Blog posts are typically stored in the `content/blog` directory as Markdown files. Create a new Markdown file for each post, and Gatsby will automatically generate a corresponding blog page.

<b>Customize Layout: </b> Modify React components in the `src` directory to change the look and feel of your blog. You can also add your own components or import UI libraries to enhance your design.

<b>Install Plugins:</b> Enhance your blog with additional functionality by installing plugins. For example, use `gatsby-plugin-image` for optimized images, or `gatsby-plugin-google-analytics` to add Google Analytics tracking.

For the next questions... maybe we can make it in diferent posts.

## Update 1:
With this blog project, I learned how to use S3 to store webpage files and deploy it, training my skills on github actions to make the whole automated deployment process. Maybe these points could be shared in other posts on this blog.