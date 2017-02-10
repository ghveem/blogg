---
ID: 366
post_title: 'WordPress  på  eigen  server  med  OpenId'
author: Guttorm
post_date: 2009-01-11 19:14:20
post_excerpt: ""
layout: post
permalink: >
  http://guttorm.hveem.no/blogg/2009/01/wordpress-pa-eigen-server-med-openid/
published: true
lightboxoff:
  - 'false'
podPressPostSpecific:
  - 'a:6:{s:15:"itunes:subtitle";s:15:"##PostExcerpt##";s:14:"itunes:summary";s:15:"##PostExcerpt##";s:15:"itunes:keywords";s:17:"##WordPressCats##";s:13:"itunes:author";s:10:"##Global##";s:15:"itunes:explicit";s:7:"Default";s:12:"itunes:block";s:7:"Default";}'
tweetbackscheck:
  - "1309587781"
shorturls:
  - 'a:8:{s:9:"permalink";s:75:"http://guttorm.hveem.no/blogg/2009/01/wordpress-pa-eigen-server-med-openid/";s:7:"tinyurl";s:25:"http://tinyurl.com/77x48e";s:4:"isgd";s:17:"http://is.gd/gFLs";s:5:"bitly";s:18:"http://bit.ly/BTcf";s:5:"snipr";s:22:"http://snipr.com/ago4q";s:5:"snurl";s:22:"http://snurl.com/ago4q";s:7:"snipurl";s:24:"http://snipurl.com/ago4q";s:4:"trim";s:17:"http://tr.im/b8k0";}'
twittercomments:
  - 'a:0:{}'
tweetcount:
  - "0"
tmac_last_id:
  - "88260845229965312"
dsq_thread_id:
  - "789543640"
post_views_count:
  - "675"
---
Nokre har kanskje merka at ikonet føre kommentarane mine rundt om har forandra seg, det heng saman med at eg har lagt inn <a href="http://no.wikipedia.org/wiki/OpenID">OpenId</a> her på bloggen. Kort fortalt gjer OpenId at eg kan bli identifisert på andre bloggar og nettsider. Tidlegare brukte eg Blogger for å stadfesta identiteten min.

Slik kan det gjerast:

1. Oppretter brukarkonto på http://www.myopenid.com/
2. Knytter guttorm.hveem.no/blogg/ til myopenid.com
3. Legg inn kode i malen på wordpress

&lt;link rel="openid.server" href="http://www.myopenid.com/server" /&gt;
&lt;link rel="openid.delegate" href="http://guttorm.myopenid.com/" /&gt;

Rimeleg enkelt og veldig praktisk.

Site 		Persona 	Last Signin 	 Approvals
https://www.blogger.com/ Guttorm 	8 minutes ago	4
http://www.blogger.com/  Guttorm 	13 minutes ago	1