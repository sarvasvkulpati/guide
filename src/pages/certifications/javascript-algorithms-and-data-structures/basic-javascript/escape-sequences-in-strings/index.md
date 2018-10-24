---
title: Escape Sequences in Strings
---
## Escape Sequences in Strings

<!-- The article goes here, in GitHub-flavored Markdown. Feel free to add YouTube videos, images, and CodePen/JSBin embeds  -->
Looking at the required string, we can see that we need "FirstLine", followed by a newline, then a tab, backslash and "SecondLine", followed by a newline and "Thirdline".

Since we can't have any spaces, and newline="\n", tab="\t", and backslash="\\", so the full string is:

```javascript
var myStr = "FirstLine\n\t\\SecondLine\nThirdLine";
```
