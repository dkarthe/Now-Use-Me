---
layout: page
title: About
permalink: /about/
published: false
---

<div class="page" markdown="1">

{% capture page_subtitle %}
<img
    class="me"
    alt="{{ author.name }}"
    src="{{ site.author.photo | relative_url }}"
    srcset="{{ site.author.photo2x | relative_url }} 2x"
/>
{% endcapture %}

{% include page/title.html title=page.title subtitle=page_subtitle %}

## Now Use ME

# My name is KD and I’m the author of this blog.

I write things I have tried. It takes a reasonable amount of time to research, test, and test again on other platforms. Writing a tech article which deals with coding isn’t easy. It involves a lot of hard work.




</div>
