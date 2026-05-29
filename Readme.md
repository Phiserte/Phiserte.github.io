# Tejas Prakash Bhat — Portfolio

Cybersecurity portfolio built with pure HTML/CSS/JS. No frameworks, no build tools, no cost.

## 🚀 Deploy to GitHub Pages (Free)

1. Create a new GitHub repo named `<your-username>.github.io`
2. Upload all files in this folder to the repo root
3. Go to repo **Settings → Pages → Source → main branch**
4. Your site is live at `https://<your-username>.github.io`

## 📝 How to Add a Blog Post

### Step 1 — Create the post file
Copy `posts/idor-race-condition-writeup.html` as a template.
Save your new post as `posts/your-post-slug.html`.

### Step 2 — Register it in blog.html
Open `blog.html` and add an entry to the `POSTS` array:

```js
{
  slug: "your-post-slug",
  title: "Your Post Title",
  excerpt: "A short 1-2 sentence description shown on the blog listing.",
  tag: "writeup",   // writeup | ctf | research | malware | web | ai-security
  date: "2025-08-01"
}
```

That's it! The blog page auto-renders the card.

## 📁 Structure

```
portfolio/
├── index.html          ← Main portfolio page
├── blog.html           ← Blog listing (add posts here)
├── style.css           ← All styles
├── script.js           ← Terminal animation + interactions
├── assets/
│   └── resume.pdf      ← Drop your PDF resume here
└── posts/
    ├── idor-race-condition-writeup.html   ← Sample post
    └── your-new-post.html                 ← Add posts here
```

## 🌐 Free Custom Domain (is-a.dev)

1. Fork https://github.com/is-a-dev/register
2. Add a file `domains/tejas.json`:
   ```json
   {
     "owner": { "username": "Phiserte" },
     "record": { "CNAME": "Phiserte.github.io" }
   }
   ```
3. Open a PR → you get `tejas.is-a.dev` for free!
4. In GitHub Pages settings → Custom domain → enter `tejas.is-a.dev`