# Kawalkada

Zręcznościowa gra przeglądarkowa w stylu pixel-art. Prowadzisz szereg bohaterów, który sunie za przywódcą jak wąż. Bohaterowie sami atakują wrogów w zasięgu, a Ty decydujesz tylko o kierunku marszu.

## Jak grać

Otwórz `index.html` w przeglądarce (działa też na telefonie). Nie trzeba niczego instalować.

- **Sterowanie:** strzałki / WASD, na telefonie przesuwanie palcem. `Spacja` (przytrzymaj) to zryw, `R` zawraca szereg, `P` lub `Esc` pauza, `M` wycisza dźwięk. Na telefonie zryw i zawrót mają własne przyciski.
- **Plansza:** duża, bez przeszkód, a kamera trzyma się przywódcy. Strzałki na krawędzi ekranu wskazują sztandar, złodzieja i strażnika.
- **Zderzenia:** uderzenie w ścianę zabiera wojownika z końca szeregu, a drużyna sama skręca. Wjazd we własny szereg zabiera tylko tego wojownika, w którego trafił przywódca. Gdy przywódca jest sam, traci część zdrowia.
- **Wrogowie** pojawiają się już w ruchu i stopniowo stają się widoczni. Półprzezroczystych można atakować, ale one jeszcze nie ranią.
- **Sztandary:** na każdej fali pojawia się sztandar nowego śmiałka. Najedź na niego przywódcą, a bohater dołączy na końcu szeregu.
- **Klejnoty** podnoszą poziom drużyny w trakcie wyprawy (więcej obrażeń i zdrowia).
- **Monety** zostają po wyprawie. W obozie ulepszasz za nie każdego bohatera osobno (do poziomu 10), odblokowujesz przywódców i kupujesz wyposażenie.
- **Co 5. fala** przychodzi strażnik krainy.

## Mechaniki specjalne

- **Zryw:** drużyna biegnie dwa razy szybciej, dopóki starcza sił. Siły odnawiają się same.
- **Zawrót:** ogon staje się czołem szeregu (co 7 sekund).
- **Seria:** szybkie zabójstwa mnożą punkty. Co 15 trafień wpadają złote klejnoty i krótki szał.
- **Złodziej skarbów:** co jakiś czas pojawia się złoty goblin, który ucieka. Złapany sypie monetami i daje premię.
- **Elitarni wrogowie:** więksi i złoci, mają więcej zdrowia, ale zawsze zostawiają premię.
- **Bractwo:** każdy kolejny bohater tej samej klasy daje całej tej klasie +20% obrażeń.

## Krainy

| Kraina | Wrogowie | Strażnik | Odblokowanie |
|---|---|---|---|
| Szepczący Las | gobliny, nietoperze, szlamy, orki | Pradawny Dąb | od początku |
| Zapomniane Lochy | szkielety, duchy, kultyści | Licz | fala 8 w Lesie |
| Lodowa Grota | wilki, yeti, lodowe szlamy | Lodowy Kolos | fala 8 w Lochach |

Trudniejsze krainy dają więcej monet.

## Bohaterowie

| Bohater | Atak |
|---|---|
| Rycerz | cięcie z bliska, rani też sąsiadów celu |
| Łuczniczka | szybkie strzały z daleka |
| Piromanta | wybuchające kule ognia |
| Kapłanka | leczy całą drużynę |
| Krasnolud | wirujący topór wokół siebie |
| Szronica | lodowe pociski spowalniające wrogów |
| Nożowniczka | grad sztyletów i trafienia krytyczne |
| Zaklinacz | błyskawica przeskakująca między wrogami |
| Łowca | oszczep przebijający wrogów i pies, który sam goni przeciwników |
| Paladyn | młot z bliska i okresowa tarcza dla całej drużyny |

## Premie na mapie

- **Szał:** potrójna szybkość ataku.
- **Magnes:** przez 10 sekund przyciąga klejnoty i monety z dużej odległości.
- **Bomba:** niszczy wszystkich wrogów w dużym promieniu wokół przywódcy (strażnikom zabiera część zdrowia).
- **Tarcza**, **Zamrożenie**, **Podwójne monety** i **Mikstura** leczącą drużynę.

Postęp (monety, poziomy bohaterów, rekordy, odblokowane krainy) zapisuje się w pamięci przeglądarki. Cała grafika jest oryginalna i rysowana w kodzie.
