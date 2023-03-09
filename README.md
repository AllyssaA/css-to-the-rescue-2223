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
In week 2 heb ik voor de themasessie animaties gekozen omdat ik nog niet veel wist hierover en hoe ik dat kon toepassen op vuurwerk. Tijdens deze sessie hebben we het o.a. gehad over:
- animation-name naam van @keyframes
- animation-duration
- animation-iteration-count
- animation-direction
- animation-play-state running paused
- animation-timing-function om te chainen en overzicht te houden meerdere divs met keyframes gebruiken, buitenkant gaat omhoog en de binnenste gaat draaien.

https://codepen.io/AllyssaA/pen/bGxGXPe

In mijn code had ik een switch gemaakt waarbij ik gebruik maakte van een form, daarin had ik een input checkbox met label en een span. Deze switch zorgt ervoor dat ik van dag naar nacht kan switchen. Ik kreeg als opmerking dat ik de de switch ook zonder label en span kon maken door middel van gebruik van `:before` en `:after`. Hiermee ging ik de rest van de week mee aan de slag.  

# Week 3
Tussen week 2 en 3 liep ik een beetje vast met het refactoren van mijn switch. Ik besloot dus om helemaal opnieuw te beginnen met mijn switch in een codepen en het duurde een tijdje maar uiteindelijk is het me toch gelukt om een switch te maken zonder label of een span.

https://codepen.io/AllyssaA/pen/KKxayZO?editors=1100

Deze week heb ik bomen aan mijn opdracht toegevoegd. Dit heb ik gedaan door 3 bomen in Illustrator te tekenen en te exporteren als SVG. Vervolgens heb ik styling hieraan toegevoegd met CSS.



# Bronnen
https://developer.mozilla.org/en-US/docs/Web/CSS/gradient/conic-gradient

https://developer.mozilla.org/en-US/docs/Web/CSS/gradient/linear-gradient

https://developer.mozilla.org/en-US/docs/Web/CSS/gradient/radial-gradient

https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Animations


