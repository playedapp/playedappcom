# Spellogg

"Untappd for boardgames"

## Grundidé
Användare checkar in speltillfälle och:
* Lägger till vilket spel och ev. vilka expansioner
* Laddar upp/tar bild(er)
* Taggar ev. andra användare (dessa notifieras och behöver godkänna att de syns i incheckningen)
* Sätter ev. betyg på spelet (ska kunna sättas av varje taggad deltagare)
* Anger metadata såsom speltid, antal spelare, poäng

Om man taggas i en incheckning ska man kunna addera den till sitt flöde (publicera, reposta eller hur det nu blir).

Man ska också kunna komplettera metadata (redigera? kanske senare) och lägga till fler bilder. Man ska kunna välja om bilderna syns i originalskaparens feed eller endast i ens egna.

Det finns även en detaljvy för spel, denna har:
* data från BGG
* bilder från incheckningar (privacy?)
* ev. brädspelspriser
* möjlighet för användaren att spara spelet i en "wishlist" (gärna med kommentar, "kolla review", "köp beg" etc.)
* statistik
  * antal sessioner
  * snittspeltid (möjlighet att filtrera på antal spelare)
  * topplistor
  * grafer

### Monetization
1. Premium membership m. tillgång till mer statistik (hur ofta man i snitt spelar, med vilka, mest spelade spel, kategori med högst snittbetyg osv) och, i sann Kickstarter-anda, att man hamnar i credits. Mer?
2. Samarbeten med utgivare som vill köra lanseringskampanjer/Kickstarters etc.
3. Möjlighet för konvent/butiker/etc att skapa upp sessioner i förväg som folk kan anmäla sig till. T.ex. Alphaspel ska ha en helg där det kommer spelas en massa. Då kan de i förväg skapa upp ett evenemang, fylla det med slots/incheckningar ("Alphaspel has scheduled a game of *Trickerion* for this saturday @ 1 PM. 2/4 chairs available. Join?". Vi kan också se till att evenemanget syns för fler än Alphaspels följare.

### Frågor
* Vad ska vi ha för betygsystem? 1-10 som BGG så att avg. rating från BGG och vårt matchar? 0,5–5 skulle också funka att matcha mot BGG.
* Hur ska vi bygga? Som en webbapp eller som en app med webbteknologi? v1 som webbapp p.g.a. minst friktion?

## Skisser

https://www.dropbox.com/s/9ihypfz3ps8dcb3/Flow.png

## BGG API

https://boardgamegeek.com/wiki/page/BGG_XML_API2

## Övriga idéer

Dessa ingår antagligen inte i en MVP…

* I förtid lägga upp ett speltillfälle, i syfte att hitta andra som vill spela det.
* Köp och sälj med fokus på "nära mig"/"nära [plats X]"
