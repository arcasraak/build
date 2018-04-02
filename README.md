# dartmouth-cs52.github.io

Source for the website for DALI Workshops and Resources.  Updated periodically.  Now includes slides and notes. Contribute at your leisure.

<hr>

Built with: [Jekyll](https://jekyllrb.com/), [GitHub Pages](https://pages.github.com/), and [Remarkjs](https://github.com/gnab/remark)

### Local installation on OSX

`brew install ruby`

`gem install bundler`

`bundle install`

`bundle exec jekyll liveserve`


### Slide Integration

uses [remarkjs](https://github.com/gnab/remark) for building slides - if you use the


```
<div class="slide" markdown="0">

# Title

---

# Agenda

1. Introduction
2. Deep-dive
3. ...

---

# Introduction

this is an intro

---
</div>
```

By default the slide content will also be shown in converted markdown on the page.  If you prefer to have slide only content add a `hidden` class.


### Search Powered by Algolia

Create an `_algolia_api_key` file and copy the key from the [dashboard](https://www.algolia.com).

Run: `bundle exec jekyll algolia` to update the index (when new content is added)

Resources:

* https://community.algolia.com/jekyll-algolia/blog.html
* https://community.algolia.com/instantsearch.js/v2/getting-started.html


### Comments Powered by [utteranc.es](https://utteranc.es/)

See [github issues](https://github.com/dali-lab/build/issues) to moderate. All comments are stored in github as comments on issues. Issues are named by the page titles - so make sure they are unique.
