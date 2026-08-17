# Pörrö Painonhallinta – Android 0.1

Tämä on ensimmäinen paikallinen Android-versio, joka lukee Health Connectista OHealthin sinne siirtämää dataa.

## Lukee
- paino
- pituus
- askeleet
- etäisyys
- aktiiviset kalorit
- kokonaiskulutus
- harjoitussessiot
- syke
- leposyke
- happisaturaatio
- hengitystiheys
- uni
- historiallinen data (jos Health Connect myöntää historian luvan)

## Tietosuoja
Sovellus ei kirjoita Health Connectiin eikä lähetä terveystietoja verkkoon. Data luetaan puhelimesta ja näytetään paikallisesti.

## Rakentaminen puhelimella
Suositus: AndroidIDE.
1. Asenna AndroidIDE.
2. Pura tämä ZIP.
3. Avaa projektin kansio AndroidIDEssä.
4. Anna Gradlen synkronoida projekti.
5. Build > Assemble Debug.
6. Asenna `app/build/outputs/apk/debug/app-debug.apk`.

Ensimmäinen versio lukee datan etualalla. Taustasynkronointi ja painonhallinnan analyysit tehdään seuraavassa vaiheessa.
