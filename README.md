R Workshop 30 Jahre Geoökologie, 12.11.2022

#### Vorbereitung

Beste [Anleitung zum Installieren](https://bookdown.org/brry/course/installieren.html#installieren) von R und RStudio

Benötigte Pakete installieren:
``` r
if(!requireNamespace("pacman", quietly=TRUE)) install.packages("pacman")
pacman::p_load("sf", "leaflet", "leaflet.extras", "osmdata")
```
Linux Nutzer? Hinweise zum [Installieren des sf Pakets](https://r-spatial.github.io/sf/#linux) unter Linux


#### Referenzen

Interaktive Karten mit R:

- Flurstücke: [Karte](https://brry.github.io/sewekow), [Quelle](https://github.com/brry/sewekow/blob/main/karte.R)
- Laufstrecken: [Karte](https://brry.github.io/runway), [Quelle](https://github.com/brry/runway/blob/master/berryMaps.R), [Shiny App](https://brry.shinyapps.io/runway)

Kataster [Shapefiles](https://data.geobasis-bb.de/geobasis/daten/alkis/Vektordaten/shape/) Brandenburg

[sf Website](https://r-spatial.github.io/sf/)

Kurze [R Einführung](https://github.com/brry/hour) anhand von Wetterdaten  
40-60 Stunden [online R Intro Kurs](https://open.hpi.de/courses/programmieren-r2022) mit Fokus auf gute Programmierpraxis


#### Über mich
[Website](https://brry.github.io/)  
[rdwd](https://bookdown.org/brry/rdwd/)  
[Berlin R User Group](https://www.meetup.com/de-DE/Berlin-R-Users-Group/)  
