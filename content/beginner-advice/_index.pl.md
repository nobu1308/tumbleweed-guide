---
title: "Tumbleweed: rady dla początkujących"
---

# Tumbleweed: rady dla początkujących

Ten poradnik pomoże ci uniknąć częstych błędów popełnianych przez początkujących graczy Tumbleweed, i wskaże sposoby na uporządkowanie twojego myślenia o grze. Niektóre z omówionych błędów to wizualnie obiecujące ruchy prowadzące to natychmiastowej straty pionka; inne to „złe nawyki” naśladujące zachowania z innych gier (zwłaszcza Go). Większość z nich została wybrana, ponieważ popełniono je w licznych grach między początkującymi na BGA. Paragrafy o błędach są uzupełnione opisem ogólnych zasad strategicznych Tumbleweed. Powinien on pomóc ci zrozumieć przebieg gry i wskazać cele do osiągnięcia w danej pozycji.

Dla zrozumienia poradnika, najlepiej żebyś zagrał wcześniej kilka gier i obejrzał to wideo wyjaśniające „tarcze” (shields) i „parowanie” (parries): [podstawowe strategie obronne w Tumbleweed (ang)](https://www.youtube.com/watch?v=b1q3ZtuE-cc).

## Kontaktowe jedynki są złe, jeśli nie atakują

Postawienie jedynki bezpośrednio dotykającej pionków przeciwnika jest zazwyczaj złym ruchem, chyba, że stwarzają bezpośrednią groźbę bicia. Na przykład, na diagramie po lewej, Czerwony zagrał E5. Biały może natychmiast kontratakować grając E6 – Czerwony nie ma tu żadnej szansy na obronę.

{{< columns >}}
![Diagram 1](1.png)
<--->
![Diagram 2](2.png)
{{< /columns >}}

Pamiętaj, że jedynki są słabe, kiedy je umieszczasz. W późniejszej fazie gry możesz wzmocnić swoje jedynki dodatkowymi przyjaznymi liniami wzroku, ale początkowo są bardzo podatne na atak. Ogólnie rzecz biorąc, dwójki są znacznie lepsze do agresywnych ruchów kontaktowych (chociaż również mogą zostać łatwo zbite, jeśli twojemu atakowi zabraknie impetu). Nie znaczy to jednak, że powinieneś całkowicie zrezygnować z grania jedynek. Na przykład, jeśli twój ruch kontaktowy stwarza bezpośrednie zagrożenie bicia, twój przeciwnik będzie musiał zażegnać tę groźbę (jeśli to w ogóle możliwe) przed kontratakiem. Na diagramie poniżej, Czerwony zagrał E6:

{{<figure src="3.png" alt="Diagram 3">}}

D5 jest atakowane. Biały nie ma czasu żeby zaatakować E6 (grając E5 lub D6), bo Czerwony obroniłby się po prostu bijąc D5x. E6 okazuje się więc dobrym ruchem w tej pozycji.

## Uważaj na „martwe” pionki przeciwnika

Kiedy gra zbliża się do końcówki, zdarzy się często, że na twoim terytorium zostało trochę jedynek przeciwnika, na które masz dwie lub więcej linie wzroku. Zbijanie ich albo granie na własnej części planszy może wyglądać na stratę tempa – ale pozbycie się tych pół-martwych intruzów jest często niezbędne. Nie powinieneś lekceważyć zagrożenia, jakie stwarzają – pamiętaj, że pozostałe na planszy pionki zapewniają linie wzroku, a przez to stwarzają dodatkowe opcje dla twojego przeciwnika. Jest to powiązane z faktem, że bicie jest szczególnie istotne w Tumbleweed, znacznie bardziej niż w niektórych innych grach jak na przykład Go. Bicie wrogiego pionka ma dodatkową zaletę ograniczenia liczby ruchów, jakie może zrobić twój przeciwnik. Rozważmy pozycję, w której jedynka bez żadnej szansy na przeżycie może być użyteczna:

{{< columns >}}
![Diagram 4](4.png)
<--->
![Diagram 5](5.png)
{{< /columns >}}

Biały gra K10. Czerwony musi teraz zagrać tarczę na J9, albo pozwolić Białemu zbić I8, tym samym łamiąc swój mur. Ale po J9, Biały może zagrać dwójkę na H10 lub I10, przeprowadzając potężny podwójny atak:

{{<figure src="6.png" alt="Diagram 6">}}

## Przecięcie dwóch połączeń jest kluczowym punktem

Jak wyjaśniono w dokumencie [Shapes of Tumbleweed](/fundamental-shapes/#link) (w angielskiej wersji poradnika), połączenia są segmentami planszy po których biegną przyjazne linie wzroku. Są one kluczowym elementem gry i powinny znajdować się w centrum twojej strategii. W grach między początkującymi bardzo częsta jest sytuacja, w której nie zauważają oni kluczowego ruchu związanego z przecinającymi się połączeniami przeciwnych kolorów:

{{<figure src="7.png" alt="Diagram 7">}}

W tym przypadku, dwa połączenia przecinają się na D4. Kontrola nad tym punktem jest kluczowa dla obu stron. Jedną z możliwości jest zagranie bezpośrednio na nim, o ile pozycja na to pozwala; inną jest dodanie kolejnej linii wzroku, na przykład grając B2 lub F6. Poniżej przedstawiamy świetny przykład z prawdziwej gry ([Tumblebot](http://34.233.90.87:8000/api/analysis/site) kontra Tumblebot), po otwarciu 1. B2 G8 2. E5 G3 3. E9 B3:

{{<figure src="8.png" alt="Diagram 8">}}

Zarówno C3 jak i E6 są na przecięciach wrogich połączeń, stanowią więc idealne możliwe ruchy dla obu graczy. Wybranie, który z tych ruchów jest ważniejszy jest nieco bardziej zaawansowane, ale mówiąc ogólnie E6 jest bliżej centrum, a po zagraniu C3 Czerwony byłby zbyt skupiony na szczycie planszy. Najlepszą kontynuacją z pozycji na Diagramie jest więc 4. E6 C3.

## Wzmacnianie pionków jest prawie zawsze złym ruchem

Wzmacnianie jest zazwyczaj złe, chyba, że nie masz żadnej innej opcji. Na przykład, w pozycji pokazanej poniżej, Czerwona jedynka na E5 jest atakowana, ale wzmocnienie jej do dwójki byłoby złym ruchem. Wzmocnienie skutecznie broni się przed atakiem I zapewnia tymczasowe bezpieczeństwo pionkowi na A5, ale nie pełni żadnej innej pożytecznej funkcji – jest bardzo pasywnym ruchem. Znacznie lepszym pomysłem byłoby parowanie ataku, na przykład grając C5 jak na diagramie z prawej. Nie tylko broni to E5, ale też otwiera nową linię wzroku: C5-I11. Ponadto zapewnia to dodatkowego obrońcę heksowi C3, co może być przydatne jeżeli Biały odpowie na grając B3.

{{< columns >}}
![Diagram 9](9.png)
<--->
![Diagram 10](10.png)
{{< /columns >}}

Co do zasady, zamiast wzmacniać jedynkę do dwójki, szukaj parującego ruchu (to znaczy takiego, który daje jej trzecią przyjazną linię wzroku). Z kolei myśląc nad umieszczeniem dwójki, spróbuj się zastanowić czy nie będziesz musiał jej niedługo wzmacniać – jeżeli tak, prawdopodobnie nie jest to najlepszy ruch.

## Graj zrównoważone otwarcia

Przechodzimy teraz od prostych błędów do fundamentalnych elementów strategii (podobne akcenty pojawiają się zresztą w wielu grach terytorialnych). Musisz stale szukać złotego środka między powiększaniem swojego terytorium a zapewnieniem mu bezpieczeństwa. W Tumbleweed, jest to zazwyczaj powiązane z wartością pionka, który chcesz umieścić: z definicji, oznacza ona jak wiele linii wzroku masz na dany heks. Umieszczenie czwórki, piątki czy szóstki jest zupełnie nieefektywne, bo dany heks był już niekwestionowaną częścią twojego terytorium, a nowy pionek nie otwiera zbyt wielu nowych linii dla dalszego rozwoju.

W każdym punkcie gry musisz zdecydować, jaka jest najlepsza droga naprzód. Czy zagranie jedynki jest zbyt zachłanne, czy jest to szybka, efektywna ekspansja? Czy zagranie trójki jest stratą tempa, czy solidnym ruchem poprawiającym twoje bezpieczeństwo? W większości pozycji są to doskonałe pytania, a im większe twoje doświadczenie w Tumbleweed, tym sprawniej nauczysz się na nie odpowiadać.

## Przygotuj swój kształt z wyprzedzeniem

Na koniec omówmy nieco bardziej zaawansowany temat kształtów, a dokładniej: kątów. Jest to bardzo złożony temat, ale opanowanie choćby jego podstaw jest ważne dla zrozumienia przebiegu gry.

W idealnym świecie, byłbyś w stanie stworzyć prosty mur dwójek przecinający całą planszę, ale zazwyczaj przeciwnik będzie próbował ci w tym przeszkodzić. W rezultacie, będziesz zmuszony wprowadzić kąty do kształtu twojego terytorium. Po kilku grach, zauważysz z pewnością, że kąty wypukłe pojawiają się znacznie częściej niż kąty proste – są one bardziej efektywne.

{{< columns >}}
![Diagram 11](11.png)
<--->
![Diagram 12](12.png)
{{< /columns >}}

Na obu diagramach, granica czerwonej strefy jest określona siedmioma pionkami, ale kąt wypukły na diagramie po lewej prowadzi do znacznie większego terytorium niż kąt ostry na diagramie po prawej. W dodatku, narożny pionek na kącie wypukłym (jak trójka na C4) może być umieszczony w bardzo naturalny sposób: Czerwony potrzebuje linii wzroku z obu stron muru i dodatkowe wsparcie z wewnątrz własnego terytorium, jak pionek F7. Tymczasem czwórka na D4 nie może być naturalnie skonstruowana od wewnątrz czerwonego terytorium. Kąt wypukły potrzebuje co najmniej trójki żeby przetrwać, kąt ostry – co najmniej czwórki. Nie zawsze musisz grać dokładnie na zgięciu terytorium, czasami potrzebujesz po prostu dostatecznie wielu linii wzroku na ten heks – dlatego kąty wypukłe są zasadniczo lepsze od kątów ostrych. Pamiętaj też, że zgięcia twojego terytorium są punktami kluczowymi. Nie powinieneś zapominać o nich w czasie gry, i co do zasady warto spróbować przewidzieć, które heksy będą ograniczać twój obszar. Oczywiście, często będziesz zmuszony zmienić swoje plany w zależności od odpowiedzi przeciwnika – ale wizualizowanie swojego przyszłego kształtu pomoże uporządkować twoją grę.

Rozważmy pozycję z gry pomiędzy testing_qwerty (Czerwony) a komacchin (Biały) ([link do gry](https://tumbleweed.games/log/4160/15/)).

{{< columns >}}
![Diagram 13](13.png)
<--->
![Diagram 14](14.png)
{{< /columns >}}

Czerwony zagrał H14, atakując białą jedynkę na H7. Biały odpowiada grając tarczę na H5. Ten ruch pełni wiele funkcji naraz. Po pierwsze, otwiera Białemu nową linię wzroku: D1-K8. Ponadto, wzmacnia G5 trzecią linią wzroku. W ten sposób, jeżeli Czerwony spróbuje okrążyć Białego (na przykład grając G4), Biały ma już zabezpieczony kąt na G5.
