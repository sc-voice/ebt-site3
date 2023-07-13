---
title: Customize your EBT-Site
description: Create custom content using Markdown
img: pexels-philippe-donn-1133957.png
img-alt: Hummingbird reaching to drink nectar from flowers
category: 1. General
order: 1
---

### Customize content

Before you can view your website, you'll need to configure it.
Github allows you to change your website 
[online](https://docs.github.com/en/repositories/working-with-files/managing-files/editing-files).
Just open your browser and login to Github.

To customize your website, you'll need to:

1. Edit ```ebt.config.mjs``` file (see below)

Once you configure your website properly, you'll be able to view 
it and add your own wiki content.

1. Edit the ```content``` folder for your new repository as desired.

##E ebt-config.mjs

The file '''ebt-config.mjs''' has several properties you will need to change.
Be sure to use [JSON syntax](https://www.json.org/json-en.html) properly!

| Property | Description |
| :----: | :----: |
| appName | The site name (e.g., ```EBT-Site```). |
| basePath | The URL base path for your site. Initially, this should be the Github repository name (e.g., "/ebt-site3/"). If you choose a custom Internet domain, change this to simply "/".
| github.account | The Github account name (e.g., "sc-voice") 
| github.repository | The Github repository name (e.g., "ebt-site3") 
| multilingual | (Optional) The two-letter language ISO code for your site. If specified, the users to your site will not have settings to change the web application language or the EBT translation language.
| content.index | The file namve for customizing the file name used for category table of contents (e.g., "toc")

Commit your changes and verify them by viewing your website.

## Custom content

Customize your EBT-Site by changing the wiki.
Custom content is located in the ```content folder```.
Content webpages are generated from
[Markdown files](https://github.com/skills/communicate-using-markdown).

For example, this web page is defined by:
```
content/welcome.md
```

## Content channels
Organize your Markdown files into sub-folders of related content.
Each content sub-directory is known as a _channel_.

For example, here is a channel of related EBT sites:

* [Sites](#/wiki/sites/toc)

### TOC files

EBT-Site automatically generates the table of contents for each channel.
You can customize a channel's table of contents by adding a ```toc.md``` file.
EBT-Site will automatically append the 
channel table of contents to your custom ```toc.md``` file.

Wed Jul 12 11:37:08 AM PDT 2023
