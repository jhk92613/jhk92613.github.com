---
layout: post
title: "레알마드리드 선수 영상"
category: [엘 클라시코 더비]
tags: []
---

* [크리스티아누 호날두](https://youtu.be/dRggqs8Gq1A)

* [가레스 베일](https://www.youtube.com/watch?v=2GF9f-apJ1c)

<iframe width="560" height="315" src="//www.youtube.com/watch?v=2GF9f-apJ1c" frameborder="0"> </iframe>

Video embeds are responsive and scale with the width of the main content block with the help of [FitVids](http://fitvidsjs.com/).

Not sure if this only effects Kramdown or if it's an issue with Markdown in general. But adding YouTube video embeds causes errors when building your Jekyll site. To fix add a space between the `<iframe>` tags and remove `allowfullscreen`. Example below:



{% highlight html %}
<iframe width="560" height="315" src="//www.youtube.com/watch?v=2GF9f-apJ1c" frameborder="0"> </iframe>
{% endhighlight %}


