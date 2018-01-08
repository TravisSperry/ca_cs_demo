```
   ___      _                 _                   _                 _
  / __\___ | |_   _ _ __ ___ | |__  _   _ ___    /_\   ___ __ _  __| | ___ _ __ ___  _   _
 / /  / _ \| | | | | '_ ` _ \| '_ \| | | / __|  //_\\ / __/ _` |/ _` |/ _ \ '_ ` _ \| | | |
/ /__| (_) | | |_| | | | | | | |_) | |_| \__ \ /  _  \ (_| (_| | (_| |  __/ | | | | | |_| |
\____/\___/|_|\__,_|_| |_| |_|_.__/ \__,_|___/ \_/ \_/\___\__,_|\__,_|\___|_| |_| |_|\__, |
                                                                                     |___/
                        ___  __                ___  __          ___
                       / __\/ _\              /   \/__\/\/\    /___\
                      / /   \ \     _____    / /\ /_\ /    \  //  //
                     / /___ _\ \   |_____|  / /_///__/ /\/\ \/ \_//
                     \____/ \__/           /___,'\__/\/    \/\___/
```
# Overview

Let's learn how to add the Bootstrap style framework to our projects. After that we'll take a quick
look at jQuery and then we will try to tackle a technical interview question 😅

## Resources

- [Bootstrap](https://getbootstrap.com/)
- [Google Hosted Libraries](https://developers.google.com/speed/libraries/)
- [jQuery](https://jquery.com/)

### Additional Resources -- Be brave.

- [MaterializeCSS](http://materializecss.com/)
- [iTerm2](https://www.iterm2.com/)
- [OhMyZsh](https://github.com/robbyrussell/oh-my-zsh)
- [Atom Text Editor](https://atom.io/)
- [Placeholder](https://placeholder.com/)

# Let's get started!

## Setup

- Create an [html5 document](https://www.w3schools.com/html/html5_intro.asp)
- Add all of the link and style tags for Bootstrap and jQuery to the head section of your doc
  - The can be found [here](https://getbootstrap.com/) in the BootstrapCDN section on the first page
  - Be sure to add the CSS and JS links

## Add things

- Create a div with class `container`
- Inside the div, add an anchor tag with the following classes: `btn btn-success`
  - Change the href attribute value to the URL for the Bootrap Docs (https://getbootstrap.com/docs/4.0/getting-started/introduction/)
  - The text of the anchor tag should be 'Bootstrap Documentation'
  - Add the attribute `target` and give it a value of `_blank`
  - Wut does that do?

Now we have quick access to the Bootstrap docs whenever we need them!

## Add moar things

Organizing content on the page can be a very challenging task. Content organization is an important
component of UI and determines how effectively a user can interact with your site. Let's learn About
[Bootstrap's grid layout](https://getbootstrap.com/docs/4.0/layout/overview/).

- After the first div, add an hr tag and create another div and give it a class of `container`
- Within this div create another div and give it a class of `row`
- With in this div add another div and give it a class of `col`
- Make another div with class `col` making sure that it's parent div is the one with class `row`

This is the basic structure for how you can organize content. We have one row with two columns. Now
let's add some content to these columns.

- In the first `col` let's give it an `h2` tag with the text 'Bootstrap Grid Information'
- Under the header tag add a p tag and type some text

- In the second `col` let's add a button
  - The button should link to the Bootstrap layout documentation referenced above
  - It should open the link in a new tab when clicked
  - It should have some helpful text that will allow the user to understand what they're clicking...
  - Remember the classes we used... instead of `btn-success` try `btn-primary`

## Moar pretty Bootstrap stuff

Bootstrap has a ton of amazing, good looking components that will help you build a killer website or
web application. Let's take a look at one example.

- Let's add a [card](https://getbootstrap.com/docs/4.0/components/card/)
- Do it.
  - Use the first example and find an image on the web to put in place of the placeholder

## Wut is jQuery?

> jQuery is a fast, small, and feature-rich JavaScript library.

# Wrap it up

While rolling your own style is a great idea, sometimes it better to start with a framework. It will
allow you to work faster, create nice looking things and give you an idea of how you might build your
own framework.

# A challenge

1. Make an HTML document.
2. Give it a valid doctype for html5.
3. Make a div on the page with paragraph text that reads "Hello, World."
4. Make the text appear horizontally centered in the viewport. It should remain centered if the browser is resized.
5. Make a border around the text.
6. Do a few things to make it look better.
7. Make the formatted content repeat for a total of 100 times.
8. Make every fifth instance say "Hello, Mr. B"
