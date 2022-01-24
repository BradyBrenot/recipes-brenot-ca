---
title: Example Recipe With Embeds
author: Sabrina
source: ""  # Source for the recipe. Can be a website or anything else.
categories: [Main, Side]  # The categories for this recipe. Can have one, or more than one.
cookTime: 20    # Cook time in minutes
prepTime: 0     # Prep time in minutes
totalTime: 20   # Total time in minutes
preheat: "350"
date: "2007-06-24 22:00:44"
ingredients:
- bread: 1 slice            # Separate ingredient quantity from name using :
- peanut butter: to taste
- good feelings (optional)  # You also just can omit the quantity
directions:
- Toast the bread
- Apply peanut butter
- Eat
notes:
- Notes work the same way as directions do.
- You can use [Markdown formatting](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) in
  notes, directions, and ingredients, as well as the blog thing on the top of the page.
type: "recipes" # Anything in the "recipes" folder can omit this
---

The text down here at the bottom ends up in the top of the resulting page. Use it as a description, as background, for images, or to link in a Youtube video.

## Formatting

You can use Markdown formatting!

## Images

Upload the image to the `static/images` folder, then embed it like this:

![Example image](/images/example.jpg)

## Video

Videos can be embedded like this:

{{< youtube qruzQcjysQQ >}}
