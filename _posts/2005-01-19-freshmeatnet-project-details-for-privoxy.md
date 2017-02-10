---
ID: 89
post_title: 'freshmeat.net:  Project  details  for  Privoxy'
author: Guttorm
post_date: 2005-01-19 22:33:00
post_excerpt: ""
layout: post
permalink: >
  http://guttorm.hveem.no/blogg/2005/01/freshmeatnet-project-details-for-privoxy/
published: true
blogger_blog:
  - guttorm1979.blogspot.com
blogger_author:
  - >
    Guttorm
    Hveemhttp://www.blogger.com/profile/16825705109380499953noreply@blogger.com
blogger_permalink:
  - >
    /2005/01/freshmeatnet-project-details-for.html
tweetbackscheck:
  - "1309964969"
shorturls:
  - 'a:8:{s:9:"permalink";s:79:"http://guttorm.hveem.no/blogg/2005/01/freshmeatnet-project-details-for-privoxy/";s:7:"tinyurl";s:25:"http://tinyurl.com/cu4bzd";s:4:"isgd";s:17:"http://is.gd/gNci";s:5:"bitly";s:19:"http://bit.ly/157LS";s:5:"snipr";s:22:"http://snipr.com/ainnn";s:5:"snurl";s:22:"http://snurl.com/ainnn";s:7:"snipurl";s:24:"http://snipurl.com/ainnn";s:4:"trim";s:17:"http://tr.im/bmmi";}'
twittercomments:
  - 'a:0:{}'
tweetcount:
  - "0"
tmac_last_id:
  - ""
dsq_thread_id:
  - "613126929"
post_views_count:
  - "284"
---
<a href="http://freshmeat.net/projects/privoxy/">freshmeat.net: Project details for Privoxy </a>: "About:
<br />Privoxy is a Web proxy based on Internet Junkbuster with advanced filtering capabilities for protecting privacy, filtering Web page content, managing cookies, controlling access, and removing ads, banners, pop-ups, and other obnoxious Internet junk. Privoxy has a very flexible configuration and can be customized to suit individual needs and tastes. Privoxy is useful for both stand-alone systems and multi-user networks."
<br />---
<br />
<br />NÃ¥r eg les nettaviser er eg ikkje interessert i all reklamen som gjer at sidene tar lang tid Ã¥ lasta ned, difor har eg no testa ad munch ei viss tid, denne fjerner mesteparten av reklamen (det er forresten kjekt Ã¥ sleppa alle annonsene til t.d. vg.no). Dersom ein t.d. vil sensurera bort reklamen pÃ¥ kvinnheringen.no mÃ¥ ein tilpassa filtera sjÃ¸lv. Programmet skriv ein heil del til kildekoden fÃ¸r du fÃ¥r sjÃ¥ nettsida du har bede om. Ad muncher kostar pengar, det gjer ikkje Privoxy... Privoxy lagar til ein proxyserver pÃ¥ maskina, du stiller inn proxyserver i din nettledar (t.d. localhost:8118) og du er kvitt mykje reklame...
<br />Loggen viser: 
<br />Jan 19 21:41:58 Privoxy(01408) Request: www.dagbladet.no/an/adframe.php?bannerid=5454&n=449&what=zone:449&target=_top&nolog=true crunch!
<br />Jan 19 21:41:58 Privoxy(00548) Request: www.dagbladet.no/an/adframe.php?bannerid=5541&n=518&what=zone:518&target=_top&nolog=true crunch!
<br />Jan 19 21:41:58 Privoxy(02252) Request: gfx.dagbladet.no/g2/a-tips2.gif
<br /> Og det ligg no litt mindre i kjeldekoda: 
<br /><head><script>function PrivoxyWindowOpen(){return(null);}</script>
<br />...
<br /></body>
<br />
<br /><script>function PrivoxyWindowOpen(a, b, c){return(window.open(a, b, c));}</script></html>
<br />
<br />Men det kan jo henda at det kan vera lurt Ã¥ "stÃ¸tta" ulike reklamefinansierte nettsider ved Ã¥ sjÃ¥ reklamen...