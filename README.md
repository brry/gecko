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

- Flurstücke: [Karte](https://brry.github.io/sewekow), [Quelle](https://github.com/brry/sewekow/blob/main/karte.R)\
- Laufstrecken: [Karte](https://brry.github.io/runway), [Quelle](https://github.com/brry/runway/blob/master/berryMaps.R), [Shiny App](https://brry.shinyapps.io/runway)

[sf website](https://r-spatial.github.io/sf/)

#### Über mich
[Website](https://brry.github.io/)  
[rdwd](https://bookdown.org/brry/rdwd/)  
[Berlin R User Group](https://www.meetup.com/de-DE/Berlin-R-Users-Group/)  
