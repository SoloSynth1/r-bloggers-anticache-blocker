# R Bloggers Anti-cache Blocker

An adblock "list" for preventing the anti-cache script on [R Bloggers](https://www.r-bloggers.com/) from messing up the page views.

## Wait, what?

Yes, I know this is awfully specific, but this issue has been plaguing me long enough for me to do something about it.

Yes, I use adblockers. Every time I go to R Bloggers searching up R tips,
the inline "anti-cache" script just decides that I shall not see its content without properly loading ads,
and overwrites everything.

This works by blocking this anti-blocking script from fetching the ads, thus effectively eliminating the issue.

## Prerequisites

You must have adblocker installed in your browser. (duh)

## Installation

Just literally import the filter list (in plain-text format) below to your favourite adblocker:
```
https://raw.githubusercontent.com/SoloSynth1/r-bloggers-anticache-blocker/master/filter-list.txt
```

And enjoy! No more pesky ads overwriting the blog posts.