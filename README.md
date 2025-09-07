# Writing a new blog entry

1.  If you have any photos to add to the site, upload them to [`content/media/`](https://github.com/cyclopsrobotics/blog/tree/main/content/media/).
2.  Create a markdown (`.md`) file in [`content/`](https://github.com/cyclopsrobotics/blog/tree/main/content/) with a short all-lowercase title:

    *Some title* :arrow_right: `some-title.md`
3.  Every file should start like this:

    ```
    ---
    date: YYYY-MM-DD
    tags: tag1,tag2
    ---
    ```

    where you substitute `YYYY-MM-DD` and `tag1,tag2` for something else.
4.  Just write!
    Do check out the [Markdown Cheatsheet](https://www.markdownguide.org/cheat-sheet/) for extra syntax.
5.  If you want to check out what the file will look like before publishing, click on `Preview` on the top left corner of the editor.
6.  When you're done, press `Commit changes...` in the right hand corner to publish it.
7.  It will take about 3 minutes for your changes to go live.

## An example blog entry
```
---
date: 2025-09-07
tags: fruits
---
# Eating bananas
Today I ate a really good banana.
It was:
* Yellow
* Yummy

## Other fruits
Some fruits I would like to eat in the future are:
1. Apples
2. Bananas.
```

That will render as this on the blog:

# Eating bananas
Today I ate a really good banana.
It was:
* Yellow
* Yummy

## Other fruits
Some fruits I would like to eat in the future are:
1. Apples
2. Bananas.
