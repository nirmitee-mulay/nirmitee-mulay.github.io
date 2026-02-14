# How to Hide the Blog Page

Until you have blog content written, you can hide the blog link from your navigation.

## Option 1: Remove Blog Link (Recommended)

Open each HTML file and remove this line from the `<nav class="sidebar-nav">` section:

```html
<a href="blog.html">Blog</a>
```

**Files to edit:**
- index.html
- research.html
- publications.html
- scicomm.html
- cv.html
- contact.html
- blog.html (optional, since nobody will navigate there)

## Option 2: Comment Out Blog Link

Instead of deleting, you can comment it out so it's easy to restore later:

```html
<!-- <a href="blog.html">Blog</a> -->
```

## Option 3: Keep "Coming Soon"

Leave everything as is - the blog page currently shows "Coming Soon" with planned topics.

---

## When You're Ready to Add Blog Posts

1. **Keep the blog.html page**
2. **Create individual blog post files** (e.g., `blog-post-1.html`, `blog-post-2.html`)
3. **Update blog.html** to list your posts instead of "Coming Soon"
4. **Make sure blog link is visible** in navigation

See the comments at the bottom of `blog.html` for an example of how to add blog posts.
