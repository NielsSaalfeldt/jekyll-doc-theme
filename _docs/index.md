---
title: Welcome
permalink: /docs/home/
redirect_from: /docs/index.html
---

## Getting started

Once you have cloned the repo [group6project](https://github.com/Ferdi28/group6project), open the corresponding R project in your files.
From there let us guide you by following the steps below.
1. Download this package to start or rather build and install it.
2. Run the app either manually or with the function run_indeed().
3. The map will appear and you will observe the number of job listing in Switzerland.
4. Play around with it by filtering the category you seek to find a job in!
5. Zoom on the region/city you desire to work in and, by clicking on the icon you will observe job title and the indeed link to the corresponding job
6. APPLY!


## Writing content

### Docs

Docs are [collections](https://jekyllrb.com/docs/collections/) of pages stored under `_docs` folder. To create a new page:

**1.** Create a new Markdown as `_docs/my-page.md` and write [front matter](https://jekyllrb.com/docs/frontmatter/) & content such as:

```
---
title: My Page
permalink: /docs/my-page/
---

Hello World!
```

**2.** Add the pagename to `_data/docs.yml` file in order to list in docs navigation panel:

```
- title: My Group Title
  docs:
  - my-page
```

### Blog posts

Add a new Markdown file such as `2017-05-09-my-post.md` and write the content similar to other post examples.

### Pages

The homepage is located under `index.html` file. You can change the content or design completely different welcome page for your taste. (You can use [bootstrap components](http://getbootstrap.com/components/))

In order to add a new page, create a new `.html` or `.md` (markdown) file under root directory and link it in `_includes/topnav.html`.
