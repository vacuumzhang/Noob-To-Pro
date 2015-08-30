---
layout: post
title: HTML
tags: HTML DISQUS
categories: HTML DISQUS
---

<div class="toc"></div>

## DISQUS setting


~~~javascript

function disqus(){
    /* * * CONFIGURATION VARIABLES * * */
    var disqus_shortname = 'vacuumzhang';

    var dsq = document.createElement('script'); dsq.type = 'text/javascript'; dsq.async = true;
    dsq.src = '//' + disqus_shortname + '.disqus.com/embed.js';
    document.getElementsByTagName("script")[0].parentNode.appendChild(dsq);
}

~~~