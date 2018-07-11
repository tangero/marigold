---
ID: 684
post_title: 'WAP help wanted&#8230; safra, jak předat slova s&nbsp;diakritikou v&nbsp;URL ve wapu?'
author: Patrick Zandl
post_excerpt: ""
layout: post
permalink: >
  https://www.marigold.cz/item/wap-help-wanted-safra-jak-predat-slova-s-diakritikou-v-url-ve-wapu
published: true
post_date: 2003-11-23 08:27:00
---
<P>Včera jsem měl volnou chvilku a pustil jsem se do zprovoznění vyhledávání hotspotů ve WAPu. Myslel jsem si, že to bude brnkačka na pár minut, jenže došlo k nepříjemnému zákusu. Ve WAPu jsem něco náročnějšího dělal naposledy před čtyřmi lety, od té doby se toho dost z hlavy vykouřilo. </P>
<P><STRONG>Problém je následující</STRONG>: chci dát seznam měst, kde jsou registrované hotspoty. Uživatel klikne na město ze seznamu a přenese se na výpis hotspotů v danném městě. Za tím účelem předávám v URL jako parametr jméno toho města. Vše funguje v pořádku v případě, že město nemá diakritiku, takže Brno se vyhledá bez problémů. <STRONG>Města s diakritikou hlásí chybně formátované URL</STRONG> - České Budějovice neprojdou. </P>
<P>Jenže co s tím, napadá někoho něco? Konstrukce, kterou používám, je následující:</P>
<P>&lt;a href="wapspot.html?mesto=Čeladná"&gt;Čeladná&lt;/a&gt;</P>
<P>zkoušel jsem použít i výběr přes <EM>OPTION - SELECT</EM> zápis a také to nefunguje. Nenapadá vás z hlavy něco? Já se jdu podívat po nějaké moudré literatuře, ale z internetu toho o wapu mnoho zmizelo, kromě jiného <STRONG>expirovala i doména wapserver.cz</STRONG>, takže tutorialy v češtině jsou v trapu... pište email nebo komentář, pokud vás něco napadne dříve, než mne.</P>