# QA

## Overview
* QA er en side hvor borgere kan spørge og svare på spørgsmål.
  * En hjælp til borgerservice.dk
  * En mulighed for borgere at give en hjælpende hånd med omkring emner de har viden

## Mål
* At skabe en vidensdatabase over de reelt oftest stillede spørgsmål og gøre den tilgængelig for borgere

## Funktionalitet
* Spørgsmål kan stemmes op eller ned af andre
  * På index for spørgsmål skal vises: antal stemmer, antal svar, antal visninger
* Til hvert spørgsmål kan man angive et svar (der kan være mange besvarelser til et spørgsmål)
  * Besvarelser kan også stemmes op eller ned
  * Man skal kunne kommentere svar uden at det bliver endnu et svar
* Brugere
  * Har karma som styres af kvaliteten og kvantiteten af spørgsmål og svar

## Backend
* Sprog? (Python? RoR? Haskell?)
* Bør opbygges som et API så andre sider kan bygge frontend/design hvis de har lyst
  * API'et skal dokumenteres
* 100% Open Source?
  * Github project med deploy hver måned

## Design
0. Brug standard udseende og lad device bestemme udseendet af så meget som muligt
0. Hastighed
0. Brugere skal forstå hvad der sker
0. Placer elementer vertikalt
0. Farver bruges til genkendelse

## Modstand / Konkurrenter
* KMD - står for borgerservice.dk (og burde selv have lavet det for lang tid siden)
* Diverse generelle fora

