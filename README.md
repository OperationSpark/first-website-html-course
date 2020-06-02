# first-website-html-course
**For use with the HTML and CSS summer camp course.**

This project walks through the creation of a nice-looking personal website over the course of several days. The project is meant to be completed on jsbin.com, and is divided up into sections as described below.


**Table of Contents**
 
- [Preliminary](#preliminary)
- [Lesson 1 Steps](#lesson-1-steps)
    - [TODO 1: Change the Title](#todo-1-change-the-title)
    - [TODO 2: Add Content](#todo-2-add-content)

## Preliminary 

### About Saving
No matter where you are, whenever you are done working for the day, make sure you do two things to save your work. JS Bin autosaves, but it's better to have backups than risk a bug causing you to lose everything!

**Save step 1:** Go to "File" and click "Save snapshot"
**Save step 2:** Go to "File" and click "Download"

Remember to do this every day so you can always continue right where you left off!

### About Loading
To open your file after returning, click on "Open bin..." and find the entry with the title of your website on it. If you open it and it is not where you left off, then open up the most recent shapshot you made instead (it will always be right below the main entry for your website).

If for some reason you don't have an entry for your website, you will need to open the copy you downloaded in the previous session, then copy and paste all of it directly into JS Bin. This should never happen, by the way, but just in case it does, that's what you need to do to get your work back on it.

## Lesson 1 Steps
Today's lesson steps will add in several of the basic components of a website, including a title, some headers, a link, an image, and a paragraph.

### TODO 1: Change the Title
To start, go ahead and change the web pages title. By default, it says "JS Bin", as seen below.

```html
<!DOCTYPE html>
<html>
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width">
  <title>JS Bin</title>
</head>
<body>

</body>
</html>
```

See the `<title> ... </title>` tags? Change "JS Bin" to the title you want your website to have. Keep in mind this will only show up in your browser tab, and only if you open the website into its own tab outside of JS Bin. To do that click the expand button as highlighted in the image below.

![Expand Button Image](images/expand.PNG)

### TODO 2: Add Content
Once your webpage has a title, it's time to add some content in there! Everything you want to show up on your website needs to be between the `<body> ... </body>` tags, so that's where you'll be doing these next steps. There are **6** things you'll want to add. Make sure you put all of them in!

#### Addition 1
The first thing you want to add is a header displaying your title on your website. To do that, use the `<h1> ... </h1>` tags to make some very big text, and put the title you want between the opening and closing tags.

#### Addition 2
Next, a good website should have links in it. You should link to the Operation Spark website to show where you learned to code! Use an anchor tag `<a href="url"> What to click </a>` to link to Operation Spark.

The Operation Spark URL is "https://operationspark.org/", by the way. Also, instead of "What to click", why not put something more appropriate, like either "Taught By" or simply "Operation Spark"?

#### Addition 3
This is your website, so your name should be on here in big letters. Use `<h2> ... </h2>` tags to do that, and remember to put your name in between them!

#### Addition 4
Next, a good website should have picture, right? Go ahead and use an `<img src="image url">` tag to embed an image into your website. Feel free to do a Google search to find one that you want. When you find an image, you need to right click on it, then select "copy image address", then paste that URL into your HTML as the "image url".

#### Addition 5
Now, add in another `<h2>` header that contains the words "About Me".

#### Addition 6
Final addition: put in a small paragraph (`<p> ... </p>`) that describes you! It doesn't have to be much, even a single line will do.
