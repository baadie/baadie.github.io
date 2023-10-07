---
layout: post
title: "HTTP ACL Bypass"
date: 2023-10-07
tags: [pentest]
---

HTTP headers te gebruiken:

{% highlight ruby linenos %}
    X-Forwarded-For
    X-Forward-For
    X-Remote-IP
    X-Originating-IP
    X-Remote-Addr
    X-Client-IP
{% endhighlight %}
