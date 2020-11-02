# **How To Host Your Resume On GitHub**


## **Purpose**
The purpose of this README is to describe a detailed step-by-step guide on how to host a resume on GitHub pages, while following the principles described by Andrew Etter’s book _Modern Technical Communication_.


## **Prerequisites**
You're going to require a few things before you get started...
1. Resume
2. GitHub account and basic familiarity with the GUI
3. Familiarity with [Markdown](https://www.markdowntutorial.com/)


## **Instructions**

### Formatting Your Resume
This tutorial **requires** that you have a resume formatted in Markdown, if it's already formatted in Markdown, please proceed to the next section, if not read on.  

Before you begin manually recreating your resume from scratch in Markdown, browse the links below as they will provide you with resources to significantly reduce the amount of work you have to do.

**Note** it's highly unlikely these converters will do a perfect job, but they should get you close!  

- [DOCX →  Markdown](https://word2md.com/) from the browser
- [PDF →  Markdown](https://pdf2md.morethan.io/) from the browser
- [Google Doc →  Markdown](https://gsuite.google.com/marketplace/app/docs_to_markdown/700168918607) from Google Docs

![Google Doc Markdown Conversion](MarkdownConvertGIF.gif)

#### **Context**
Markdown is a lightweight markup language. Andrew Etter outlines several reasons why lightweight markup languages, specifically Markdown, are the go-to document types for use on websites. And in my opinion, the most important reason he describes is that the syntax is clean, which makes reading the prerendered document simple. Not only is reading it simple, but writing it is too. Both facets of this simplicity are vital, as it enables contributions from individuals who won't need any specialized knowledge in a complex tool to write clean maintainable documents. In your case, creating your Markdown resume should have been relatively painless; and once this tutorial is completed you will see a beautifully rendered resume, that can be changed on the spot without hassle.

### Setting Up The GitHub Repository
Create a new repository on your GitHub account:
1. Name it **[_GitHub Username_].github.io**
2. Set it to **public**
3. Initialization the repository with a **README**  

Navigate to the new repo and create **2** new files:
1. Create a file called `index.md` that will contain your resume   
    a. Click `Add file` → `Create new file`  
    b. Name it `index.md`  
    c. Paste your Markdown formatted resume into the edit file window  
    d. Click `Commit new file`
2. Create a file called `_config.yml` that will contain your Jekyll theme  
    a. Click `Add file` → `Create new file`  
    b. Name it `_config.yml`  
    c. Leave the edit file window empty  
    d. Click `Commit new file`  

#### **Context**
Git is one of the most powerful tools in a developers repertoire. It simplifies and streamlines projects where you are not the only contributor. The contributors of the project don't need to worry about maintaining synchronicity of the code base, as git does that for you. Git can be used for more than just maintaining a codebase, as Andrew Etter explains why it's useful for documentation as well. He explains that it allows documentation to stay in sync with the code base, as it is intrinsically linked. If functionality changes or if additional capabilities have been added, the developers can then immediately go and update the documentation. They are not forced to go to a completely different service to do so, and thus making them more likely to make the required update to the documentation.

### Adding A Theme
Select a prebuilt theme to enhance the visual appeal of your resume:
1. Click on the `Settings` option
2. Locate the `GitHub Pages` subsection by scrolling down  
    - It is near the bottom of the default tab
3. Click on the `Change theme` button
4. Browse the prebuilt themes then click `Select theme`
    - A banner will appear at the top of the screen notifying you of your selection, ensure it matches what you have selected
    - If you open `_config.yml` you will also be able to see your selected theme
5. **_Optional_ |** Modify your `_config.yml` to add additional website wide settings; some examples include:
    - `name:` Name of the page
    - `title:` Title of the tab
    - `description:` Short snippet outlining what the website is
    - Learn about them and others [here](https://gitlab.com/pages/jekyll/blob/master/_config.yml)
6. Check out your site by going to: **https://[_GitHub Username_].github.io/** or you can additionally find the name of your site in the `GitHub Pages` subsection in the `Settings` option from before.

#### **Context**
In this tutorial you've simply selected a theme to apply to your hosted resume. However, the depth of customization static site generators provide you is extensive. This customization allows you to create uniquely designed sites that stand out from the crowd. Not only will your sites be beautifully designed, but if you go and inspect the site you've just created by clicking `F12`, you can see the extensive amount of code Jekyll has generated from your simple document; this relatively complex code, that you didn't have to write, was generated in seconds bug free. Andrew Etter echos these ideas in addition to praising static site generators for their "speed, simplicity, portability, and security". When reading documentation functionality and visual appeal are key, and both of these are effectively and efficiently done by utilizing static site generators.


## **Resources**
- Tutorial to learn/refamiliarize yourself with the basics of [Markdown](https://www.markdowntutorial.com/).
- Andrew Etter's [_Modern Technical Communication_](https://www.amazon.com/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS).
- Interested in exploring the power of Jekyll further? Here's a [tutorial](https://www.awesomeinc.org/tutorials/jekyll-basics/) on the basic to get you started.

## **FAQs**
1. Why is Markdown better than a word processor?
    > It's not better in all cases but in this scenario, it is the best tool for the job. This is because it will allow you to easily modify your resume. Say you go to a programming event and you would like to include it on your resume; with Markdown it is as simple as clicking edit in the repository. On the other hand, if you used a word processor you will have to update it, exported it, remove the old version for GitHub, then upload the new version. Markdown makes sure you avoid this multi-step process every time you want to update your resume. In short, Markdown is both versatile and lightweight which makes it perfect for web based documents that will be modified and grow over time.

2. Why is my resume not showing up?
    > The first, and most likely, reason is you simply have to wait a while for github to process the changes and update the site. Github is offering this capability for free, to anyone, so there is potentially a line of people waiting for their site to update.

    > The second, and more unlikely, reason could be you've made a mistake during the tutorial that is preventing it from showing up.

## **Author & Acknowledgements**
- **Author**: Kyle Lamoureux
- **Proof Readers:** ...
- **Theme:** GitHub's [jekyll-theme-tactile](https://github.com/pages-themes/tactile)