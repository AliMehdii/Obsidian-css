## Features
1. Use nested tag to easily manage/search highlights text background, colors bold, colors italic with statistics on the tag panel.
2. Toggle highlight nested tags in Editor mode by WYSIWYG editor css and Auto hide them in preview mode .
3. 8 + 8 = 16 colors for higlight text ==background==, **bold**, _italic_.


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
 
## FAQ

### Why don't use html ` <mark>`  for highlight ?
 Use ` <mark>`  need to hit many more times keyboard.

### Why use nested tag ? Why not lessly typing ?
 If don't use nested tag, although we only need to type color name: pink, navy, lime, the color tags list is too long ,and mixed with other nested tag , and it's not easy to manage color tags on the tag panel.
 
 If use nested tag, all color tags are placed under the same "h" parent tag. **"h" means highlight**.
 
 It's easy to search all pink color highlight contents in all pages, all blocks by just one click tag, and there are the highlight statistics on the tag panel.
 
### Why add WYSIWYG editor css for highlight colors ?
 If don't use WYSIWYS edior css , the color tag always display. We use that css for toggle it.
 
### If Obsidian have highlight toolbar in the future, Is this css snippet is necessary ？
If Obisidan have highlight toolbar, select text, click color, **AND** allow search these highlight, This css snippet is not necessary any more.

If Obisidan have highlight toolbar, **Don't allow to search these highlight.** **This css snippet still works for easily search all highlight colors by just one click tag, and there are the highlight statistics on the tag panel.**

### Bugs ? but not bugs
In light theme, haze but perfect with yellow color.

### Why called 8 + 8 ? 
This is the most valuable, interesting and mysterious thing. 
And This is also why I built this css snippet after I discovered something. 

