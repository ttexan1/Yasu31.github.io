# My page
Uses [Jekyll](https://jekyllrb.com/) to build website.
Check out their [step by step Tutorial](https://jekyllrb.com/docs/step-by-step/01-setup/) for a refresher.

## to add new [blog post](https://jekyllrb.com/docs/posts/)
create `2018-09-10-title_of_blog.md` with contents:
```md
---
layout: post
title: タイトル
---
内容
![](/assets/img/image.png)
```

Link to posts with `{% post_url 2010-07-21-name-of-post %}`

## to add new project to portfolio
Uses [collections](https://jekyllrb.com/docs/collections/) in Jekyll. In /\_projects, create `~~~.md` with contents:

```md
---
name: Project name
summary: One sentence summary of project
image: ~~.jpg (place image in /assets/img/)
duration: Month 2018 ~ Month 2018
video: <iframe width="560" height="315" src="https://www.youtube.com/embed/0Q0_jMWFcIw?rel=0&amp;showinfo=0" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>
---
* [any links if you have them](https://connected-robotics.com)

Lorem Ipsum ...
```
