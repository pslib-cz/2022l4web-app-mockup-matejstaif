
# Zachran Ivana

## Úvod

![náhled hry na monitoru při 1920px](https://github.com/pslib-cz/2022l4web-app-mockup-matejstaif/blob/87c09513874f9956e9265d37c520826e40d058ff/img/n%C3%A1hled-hry.png)

Hra Zachran Ivana je matematická hra s jednoduchými pravidly. Hra má za cíl procvičit jednoduché matematické počítaní. S každým levelem se obtížnost příkladů zvyšuje, ale časový limit zůstává pořád stejný.

Hlavním cílem je zachránit ubohého Ivana před strašlivými monstry! Hra obsahuje úrovně obtížnosti, kde každá obtížnost obsahuje 4 monstra, které musí hráč přemoct silou matematiky a každé monstrum zničit správnou odpovědí.

## Filozofie hry

Po spuštění hry se spustí časovač. Na každou odpověd má hráč 30 vteřin. Uprostřed je Ivan, který každých 50 veřin řekne jednu z hlášek. Hláška je viditelná následných 15 vteřin. Poté zmizí a další hláška se objeví za dalších 50 vteřin.

Každé z monster pod sebou má jednu z odpovědí na příslušný příklad. Pouze jeden je, ale správný. 
### Správná odpověd
Po kliknutí na mostrum, které má pod sebou správnou odpoved na příslušný příklad. Monstrum zmizí a zbydou pouze 3 monstra. Takto to pokračuje - za každou správnou odpoved jedno monstrum zmizí. Při každém 4 příkladu, když zbyde pouze jedno monstrum. Pod příšerou není výsledek, ale políčko na správnou odpoved a hráč musí číselně odpovedet.
### Špatná odpověd
Když hráč odpoví špatně na prázdném místě, kde dříve bylo monstrum se objeví jedna příšera znovu. Výjmkou je situace, když mám plný počet monster, tedy 4, v tom případě se nic nestane a pouze se resetuje příklad.

Při špatné odpovědi se taktéž vždy zobrazí červený křížek značící špatnou odpoved
### Vypršení času
Vypršení času je bráno jako špatná odpoved.

## Ivanovi hlášky
Ivan používá následující hlášky: Pomoc, bojím se; Zachran mě; Nesnáším monstra; Ivan se bojí, pomoc; Pomoc mi prosím; Jsem k smrti vyděšený; Zachran mě před ukrutnými monstry; Nesnáším příšery, zachran mě prosím!
