# colee
1. félév HTML beadandó kész weboldala

Készítette: Hegyi Levente
URL: https://mtlevi70.github.io/colee/bemutatas.html

A weboldalamat Co Lee magyar rapperől készítettem. Célom az volt, hogy egyrészről megismertesse a laikussal a zenészt, másrészről aki már ismeri, kicsit mélyebb betekintést nyerhessen Kolos személyébe.

JavaScript kódok:
	- mindegyik oldalon a hamburgermenü
	- index.html-en az idézetek váltakozása és a zeneajánló
	-Működésük:
		- Hamburgermenü: célja a telefonos illetve tabletes nézetben a menük felhasználóbarátabb megjelenítése. Létrehoztam egy nav-ot a navigációs menükkel, illetve egy x gombot, amiket elrejtettem. A függvény hívásakor (amikor rákattintok a hamburgermenüre) elrejti a hamburgermenü ikont, megjeleníti az x ikont es a navigációs menüt. az x gomb megnyomásánál visszaáll minden az eredeti helyzetére.
		- Idézetek: mindegyik idézetet position: absolute-tal egymásra helyeztem. opacity-je mindegyiknek 0. a függvény hívásakor (amikor betölt az oldal) az elsőt megjeleníti, majd lejátszódik az eltűnési animáció, és megjelenik a következő, és így tovább. 
első idézetnél az utolsót tűnteti el.
		- Spotify zeneajánló: a Spotify embbed kódját bárki felhasználhatja. Egymásra raktam position: absolute-tal és elrejtem őket. Egy random generátor szerint az adott indexű embbed-et megjelenítem.

Mindenhol egységes Google Fontsot használok:https://fonts.google.com/specimen/Oswald

A JQuery errorok a radiokat és checkboxokat szétválasztotta, ezért chatgpt-től kértem segítséget, hogy hogy kell az errorokat formázni.
A hamburger menüt számos forrásból ihlettem, chatgpt-től is kértem segítséget, de csak a megértés végett. A végső (mostani) verziója már saját (épp megtanult) tudás alapján készült


Források:
Képeket interjúk blogjairól szedtem, illetve Google Images, Co Lee-ra rákeresve.
A bemutatás.html szövegi felépítése chatGPT, hiteles információkkal saját tudásomból, illetve Spotify-ról töltöttem fel.
	Interjúk:
		https://musicbackstage.hu/hu/interju/2023/01/12/a-cirkuszban-mindenki-maga-donti-el-mikent-lep-be-es-mikent-tavozik-interju-co-lee-val
		https://hajogyar.hu/hirek/debut-co-lee-a-program-lemezpremier-interju
		https://keretblog.hu/egy-melankolikus-enresz-legjobb-teljesitmenye-co-lee-interju/
		https://recorder.blog.hu/2024/02/25/_nekem_masfajta_nehezeim_vannak_co_lee-interju
		https://hvg.hu/elet/20241005_co-lee-fotok-akvarium

Ui.: a Google DevToolsban hibát ír ki a Spotify embbedekre,de ettől függetlenül tökéletesen működnek.
