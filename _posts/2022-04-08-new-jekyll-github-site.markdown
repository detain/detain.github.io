---
title: The new Jekyll GitHub pages site.
layout: post
date: '2022-04-08 05:26:09'
categories:
- jekyll
- update
---

You’ll find this post in your `_posts` directory. Go ahead and edit it and re-build the site to see your changes. You can rebuild the site in many different ways, but the most common way is to run `jekyll serve`, which launches a web server and auto-regenerates your site when a file is updated.

To add new posts, simply add a file in the `_posts` directory that follows the convention `YYYY-MM-DD-name-of-post.ext` and includes the necessary front matter. Take a look at the source for this post to get an idea about how it works.

Jekyll also offers powerful support for code snippets:

{% highlight bash %}
cd /home/sites/detain.github.io
bundle update
bundle exec jekyll serve -H 192.64.80.218
{% endhighlight %}

{% highlight php %}
foreach ($GLOBALS['modules'] as $module => $settings) {
	if (mb_substr($order, 0, mb_strlen($module)) == $module) {
		$service = (int)mb_substr($order, mb_strlen($module));
{% endhighlight %}

Check out the [Jekyll docs][jekyll-docs] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll Talk][jekyll-talk].

[jekyll-docs]: https://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/
