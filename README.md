# Week 1

In de eerste week kon ik een keuze maken uit een van de volgende eindopdrachten.
- Modulair bedieningspaneel
- Interactieve vuurwerkshow
- Maak een 3D Rubrik's kubus
- Tailwind zonder Tailwind, met moderne CSS

Ik heb gekozen voor de opdracht Interactieve vuurwerkshow. het leek me leuk om meer te leren over animaties, transities.

De opdracht had de volgende eisen:
- Creëer een dynamische CSS-only vuurwerkshow.
- De gebruiker kan de show beïnvloeden.
- Je moet het vuurwerk zelf maken. 

Schets
![Schets van mijn vuurwerkshow](https://github.com/AllyssaA/css-to-the-rescue-2223/blob/main/docs/img/schets1.png)

In de eerste week ben ik begonnen aan het creëeren van de canvas van mijn vuurwerkshow. Hierbij heb ik een beetje rond gespeeld met linear-gradient, radial-gradient en conic-gradient.

Linear-gradient creëert een beeld die bestaat uit een progressieve overgang tussen twee of meer kleuren langs een rechte lijn. Dit heb ik toegepast op de lucht in mijn project. 
```css
background-image: linear-gradient(
    0deg,
    hsl(207deg 58% 40%) 4%,
    hsl(210deg 63% 37%) 9%,
    hsl(213deg 69% 35%) 15%,
    hsl(216deg 80% 32%) 21%,
    hsl(215deg 98% 27%) 28%,
    hsl(215deg 96% 25%) 35%,
    hsl(214deg 94% 23%) 42%,
    hsl(212deg 91% 20%) 49%,
    hsl(208deg 88% 16%) 56%,
    hsl(210deg 89% 16%) 63%,
    hsl(213deg 91% 15%) 70%,
    hsl(216deg 93% 15%) 76%,
    hsl(220deg 96% 15%) 82%,
    hsl(220deg 98% 14%) 87%,
    hsl(218deg 97% 13%) 91%,
    hsl(215deg 95% 13%) 95%,
    hsl(211deg 94% 12%) 98%,
    hsl(206deg 93% 11%) 100%
  );
  ```

Radial-gradient creëert een beeld dat bestaat uit een progressieve overgang tussen twee of meer kleuren die vanuit een oorsprong stralen. De vorm kan een circle of een ellipse zijn. Dit heb ik toegepast op de zon en de maan.
```css
/* zon */
background: radial-gradient(
    circle,
    #fff2d6 20%,
    #d89766 35%,
    transparent 55%
);
/* maan */
background: radial-gradient(
    circle,
    #c2bfba 20%,
    #e1dbd6 35%,
    transparent 55%
);
```

Conic-gradient maakt een beeld die bestaat uit een verloop met kleurovergangen die rond een middelpunt zijn geroteerd (in plaats van uit te stralen vanuit het midden). Voorbeelden van conische verlopen zijn cirkeldiagrammen en kleurenwielen. Dit heb ik toegepast op de oceaan. Waardoor het lijkt alsof het licht van maan/zon op de oceaan weerkaatst.
```css
background: conic-gradient(
    from 90deg at 50% 150%,
    #589bce,
    #055ca7,
    #052b4c,
    #003b90,
    #00174a
);
```

# Week 2
In week 2 heb ik tijdens de themasessie over animaties gekozen, omdat ik nog niet veel kennis had over dit onderwerp en wilde leren hoe ik animaties kon toepassen op mijn vuurwerkshow. Tijdens deze sessie hebben we verschillende aspecten van animaties besproken, zoals de naam van @keyframes, de duur, het aantal herhalingen, de richting, de afspeelstatus en de timingfunctie van de animatie.
- animation-name naam van @keyframes
- animation-duration
- animation-iteration-count
- animation-direction
- animation-play-state running paused
- animation-timing-function om te chainen en overzicht te houden meerdere divs met keyframes gebruiken, buitenkant gaat omhoog en de binnenste gaat draaien.

Ik heb een codepen gemaakt waarin ik animaties heb toegepast op mijn vuurwerkshow. Ik gebruikte meerdere div-elementen met bijbehorende @keyframes-regels om de beweging van het vuurwerk te simuleren. Dit was een uitdagende taak waarbij ik moest zorgen dat de timing en de coördinaten van de animatie goed waren ingesteld.

Ik heb ook gewerkt aan het verbeteren van mijn switch-toggle. In plaats van het gebruik van een label en een span, heb ik gebruikgemaakt van de pseudoelementen :before en :after om de switch te maken. Hierdoor kon ik de code vereenvoudigen en de interactieve functionaliteit behouden.

https://codepen.io/AllyssaA/pen/bGxGXPe


# Week 3
Tussen week 2 en week 3 liep ik vast bij het refactoren van mijn switch-toggle. Ik besloot om helemaal opnieuw te beginnen met het maken van de switch in een codepen. Het kostte me wat tijd, maar uiteindelijk slaagde ik erin om een switch te maken zonder het gebruik van een label of een span.

https://codepen.io/AllyssaA/pen/KKxayZO?editors=1100

In deze week voegde ik ook bomen toe aan mijn vuurwerkshow. Ik tekende drie bomen in Illustrator en exporteerde ze als SVG-bestanden. Vervolgens voegde ik styling toe met behulp van CSS om de bomen weer te geven.


# Wat ging er soepel , wat was lastig en waar ben je trots op
Ik ben trots op de switch-toggle die ik heb gemaakt. Ik heb hier veel tijd aan besteed om het goed werkend te krijgen door het te refactoren en gebruik te maken van :before en :after pseudo-elementen.

Wat ik lastig vond, was het maken van het vuurwerk. Doordat ik veel div-elementen heb gebruikt, raakte ik op een gegeven moment het overzicht kwijt over welke CSS-code bij welk HTML-element hoorde. Dit maakte het een puzzel om alles op de juiste manier te organiseren.

# Heb je nieuwe inzichten hoe je de kracht CSS kunt benutten (of juist niet).
Ik heb nieuwe inzichten gekregen in hoe ik de kracht van CSS kan benutten, met name op het gebied van animaties en keyframes. Het gebruik van @keyframes stelde me in staat om complexe bewegingen en overgangen te creëren, en ik heb geleerd hoe ik deze effectief kan combineren om de gewenste visuele effecten te bereiken.

Ik heb ook geleerd hoe ik met behulp van lineaire, radiale en conische gradiënten interessante achtergrondeffecten kan creëren. Dit stelde me in staat om de lucht, de zon, de maan en de oceaan op een realistische en boeiende manier weer te geven.

Over het algemeen ben ik blij met de nieuwe inzichten die ik heb opgedaan en de mogelijkheden die CSS biedt om creatieve en interactieve webervaringen te creëren.


# Herkansing
Voor de herkansing heb ik mijn werk verbeterd door gebruik te maken van verschillende geavanceerde technieken. Ik heb keyframes toegepast om animaties te creëren die het vuurwerk laten exploderen op het scherm. Het was een uitdaging om de timing van de animaties precies goed te krijgen, maar ik ben erin geslaagd om een visueel effect te creëren.

Daarnaast heb ik de pseudo-elementen :before en :after gebruikt om extra elementen aan mijn ontwerp toe te voegen. Zo heb ik een reflectie van de maan gemaakt, die een realistisch effect geeft aan de scène. Ook heb ik met behulp van :before en :after het wolkje geanimeerd, waardoor het lijkt alsof het voorbij drijft.

Om mijn code georganiseerd te houden en herbruikbaarheid te bevorderen, heb ik veelvuldig gebruik gemaakt van ul (unordered list) en li (list item) elementen, met een div-element eromheen. Dit stelde me in staat om de verschillende onderdelen van mijn ontwerp logisch te groeperen en gemakkelijk stijlen en animaties toe te passen op specifieke elementen.

De toevoeging van meer vuurwerk en het experimenteren met animaties hebben mijn werk visueel aantrekkelijker gemaakt. Dankzij het gebruik van keyframes, pseudo-elementen en goed gestructureerde code heb ik een vuurwerkshow kunnen realiseren.

# Wishlist
Er zijn nog enkele punten die ik niet heb kunnen aanpakken maar waar ik wel graag nog aan zou willen werken:

- Het animeren van een rondje op de switch (iets spectaculairder maken)
- Het creëren van een berg met een beetje sneeuw op de top
- Het intensiveren van de vuurwerkshow door verschillende animaties toe te voegen
- Het creëren van een prachtige sterrenhemel



# Bronnen
https://developer.mozilla.org/en-US/docs/Web/CSS/gradient/conic-gradient

https://developer.mozilla.org/en-US/docs/Web/CSS/gradient/linear-gradient

https://developer.mozilla.org/en-US/docs/Web/CSS/gradient/radial-gradient

https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Animations


