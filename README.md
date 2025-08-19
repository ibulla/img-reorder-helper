# Image Tag Reorder Helper

A lightweight HTML+JS helper to reorder `<img>` tags effortlessly—take your image collections from static clutter to curated clarity.

##  Why This Exists

I had a trove of old drawings, collages, and canvases scattered across blog posts—valuable pieces of my creative journey but buried and disconnected. I needed a way to bring them all together coherently, not by writing a full UI tool, but by simply rearranging the `<img>` tags in the order I wanted. Thanks to AI (specifically, ChatGPT), I just had to describe the idea—and the script existed.

This little helper embodies a moment where imagination met execution. The time and effort I saved reminded me how AI can remove friction, leaving more room for creativity.

##  What It Does

- Takes a block of HTML `<img>` tags.  
- Lets you **drag & drop** the images into a new sequence.  
- Outputs the reordered `<img>` tags so you can paste them back into your blog, gallery, or database.  

Perfect for curating blog posts, online archives, or personal collections.

##  How to Use

1. **Download** or clone this repo.  
2. Open `img-reorder-helper.html` in your browser (or place it on your webserver).  
3. **Paste** your `<img>` tag list into the input field.  
4. **Drag & drop** to reorder the images.  
5. **Copy** the reordered HTML output.  
6. Paste it back into your blog or wherever you want the curated sequence to appear.  

See it in action with my archives:  
- [Chronotopes](https://ibulla.com/i/works/chronotopes)  
- [Daily Cut](https://ibulla.com/i/works/daily-cut)  
- [Daily Cut 2](https://ibulla.com/i/works/daily-cut-2)  

##  Example

Input:
```html
<img src="a.jpg">
<img src="b.jpg">
<img src="c.jpg">
````

After reordering →

```html
<img src="c.jpg">
<img src="a.jpg">
<img src="b.jpg">
```

## Why It Matters

It’s more than a helper script—it’s a symbol of how AI can shift our creative workflows. The fewer barriers between an idea and its realization, the more we’re able to create, reflect, and share.
