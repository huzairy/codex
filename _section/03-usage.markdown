---
title:  "Getting Started"
date: 2015-05-03
hashlink: usage
---

### Installation

1. Install [Jekyll](http://jekyllrb.com).
2. Download or fork [Codex](https://github.com/huzairy/codex).
3. Replace all contents in your Jekyll working directory with Codex directory content. 
4. Your're done!

### How to use Codex

1. Add or edit your post in <code>_section</code> directory.
2. The post arrangement were made through the file naming, thus the file name, <code>01-title.markdown</code>.
3. Modify the <code>_config.yml</code> file to change your Codex title.
4. You just need to edit the front matter to add/edit new post:
{% highlight c %}
---
title:  "Getting Started" // This is for the post title. Required.
date: 2015-05-03 // Not required, but just for our own record.
hashlink: usage // The hashlink for the in-page navigation. Required.
---
{% endhighlight %}