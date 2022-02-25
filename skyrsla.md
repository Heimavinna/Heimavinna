#### Jónas Orri Daníelsson, Snorri Már Gunnarsson, Stefán Örn Lárusson     VEFÞ2VÞ05DU     Tölvubraut      Tækniskólinn <br>
[Linkur á kóða repo](https://github.com/Heimavinna/kodi) <br>
[Linkur á vefsíðu](https://heimavinna.pythonanywhere.com/) <br>

## Virkni <br>

III. Verkefnalýsing <br> Heimavinnusíðan er ætluð til að frammhaldskólanemendur geti skráð niður heimavinnuna sína á þæginlegann og einfaldan máta. Inna býður ekki uppá það að skrá niður heimavinnu og þess vegna ákváðum við að gera heimasíðu til þess að gera nemendum kleift að halda betur utan um heimanámið sitt. Heimavinna skráist niður á notanda og er aðgengileg á hvaða tæki sem notandinn ákveður að nota. <br>

IV. Lýsing verkefnis<br> Við notuðum Flask sem framework. Við settum upp flask og virtual engine í vs code. Síðan byrjuðum við á því að vinna routes, gerðum einföld hello world routes til þess að sjá til þess að allt myndi virka. Eftir að routin voru komin þá var komið að því að gera nav bar og drop down listann. Fyrir dropdown listann var notað efni frá [W3 schools](https://www.w3schools.com/howto/howto_css_dropdown.asp). Þá var komið að aðal dæminu og það er heimavinnuskráningin sjálf. Við notuðum góða [grein](https://morioh.com/p/0211e637f4db) sem hjálpaði mjög mikið að koma síðunni í gang. Eftir að pússla þessu við það sem við höfðum áður verið komnir með þá fórum við að pæla í database og hvernig við ættum að vista Usera, Password og heimavinnuna. Við kynntum okkur SQLAlchemy og settum það upp.
 <br>

V. Þarfagreining og hönnunarlýsing <br>
[Wiki á hönnun](https://github.com/Heimavinna/Heimavinna/wiki/User-Cases-&-Scenarios) <br>
[Hönnunarpælingar](https://github.com/Heimavinna/Heimavinna/wiki/Wireframe)

VI. Gagnagrunnshönnun og lýsing gagna í vefkerfi. <br>
Við notuðum SQLAlchemy fyrir vefsíðuna okkar. 
Við stilltum upp tvem töflum í Flask, eina fyrir notanda og hina fyrir 'todo'. Þar var geymt t.d. password og username

VII. Skjámyndir af vefappi <br>
* [Register](https://github.com/Heimavinna/Heimavinna/blob/main/HomePageMyndir/Register.png?raw=true)
* [Login](https://github.com/Heimavinna/Heimavinna/blob/main/HomePageMyndir/Login.png?raw=true)
* [Home Page](https://github.com/Heimavinna/Heimavinna/blob/main/HomePageMyndir/HomePage.png?raw=true)
* [Drop Down](https://github.com/Heimavinna/Heimavinna/blob/main/HomePageMyndir/DropDown.png?raw=true)

VIII. Tengill á youtube með stutta skjámyndsupptöku af notkun vefapps, sjá https://screencast-o-matic.com/ <br>
https://youtu.be/VCfbfWR84Lw

IX. Stillingar og leiðbeiningar fyrir uppsetningu kerfis. <br>


X. Heimildir. <br>
[Todo](https://morioh.com/p/0211e637f4db)
[Dropdown](https://www.w3schools.com/howto/howto_css_dropdown.asp)


XI. Vinnuflæði, verkaskipting og verkþættir (e. Github projects). <br>
[Projects](https://github.com/Heimavinna/Heimavinna/projects/1) <br>
Við vorum auðvitað með github 'kodi' repository'ið þar sem að við geymdum verkefnið.
Við tókum alltaf svona góða fundi í þeim tímum sem við hittumst og unnum út frá þeim.
Það var mjög þæginlegt og gerði það að verkum að manni fannst maður alltaf vera á sömu síðu.
Annars fóru mestu framfarinrar fram heima þegar og var greinilegt að við vorum dugleigi
í að 'pusha' og 'pulla'. Það kom aldrei upp neitt stórt vandamál
varðandi 'conflicts'.

Það mætti segja að við skiptum þessu í tvo hópa. Snorri sá aðalega um CSS stýlun og todo skráninguna á
meðan Stefán og Jónas vorum í bakendanum. Þetta voru ekkert strangar skiptingar og fengu allir
að dífa tánum ofan í allt. 

Þessi 'github projects' komu sér mjög vel þar sem að það gerði það að verkum að maður sá 
mikið betur framfarirnar. Maður gat alveg kíkt þangað og séð hvað var eftir og vann maður þá
bara á því og það var alveg yndislegt að geta sett hluti yfir í done.



XII. Samantekt. Hvernig tókst til. Hver væru næstu skref, ókláruð virkni, endurbætur osfrv. <br>
Verkefnið gekk vel hjá okkur. Við byrjuðum á því að vera með mikinn fókus á Javascript og settum upp síðu með því. En við komumst að því að það yrði flókið að nota það og það myndi vera mun einfaldara að nota Flask þannig að við ákváðum að skipta yfir í Flask. Eftir að við skiptum yfir byrjaði allt að rúlla mjög vel. Við byrjuðum að sjá miklar framfarir á síðunni og breytingar sem við náðum ekki að gera með javascript náðum við að gera með flask. Næstu skref hefðu verið að bæta við betri notenda stillingum, eins og að leyfa notenda að vera með mynd, breyta lykilorði og ef við hefðum meiri tíma væri hægt að bæta við einhverjum fleiri snjöllum featurum.
