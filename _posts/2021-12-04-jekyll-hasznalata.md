---
layout: post
author: PaTa
title: "Miért éppen a Jekyll?"
pic: "/assets/images/jekyll.png"
meta: "Ha nincs saját webtárhelyed vagy épp a WordPress helyett akarsz egy gyorsabb megoldást, a Jekyll tartalomépítő rendszer neked való választás lehet. Igaz, a Jekyll nem teljesen grafikus és ismerni kell hozzá a HTML/CSS/JavaScript nyelveket alapszinten, sokkal könnyebben befolyásolhatod a weboldalad gyorsaságát. Jóllehet, többet kell tanulni, hogy valaki használhassa, de cserébe egy hatalmas előnyre tehetsz szert: Teljesen ingyenesen tudod publikálni a blogcikkeidet a Githubon keresztül."
---
<div class="promenade">
    <p>{{page.meta}}</p>
    <img src="{{page.pic}}">
</div>

<h2>A Jekyll előnyei a WordPress-szel szemben:</h2>
<p>
    Én is úgy kezdtem a weboldal építést, mint sokan mások. Feltelepítettem a Wordpresst és elkezdtem kattintgatni. Később feltelepítettem a Divi témát és még szebben nézett ki a weboldalam. Viszont alig telt el egy év és egy kellemetlen problémával szembesültem: nem tudtam megváltoztatni a logót a fejlécmenüben. És mivel nem értettem a kódoláshoz nem tudtam orvosolni a problémát.
</p>
<p>
    Hamar kiderült a számomra, hogy nem baj, ha megtanulok ezt azt a webfejlesztésről. Ezek után elkezdtem keresni azokat a megoldásokat, amik segítségével WP nélkül is boldogulok. Az alap HTML/CSS/JavaScript tudás elég ahhoz, hogy statikus weboldalakat készítsek. De mi van a blogcikkekkel. Akkoriban egy coaching praxis kiépítéséhez kellett a weboldal. Egy coach pedig nem árt, ha publikál néhány blogcikket, hiszen pont az eszéért szeretik. Na például itt tud jó szolgálatot tenni a Jekyll.
</p>

<h2>Adatbázisok helyett statikus fájlok</h2>

<p>
    A jekyll csupán minimális mennyiségű adatbázissal operál. Ez lehet nem a legprofibb, de ha nem értesz a PHP nyelvhez, a Jekyll segítségével is tudsz blogmotort építeni. Ráadásul Githubra is fel tudod tölteni a weboldaladat. Ha wordpresst vagy egyéb PHP oldalt akarnál publikálni, ahhoz már nem elég a github oldal (pontosabban nehezebb megoldani, hogy működjön is).
</p>
<p>
    Amíg a WordPress adatbázisokkal építi fel a weboldalad tartalmát, Jekyll esetében a blogcikkek statikus fájlokban van eltárolva (.md vagyis markdown formátumban). Amikor betölt az oldal, ezekből az md fájlokból csinál a rendszer html fájlokat, amik aztán betöltenek, ha egy cikknek a linkjére kattintasz. Ahhoz, hogy sablonokat lehessen használni persze kellenek adatbázis fájlok, de ezeket az úgy nevezett Liquiddel lehet kezelni. (Erről lentebb még lesz szó.)
</p>

<h2></h2>