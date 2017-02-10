---
ID: 154
post_title: 'Referansar  og  kjelder,  praktisk  script&#8230;'
author: Guttorm
post_date: 2007-01-25 20:15:00
post_excerpt: ""
layout: post
permalink: >
  http://guttorm.hveem.no/blogg/2007/01/referansar-og-kjelder-praktisk-script/
published: true
blogger_blog:
  - guttorm1979.blogspot.com
blogger_author:
  - >
    Guttorm
    Hveemhttp://www.blogger.com/profile/16825705109380499953noreply@blogger.com
blogger_permalink:
  - >
    /2007/01/referansar-og-kjelder-praktisk-script.html
tweetbackscheck:
  - "1309859082"
shorturls:
  - 'a:7:{s:9:"permalink";s:76:"http://guttorm.hveem.no/blogg/2007/01/referansar-og-kjelder-praktisk-script/";s:7:"tinyurl";s:25:"http://tinyurl.com/avblcf";s:4:"isgd";s:17:"http://is.gd/hwEI";s:5:"bitly";s:18:"http://bit.ly/cwys";s:5:"snipr";s:22:"http://snipr.com/avnpo";s:5:"snurl";s:22:"http://snurl.com/avnpo";s:7:"snipurl";s:24:"http://snipurl.com/avnpo";}'
twittercomments:
  - 'a:0:{}'
tweetcount:
  - "0"
tmac_last_id:
  - ""
dsq_thread_id:
  - "885980091"
post_views_count:
  - "799"
---
Som du kanskje har sett nede på sidene mine i bloggen er det ferdig referanse klar til bruk (Trur det var Harvard-stil eg laga). Det er ikkje verre enn å leggje inn eit lite script  i malen din, scriptet ser omtrent slik ut (NB, <strong>[</strong> må byttast med <strong><</strong> og <strong>]</strong> må byttast med <strong>></strong>):<br /><br /><blockquote>[p align="center"]Referer til denne sida (Klipp og lim):[br /]<br />[script language="JavaScript" type="text/javascript"]<br />[!--<br />document.write (document.title)<br />// --][/script]<br />[Internett] NO: Adresse: [u]<br />[script language="JavaScript" type="text/javascript"]<br />[!--<br />document.write (location.href)<br />// --][/script]<br />[/u] Lest:<br />[script]<br />var mydate=new Date()<br />var year=mydate.getYear()<br />if (year [ 1000)<br />year+=1900<br />var day=mydate.getDay()<br />var month=mydate.getMonth()<br />var montharray=new<br />Array("Januar","Februar","Mars","April","Mai","Juni","Juli","August","September","Oktober","November","Desember")<br />var daym=mydate.getDate()<br />document.write(""+daym+" "+montharray[month]+" "+year+"")<br />               [/script]</blockquote><br /><br />Det som vert vist er:<br />Tittel på sida  [Internett] NO: Adresse: http://server.no/mappe/fil.hm  Lest: 25 Januar 2007<br /><br />Du finn ein ferdig versjon på <a href="http://guttorm.hveem.no/dev/referer.txt">http://guttorm.hveem.no/dev/referer.txt</a><br />Eg lev i trua at det kanskje får nokre fleire til å leggje inn referansar på sine referanselister. Og lurer du på om noko av det du har skriv finst andre stadar på nettet kan du jo sjekka på <a href="http://copyscape.com/">http://copyscape.com/</a><br /><br /><a href="http://guttorm.hveem.no/blogg/arkiv/2005_06_01_arkiv.html">Dersom du søker i bloggen finn du nok ei post om korleis eg laga min eigen automagiske referanseknapp eg bruker i Opera.</a>