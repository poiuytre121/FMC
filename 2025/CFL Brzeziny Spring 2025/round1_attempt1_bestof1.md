# Próba 1 Runda 1

## Scramble: R' U' F R2 L D' L2 D B2 D' B' U R' F U' R' B D' R2 B D' R' U' F

Na początek trochę kontekstu do tej próby. W normalnych okolicznościach runda w formacie best of 1 oznacza,
że bezmyślnie można atakować dobrego singla, nie przejmując się za bardzo DNFem, bo gorsze single i tak nie dadzą podium.
W tym wypadku jednak musiałem wziąć pod uwagę, że jest no konkurencja normalnie liczona do klasyfikacji generalnej CFL,
a więc startowałem z prostym założeniem, że DNF nie jest opcją. Z tego powodu przyjąłem założenie, że w okolicach 30 minuty zacznę insertować szkielety które znajdę do tego momentu.
Mając tą świadomość i wiedząc, że podchodzę z dawno nieposiadanej roli faworyta, w momencie uruchomienia stopera miałem nieco wyższy poziom stresu niż zwykle.

Pierwsza rzecz którą zauważyłem, to to, że nie trafiliśmy bezbloczkowca, i bardzo szybko zbudowałem taki bloczek:

B R2 U R U2 //2x2x2 (5/5)

Po tych ruchach nie zauważyłem jednak nic ciekawego, więc zanim nawet zapisałem cokolwiek (finalnie nie zapisałem nawet tego bloczka na brudnopisie podczas próby). Zamiast tego stwierdziłem, że rzucę okiem, czy na inwersji ten bloczek nie będzie prostszy.
Jak się okazało był:

(L' U R2 B) //2x2x2 (4/4)

Dalej na inwersji zobaczyłem dość prostą kontynuację, która doprowadziła mnie do liniowego rozwiązania:

(U F2 L2 U' L' U F2) //2x2x3 (7/11)

(U' L2 U2 L U L2) //F2L-1 (6/17)

(F U F2 L F L') //F2L (6/23)

(B' U2 B U B' U' B U B' U B U) //ZBLL + AUF (12/35)

To 35 dało mi trochę spokoju pod względem braku DNFa, przepisanie tego w razie czego na normala nie zajęłoby mi dużo czasu, więc po bloczku 2x2x2 przeszedłem na inwersję, a tam jednoruchowy setup do 3-ruchowego slota. W momencie gdy miałem to zapisane była 9 minuta próby.

(L' U R2 B) ///2x2x2 (4/4)

L' F' U' F //2x2x3 (4/8)

W tym miejscu zauważyłem, że można po prostu przejść na czerwony kolor

L2 U2 F' L F //F2L-1 (5/13)

U' L U2 B' U' B L' //2tc (7/20)

Przez sekundę, zanim zauważyłem te dwa obrócone rogi przemknęła mi przez myśl, że znalazłem LL skipa, ale nie tym razem. 
Nigdy wcześniej nie insertowałem 2tc, ale wiedziałem, że często pierwsza insercja skraca bardzo dużo ruchów, więc zapisałem to z myślą, że z pewnością będzie to lepsze niż to 35 jakie miałem gotowe w tamtej chwili.
Jednak szukałem dalej kontynuacji do znalezionego 2x2x3:

(L' U R2 B) ///2x2x2 (4/4)

L' F' U' F //2x2x3 (4/8)

L' B' U' B //EO (4/12)

L' U' L2 U2 //pseudo F2L (4/16)

(U') //naprawa pseudo (1/17)

B L2 B' L' B L' B' //sune do 3c (7/24)

Więcej na tym starcie nie widziałem, więc spojrzałem na EO...no nie patrzyłem nazbyt długo, na osi R/L bodajże były nawet 4 niezorientowane krawędzie.
Przez chwilę nawet źle zinterpretowałem to, które krawędzie są niezorientowane i w panice zacząłem mieszać inwersją, sądząc, że nie zauważyłem trzeciego w tym roku jednoruchowego EO.
Szybko jednak okazało się, że zarówno na scramblu, jak i na inwersji krawędzie nie są ułożone przyjaźnie pod EO, a jednocześnie wybiła 30 minuta próby.
Pozostało zdecydować się, od którego szkieletu zacząć. Stwierdziłem, że szybciej zajmę się 3c, licząc, że dostanę chociaż statystyczne -2 na insercji, a potem zajmę się nowym dla mnie 2tc.

Szkielet: L' F' @1 U' F L' B' U' B L' U' L2 U2 B L2 B' L' B L' B' U B' R2 U' L (24)

@1: F' U' F D2 F' U F D2 (8-1)

Rozwiązanie: L' F2 U' F D2 F' U F U' D2 F L' B' U' B L' U' L2 U2 B L2 B' L' B L' B' U B' R2 U' L (31)

Mając kolejny lepszy backup, podszedłem do wcześniejszego szkieletu. Od razu po pomieszaniu i po pierwszym ruchu zauważyłem sekwencję F' U' F i znalazłem komutator, który natychmiast skróci 6 ruchów:

Szkielet 2: L' @1 F' U' F L2 U2 F' L F U' L U2 B' U' B L' B' R2 U' L (20)

@1: D F' U' F D' F' U F (8-6)

Po pierwszej insercji: L' D F' U' F D' L2 U2 F' L F U' L U2 B' @2 U' B L' B' R2 U' L

@2: F' U' B' U F U' B U (8-3)

Szukając drugiej insercji aż do miejsca, w którym insercja finalnie się znajduje, nie widziałem, żadnego 8-ruchowego komutatora. W tym miejscu naklejki wskazały mi komutator F' D' F U2 F' D F U2, który skracałby jeden ruch.
Mam nawyk sprawdzania, czy zapisana insercja działa na innej kostce i po przejściu przez szkielet na kostce zostało mi...5 rogów nieułożonych. Po sprawdzeniu komutatora na kartce postanowiłem przejść przez całość jeszcze raz.
Tuż przed nową insercją zatrzymałem się i niestety okazało się, że w tym miejscu stan kostki, na której szukałem insercji, był inny niż powinien. Stało się to w okolicach 52/53 minuty, więc dość późno. Mając do wyboru szukać od początku bądź od tego miejsca, do którego doszedłem wybrałem tę drugą opcję.
Opłaciło się, bo akurat właśnie tam jest optymalna insercja. Taka to historia lekkiego jumpscare'a na koniec próby.

Finalne rozwiązanie: L' D F' U' F D' L2 U2 F' L F U' L U2 F' B' U' B' U F U' B2 L' B' R2 U' L (27)

[Wizualizacja](https://alg.cubing.net/?alg=L-_D_F-_U-_F_D-_L2_U2_F-_L_F_U-_L_U2_F-_B-_U-_B-_U_F_U-_B2_L-_B-_R2_U-_L_&setup=R-_U-_F_R2_L_D-_L2_D_B2_D-_B-_U_R-_F_U-_R-_B_D-_R2_B_D-_R-_U-_F)

Próba pod presją, pierwsze złoto w Polsce od ponad roku, punkty do ligi zdobyte, cele osiągnięte. Bardzo cieszy też fakt, że w tej próbie wzięło udział aż tyle osób, choć ze zmiennym szczęściem, ale jednak podjęli się tego wyzwania, być może część z nich będzie chciała rozwijać się też w tej konkurencji :D
