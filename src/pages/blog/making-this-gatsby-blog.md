---
path: /making-gatsby-blog
date: 2020-12-22T05:52:32.009Z
title: making this gatsby blog
---
hello! so it took me half a day (plus another few hours yesterday night) to figure out how to make a blog with netlifly and gatsby! i read a few articles and then found this [article](https://dev.to/thatgalnatalie/how-to-use-netlify-as-your-cms-for-your-gatsby-blog-6jm) to be super helpful and straightword in helping me go through all the steps of setting up the working blog. the most trouble that i had was figuring the right file path so that the posts can be generated in the right folder. i first tried src/pages/blog inside of the file config.yml (which didn't work) and then i tried putting qoutes around it (which didn't work either). then, after creating 7 posts in the wrong blog folder, i just deleted the folder all together and it worked! i saw the default posts in the CMS and was able to see the newly created posts on the site! 

overall, i felt good that i was able to figure it out mostly on my own! thank you sophia li for helping me with ideas on how to debug this to make it work!

thoughts after coming back from a break: maybe i should add tags! (i couldn't figure it out)

also i saw another gatsby template with dark mode enabled and it's so image-centric and clean! maybe another time for another purpose. for a dev learning blog, a text-based look will do! :)

i also replaced the original with this instead in the gatsby-browser.js file so that it's dark-theme. also, apparently i need to select the language that it's written in so that the code block shows syntax highlighting!

```javascript
require("prismjs/themes/prism-tomorrow.css");

```