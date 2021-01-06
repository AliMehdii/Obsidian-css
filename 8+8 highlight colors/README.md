## Features
1. Use nested tag to easily manage(**search/count**) highlights text background, bold, italic with statistics on the tag panel.
2. Toggle highlight nested tags in Editor mode by WYSIWYG editor css and Auto hide them in preview mode .
3. 8 + 8 = 16 colors for higlight text ==background==, **bold**, _italic_._italic_.

## How to use
```
#h/COLOR_name

Highlight text background 
Highlight text bold 
Highlight text italic
``` 
``` 
#h/pink ==pink==

#h/pink **pink

#h/pink _pink_
``` 

## Editor mode and Preview mode
 
### Highlight-text-background
![Text Background](https://github.com/steveyang331/Obsidian-css/blob/main/8%2B8%20highlight%20colors/images/Highlight-text-background.png)
 
### Highlight-text-bold
 ![Highlight-text-bold](https://github.com/steveyang331/Obsidian-css/blob/main/8%2B8%20highlight%20colors/images/Highlight-text-bold.png)
 
### Highlight-text-italic
 ![Highlight-text-italic](https://github.com/steveyang331/Obsidian-css/blob/main/8%2B8%20highlight%20colors/images/Highlight-text-italic.png)


# Installation
1. Download and move css file to `/vault/.obsidian/snippets/ ` folder .
2. Open Obsidian's `settings`, go to `Appearance`.
3. Active `8 + 8 highlight colors` .

 
# FAQ for code design

## 1 . Why don't use html ` <mark>`  for highlight ?
 Use ` <mark>`  need to hit many more times keyboard. ` <mark> ... </mark>`
 Not obvious statistics by typing color name to search. 
 
## 2. Customize '#h/' ?
You can customize it, such as: # h-/pink, # hlt/red, # highlight/blue, # H/gray , # HLT/yellow, # h_/green, # HIGHLIGHT/lime, etc. 

But #h/color is the balance option. 
h is only one character and a lower case by without click "shift" key. Easy to remember and understand.

## 3. Why use nested tag ? Why not lessly typing ?
 If don't use nested tag, although we only need to type color name: pink, navy, lime, the color tags list is too long ,and mixed with other nested tag , and it's not easy to manage color tags on the tag panel.
 
 If use nested tag, all color tags are placed under the same "h" parent tag. **"h" means highlight**.
 
 It's easy to search all pink color highlight contents in all pages, all blocks by just one click tag, and there are the highlight statistics on the tag panel.  
 
## 4. Why add WYSIWYG editor css  ?
 If don't use WYSIWYS edior css , the color tag always display. We use that css for toggle it.
 
## 5. If Obsidian have highlight toolbar in the future, Is this un-necessary ？
If Obisidan have highlight toolbar, **AND**  allow ** search them by one click and have statistics**  , This css snippet is not necessary any more.

But until today, there're no one toolbars can do both.

If Obisidan have highlight toolbar, AND **Don't allow search these highlight.** **This css snippet still works for easily search all highlight colors by just one click tag, and there are the highlight statistics on the tag panel.**

## 6. Does "#h/" conflict with '#h-'words tags ?
No conflict, you can download '#h-' words for testing.md . 
No one hidden.

## 7. Imagining the best solution is ?
Probably I can imagine the best solution is toolbar will support nested tag for highlight without typing color name. 

But until today, there're no one toolbars can search highlight colors by one click and have highlight colors statistics.

## 8. Is this the best solution ? 
Compare all the things, using nested tag for manage highlights is the balance solution **currently** between creating highlight text background, bold, italic, search them, count them , hide nested tag , lessly typing and without 'h-'words conflict.

## 9. Bugs ? but not bugs
1. Yellow color : In light theme, Every haze yellow background but perfect to hide text. You could change yellow to orange or others by css code. If you don't know how to do, please feedback I'll build for you. 

2. If you use theme color is not dark or other colors like purple theme, pink theme, probably you have to change highlight colors for better looks. If you don't know how to do, please feedback I'll build for you. 

3.  After opened WYSIWYG css code for highlight, bold and italic. 
**In editor mode**, It's not much easy to select/copy texts by mouse and by ctrl + arrow keys, ctrl + shift + arrow keys. This is the WYSIWYG's style, like Typora. but Default is opened it for looks good.
**In preview mode** , you can still easy to select texts.


# FAQ for highlight colors usage
## Which highlight colors for specific contents ？ 
## Do I need all 16 highlight colors ? 

Nested tag colors confilct with highlight colors .

probably, You already have colorful tag or/and colorful nested tag. 

such as

![Pasted image 20210106160008.png](https://github.com/steveyang331/Obsidian-css/blob/main/8%2B8%20highlight%20colors/images/Pasted%20image%2020210106160008.png)

![Pasted image 20210106160058.png](https://github.com/steveyang331/Obsidian-css/blob/main/8%2B8%20highlight%20colors/images/Pasted%20image%2020210106160058.png)

![Pasted image 20210106160113.png](https://github.com/steveyang331/Obsidian-css/blob/main/8%2B8%20highlight%20colors/images/Pasted%20image%2020210106160113.png)

At this time, use colorful highlights for text background ,bold, italic. 

The whole page looks very beautiful, but the colors make chaos, **color chaos**, right? 

such as 

![Pasted image 20210106162826.png](https://github.com/steveyang331/Obsidian-css/blob/main/8%2B8%20highlight%20colors/images/Pasted%20image%2020210106162826.png)

**How to distinguish different color text?**

**It's really hard to distinguish by eyes ,right?**

**Where the issue came from?**

- Is this issue about colors ? No, colors don't do by themselves if you don't use them.
- Is this issue about so many colors ? No.
- Is this issue about this css snippet ? No.

Probably, the problem came from nested tag and highlight color use different colors, Okay. 

**What looks like use the same colors for both nested tag and highlight?**

**Combine Nested tag colors and Highlight colors?**

Such as 

![Pasted image 20210106164507.png](https://github.com/steveyang331/Obsidian-css/blob/main/8%2B8%20highlight%20colors/images/Pasted%20image%2020210106164507.png)

Here's code if you need : 

Looks good, but still have many more colors. 

**Can solve this issue by build plugin?**

**Well, the plugin can solve issue that more easier to set what you want colors.**

**But the plugin can't solve color chaos, right ?**  

**How to solve color chaos issue?**

# How do I use nested tag with color and highligh color ?

In fact, I really rarely use tags, rarely use nested tag, so colorful tags and colorful nested tags are still rarely use. So , I don't need colorful (nested) tags.

About highlight colors. Currently I just need to use 2 colors, white and black. 

![Pasted image 20210106170155.png](https://github.com/steveyang331/Obsidian-css/blob/main/8%2B8%20highlight%20colors/images/Pasted%20image%2020210106170155.png)

In the further, I wish I don't use only 2 white and black highlight colors and also use white and black for highlight is temporary. 

**Yes, rarely use highlight colors is my final goal ,is my solution.**

**If I don't use highlight colors , use what to highlight?**

` I use mind/heart to highlight text or background, not through code` .

## Why called 8 + 8 ? Why did I build 8 + 8 highlight colors?

This is the most valuable, interesting and mysterious thing. 

And This is also why I built this css snippet after I discovered mysterious thing.

# About
```
Name:: 8 + 8 highlight colors
Author:: @steve_yang331
version:: 0.0.1
Date:: 2021-1-5 15:08:45
Download:: https://github.com/steveyang331/Obsidian-css
```

