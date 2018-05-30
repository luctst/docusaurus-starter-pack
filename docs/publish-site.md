---
id: publish
title: Publish your site
sidebar_label: Publishing your site
---
Docusaurus make things really simple when you have to push your site online, we will see here how to correctly do that with the Github pages hosting service.

## Building your HTML pages
Like you probably know web browsers cannot read your markdown files so you have to create HTML pages, but for now we only work with markdown files so how is it possible ? Remember docusaurus is a tool who can convert your .md files in .html, let's see how to do this: 

Place yourself in the `website` folder and run:
```
npm run build
```
this command will build your HTML pages in a folder called `build`.

## Push on github page
### Configure your siteConfig.js file
You first need to add some information's in your `siteConfig.js` file:

- `url`.
- `baseUrl`.
- `projectName`.
- `organizationName`.

Follow the instructions in comments to correctly set the information's.