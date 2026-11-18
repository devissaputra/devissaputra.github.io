# Publishing a blog article

The blog lives at `/blog.html` and uses a static JSON index. No build tools or external services are required.

1. Copy `blog/POST_TEMPLATE.html` to `blog/posts/your-article-slug.html`.
2. Replace the placeholders with your original writing, date, category, and verified references.
3. Add an object to `blog/posts.json`:

```json
{
  "title": "Your article title",
  "date": "2026-11-18",
  "category": "AI in Education",
  "excerpt": "A brief summary.",
  "url": "blog/posts/your-article-slug.html",
  "published": true
}
```

Use a real date. Articles with `published` other than `true` are hidden from the index. Valid article URLs must be within `blog/posts/` and end in `.html`.

Available examples of categories: AI in Education, Machine Learning, Research Methods, Learning Systems, Robotics.

The article list supports keyword search, topic filtering, and newest-first sorting. Keep original research claims and citation information accurate. Do not add drafts to the public index before publication.
