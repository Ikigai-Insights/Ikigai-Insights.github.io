# Ikigai Insights Blog

A permanent, paywall-free archive for your writing on lunar governance, coordination systems, and expanded human presence.

## What You Have Here

This is a complete Jekyll blog ready to deploy to GitHub Pages. Everything is set up - you just need to put it on GitHub.

## Setup Instructions (One Time Only)

### Step 1: Create a GitHub Account
1. Go to https://github.com
2. Sign up with your `ikigai.insights@gmail.com` email
3. Choose a username (this will be part of your blog URL)
   - Example: if you choose "ikigai-insights", your blog will be at `ikigai-insights.github.io`

### Step 2: Create a New Repository
1. Once logged in, click the "+" in the top right corner
2. Click "New repository"
3. Name it: `yourusername.github.io` (replace "yourusername" with whatever username you chose)
   - This MUST be exactly `yourusername.github.io` for GitHub Pages to work automatically
4. Make it Public
5. Do NOT initialize with README (we already have files)
6. Click "Create repository"

### Step 3: Upload These Files
1. On your new repository page, you'll see "uploading an existing file"
2. Click that link
3. Drag and drop ALL the files from this folder into the upload area:
   - `_config.yml`
   - `index.html`
   - The entire `_posts` folder with the example post inside
4. Scroll down and click "Commit changes"

### Step 4: Enable GitHub Pages
1. In your repository, click "Settings" (top menu)
2. Scroll down to "Pages" in the left sidebar
3. Under "Source", select "Deploy from a branch"
4. Under "Branch", select "main" (or "master") and "/ (root)"
5. Click "Save"

### Step 5: Wait a Few Minutes
GitHub needs to build your site. After 2-5 minutes, your blog will be live at:
`https://yourusername.github.io`

## How to Write and Publish Posts

### The Simple Way (No Technical Knowledge Required)

1. Go to your repository on GitHub
2. Click into the `_posts` folder
3. Click "Add file" → "Create new file"
4. Name your file: `YYYY-MM-DD-title-of-post.md`
   - Example: `2024-12-15-davos-intervention.md`
5. Copy this template for the top of every post:

```
---
layout: post
title: "Your Post Title Here"
date: 2024-12-15
categories: governance space
---

Your writing starts here...
```

6. Write your post below the `---` using Markdown (see below)
7. Click "Commit changes" at the bottom
8. Wait 1-2 minutes and your post will appear on your blog

### Markdown Cheat Sheet

```markdown
# Large Heading
## Medium Heading
### Small Heading

**bold text**
*italic text*

[Link text](https://url.com)

- Bullet point
- Another point

1. Numbered list
2. Second item

> This is a quote

---
(That's a horizontal line)
```

That's literally it. If you can write in a text editor, you can publish.

## Editing the Site Settings

To change the title, description, or other site-wide settings:

1. Go to your repository
2. Click on `_config.yml`
3. Click the pencil icon (Edit)
4. Change whatever you want:
   - `title:` Your blog's name
   - `description:` The subtitle/tagline
   - `author:` Your name
5. Commit changes

## Optional: Custom Domain

If you want `ikigai-insights.com` instead of `username.github.io`:

1. Buy a domain (~$12/year from Namecheap, Google Domains, etc.)
2. In your domain settings, add a CNAME record pointing to `yourusername.github.io`
3. In your GitHub repository settings → Pages → Custom domain, enter your domain
4. Wait for DNS to propagate (can take up to 24 hours)

## Everything Else

- **Your writing is backed up** - GitHub keeps every version of every file forever
- **No ads, no paywalls** - Just your writing
- **You own it** - Export it anytime as simple text files
- **It's free forever** - GitHub Pages is free for public repositories

## Questions?

The example post in `_posts` shows you the format. Just copy that structure for new posts.

If something breaks, you can always re-upload these files and start over. GitHub keeps history, so nothing is ever truly lost.
