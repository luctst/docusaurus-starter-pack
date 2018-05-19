---
id: header
title: Configure your header
sidebar_label: Header 
---
The header contains the link of your navigation menu and the title of your project. You can customize the content of your links and change the name of your project, you also have the possibility to change the color of your header.


## Title of your project
To change the name of your project you have to go in the **siteConfig.js** files at the lines 14:
```
const siteConfig  {
    title: 'Enter the name of your project here'
}
```
and change the content in the `title` property.


## Links in navigation
Those links allow you to navigate between the different pages of your website, to change the direction in the `Docs` link simply change in the **siteConfig.js** file:
```
headerLinks: [
    {doc: 'name of a page in your docs folder', label: 'Docs'},
]
```
The content of the `doc` property.

This structure contains a link to your github repo, simply change:
```
headerLinks: [
    {href: 'URL of your repo', label: 'Github'}
]
```
The content of the href property by your URL repo.