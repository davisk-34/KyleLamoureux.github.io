# **How To Host Your Resume On GitHub**


## **Purpose**
The purpose of this README is to describe a detailed step-by-step guide on how to host a resume on GitHub pages, while following the principles described by Andrew Etter’s book _Modern Technical Communication_.


## **Prerequisites**
You're going to require a few things before you get started...
1. Resume
2. GitHub account
3. Familarity with [Markdown](https://www.markdowntutorial.com/)


## **Instructions**

## Formatting Your Resume
---
This tutorial **requires** that you have a resume formatted in Markdown, if it's already formatted in Markdown, please proceed to the next section, if not read on.  

Before you begin manually recreating your resume from scratch in Markdown, browse the links below as they will provide you with resources to significantly reduce the amount of work you have to do.

**Note** it's highly unlikely these converters will do a perfect job, but they should get you close to a correctly formatted resume!  
- [DOCX -> Markdown](https://word2md.com/) from the browser
- [DOCX -> Markdown](https://www.epiphanydigest.com/2020/06/12/how-to-convert-a-word-document-to-markdown-format/) from the command line
- [PDF -> Markdown](https://pdf2md.morethan.io/) from the browser
- [Google Doc -> Markdown](https://gsuite.google.com/marketplace/app/docs_to_markdown/700168918607) from Google docs

![Google Doc Markdown Conversion](arkdownConvertGIF.gif)

### **Context**
We

## Setting Up The GitHub Repositiory
---
Create a new repository in your GitHub account:
1. Name it **[_GitHub Username_].github.io**
2. Set it to **public**
3. Initialization the repository with a **README**  

Navigate to the new repo and create **2** new files:
1. Create a file called `index.md` that will contain your resume   
    a. Click `Add file` -> `Create new file`  
    b. Name it `index.md`  
    c. Paste your Markdown formatted resume into the edit file window
    d. Click `Commit new file`
2. Create a file called `_config.yml` that will contain your jekyll theme  
    a. Click `Add file` -> `Create new file`  
    b. Name it `_config.yml`  
    c. Leave the edit file window empty  
    d. Click `Commit new file`  

### **Context**

## Adding A Theme
---
Select a prebuilt theme to enhance the visual appeal of your resume:
1. Click on the `Settings` option
2. Locate the `GitHub Pages` sub-section  
    - It is near the bottom of the default tab
3. Click on the `Change theme` button
4. Browse the prebuilt themes then click `Select theme`
    - A banner will appear at the top of the screen notifiying you of your selection, ensure it matches what you have selected
    - If you open `_config.yml` you will also be able see your selected theme
5. **_Optional_ |** Modify your `_config.yml` to add additional website wide settings; some examples include:
    - `name:` Name of the page
    - `title:` Title of the tab
    - `description:` Short snippet outlining what the website is
    - Learn about them and others [here](https://gitlab.com/pages/jekyll/blob/master/_config.yml)

### **Context**




## **Resources**
- Tutorial to learn/refamiliarize yourself with the basics of [Markdown](https://www.markdowntutorial.com/).
- Andrew Etter's [_Modern Technical Communication_](https://www.amazon.com/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS).
- Interested in exploring the power of Jekyll further? Here's a [tutorial](https://www.awesomeinc.org/tutorials/jekyll-basics/) on the basic to get you started.

## **FAQs**
1. Why is Markdown better than a word processor?
> It's not better in all cases, but in this scenario, it is the best tool for the job. This is because it will allow you to easily modify your resume; say you go to a programming event adn you would like to add it to your resume, with Markdown it is as simple as clicking edit in the repo. On the other hand, if you used a word processor to exported it as a DOCX or PDF, you would have to go through a multi-step process to update your resume. In short, Markdown is both versatile and lightweight which makes it perfect for web based documents that will be modified over time.

2. Why is my resume not showing up?
> The first, and most likely, reason is you simply have to wait a while for github to process the changes and update the site. Github is offering this capability for free, to anyone, so there is likely a long line of people waiting for their site to update just like you.

> The second, and more unlikely, reason could be you've made a mistake during the tutioral that is preventing it from showing up.

## **Author & Acknowledgements**
- **Kyle Lamoureux**
- Theme: **jekyll-theme-tactile**



### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/KyleLamoureux/KyleLamoureux.github.io/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.