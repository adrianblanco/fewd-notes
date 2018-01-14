# Front End Web Development course notes

Course: **Front End Wed Development**

Year: 2017/2018

Institution: **Udacity**

Granted by: **Google Developer Scholarship**

In October 2017 I was one of the 20,000 students all over Europe, Russia, Egypt, Israel and Turkey selected to enter the [Front-End Web Developer track](https://www.udacity.com/google-scholarships), granted by Google and Udacity.


## Table of Contents
1. [HTML](##HTML)
2. [CSS](##CSS)
3. [Javascript](##Javascript)


## HTML <a name="HTML"></a>

`<tag>content</tag>`

`<p> </p>` A big block of text separate from other pieces of text

`<span> </span>`  A line of text. It isn't really separate form other pieces of text

`<em> </em>` emphasis italic

`<strong> </strong>` b

`<!DOCTYPE html>`: Describes the type of HTML. While there are technically different types

`<head>`: Describes meta information about the site, such as the title, and provides links to scripts and stylesheets the site needs to render and behave correctly.

`<body>`: Describes the actual content of the site that users will see. the content of the page. Always visible.

The `<head>`, on the other hand, is never visible, but the information in it describes the page and links to other files the browser needs to render the website correctly. For instance, the <head> is responsible for:

the document’s title (the text that shows up in browser tabs): <title>About Me</title>.
associated CSS files (for style): <link rel="stylesheet" type="text/css" href="style.css">.
associated JavaScript files (multipurpose scripts to change rendering and behavior): <script src="animations.js"></script>.
the charset being used (the text's encoding): <meta charset="utf-8">.
keywords, authors, and descriptions (often useful for SEO): <meta name="description" content="This is what my website is all about!">.
… and more!
At this point, just focus on these two tags:

<title>About Me</title>
<meta charset="utf-8">
<meta charset="utf-8"> is pretty standard, and will allow your website to display any Unicode character. (Read more on how UTF-8 works here.) <title> will define the title of the document and will be displayed in the tab of the browser window when a user visits the page.

As I mentioned before, there's another kind of list: an ordered list. Try switching the `<ul> for an <ol>` to see how it looks!

Actually, you might find that you can make an <li> element appear on the page without putting it inside a `<ul> or <ol>`. Just because this works doesn't mean that you should ever do this. It's the equivalent of writing a sentence with bad grammar - most people will probably understand what you mean but some people will get confused. In this case, "people" are browsers and "confused" means "render your website incorrectly."

Inside the opening a tag there is href, which stands for "reference." This is called an attribute. Attributes like href describe the properties of HTML elements. In this case, the href attribute is the target URL that the link will open. The content inside the anchor element is the text that users see displayed on the page.

This is the format that you must use when you make hyperlinks! Note:

There is a space between a and href.
There are no spaces around the =.
The website has two " around it.
There are no spaces between the href attribute and the > of the opening tag.

```
<!DOCTYPE html>
<html>
<head>
<meta charset="utf-8">
<title>Title</title>
</head>
<body>
<h1>This is a title</h1>
</body>
</html>
```

## CSS <a name="CSS"></a>

## Javascript <a name="Javascript"></a>
