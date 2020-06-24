# Website

Stock2Shop website, documentation and WIKI built with Hugo.

## Getting Started

- Install GoHugo
- Clone the project
- Navigate to the project parent directory
- Run ```hugo new site website --force```
- Run ```hugo server -D```
- View in your browser with http://localhost:1313/

## Key Terms
- Draft: Drafts do not get deployed; once you finish a post, update the header of the post to say draft: false
- Front matter: Post meta data as shown below
```
title: "What are the requirements for Stock2Shop Software (APIFACT)?"
date: 2020-03-31T14:13:36+02:00
draft: true
menu: "main"
```
- Section:
- Type:

## Images
To add image in markdown use below syntax and save image in the static directory
```
![Example image](/images/howto_1.png)
```

## Menus

There are two ways to add menus:
1. Front Matter
    1. Add menu entry to Front matter
    2. Create Nav partial
    3. Include partial in header.html or
2. Config.toml file
[Read more] (https://gohugo.io/templates/menu-templates/)

## Notes

- static/css are cached in the browser

## General Commands

- Start Hugo server with drafts enabled:  
```hugo server -D```
- Build static pages and output to ```./public/```  
```hugo -D```