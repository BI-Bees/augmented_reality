## Augmented Reality
#### Tim Hemmmingsen, Ørvur Guttesen og Laura Hartig

### Kontrakt
Vi fik først til opgave at finde data omkring brug af Augmented Reality(AR) inden for uddannelser, som vi så ville bruge til at lave visuel statistik. Det viste sig dog, at være meget svært at finde data vedrørende AR, da det er ret nyt. Vi fandt dog nogle datasæt omkring dødsfald og dødsårsager i hhv. Danmark og USA. Vi blev derefter enige med de I&E studerende om, at bruge det data til at analysere, hvor brug af AR inden for læge/medicin uddannelser kunne være mest effektiv. Vi vil så forsyne dem med grafer/tabeller til at illustrere det fundne data.

#
### Arbejstimer
Vi mødtes med de I&E studerende 4 gange, hvor vi diskuterede projektet, hvor langt vi var kommet og hvad vi havde planer om. Hvert møde tog cirka 30 min. Vi var henholdsvis 1,2,2,3 personer til stede ved møderne. Vi havde også kontakt med dem på Facebook. Dette var dog en meget lille mængde tid og vi føler ikke det skal medregnes, da det vil være under 30 min.

**Dette giver 4 arbejdstimer spredt ud over 3 personer.**

De gav os opgaver omkring projektet, som i starten lød på at finde hvor mange penge der bliver brugt på AR og hvor mange penge der vil blive brugt på det i fremtiden. Vi brugte 4 timer på dette uden noget held. Derefter fandt vi noget data omkring dødstilfælde, som vi alle 3 endte med at bruge omkring 2 timer på.

**Dette giver 18 arbejdstimer spredt ud over 3 personer.**

Efter vi havde fundet vores data skulle det bearbejdes, så det kunne bruges. Vi sad 2 personer og arbejdede på det i 3 timer og efterfølgende sad 1 person og arbejdede med det i 2 timer. Til slut arbejdede vi alle 3 sammen i omkring 4 timer.

**Dette giver 20 arbejdstimer spredt ud over 3 personer.**

**I alt endte vi med at have brugt 42 arbejdstimer.**

Vi vælger at tage udgangspunkt i, at vores arbejde koster 500 kr. i timen og med 42 arbejdstimer ville det i alt give 21.000 kroner.

#
### Brugerdokumentation
Alt behandlet data er frit tilgængeligt i form af grafer (PNG-filer) på vores GitHub repository(https://github.com/BI-Bees/augmented_reality). Øverst ligger selve filen vi har brugt til at lave dataene om til grafer (IPYNB-fil) og nederst ligger de ubehandlet datasæt (CSV-filer). Man kan blot klikke på de enkelte filer for at åbne dem.

#
### Datasources
Vi fandt to datasæt for hhv. USA og Danmark, hvor det er opdelt efter stater/regioner og dødsårsager.

**DK data:** http://esundhed.dk/sundhedsregistre/DAR01/Sider/Tabel.aspx?fbclid=IwAR0Yth3CyiPGHozfH1xNHuvC-RKX4qReyypnppyZonFiBNkVE6kbyocQJz0

**US data:** https://healthdata.gov/dataset/nchs-leading-causes-death-united-states/resource/cf5ffb83-363e-4292-b746-ecd1bcf58156?fbclid=IwAR24-BIXSKzOsOFahiq_JPA1Z_v1mv0ssi5nfTXHBohD5DvqkAUJUIZX_wc#{view-graph:{graphOptions:{hooks:{processOffset:{},bindEvents:{}}}},graphOptions:{hooks:{processOffset:{},bindEvents:{}}}}

#
### Teknisk dokumentation
Vi har lavet vores kode i en Jupyter notebook, som også ligger på vores GitHub repository(https://github.com/BI-Bees/augmented_reality), sammen med vores to data filer også, som er CSV-filer. Vores Jupyter notebook er bygget op i nogle få celler, hvor de øverste celler er brugt til opsætning af notebooken som bl.a. imports og hentningen af vores CSV-filer. Vi bruger et library i Python som hedder Pandas, som bliver brugt til at sortere datasættene. Derefter bruger et library kaldet Matplotlib, som vi bruger til at oprette grafer ud fra det sorteret data.

Vores datasæt er bygget op af rækker og kolonner og har samme struktur som et Pandas dataframe og er derfor lette importere. Efter vi har oprettet vores dataframes, henter vi den bestemte data ud, som vi skal bruge. Vi bruger så Pandas masking for at lave et subset af datasættene, som vi benytter til at lave de gældende grafer med Matplotlib.

Eftersom at selve notebooken ikke decideret skulle afleveres, har vi ikke lavet den særlig præsentabel. Vi har lavet én celle, som blev brugt til at lave graferne fra den danske CSV-fil og en anden celle til at lave de amerikanske.
