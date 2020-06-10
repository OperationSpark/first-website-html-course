# first-website-html-course
**For use with the HTML and CSS summer camp course.**

This project walks through the creation of a nice-looking personal website over the course of several days. The project is meant to be completed on jsbin.com, and is divided up into sections as described below.


**Table of Contents**
 
- [Preliminary](#preliminary)
- [Lesson 1 Steps](#lesson-1-steps)
    - [TODO 1: Change the Title](#todo-1-change-the-title)
    - [TODO 2: Add Content](#todo-2-add-content)
- [Lesson 2 Steps](#lesson-2-steps)
    - [TODO 1: Container Div](#todo-1-container-div)
    - [TODO 2: Nav Section](#todo-2-nav-section)
    - [TODO 3: Main Section](#todo-3-main-section)
    - [TODO 4: Image Link](#todo-4-image-link)
- [Lesson 3 Steps](#lesson-3-steps)
    - [TODO 1: Update Nav Section](#todo-1-update-nav-section)
    - [TODO 2: Interests Section](#todo-2-interests-section)
- [Lesson 4 Steps](#lesson-4-steps)
    - [TODO 1: Add in Borders](#todo-1-add-in-borders)
    - [TODO 2: Add in Background Colors](#todo-2-add-in-background-colors)
    - [TODO 3: Change Text Colors](#todo-3-change-text-colors)

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
To start, click "New bin". Then, go ahead and change the web page's title. By default, it says "JS Bin", as seen below.

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
Once your webpage has a title, it's time to add some content in there! Everything you want to show up on your website needs to be between the `<body> ... </body>` tags, so that's where you'll be doing these next steps. There are **6** things you'll want to add. Make sure you put all of them in, and **don't forget to indent when you add in new elements!**

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
Now, add in another **h2** header that contains the words "About Me".

#### Addition 6
Final addition: put in a small paragraph (`<p> ... </p>`) that describes you! It doesn't have to be much, even a single line will do.

In the end, your code should look something like this:

```html
<!DOCTYPE html>
<html>
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width">
  <title>Website Title</title>
</head>
<body>
  <h1> Website Title </title>
  <a href="https://operationspark.org/"> Taught By </a>
  <h2> Your name </h2>
  <img src="image url">
  <h2> About Me </h2>
  <p> Stuff about you </p>
</body>
</html>
```

## Lesson 2 Steps
Today's lesson steps will help you divide your website into different sections. You'll also add in a few more bits of content and turn you image into a link, all to make your website a bit more engaging!

### TODO 1: Container Div
To begin with, you'll want to wrap up everything in your **body** with a **div**. The reason for this won't become clear until you start adding in your CSS, but suffice it to say that eventually it will be used to make sure that your web page is centered and the right size.

When you're done, your code should look something like this:

```html
<body>
    <div>
        <!-- A bunch of stuff from yesterday. -->
    </div>
</body>
```

Make sure that you **indent** everything properly! A quick way to do that is to highlight all of the lines you want to indent, and then press "Tab" on your keyboard.

### TODO 2: Nav Section

A good web page has a navigation section. To do so, put in a custom pair of tags called `<nav> ... </nav>`, and make sure they go around your **h1** header and your **anchor** tags. 

After you've done that, add in another anchor tag to the nav area. This new anchor tag should have the URL of "https://jsbin.com" and the text "JS Bin". When finished, your code should look something like this:

```html
<body>
    <div>
        <nav>
            <h1> Your header </h1>
            <a href="https://operationspark.org"> Taught By </a>
            <a href="https://jsbin.com"> JS Bin </a>
        </nav>

        <!-- More stuff -->

    </div>
</body>
```
Again, don't forget to **indent!**

### TODO 3: Main Section
The goal here is to put all of the rest of your content into one big section, and then divide that sectino up into smaller parts. This is a big one, so we'll break it up into 3 steps.

#### Step 1:
Put custom `<main> ... </main>` tags around your **h2** headers, your **image**, and your **paragraph**. Then, indent the stuff inside!

Code afterward:

```html
<body>
    <div>
        <nav> ... </nav>

        <main>
            <h2> ... </h2>
            <img>
            <h2> ... </h2>
            <p> ... </p>
        </main>
    </div>
</body>
```

#### Step 2:
Put a new div inside of the **main** section and give it an id of "id=sidebar". This div should wrap around your first **h2** section and your **img**.

#### Step 3:
Put *another* new div inside of the **main** section and give it an id of "id=about". This div should wrap around your second **h2** section and your **paragraph**.

At the end of all of this, your main section should look similar to this:

```html
    <main>
        <div id="sidebar">
            <h2> ... </h2>
            <img>
        </div>
        <div id="about">
            <h2> ... </h2>
            <p> ... </p>
        </div>
    </main>
```

### TODO 4: Image Link
Next, add something a little fun into your website. Go ahead and turn your image into a link to whatever (appropriate) website you'd like. As a reminder, you can make an image a link by putting the image inside of an anchor tag, like so:

```html
<a href="url to somewhere"> 
    <img src="url to image"> 
</a>
```

## Lesson 3 Steps
Today's lesson is all about adding in some lists to your website. One will be an interests list, and one will be a navigation list. You already have the pieces of the navigation list, so you'll work on that first.

### TODO 1: Update Nav Section
The first thing you'll want to do is put `<ul> ... </ul>` tags around your anchor tags in your nav area. Once you've done that, put `<li> ... </li>` tags around each anchor. Your result should look similar to:

```html
<nav>
    <h1> Your header </h1>
    <ul>
        <li> <a href="https://operationspark.org"> Taught By </a> </li>
        <li> <a href="https://jsbin.com"> JS Bin </a> </li>
    </ul>
</nav>
```

### TODO 2: Interests Section
The last new thing you'll need to do today is create a new section in your "about" area. This will done is several steps.

#### Step 1:
Put custom `<section> ... </section>` tags inside of your "about" div. Make it look like this:

```https
<div id="about">
    <section>
    </section>
</div>
``` 

#### Step 2:
Put an **h3** header inside of your **section** with the text "Interests"

#### Step 3:
Put in `<ul> ... </ul>` tags just below the **h3** header. Give the opening `<ul>` tag an id of "id=interests".

#### Step 4:
Lastly, put at least 3 **li** tags inside your **ul**, and use them to list some of your interests! In the end, your code should look similar to this:

```https
<section>
    <h3> Interests </h3>
    <ul id="interests">
        <li> Interest 1 </li>
        <li> Interest 2 </li>
        <li> Interest 3 </li>
    </ul>
</section>
``` 

## Lesson 4 Steps
Today you'll finally be getting to CSS and beginning to customize the look of your website! No more boring black text and white backgrounds. Finally, you'll have a web page with some style!

### TODO 1: Add in Borders
To start with, go ahead and put in some borders for your different sections. To start with, put one around your `nav` section. Here's some example code for how you could style your **nav**, but absolutely feel free to change it up a bit!

```css
nav {
    border: 4px gold ridge;
}
```

After you've put a border around your **nav** try putting one around your `main` section and your `img`, too! 

### TODO 2: Add in Background Colors
Once you've got some nice, fancy borders, the next thing you'll want to do is give each section a background color. You can do this by just adding in the `background` property to your existing rules for the `nav` and `main`. For example, your **nav** rule might look something like *this* when you're done:

```css
nav {
    border: 4px gold ridge;
    background: black;
}
```

After you've given good background colors to your **nav** and **main** sections, you might want to give a background to your **body** as well. You can do that the exact same way you would for any other section!

### TODO 3: Change Text Colors
Only one more thing to do for today, and that's change the text colors (if you want to)! By simply adding in the `color` property to any of your rules (or making new rules altogether), you can customize your text color as well! For instance, here's a **nav** rule that's got all of the above properties in it:

```css
nav {
    border: 4px gold ridge;
    background: black;
    color: white;
}
```
