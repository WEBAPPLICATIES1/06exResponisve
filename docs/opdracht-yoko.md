# Oefening Yoko

## Alvorens te beginnen:
- Open de map **Yoko**
- Activeer Live Server

We starten met het resultaat uit vorige les, dit is de desktop view (vanaf 992px)

![](images/rwd08.png)

## **Smartphone weergave**

![](images/rwd09.png)

## **Tablet weergave (vanaf 480px)**

![](images/rwd10.png)

Vul de viewport aan in het html document.
In het css bestand staan reeds aanwijzingen wat aan te passen.

- Declareer de opmaak (niet device gebonden):
- zorg ervoor dat width en height content/padding/border omvat
- algemene eigenschappen: font-family – color – achtergrond – lijnhoogte…
- opmaak voor de verschillende logische blokken.
- opmaak voor headers - anchors – images - …

Bepaal opmaak en layout voor kleinste device:

- 1 kolom.
- menubalk vervangen door icon met uitklapmenu (verborgen).
- belangrijkste content bovenaan.

Na de algemene opmaak en layout voor het kleinste device, worden enkel die eigenschappen aangepast die nodig zijn om de layout bij te sturen voor tablets (width > 480 px en width < 992px).

- Verplaats bepaalde logische blokken (float), zodat de 1-kolom layout wordt doorbroken.
- Pas eventueel ook margin en padding aan indien nodig.
- Verberg de nodige afbeelding(en) – icoon en voeg de juiste afbeeldingen toe (HTML) maak de juist afbeeldingen zichtbaar.
- Pas eventueel background-images aan.
- Pas eventueel layout van menubalk aan.
- Voor de images (header – main content) maken we gebruik van het picture element. Hier is het mogelijk om aan de hand van breakpoints andere afbeeldingen weer te geven – hiervoor maken we gebruik van het source element en het srcset attribuut.
  ![](images/rwd11.png)

- Tot slot pas je de layout aan voor de desktop (> 992px).
- Eventueel images aanpassen.
- Margin - padding aanpassen.
- Verhoudingen tussen kolommen aanpassen.