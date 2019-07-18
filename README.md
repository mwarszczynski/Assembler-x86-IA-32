# Assembler-x86-IA-32

**OS:**
> Ubuntu

**Compilator:**
> GCC, GAS

**Syntax:**
> AT&T

**Required packages:**
> suggest latest

**Compilation:**
> as --32 --gstabs zad1.s -o zad1.o 
> ld -melf_i386 zad1.o
> gdb a.out

**Listing in debugger:**
> l

**Set the break:**
> b 14

**Run**
> r

**Info, run:**
> i
> r

** Remember to give one empty line below 'NOP'**

b 14 -> breakpoint na 14 lini (przed NOP - za NOP linia wolna)
r -> run
i r -> info run


**Below description and commands about Assembler-x86-IA-32 scripts / Ponizej polecenia i krótkie opisy zadan.**

1.a Funkcja do wyznaczania kwadratu wartosci parametru, argument przez EAX, wynik przez EAX

1.b. argument przez stos, wynik przez EAX, argument przez stos, wynik przez EAX

2.a. Funkcja do wyznaczania modulo wartosci parametru, argument przez EAX, wynik przez EAX

2.b. Funkcja do wyznaczania modulo wartosci parametru, argument przez stos, wynik przez EAX

3. Napisz program do wyznaczenia liczby elementow o wartosci > 0.

4. Napisz program do wyznaczenia sredniej arytmetycznej elementow o wartosci > 0.

5. Napisz program do wypelniania tablicy liczb calkowitych wartosciami kwadratu indeksu (kolejno: 0,1,4,9,16,25).

6. Napisz program do sprawdzania, czy tablica liczb jest posortowana rosnaco.

7.a. Funkcja do wyznaczania wartosci wiekszej z dwoch parametrow (parametry przez rejestry EBX, ECX, wynik przez EAX)

7.b. Funkcja do wyznaczania wartosci wiekszej z trzech parametrow (parametry przez stos, wynik przez rejestr EAX)

8. Funkcja do sprawdzania, czy wartosc parametru jest liczba pierwsza.

9. Prosze przedstawic implementacje funkcji wraz z przykladem wywolania do wyznaczania najbardziej znaczacej cyfry rozwiniecia dziesietnego wartosci przekazanej jako parametr przez rejestr EAX. Wynik zwracany rowniez przez rejestr EAX.

10. Napisz program do sprawdzania, czy wartosci umieszczone w rejestrach EBX,ECX,EDX moga byc dlugosciami bokow trojkata. Wynik (wart 1, ozbacza TAK, lub 0 oznaczajaca NIE) ma zostac umeiszczony w rejestrze AL.

11. Napisz program do sprawdzania, czy wartosci umieszczone w rejestrach EBX,ECX,EDX moga byc dlugosciami bokow trojkata prostakatnego. ynik (wart 1, ozbacza TAK, lub 0 oznaczajaca NIE) ma zostac umeiszczony w rejestrze AL.

12. EBX <- [^ECX^], czyli umiesc w EBX najmniejsza wartosc calkowita, ktorej kwadrat jest wiekszy lub rowny zawartosci rejestru ECX (sprawdzajac kolejne liczby poczawszy od 1, podnoszac je do kwadratu i porownujac z zawartoscia rejestru ECX)

13. Sumowanie wartosci tablicy
