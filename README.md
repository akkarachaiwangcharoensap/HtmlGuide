# Html Guide
An introduction guide to HTML

Welcome to an introduction guide to HTML. In this guide, I'll briefly go through the basic concept of HTML. Please note that, I write this guide based on my experience working with HTML and its historical is on Wikipedia which you can read it at anytime!

# What is HTML?

HTML stands for Hypertext Markup language, it is used to render web pages with other scripting languages along the side.
HTML is made up with tags. For an example,

html, head, body are html tags.
```
<html>
<head></head>
<body>
</body>
</html>
```


This is called a head tag.
```
<head></head>
```

This is an opening head tag
```
<head>
```

This is an closing head tag
```
</head>
```

Web page starts to render page from the top of the file to the bottom with an opening HTML tag, for an example
```
<html>
```
and ends with a closing HTML tag
```
</html>
```

Full example,
```
<html>
  <head>
    <!-- Stylesheets and Scripts -->
  </head>
  <body>
    <!-- HTML tags go here-->
  </body>
</html>
```

# Head Tag
Within the head tag, you can use meta tags, link tags, and a script tag to develop your web page.

Meta tags are the tags that will be used to improve your site searching (web crawling) which is also known as SEO. I won't be cover SEO on this guide. But, if you are interested. You can learn more by doing some research.

Link tags are used to link your site to a CSS script. What is a CSS? CSS stands for Cascading Style Sheet. It is basically a script that is used to customize your site with COLOURS and layout! Most of the site is being rendered by HTML and styled by CSS scripts. I won't be covering this in this guide. I'll cover this on the next guide. (CSS Guide)

Lastly, we have a script tag. Script tag is basically like a CSS link tag, but it is javascript. Again, I won't be covering this in this guide. I'll be covering this on the javascript guide.

# Body Tag
Body tag is where the magic begins. Within a body tags, you will have many other HTML tags such as
```
<h1></h1><h2></h2><h3></h3><div></div><span></span><i></i><b></b><u></u>
```

Basically, body tag is the main part of your web page. Whenever it is a menu, a link, or any other. It will go in between the body tag.

For an example,

```
<html>
  <head>
    <!-- This is a comment, the page won't render this -->
    <!-- CSS and Javascript links -->
  </head>
  <body>
    <h1>Hey! My name is Aki! Nice to meet you!</h1>
  </body>
</html>
```

View it live: [Here](https://akkarachaiwangcharoensap.github.io/html-guide/).

That is it for this guide! The most important thing to learn about HTML is to practice. Pratice makes PERFECT! Most of the HTML tags can be found at [W3 Schools](http://www.w3schools.com/html/)
