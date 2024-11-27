# Próba 3 Runda 1

## Scramble: R' U' F U' F' R2 D' L2 R2 F2 L2 U' L' D B' U2 L' R2 B' F L2 U R' U' F

Po odsłonięciu scrambla zobaczyłem ogromny blok niebieskiego na draw scramblu, a po pomieszaniu z paradoksalną mieszanką przerażenia i uspokojenia odkryłem gotowy bloczek 3x1x1 a do tego kilka mniejszych bloczków.
Wiadomo było, że będzie z czego wybierać, a także, że jest spora szansa że nie zauważy się czegoś dobrego pomimo, że to co się zrobi i tak będzie niezłe. Tak też zresztą dokładnie się stało.

Zacząłem spokojnie, w kilka minut znajdując backupowy szkielet:

R2 B2 R2 //1x2x3 (3/3)

B' U' F' U' B2 //2x2x3 (5/8)

F' D' R F2 R' //EO (5/13)

F D2 F D' F D F2 //3C + 1TC (7/20)

No cóż, na czystych 8 ruchowych komutatorach Insertion Finder nie znajduje rozwiązania, przy umożliwieniu wszystkich daje 31, nie żałuję niczego.

Kontynuując przygodę, stwierdziłem, że po pierwszych trzech ruchach przejdę na inwersję:

R2 B2 R2 //1x2x3 (3/3)

(F2 D2 F2 D' F' B2) //pseudo F2L-1 (6/9)

B' //F2L-1 (1/10)

(U F R' F' R) //EO + krawędzie F2La (5/15)

F' U' F U' F' U2 F U' //sune do 3C i AUF (8/23)

Szkielet: R2 B2 R2 B' U @1 F' U2 F U F' U F R' F R F' U' B2 F D F2 D2 F2 (23)

@1 R F' L F R' F' L' F (8-2)

Rozwiązanie: R2 B2 R2 B' U R F' L F R' F' L' U2 F U F' U F R' F R F' U' B2 F D F2 D2 F2 (29)

Mając to zapisane, pogratulowałem sobie mentalnie zrobienia PRa i zacząłem szukać dalej czy nie ma czegoś lepszego, żeby jeszcze podbić sobie statystyki. Zdecydowałem się zatem sprawdzić EO:

W osi R/L są tylko dwie niezorientowane krawędzie, więc:

R U' R //EO (3/3)

B2 //kwadrat (1/4)

F D U2 B2 D //pseudo 2x2x3 (5/9)

U' B2 //kwadrat (2/11)

U' B U D' //5C (4/15)

Mając zapisane już 29 wiedziałem, że muszę skrócić co najmniej 3 ruchy żeby coś zyskać, no i nie zdążyłem już zrobić insercji która dawała by lepszy wynik niż 29, po sprawdzeniu IF mówi 27 za pomocą 8-ruchowców, 25 ogólnie, no sub 25 mo3 z lekka missnięte niestety.

Podsumowując średnią, zdecydowanie ponad stan, patrząc na to, że to 20 z pierwszej próby jest chyba trzecim sub 25 w ogóle jakie zrobiłem zdecydowanie nie będę narzekał.

Na dokładkę dorzucę bloczkowe 23 które znalazł Dawid Wójcik, a który to start na inwersji "zostawiłem na później" bodajże, choć nie jest pewne, czy bym to znalazł:

(U2 B2 U2) //1x2x3 (3/3)
(D' F' B2) //pseudo F2L-1 (3/6)
B' //F2L-1 (1/7)
(U F' U' F) //kwadrat (4/11)
(U R' F R F' U) //3C (6/17)

Optymalna insercja daje 23, gdybym to znalazł obudzilibyśmy się w świecie gdzie mam meana 23,33. To by była pewna przesada :P
