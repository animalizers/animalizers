---
layout: post
title:  "Dark Reader custom dynamic profile fo e-hentai.net"
categories: stylesheet
---

Usage: Copy code below or <a href="https://github.com/animalizers/anii/blob/master/Dark%20Reader%20custom%20preset/e-hentai.net.css" target="_blank">view in github</a>
{% highlight css %}
================================

e-hentai.org

CSS
/*General preset for text color and border*/
*{
    color: rgb(192,192,198) !important;
    border-color: #4f5b6b !important;
}
/*end General preset*/
/*Gallery stats setting*/
.stuffbox{
    background-color: #1b3035 !important;
    /*background-color: #2b2b2b !important;*/
}
/*end gallery stats*/
/*Main page and content*/
body{
    background-color: #161716 !important;
    color: rgb(170, 170, 170) !important;
    border: #3f3f3f !important;
}
div.gm, #gleft, #gd2, #gright, #gmid, #gdt{
    background-color: #1b3035 !important;
    /*background-color: #2b2b2b !important;*/
}
div.idi{
    border: 1px solid #4f5b6b !important;
}
div.ido{
    background-color: #1b3035 !important;
    /*background-color: #2b2b2b !important;*/
    border: 1px solid #4f5b6b !important;
}
div.sni{
    background-color: #1b3035 !important;
    /*background-color: #2b2b2b !important;*/
}
/*Table of content*/
table.itg, table.ptdd td, table.ptds td{
    border: 1px solid #4f5b6b !important;
}
table.itg > tbody > tr:nth-child(2n+1),
table.itg > tbody > tr:nth-child(2n+1) .glthumb,
table.itg > tbody > tr:nth-child(2n+1) .glcut {
    background-image: initial;
    background-color: #2b2b2b !important;
    border: 1px solid #4f5b6b !important;
}
table.itg > tbody > tr:nth-child(2n+2),
table.itg > tbody > tr:nth-child(2n+2) .glthumb,
table.itg > tbody > tr:nth-child(2n+2) .glcut {
    background-image: initial;
    background-color: #1d1d1d !important;
    border: 1px solid #4f5b6b !important;
}
/*Login Screen*/
.d{
    background-color: #1b3035 !important;
    /*background-color: #2b2b2b !important;*/
}
/*end Main page and content*/
================================
{% endhighlight %}
Visit e-hentai.org

Open Dark Reader extension

Click dev tools (go to setting > dev tools, if you're on the new UI)

Paste the code at the very bottom of the editor

Click save/apply