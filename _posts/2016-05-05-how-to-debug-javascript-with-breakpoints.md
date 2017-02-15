---
layout: post 
title: How to debug Javascript
category: Web Development
tag: Javascript
excerpt: A brief write up of the procedure I use to debug Javascript errors when a script is run via an event being fired.
---

If you are looking to debug a javascript which runs when an event fires (e.g. A link is clicked, a key pressed, mouse pointer goes over an element, etc) then a good debugging technique is to set a break point in the function and step through each line of the script and watch what is happening at every line in the script.  Here's how to do this:

1. In the browser with your page open, hit F12 to open Web Inspector
2. Hover over the element with the event listener bound to it and in the 'elements' tab of web inspector try work out which class
ID or other element attribute is being used to select it to bind the event listener to in the Javascript. 
3. Go to console tab
4. Hit CTRL + SHIFT + F
5. Search for the name of the function with the event listener which you indentfied in the step 2 *
6. Click on what you think is the function decleration which contains the event listener
7. Add a breakpoint at the first line of code which does something in the function, NOT the line which declares the function
8. Go back to the browser, reinvoke the event (click the link, etc) and browser will pause processing at the step in the breakpont
9. Step through each line of code by pressing F10 and watch what happens at each point and watch out for the step where your error occurs.
10. This should then help you identify exactly where the bug is coming from and you should hoepfully know what to do to fix it!

* To try to locate the source file by searching for this name (or a longer unique string of text around this name) in your IDE of choice. (CTRL + H for Eclipse, in my case)   

### Watch a video

I'll post a screencast video of this in action soon as I think this makes it a bit easier to understand how this works. 