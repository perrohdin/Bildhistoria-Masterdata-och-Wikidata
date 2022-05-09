# Bakgrund
Repository för skolenheter i Sverige. Eftersom [Bildhistoria](https://blogg.bildhistoria.se/) fokuserar på tiden 1850-1970 ungefär, är historiska skolenheter viktgt även om de inte finns kvar idag. Tanken är att användare kan koppla personer till en skola/examenstyps/tidsintervall för att beskriva indviders utbildning. [Bildhistoria](https://blogg.bildhistoria.se/) skall ha alla Svenska skolor och detta repository är för att 

* [ ] inventera vad som finns i Wikidata https://github.com/salgo60/SvenskaSkolor/issues/2
* [ ] fylla på wikidata med skolenheter/utbildningsanastalter som ännu inte finns i wikidata. 
  * [ ] hitta bra källor https://github.com/salgo60/SvenskaSkolor/issues/1

Tanken är att förpopulera [Bildhistoria](https://blogg.bildhistoria.se/) med så många skolor det går för att bespara användare inmatninsarbete och undvika dubletter (pch kopling till Wikidata för att uppdatera info vid behov), men vi kommer även att tillåta användare att skapa nya skolenheter som kanske sedan i framtiden kan skapas i wikidata. 

Bakgrundsartiklar om svenska skolväsendet: 

* https://lararnashistoria.se/
* https://www.scb.se/hitta-statistik/statistik-efter-amne/utbildning-och-forskning/befolkningens-utbildning/historisk-statistik-om-utbildning/

Vi önskar se alla typer av lägre och högre utbildningsformer (småskola, folkskola, realskola, läroverk, gymnasier, universitet, folkhögskolor, studieförbund)

## Önskade egenskaper för skola

* Wikidata ID	
* Typ av skola (enl UNESCO's klassificering)	
* Namn1	
* Namn2	
* Namn3	
* Grundades (datum)
* Grundades av - koppling till person	
* En eller flera platser för verksamhet + tidsintervall (I BH använder vi lantmäteriets Ortsnamn för platser)	
* Eventuella bilder på utbildningsanstaltens byggnader eller interör	
* Kommentar
* Avvecklades/Upphörde (Datum)
* Omvandlades till (wikidata ID + namn på den eventuella skolan som skolan omvandlades till)

## Svenska skolor i Wikipedia/Wikidata

* [Lista över läroverk och realskolor i Sverige](https://sv.wikipedia.org/wiki/Lista_%C3%B6ver_l%C3%A4roverk_och_realskolor_i_Sverige) 
   * --> SPARQL instance av läroverk [Q10572388](https://www.wikidata.org/wiki/Q10572388) / realskola [Q667471](https://www.wikidata.org/wiki/Q667471) / folkhögskola [Q170087](https://www.wikidata.org/wiki/Q170087) / skola [Q3914](https://www.wikidata.org/wiki/Q3914)
      * [SPARQL](https://w.wiki/58nT) / [koppling sv:Wikipedia](https://w.wiki/58nb) / [karta](https://w.wiki/58nj) / [bild](https://w.wiki/58nm) / [saknar bild](https://w.wiki/58ni)
* [Lista över tekniska läroverk och gymnasier i Sverige](https://sv.m.wikipedia.org/wiki/Lista_%C3%B6ver_tekniska_l%C3%A4roverk_och_gymnasier_i_Sverige)
* [Lista över folkhögskolor i Sverige](https://sv.wikipedia.org/wiki/Lista_%C3%B6ver_folkh%C3%B6gskolor_i_Sverige)
* [Kategori:Listor_med_anknytning_till_utbildning](https://sv.wikipedia.org/wiki/Kategori:Listor_med_anknytning_till_utbildning)

## Listor på skolor utanför Wikivärlden
* http://www.tam-arkiv.se/arkivet borde kanske ha listor på skolor eftersom de är arkivbildare för många av lärarfacken
* [Datastory school-map-sweden](https://www.datastory.org/sv/services/school-map-sweden)
* [Skoladresser från skolenhetsregistret](https://www.skolverket.se/skolutveckling/statistik/skoladresser-fran-skolenhetsregistret)
* Kulturnav [Svenska skolor - skolenhetsregistret (SCB)](https://kulturnav.org/566244ce-12e7-430c-a00c-005edda27564) läst 2020-02-13
   * digitaltmuseum [sökning topic skolor](https://digitaltmuseum.se/search/?aq=topic%3A%22Skolor%22) --> 1,644 results [skola](https://digitaltmuseum.se/search/?aq=topic%3A%22Skola%22) --> 12,996 results


## Mer info
* [Bildhistoria på FB](https://www.facebook.com/Bildhistoria-101067058804043/)
* [Telegram grupp](https://t.me/joinchat/FgDj6BTRqdKkYZaCqOB_FA) där det pratas Wikidata då och då
* [frågade på Wikipedia Bybrunnen](https://sv.wikipedia.org/wiki/Wikipedia:Bybrunnen#Bildhistoria_-_skolor_i_Sverige)

<img width="300" alt="image" src="https://user-images.githubusercontent.com/14206509/167285159-0be86c17-8efc-4809-ae38-4703a16520bd.png">

* frågade på [FB Bygdeband](https://www.facebook.com/Bygdeband/posts/10158061895557315)
  * test söka "[skola på www.hembygd.se](https://www.hembygd.se/shf/utforska-platsen?searchTerm=skola&redirect=map&showInfo=true&detailedSearch=false&showSearch=true)" > 13528 träff [begränsar till plats ](https://www.hembygd.se/shf/utforska-platsen?searchTerm=skola&redirect=map&showInfo=true&detailedSearch=false&showSearch=true)--> 1912

<img width="300" alt="image" src="https://user-images.githubusercontent.com/14206509/167285284-073e3d97-eb9e-4159-96af-e659b4034617.png">


* [Category:Educational_institutions_in_Sweden](https://commons.wikimedia.org/wiki/Category:Educational_institutions_in_Sweden)

## Misc ##

