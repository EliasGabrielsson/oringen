# Kartbaserad information Oringen 2017
Detta git repo har skapats i syfte att på ett GIS baserat sätt sammanställa information.
Det finns många beroenden i projektet som är avhängt fysisk position. Tex. Hur långa kablar behöver dras?
Vart ska vatten finnas? Vart kommer deltagare finnas?

Syftet med informationen här är att stödja detta beslutsfattande med ett grafiskt verktyg. (GIS)
Informationen hanteras mha. GIT vilket är ett versionshanterings verktyg vilket möjliggör sammarbete med samma filer på ett smartare sätt än tex. Dropbox motsv. *Filerna går dock att "laddas ner" på vanligt sätt.*

För en introduktion för att komma igång med git vilket kräver lite dator- / system-vana. [Kom igång guide](https://try.github.io/levels/1/challenges/1)

## Kom igång guide

1. Ladda ner och installera programvaran [Mapper](http://www.openorienteering.org/apps/mapper/)
2. Hämta kartinformationen, <br>
a) Hämta .zip fil mha. gröna knappen eller [klicka här](https://github.com/EliasGabrielsson/oringen/archive/master.zip) <br>
b) Använd git kör: `git clone https://github.com/EliasGabrielsson/oringen.git`
3. Öppna Mapper, välj önskad arena tex. `Map_Arena_Boda`.

## Filer
Informationen är främst uppdelad i ett antal kartfiler (`.ocd`) där varje del kan ses som ett lager.
När en kartfil är öppnad kan andra kartfiler (lager) läggs till för visning tillsammans. Observera att endast den ursprungligt öppnade kartfilen kan redigeras.

För att visa flera ytterligare lager:
1. Öppna template menyn: `Template -> Template Setup Window`, den bör komma upp nere i högra hörnet.
2. Kryssa i intressanta lager. Justera transparanthet och vilket lager som ligger överst.
3. [Lägg till nya lager (filer) genom att trycka på pluset `+` följt av `open`. Välj kartfil]

### Typer:

#### Map_Grundkarta_Namn.ocd
Orienteringskarta över tävlingsområdet.

#### Map_Bakgrund_Namn.ocd
Förenklad grundkarta i syfte att ge bra bakgrund över arenorna. <br> Beskuren att endast avse arena området.

#### Map_Arena_Namn.ocd
Huvudkarta för placering av materiel och funktioner. <br>
Kompletera med template: `Map_Bakgrund` för bakgrund.

#### Map_Network_Namn.ocd
Karta för att visa kabeldragning av nätverksutrustning.

#### [Funktionsnummer.md](../Funktionsnummer.md)
Översättnings lista för alla nummer på arena kartorna. <br>
(Skriven med [Markdown](http://www.markdowntutorial.com/), ett simpelt sätt att formatera text)

#### README.md
Den här filen du läser nu.

#### Skiss/
Mapp för skisser gjorda på tex. fysiskt papper.
(Importeras som extra lager, kräver oftast mer justering.)

#### Export/
Map för färdig exporterade .PDF filer för utskrift och visning

## Export:
Skriv ut PDF. Vid utskrift kryssa i `Show templates`, detta gör att alla lager kommer med. <br>
Om rutan ej syns gå då in i `Template -> Template Setup Window` och markera ett lager därefter pröva igen.


## Karta i mobilen
Mapper finns även för Android telefoner. Då kan mobilens GPS användas för att tex. stega på kartan. För att enkelt komma igång:

1. Ladda ner Mapper `.APK`-filen från mobilen, installera.
2. Skicka kartorna till mobilen, förslagsvis använd Google Drive elle Dropbox för mobilen.
3. Öppna appen, öppna kartor.
