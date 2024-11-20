---
layout: default
title: "Jekyll Docs Template"
---

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>



### Get Started

Start by [creating a new post](http://jekyllrb.com/docs/posts/) one of the categories listed in `_config.yml`. It will appear in the navigation on the left once recompiled. Or use the supplied script to make creating pages easier:

```bash
ruby bin/jekyll-page "Some Page Title" ref
```

#### Don't Forget

- Add your own content to this page (i.e. `index.md`) and change the `title`
- Change `title` and `subtitle` defined in `config.yml` for your site
- Set the `baseurl` in `_config.yml` for your repo if deploying to GitHub pages
