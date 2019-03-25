### Opdracht 2b-1) Maak een zeshoek met een for-lus 

Deze les wordt afgetekend als:

- Je een zeshoek hebt getekend met Python
- Je daarvoor een forlus hebt gebruikt

Vorige week heb je een zeshoek getekend. Dat ging zo:

```python
pen.forward(100)
pen.left(60)
pen.forward(100)
pen.left(60)
pen.forward(100)
pen.left(60)
pen.forward(100)
pen.left(60)
pen.forward(100)
pen.left(60)
pen.forward(100)
pen.left(60)
```

**Opdracht.** Teken een zeshoek met een for-lus.

Denk aan deze tips:

* Vergeet de dubbele punt : niet aan het einde van de regel
* Regels in de lus moeten beginnen met 2 spaties!
* Als je het goed doet, heb je maar 3 regels nodig voor de zeshoek 
  * De regels die we al hadden staan tellen daarvoor niet mee (import, en pen= en pen.speed)



### Opdracht 2b-2) Maak een vierkant met een for-lus (extra)

Deze les wordt afgetekend als:

- Je weet welke regels we moeten veranderen om een vierkant te maken.
- Je een vierkant hebt getekend met Python
- Je daarvoor een forlus hebt gebruikt

In de vorige opdracht heb je een zeshoek getekend met een for-lus Dat ging zo:

```python
for i in range(6):
    pen.forward(100)
    pen.left(60)
```

**Opdracht.** Als je nu een vierkant wilt maken, moet je de getallen 6 en 60 veranderen. Waarin? 
Schrijf het op in je schrift:

* 6 wordt ....
* 60 wordt ...

**Opdracht.** Teken nu het vierkant met een for-lus

Tip: Je hoeft niets anders te veranderen, alleen de getallen.

### Opdracht 2b-3) Maak een spirograaffiguur met een for-lus

Deze les wordt afgetekend als:

- Je een spirograafachtig figuur maakt met Python
- Je daarvoor een forlus hebt gebruikt

In de vorige opdracht heb je een vierkant getekend met een for-lus. Nu willen we een soort sterfiguur. Weet je nog van vorige week wat voor hoek je dan moet gebruiken? En hoevaak dnek je dat je rond moet gaan? Probeer dit figuur zo precies mogelijk na te maken

![image-20190322130521606](/Users/Felienne/Library/Application Support/typora-user-images/image-20190322130521606.png)

**Opdracht.** Teken nu het figuur met een for-lus

### Opdracht 2b-4) Teken een schilderij met twee forlussen

Deze les wordt afgetekend als:

- Je het goede plaatje hebt getekend met Python
- Je daarvoor twee for-lussen gebruikt

Dit is een schilderij van een berg (met een beetje fantasie!). Kun jij het namaken met Python? Je moet wel twee lussen gebruiken!

![image-20181207110047621](/Users/Felienne/Library/Application%20Support/typora-user-images/image-20181207110047621.png)





### Opdracht 2b-5) Maak een huisje met twee forlussen (extra)

Deze les wordt afgetekend als:

- Je het huisje hieronder hebt getekend
- Je daarvoor twee for-lussen gebruikt

**Opdracht.** Probeer dit huisje na te maken.

![image-20190322131013102](/Users/Felienne/Library/Application Support/typora-user-images/image-20190322131013102.png)

### Opdracht 2b-6) Maak een diamant met twee forlussen (extra)

Deze les wordt afgetekend als:

- Je de diamant hieronder hebt getekend.
- Je daarvoor twee for-lussen gebruikt

Opdracht. Probeer dit na te maken.

![image-20190322131023789](/Users/Felienne/Library/Application Support/typora-user-images/image-20190322131023789.png)

------

 <div style="page-break-after: always;"></div>

### Opdracht 2b-7) Maak een vierkant met een variabele (extra)

Deze les wordt afgetekend als:

- Je de juiste som voor alle figuren hebt opgeschreven, met de twee variabelen
- Je een vierkant hebt getekend met Python
- Het veranderen van alleen de regel `aantal_hoeken = ...` een ander figuur oplevert

In vorige opdrachten heb je een vierkant, een driehoek en toen een zeshoek getekend. Je gebruikt steeds dezelfde som om uit te rekenen welke hoek je gaat draaien, kijk maar:

Bij de driehoek: de hoek is 360 gedeeld door 3
Bij het vierkant: de hoek is 360 gedeeld door 4
Bij de zeshoek:  de hoek is 360 gedeeld door 6

We gaan het aantal hoeken nu in een variabele opslaan. 

Dat doen we zo voor de driehoek:

```python
aantal_hoeken = 3
```


**Opdracht.** Nu moet jij de hoek uitrekenen, hoe moet dat?

* Schrijf het eerst op in woorden:

  hoek = …………. aantal_hoeken

* Schrijf het nu op in Pythoncode

  hoek = …………. aantal_hoeken



Deze code kun je nu gebruiken in je for-lus. Dan verandert de hoek vanzelf als je het aantal hoeken verandert!

**Opdracht.** Maak deze code af:

```python
aantal_hoeken = 4

for i in range(...):
    hoek = .......
    pen.forward(100)
```

**Let op!** Je krijgt alleen een stempel als je het foguur kunt veranderen door alleen de regel `aantal_hoeken = ...`  aan te passen!! Dus bijv aantal_hoeken = 3 maakt een driehoek en aantal_hoeken = 10 maakt een tienhoek.
