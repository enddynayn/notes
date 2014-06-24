---
layout: post
title:  "Race, Rescue, God"
date:   2014-06-23 14:01:36
categories: jekyll update
---

- Race Condition
- Rescue
- God Object

Rescueing Exception

Basic outline: 
{% highlight ruby %}
begin

rescue

end
{% endhighlight %}

If we are inside a method and we want to rescue some exception we do not need to use begin.

{% highlight ruby %}
def method_name
  call_to_api
rescue
  puts 'This line will be called if call to api throws an error'
end

{% endhighlight %}

Check out the [Jekyll docs][jekyll] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll's GitHub repo][jekyll-gh].

[jekyll-gh]: https://github.com/jekyll/jekyll
[jekyll]:    http://jekyllrb.com
