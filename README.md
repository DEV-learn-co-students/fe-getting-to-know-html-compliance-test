# Getting To Know HTML

## Overview

In this lesson we will introduce the fundamentals of HTML syntax, document structure, typography, images, and links, as well as how to validate our HTML. HTML will act as the structure of our webpages, wrapping our content and describing how the browser should display it. HTML is often described romantically as the unifying language of the web. Along with CSS, and JavaScript, HTML is the life-blood of our webpages and an excellent place to start our code journey.

## Objectives

1. HTML Syntax
2. Document Structure
3. Typography
4. Images
5. Links
6. Validation

## HTML Fundamentals

<iframe width="640" height="480" src="//www.youtube.com/embed/tuDKQxfiXmY?rel=0" frameborder="0" allowfullscreen></iframe>

*Note: Slides for this lecture video are provided in the resources at the bottom of this lesson.*

### Syntax

HTML stands for Hyper Text Markup Language. Markup languages surround content in order to tell the browser how to format it. It does this through a series of elements. HTML Elements are made up of a starting tag and an ending tag like so:

```html
<p>You're Learning HTML!</p> 
```

Above we can see the `p` element which indicates a paragraph in the browser. The start tag `<p>` indicates the beginning of the paragraph and the ending tag `</p>` defines the end of the paragraph. As you can see tags names are surrounded by `<>` angle brackets. All the content `You're Learning HTML!` in the center is the body of the paragraph. This tells the browser to addd pace before and after the content "You're Learning HTML!".

There are a few exceptions where elements may just have an opening tag only. We will see a few of these in examples below such as the image element `<img>` but more on that later.

Inside the starting tag `<p>` we can place options `<p class="intro">` that will alter the way our paragraph element displays. These options are only found in the starting tag and never in the ending tag. We separate the element name `p` from the attribute name `class=""` using a keyboard space. We can set a value for our attribute `attribute="value"` using `=` equals symbol and `"` quotes to surround our value.

### Document Structure

All HTML pages have a standardized document structure:

```html
<html>
  <head>
    <!-- Meta data for the browser and search engines -->
  </head>
  <body>
    <!-- Visible content area -->
  </body>
</html>
```

Starting with the `<html>` element that wraps all of our content. This tells the browser that everything in between the starting and ending `<html>...</html>` tags is to be interpreted is HTML code. Nested inside we have the `<head>...</head>` and the `<body>...</body>`. The head contains meta data for the browser and search engines such as: the title of the page, links to other stylesheets and scripts, meta keywords, and descriptions for search engines among others. This content is not something a visitor to our website will see directly. In contrast to that the `<body>` contains all of the visible content we will see for the webpage. This includes text such as headings, paragraphs, and images, links, videos, audio players, maps, forms, and more.

### Doctype

A special element proceeding the document structure is the `<!DOCTYPE>` tag.

```html
<!DOCTYPE html>
<html>
  <head>...</head>
  <body>...</body>
</html>
```

The Doctype tells the browser the version of HTML that it should interpret the document as. In the case of HTML5 you simply state `<!DOCTYPE html>`.

### Typography



### Links

...

### Validation

...

## Summary

- ...

## Resources

- [Presentation Slides](https://docs.google.com/presentation/d/1eU-4wD5dsxV1t-3CA3T82gbv2K3pAs92pq30HlmXM_U/edit?usp=sharing)
- [Mozilla Dev Network - Learn HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)
- [Bonus Video - Image Compression](https://www.youtube.com/watch?v=2jusYaU-CFM&feature=youtu.be)
- [Bonus Slides - Image Compression](https://docs.google.com/presentation/d/1CVHOE65QkP1ioHD0u9Ryh6cIT6DW0YQNyhFP0-OYECc/edit?usp=sharing)
- [Compress Images In Photoshop](https://www.youtube.com/watch?v=Ut_F7iGlze8)
- [Compress Images In GIMP](https://www.youtube.com/watch?v=x-3fp4ksoRc)
- [ISO Lang Codes](http://en.wikipedia.org/wiki/List_of_ISO_639-1_codes)
- [What does the Charset Attribute Do?](http://community.spiceworks.com/topic/91624-what-does-charset-utf-8-mean)
- [HTML Element Lookup Refernce](https://developer.mozilla.org/en-US/docs/Web/HTML/Element)
- [HTML Element Cheatsheet](http://overapi.com/html-dom/)

<p data-visibility='hidden'>View <a href='https://learn.co/lessons/fe-getting-to-know-html' title='HTML Fundamentals ~ 12min'>HTML Fundamentals ~ 12min</a> on Learn.co and start learning to code for free.</p>
