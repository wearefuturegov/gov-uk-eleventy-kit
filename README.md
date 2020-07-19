# GOV.UK Eleventy starter kit

This is a basic 11ty website that includes the styles, assets and scripts of GOV.UK Frontend.

It's intended for quickly building static websites.

It should be great for prototypes, but might also be suitable for some production services as well.

## Anatomy

The main folder is `/pages` where HTML pages live.

Layouts are in the `/_includes` subfolder. Choose which layout you want to use by chaning the front matter:

```
---
title: My first page
layout: default
---
```

You can copy and paste code samples from the GOV.UK design system into these.

Other folders you might see:

- `/assets` images and font files needed by the site live in here
- `/javascript` you can write custom JavaScript in here
- `/styles` you can style your website using SCSS here

## Using it

You need [node.js](https://nodejs.org/en/download/) installed for this to work.

Check if you have it by running `node -v` in your terminal.

If you do, run these commands:

```
npm install
npm run dev
```

It should be available in your browser at `http://localhost:8080`.


## Putting it on the web

If you run `npm run build` in your terminal, it will build a set of HTML webpages that are ready to host on the web.

It's suitable for any static file host, like [Netlify](https://www.netlify.com/).

Netlify brings lots of handy enhancements, such as quick [forms](https://docs.netlify.com/forms/setup/).