# Webbutveckling 1 - Kursplanering

Beskrivning av kursen, länk till skolverket, osv…

#### Modul 3 - Färglära

Länk till videogenomgång.

Länk till uppgift.

#### Modul 8 - Vektorgrafik 

8.0 Introduktion till Vektorgrafik 

8.1 Personligt varumärke 

8.2 Animera SVG 

## Installera Drupal

```mermaid
%%{init: {'theme': 'base', 'themeVariables': { 'primaryColor': '#bddfff', 'edgeLabelBackground':'#d39100', 'lineColor': '#29568f'}}}%%
flowchart TD
    start([Hur du startar Drupal <br />i en container med Docker]) ==> alla1
    alla1 ==>|Ja, Linux| linux1 
    linux1("Installera <br />#quot;Docker Engine <br />for Linux#quot; och <br />#quot;Docker Compose#quot;") ==> alla2
    alla1{Kör du ett <br />vettigt OS?} -->|Nej, Windows| windows1
    windows1[Aktivera WSL 2 och <br />installera senaste <br />Ubuntu LTS] --> windows2
    windows2["Installera <br />#quot;Docker Desktop <br />for Windows#quot; <br />(stable)"] --> alla2
    alla2(Tanka hem filen <br />docker-compose.yml <br />och lägg i en <br />projektkatalog) ==> alla3 
    alla3("Kör <br />docker-compose up <br />och tryck [Ctrl]+[c] när <br />processen är klar") ==> slut
    slut((Du kan nu köra <br />docker-compose start <br />och <br />docker-compose stop<br /> föŕ att kontrollera <br />din container.))
```

## Ikoner 
* Bok &#x1F4D7; / &#x1F4D8; / &#x1F4D9;
* Cirkel &#x1F534; / &#x1F535;
* Diamant &#x1F536; / &#x1F537; / &#x1F538; / &#x1F539;
* Pil Upp/Ned &#x1F53A; / &#x1F53B;
* Podcast &#x1f3a7; 
* Film &#x1f3ac; 
* Spel &#x1f3ae; 
* Vinnare &#x1f3c6; 
* Katalog Stängd/Öppen &#x1f4c1; / &#x1f4c2;
* Diskett &#x1f4be;
* Mobiltelefon &#x1f4f1; / &#x1f4f5;
* PC &#x1f4bb;
