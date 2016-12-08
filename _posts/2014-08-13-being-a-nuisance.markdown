---
layout: post
title:  "Usability bug bears"
date:   2014-08-13
category: web
type: blog
---
I have had this post in my mind for a while. The more we browse the web - and, shit, do we! - the more we rely on our own techniques and experiences to do so quickly and efficiently. We may appreciate subtle design nuances, but we're usually adept at finding usability flaws: the small bug bears that stutter our progress. So how do we ensure, as developers, that we're providing the best experience possible, using the simplest techniques?

## Helpful form labels

Placing your radio buttons and checkboxes in labels allows the user to activate one by clicking either the label or the input. By doing this, we're avoiding frustration when users click on the label and get no feedback.
    
```
<label>
  <input type="checkbox"> Free money
</label>
```

We missed the 'for' attribute out of that last code example. Clicking a label with a matching 'for' attribute will focus the mouse cursor on the respective input. Let's use a text input field as an example:

```
<label for="surname">Surname</label>
<input type="text" id="surname">
```

## Enter to submit

Users should be able to submit forms by completing the fields and hitting 'enter' on their keyboard. I've seen websites where the user has to click the submit button. This is pants, and we shouldn't rely on this. Providing we use submit inputs, there should be no problem.

## Improving menu usability

Add padding to your menu links and not your list items. This will provide a bigger hit area - and your users will thank you when it comes to mobile and tablet browsing.


[jekyll-gh]: https://github.com/mojombo/jekyll
[jekyll]:    http://jekyllrb.com
