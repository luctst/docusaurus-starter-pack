---
id: overview
title: Getting started
sidebar_label: Overview
---
This project was created to be easily used and quickly online, is powered by docusaurus and maintained by Facebook. This documentation provides quick and easy documentation to launch your static site as quickly as possible, it implies that you adhere to the custom structure know in any case that you can modify, add as you wish the pages but you will have to read the official documentation of docusaurus [https://www.docusaurus.com](https://www.docusaurus.com).


## Structure
After instal your project should be like that:
![Structure du projet](../static/img/carbon.png)
- **docs** - include all your documentation file.
- **website** - this folder represent the file who run your website.
  - **blog** - this folder should be empty in our starter-pack we don't include blog, however you can check [this page](https://docusaurus.io/docs/en/blog.html) to know how to add a blog in your website.
  - **core** - include the file who load the footer on the whole website.
  - **i18n** - include the files in connection with translation.
  - **pages** -  include the pages of the website.
  - **static** - include static files.
    - **css** - include css custom files.
    - **img** - include all the image for the website.
- **package-lock, package.json** - files npm need to work.
- **sidebars.json** - Json file who generate content in sidebar pages.
- **siteConfig.js** - files who handle the website.