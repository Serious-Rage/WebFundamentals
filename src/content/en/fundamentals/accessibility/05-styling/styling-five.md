---
layout: shared/narrow
title: "Accessibility Codelab"
description: "Accessibility Codelab"
published_on: 2016-03-01
updated_on: 2016-03-01
order: 40
translation_priority: 0
authors:
  - megginkearney
  - dgash
key-takeaways:
  tldr: 
    - "Learn what accessibility means and how it applies to web development."
    - "Learn how to make web sites accessible and usable for everyone."
    - "Learn how to include basic accessibility with minimal development impace."
    - "Learn what HTML features are available and how to use them to improve accessibility."
    - "Learn about advanced accessibility techniques for creating polished accessibility experiences."
notes:
  efficiency:
    - "Understanding the accessibility issue, its scope, and its impact can make you a better web developer."
  problem-solving:
    - "Catching, identifying, and removing potential accessibility roadblocks before they happen can improve your development process and reduce maintenance requirements."
---

# Color and Contrast Requirements

If you have good vision, it's easy to fall into the trap of thinking that everyone perceives colors, or text legibility, the same way you do &mdash; but evidence proves otherwise. Let's wrap things up by looking at how we can effectively use color and contrast to create pleasant designs that are accessible to everyone.

As you might imagine, some color combinations that are easy for many people to read are difficult or impossible for others. This usually comes down to *color contrast*, the relationship between the foreground and background colors' *luminance*. When the colors are similar, the contrast ratio is low; when they are different, the contrast ratio is high.

The WebAIM guidelines recommend a minimum contrast ratio of 4.5:1 for all text. An exception is made for very large text (120-150% larger than the default body text), for which the ratio can go down to 3:1.

The contrast ratio of 4.5:1 was chosen for level AA because it compensates for the loss in contrast sensitivity usually experienced by users with vision loss equivalent to approximately 20/40 vision. 20/40 is commonly reported as typical visual acuity of people at about age 80. For users with low vision impairments or color deficiencies, we can increase the contrast up to 7:1 for body text.

You can use the accessibility tools in Chrome to identify contrast ratios. If you run an audit on your page you may get a few warnings for low contrast colors. One benefit of using the Chrome Devtools is that they will suggest AA and AAA alternatives to your current colors, and you can click the values to preview them in your app.

WebAIM itself provides a handy [color contrast checker](http://webaim.org/resources/contrastchecker/) you can use to examine the contrast of any color pair.
