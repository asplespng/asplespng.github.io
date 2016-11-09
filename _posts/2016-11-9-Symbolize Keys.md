---
layout: post
title: You're up and running!
tags: Ruby On Rails
---

Next you can update your site name, avatar and other options using the _config.yml file in the root of your repository (shown below).

![_config.yml]({{ site.baseurl }}/images/config.png)

Discovered a useful function in Ruby on Rails today.

```Ruby
params = {"key1"=>"value1", "key2"=>"value2"}
params.symbolize_keys
```
Result:
```Ruby
{:key1=>"value1", :key2=>"value2"} 
```

I find this function useful when using options hashes passed through[Redis](http://redis.io/).