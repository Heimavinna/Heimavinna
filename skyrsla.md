#### Jónas Orri Daníelsson, Snorri Már Gunnarsson, Stefán Örn Lárusson     VEFÞ2VÞ05DU     Tölvubraut      Tækniskólinn <br>
[Linkur á kóða repo](https://github.com/Heimavinna/kodi) <br>
[Linkur á vefsíðu](https://heimavinna.pythonanywhere.com/) <br>

## Virkni <br>

III. Verkefnalýsing <br> Heimavinnusíðan er ætluð til að frammhaldskólanemendur geti skráð niður heimavinnuna sína á þæginlegann og einfaldan máta. Inna býður ekki uppá það að skrá niður heimavinnu og þess vegna ákváðum við að gera heimasíðu til þess að gera nemendum kleift að halda betur utan um heimanámið sitt. Heimavinna skráist niður á notanda og er aðgengileg á hvaða tæki sem notandinn ákveður að nota. <br>

IV. Lýsing verkefnis<br> Við notuðum Flask sem framework. Við settum upp flask og virtual engine í vs code. Síðan byrjuðum við á því að vinna routes, gerðum einföld hello world routes til þess að sjá til þess að allt myndi virka. Eftir að routin voru komin þá var komið að því að gera nav bar og drop down listann. Fyrir dropdown listann var notað efni frá [W3 schools](https://www.w3schools.com/howto/howto_css_dropdown.asp). Þá var komið að aðal dæminu og það er heimavinnuskráningin sjálf. Við notuðum góða [grein](https://morioh.com/p/0211e637f4db) sem hjálpaði mjög mikið að koma síðunni í gang. Það var farið aðeins í semantic UI í þessari grein. Við kynntum okkur það og fannst það vera algjör snilld. Það virkaði mjög vel og það var frábært að geta gert css stílbreytingar án þess að þurfa að skrifa niður classa og búa til t.d grænn takka sjálfur. Það hefði verið næs að hafa kynnt sér það fyrr áður enn við vorum búnir að hanna stílinn á meirihluta vefsíðunnar. En aftur á móti var gott að læra aftur á basic css og að læra einhvað nýtt líka.
Eftir að pússla þessu við það sem við höfðum áður verið komnir með þá fórum við að pæla í database og hvernig við ættum að vista Usera, Password og heimavinnuna. Við kynntum okkur SQLAlchemy og settum það upp.
Það fór smá tími í að kynna sér hvernig SQLAlchemy virkaði, það er mjög öflugt dæmi og skemmtilegt.
Við vorum búnir að prufa aðrar database leiðir eins og Firebase og MySQL en þau virkuðu ekki. Þegar
SQLAlchemy virkaði þá fór boltinn að rúlla. Database uppsetningin var einföld og síðan var mjög gaman að
finna út leiðir til þess að setja réttu hlutina í hann og geta lesið úr honum. Það var notast við nokkur 
svakalega öflug library eins og flask_login þar sem að hægt far að ná í föll eins
og login_user, logout_user og current_user sem manni fannst virka eins og hálfgerðir
töfrar síðan voru það UserMixin og LoginManager sem einfölduðuð lífði fyrir mann líka.
Bcrypt notuðum við til þess að 'hasha' lykilorðunum og er hægt að nota það til að af rugla
lykilorð o.s.frv.
 <br>

V. Þarfagreining og hönnunarlýsing <br>
[Wiki á hönnun](https://github.com/Heimavinna/Heimavinna/wiki/User-Cases-&-Scenarios) <br>
[Hönnunarpælingar](https://github.com/Heimavinna/Heimavinna/wiki/Wireframe)

VI. Gagnagrunnshönnun og lýsing gagna í vefkerfi. <br>

Databasinn var ekkert sérlega flókinn. Við notuðum SQLAlchemy sem kemur með flask en það er mjög
öflugt og henntugt. Við notuðumst við tvær töflur User og Todo. Við tengdum þær við hvora aðra til
þess að geta tengt heimavinnu við ákveðinn notanda. Annars vorum við með hefðbundna dálka eins og username
og password en fyrir Todo databaseinn vorum við með tvo dálka, einn fyrir textan og hinn hélt utan um stöðuna á todo'inu. Lykilorðið er auðvitað sett inn í gagnagrunninn sem ruglað lykilorð en við notuðum bcrypt
libraryið fyrir það.


VII. Skjámyndir af vefappi <br>
* [Register](https://github.com/Heimavinna/Heimavinna/blob/main/HomePageMyndir/Register.png?raw=true)
* [Login](https://github.com/Heimavinna/Heimavinna/blob/main/HomePageMyndir/Login.png?raw=true)
* [Home Page](https://github.com/Heimavinna/Heimavinna/blob/main/HomePageMyndir/HomePage.png?raw=true)
* [Drop Down](https://github.com/Heimavinna/Heimavinna/blob/main/HomePageMyndir/DropDown.png?raw=true)
* [Stillingar](https://github.com/Heimavinna/Heimavinna/blob/main/HomePageMyndir/stillingar.png?raw=true)
* [Breyting](https://github.com/Heimavinna/Heimavinna/blob/main/HomePageMyndir/breyting.png?raw=true)

VIII. Tengill á youtube með stutta skjámyndsupptöku af notkun vefapps, sjá https://screencast-o-matic.com/ <br>
https://youtu.be/VCfbfWR84Lw

IX. Stillingar og leiðbeiningar fyrir uppsetningu kerfis. <br>
Setja upp Flask, virtual engine, SQLAlchemy, Flask_login og flask_bcrypt í gegnum terminal í vs code. Hýsing var í gegnum Pythonanywhere.

X. Heimildir. <br>
[Todo](https://morioh.com/p/0211e637f4db) <br>
[Dropdown](https://www.w3schools.com/howto/howto_css_dropdown.asp) <br>
Stack Overflow 


XI. Vinnuflæði, verkaskipting og verkþættir (e. Github projects). <br>
Við vorum auðvitað með github 'kodi' repository'ið þar sem að við geymdum verkefnið.
Við tókum alltaf svona góða fundi í þeim tímum sem við hittumst og unnum út frá þeim.
Það var mjög þæginlegt og gerði það að verkum að manni fannst maður alltaf vera á sömu síðu.
Annars fóru mestu framfarinrar fram heima og var greinilegt að við vorum dugleigi
í að 'pusha' og 'pulla'. Það kom aldrei upp neitt stórt vandamál
varðandi 'conflicts'.

Það mætti segja að við skiptum þessu í tvo hópa. Snorri sá aðalega um CSS stýlun og tók það að sér að
hanna todo skráninguna og láta hana virka. Á meðan Stefán og Jónas vorum í bakendanum. Jónas sá
um að búa til Login og register forminn og útfærði þau þannig að það var bara hægt að tengja þau
strax við database þegar Stefán fór í það. Jónas notaði líka smá JavaScript sem er eina JavaScript'ið
í verkefninu. Þessar verkefna skiptingar voru ekkert strangar og fengu allir að dífa tánum ofan í allt. 

[Projects](https://github.com/Heimavinna/Heimavinna/projects/1) <br>
Þessi 'github projects' komu sér mjög vel þar sem að það gerði það að verkum að maður sá 
mikið betur framfarirnar. Maður gat alveg kíkt þangað og séð hvað var eftir og vann maður þá
bara á því og það var alveg yndislegt að geta sett hluti yfir í done.



XII. Samantekt. Hvernig tókst til. Hver væru næstu skref, ókláruð virkni, endurbætur osfrv. <br>
Verkefnið gekk vel hjá okkur. Við byrjuðum á því að vera með mikinn fókus á Javascript og settum upp síðu með því. En við komumst að því að það yrði flókið að nota það og það myndi vera mun einfaldara að nota Flask þannig að við ákváðum að skipta yfir í Flask. Eftir að við skiptum yfir byrjaði allt að rúlla mjög vel. Við byrjuðum að sjá miklar framfarir á síðunni og breytingar sem við náðum ekki að gera með javascript náðum við að gera með flask. Næstu skref hefðu verið að bæta við betri notenda stillingum, eins og að leyfa notenda að vera með mynd og ef við hefðum meiri tíma væri hægt að bæta við einhverjum fleiri snjöllum featurum.
