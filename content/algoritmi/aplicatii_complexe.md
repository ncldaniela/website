---
title: "Aplicatii Complexe"
date: 2018-08-20T03:16:20+03:00
weight: 4
draft: false
---

<html>
  <body>
    <div class="wiki" id="content_view" style="display: block;">
<span style="display: block; text-align: center;"><strong>APLICATII COMPLEXE</strong></span><br />
1.Scrieti un program C/C++ care citeste de la tastatura doua siruri de caractere formate din litere mici. Sa se creeze fisierul BAC.TXT in care sa scrie unul din cele doua siruri care se dovedeste a fi o subsecventa a celuilalt sir. Daca cele doua siruri nu au aceasta proprietate atunci in fisierul BAC.TXT se va scrie textul “FARA SOLUTIE”.<br />
<br />
Exemplu:<br />
<br />
Se citesc sirurile: Se afiseaza in BAC.TXT<br />
<br />
Calculator lat<br />
<br />
lat<br />
2.Scrieti un program C/C++ care citeste de la tastatura un numar natural n (2&lt;n&lt;21) si apoi n linii cu cate n numere intregi de cel mult 7 cifre ce formeaza un tablou bidimensional a.<br />
<br />
Sa se afiseze pe ecran diferenta dintre suma elementelor de pe diagonala principala si suma elementelor de pe diagonala secundara a matricei a.<br />
3.Fisierele text X.TXT si Y.TXT contin fiecare numele a 7 persoane, câte un nume pe fiecare linie , fiecare nume având cel mult 15 litere. Stiind ca în fiecare fisier numele sunt memorate în ordine alfabetica, scrieti un program C/C++ care sa citeasca din cele doua fisiere si sa afiseze pe ecran toate numele din cele doua fisiere în ordine alfabetica, separate printr-un spatiu.<br />
<br />
Exemplu :<br />
<br />
Daca fisierul X.TXT are continutul :<br />
<br />
Ana<br />
<br />
Dana<br />
<br />
Daniel<br />
<br />
Ene<br />
<br />
Mara<br />
<br />
Nae<br />
<br />
Paul<br />
<br />
iar fisierul Y.TXT are continutul:<br />
<br />
Angie<br />
<br />
Cora<br />
<br />
Dora<br />
<br />
Horia<br />
<br />
Oana<br />
<br />
Paul<br />
<br />
Tibi<br />
Se va afisa pe ecran :<br />
Ana Angie Cora Dana Daniel Dora Ene Horia Mara Nae Oana Paul Paul Tibi<br />
4. Scrieti programul C/C++ care scrie de la tastatura un numar natural n (n&lt;100) si un sir cu n numere intregi din intervalul [100 ;999] ; programul construieste un sir de numere rezultat prin inlocuirea fiecarui numar din sirul citit cu numarul obtinut prin interschimbarea cifrei unitatilor cu cifra sutelor. umerele din noul sir se vor afisa pe ecran separate printr-un singur spatiu.<br />
<br />
De exemplu , pentru n=3 si sirul 123 , 904 , 500 , se afiseaza 321 , 409 , 5.<br />
5.Doua tablouri unidimensionale a si b , cu elementele a1 , a2 , … , an , respctiv b1 , b2 , … bn sunt in relatia a&lt;=b daca : a1&lt;=b1 , a2&lt;=b2 , … , an&lt;=bn. Scrieti program in limbajul C/C++ care citeste doua tablouri unidimensionale a si b cu acelasi numar de elemente de tip intreg si verifica daca a&lt;=b sau b&lt;=a afisand un mesaj adecvat.<br />
6.Scrieti subprogramul sortare care primeste prin intermediul parametrului a un tablou unidimensional de numere reale cu 1000 de componente si prin intermediul parametrilor i si j doua numere intregi , 1&lt;=i&lt;j&lt;=1000. Subprogramul realizeaza ordonarea crescatoare a elementelor ai , ai+1 , … , aj.<br />
7. Scrieti programul C/C++ care citeste de la tastatura elementele unui vector x cu 1000 de numere reale si care ordoneaza crescator termenii sirului. Programul va afisa pe ecran noile valori ale vectorului x separate intre ele prin spatiu.<br />
8. Intr-un sistem de coordonate carteziene se considera punctele A(x1,y1) si B(x2,y2), unde coordonatele intregi x1 , y1 , x2 , y2 sunt , in aceasta ordine , urmatorii termini consecutive ai sirului Fibonacci : fn , fn+1 , fn+2 , fn+3 (n natural).Scrieti un program C/C++ care citeste de la tastatura un numar natural n (1&lt;=n&lt;=20) , determina si afiseaza pe ecran cele doua puncte A si B astfel determinate.<br />
9.Într-o lista simplu înlantuita alocata dinamic, fiecare element retine în câmpul info un numar natural cu cel mult noua cifre si in câmpul adru adresa elementului urmator din lista. Scrieti subprogramul divizor, care prin parametrul p primeste adresa primului element al listei descrise mai sus, prin parametrul x primeste un numar natural cu cel mult noua cifre si care afiseaza pe ecran, câte unul pe linie numerele din lista care au exact un divizor comun cu x. Daca în lista nu exista un astfel de element atunci se va afisa mesajul “problema nu are solutie”.<br />
10.Fisierele text f1.txt si f2.txt contin , fiecare , elementele a cate unui sir de numere reale a , respective b.Fisierele contin numere distincte scrise pe o linie si separate printr-un singur spatiu. Scrieti un program in limbajul C/C++ care citeste cele 2 siruri de numere din fisierele f1.txt si f2.txt si care scrie in fisierul f3.txt toate elementele comune sirurilor a si b , pe o linie si separate printr-un spatiu.<br />
<br />
Exemplu : Daca continutul fisierelor f1.txt si f2.txt este : 10.3, 2.05, 5, 7.12, respectiv 67 , 7.12 , 5 , 3 , 7.33 , 9 , atunci f3.txt va contine : 7.12, 5. (10p.)<br />
11. Scrieti un program in limbajul C/C++ care afiseaza toate numerele naturale formate din cifre identice , mai mari decat 10 si mai mici decat o valoare data n, n&lt;=2.000.000.000.<br />
<br />
De exemplu pentru n=195 , se afiseaza : 11 , 22 , 33 , 44 , 55 , 66 , 77 , 88 , 99 , 111.<br />
12. Prin asocierea fiecarei litere mici din alfabetul englez cu un numar egal cu pozitia cifrei in alfabet, se poate codifica orice secventa de litere mici cu o secventa de numere. Scrieti un program C/C++ care citeste din fisierul text cod.txt un numar n (0&lt;n&lt;30000) si, de pe randul urmator , o secventa de n litere mici. Programul va codifica secventa de caractere citita si va scrie pe ecran numerele asociate, separate prin spatii.<br />
<br />
Exemplu : pentru fisierul cod.txt : 7<br />
<br />
bacinfo<br />
<br />
se vor afisa pe ecran , in ordine , numerele :<br />
<br />
2 1 3 9 14 6 15<br />
13. Scrieti un program C/C++ care citeste de la tastatura trei numere naturale x, y si k, (1&lt;x&lt;y&lt;2000000, k&lt;1000) si afiseaza pe ecran k numere prime din intervalul [x, y]. Daca nu exista k numere prime în intervalul [x,y] se vor afisa toate numerele prime gasite iar pe linia urmatoare se va afisa mesajul “s-au gasit mai putine numere prime: ” urmat de numarul acestora. De exemplu, pentru x=3, y=12 si k=5 se vor afisa pe ecran:<br />
<br />
3 5 7 11<br />
<br />
s-au gasit mai putine numere prime:4<br />
14. Scrieti un program C/C++ care citeste un numar natural nenul par, n, n&lt;100 si apoi n numere naturale de cel mult 4 cifre fiecare si determina cea mai mare suma care poate fi obtinuta adunand numai o jumatate din toate numerele naturale citite. Rezultatul se va afisa pe ecran.<br />
<br />
De exemplu, pentru n=6 si numerele 728 , 10 , 103 , 44 , 1000 , 94 se va afisa : 1831 (reprezentand suma : 728+103+1000).<br />
15. Scrieti un program C/C++ care citeste din fisierul text BAC.TXT , cel mult 100 de numere naturale aflate pe o singura linie , formate din cel mult 9 cifre fiecare , separate prin spatii si dintre aceastea le afiseaza pe ecran doar pe acelea care au proprietatea de a fi palindrom. Daca nu se gasesc numere palindrom, se va afisa pe ecran valoarea –1. Un numar are proprietatea de a fi palindrom daca citit de la dreapta la stanga sau de la stanga la dreapta are aceeasi valoare. De exemplu 1221 este palindrom, in timp ce 1210 nu este palindrom.<br />
<br />
Exemplu : daca din fisierul BAC.TXT se citesc numerele : 7341 , 8228 , 660 , 2 , 80 , 131 , atunci pe ecran se vor afisa : 828 , 2 , 131.<br />
16. Scrieti un program C/C++ care citeste un numar natural nenul n (n&lt;100) si un sir de n numere naturale nenule de cel mult 4 cifre fiecare, si care afiseaza pe ecran sirul ordonat crescator in functie de suma cifrelor corespunzatoare fiecarui termen al sau. Daca doua numere au aceeasi suma a cifrelor se va afisa cel mai mic dintre ele. De exemplu pentru n=5 si numerele 701, 1000, 49, 99, 143, se va afisa sirul 1000 44 143 701 99.<br />
17. Pentru orice numar natural nenul n definim n factorial (notat n!) ca fiind produsul tuturor numerelor naturale nenule mai mici sau egale cu n (n! = 1*2*3*…*n) De exemplu : 3!=1*2*3=6 5!=1*2*3*4*5=120 . Scrieti un program C/C++ care determina a numarul de cifre nule aflate pe ultimile pozitii consecutive ale valorii obtinute in urma evaluarii lui n!, n fiind un numar natural de cel mult 4 cifre. De exemplu daca n=10, n!=3628800 rezultatul va fi 2 deoarece 3628800 are doi de 0 la sfarsit.<br />
18. Scrieti un program C/C++ care citeste de la tastatura un numar natural nenul n de cel mult 4 cifre si afiseaza pe ecran numarul de cifre nule aflate la sfarsitul lui n! De exemplu pentru n=6 se va afisa 0.<br />
19. Scrieti un program C/C++ care citeste din fisierul text DATE.IN cel mult 100 de numere naturale nenule aflate pe o singura linie, formate din cel mult 4 cifre fiecare, separate prin spatii si scrie in fisierul DATE.OUT, in ordine inversa fata de cea in care au fost citite pe o singura linie separate prin spatii. De exemplu daca din fisierul DATE.IN se citesc numerele 93 207 15 1982 3762, atunci continutul fisierului DATE.OUT va fi 3762 1982 15 207 93.<br />
20. Scrieti un program C/C++ care citeste de pe prima linie a fisierului text BAC.TXT , cel mult 100 de numere naturale nenule formate din cel mult 4 cifre fiecare , separate prin spatii si afiseaza pe ecran cifra care apare de cele mai multe ori in scrierea numerelor citite. Daca exista mai multe cifre care apar de cele mai multe ori , se vor afisa toate acestea. De exemplu , daca din fisier se citesc numerele : 90 , 73 , 109 , 1248 , 2771 , atunci afiseaza 1 , 7 , deoarece fiecare dintre aceastea apare de 3 ori.<br />
21. Scrieti un program C/C++ care citeste de pe prima linie a fisierului text BAC.TXT trei numere naturale a, b, c formate din cel mult patru cifre fiecare, separate prin cate un spatiu si afiseaza pe ecran cel mai mare divizor comun al acestora. De exemplu, daca din fisier se citesc numerele : 9 27 15, atunci se afiseaza 3.<br />
22. Se considera programul pseudocod în care s-a folosit notatia [x] pentru partea întreaga a lui x.<br />
<br />
citeste n (numar natural)<br />
<br />
repeta<br />
<br />
n &lt;- [n\10]<br />
<br />
pâna când n&lt;10<br />
<br />
scrie n<br />
<br />
Scrieti algoritmul pseudocod echivalent cu algoritmul dat, dar care sa utilizeze un alt tip de structura repetitiva.<br />
23. Se considera programul pseudocod în care s-a folosit notatia [x] pentru partea întreaga a lui x.<br />
<br />
citeste n (numar natural)<br />
<br />
repeta<br />
<br />
n &lt;- [n\10]<br />
<br />
pâna când n&lt;10<br />
<br />
scrie n<br />
<br />
Scrieti programul pentru algoritmul dat si care sa afiseze si numarul de repetitii efectuate de algoritm.<br />
24. Se considera subprogramul numar, care:<br />
<br />
– primeste prin intermediul unicului sau parametru, a, un numar natural de cel mult 4 cifre;<br />
<br />
– returneaza numarul divizorilor lui a;<br />
<br />
Scrieti un program care stabileste daca un numar este prim utilizând aceasta functie.<br />
25. Scrieti un program care verifica daca un numar natural k(1&lt;k2.<br />
<br />
De exemplu, daca a=3 si b=5 atunci se va afisa « Da », iar pentru a=21 si b=5 se va afisa mesajul « Nu ».<br />
27. Se considera fisierul text date.in care contine exact 899 numere distincte formate fiecare din cate 3 cifre.Sa se afiseze in fisierul text date.out numarul format din 3 cifre care lipseste din fisierul date.in.<br />
28. Se citesc 2 numere naturale nenule m , n(2&lt;m, n&lt;20). Sa se scrie programul C/C++ care construieste în memorie o matrice A cu m linii si n coloane cu proprietatea ca elementul A[i][j] este egal cel mai mare divizor comun dintre numerele i si j. Matricea se va afisa pe ecran, câte o linie a matricei pe câte o linie a ecranului, elementele fiecarei linii fiind separate prin spatii. De exemplu pentru m=3 si n=4 se va afisa matricea urmatoare :<br />
1 1 1 1<br />
<br />
1 2 1 2<br />
<br />
1 1 3 1<br />
29. Se citeste de la tastatura un numar natural nenul n (n&lt;1000). Scrieti un program C/C++ care construieste fisierul text bac.txt care sa contina, pe prima linie, toti divizorii lui n in ordine strict descrescatoare. Divizorii vor fi separati prin spatiu. De exemplu, daca n=10 , atunci fisierul bac.txt va contine : 10 , 5 , 2 , 1<br />
30. Se considera fisierul text Cuvinte.in ce contine pe prima linie un numar natural nenul n (n&lt;=100) iar pe urmatoarele n linii cate un cuvant cu maximum 10 caractere. Sa se afiseze pe ecran cuvintele din fisierul dat care sunt palindroame. In cazul in care nu exista nici un cuvant palindrom se va afisa mesajul ”NU” .Un cuvant este palindrom daca citindu-l de la dreapta la stanga sau de la stanga la dreapta se obtine acelasi cuvant.<br />
<br />
De exemplu daca fisierul Cuvinte.in are urmatorul continut :<br />
<br />
3<br />
<br />
sas<br />
<br />
creion<br />
<br />
Ion<br />
<br />
aunci se va afisa pe ecran :<br />
<br />
sas<br />
31. Scrieti definitia unui subprogram sdiv cu doi parametri, subprogram care:<br />
<br />
– primeste prin intermediul parametrului n, un numar întreg de maxim 9 cifre;<br />
<br />
– returneaza prin intermediul celui de al doilea parametru k suma tuturor divizorilor lui n.<br />
<br />
De exemplu pentru valoarea 6 a lui n, valoarea lui k va fi 12.<br />
32. Scrieti un program C/C++ care determina primele p perechi distincte de numere prietene. Fiecare pereche va fi afisata pe câte un rând, iar elementele unei perechi vor fi separate prin câte un spatiu. Doua numere naturale distincte a si b sunt numere prietene daca a este egal cu suma divizorilor lui b mai mici decât b, iar b este egal cu suma divizorilor lui a mai mici decât a. Valoarea numarului p se citeste de la tastatura. (1&lt;=p&lt;=8).<br />
<br />
De exemplu pentru p=3 se vor afisa :<br />
<br />
220 284<br />
<br />
1184 1210<br />
<br />
2620 2924<br />
33. Se citeste de la tastatura un numar natural nenul n care are cel mult 9 cifre. Sa se afiseze in fisierul Date.out numarul k, natural, astfel incat produsul 1*2*…*(k-1)*k sa aiba o valoare cat mai apropiata de numarul n. De exemplu, daca se citeste numarul n=25 fisierul Date.out are urmatorul continut: 4. iar daca se citeste numarul n=119 fisierul Date.out are urmatorul continut: 5<br />
34.Pentru o valoare n(numar natural, 1&lt;=n1 cu maximum 9 cifre, si afiseaza valoarea celui mai mic divizor prim a lui n, precum si puterea la care acest divizor apare in descompunerea in factori primi a numarului n.<br />
36. Scrieti programul C/C++ care citeste de la tastatura doua numere naturale n si x (x,n &gt;1), cu maximum 9 cifre si verifica daca n este divizibil cu 2¬¬¬¬¬¬x. Programul afiseaza DA in caz afirmativ si NU in caz contrar.<br />
37. Se citeste de la tastatura un numar natural n (1&lt;=n&lt;=100).Sa se afiseze pe ecran al n-lea termen al sirului 11,22,33,44,55,66,77,88,99,111,222,333,444,etc.<br />
<br />
De exemplu, daca n=11 se afiseaza 222.<br />
38. Scrieti programul C/C++ care citeste de la tastatura un numar natural n (2&lt;n&lt;30) si construieste in memorie o matrice patratica de n linii si n coloane formata numai din valori ce apartin multimii {1,2,3,…,n} astfel incat elementele din matrice situate pe diagonala secundara sa fie egale cu n, elementele situate pe celelalte doua « semidiagonale » paralele cu diagonala secundara, de o parte si de lata a acesteia, sa fie egale cu n-2 etc. Matricea se va afisa pe ecran cate o linie a matricei pe cate o linie a ecranului, cu spatii intre elementele fiecarei linii (ca in exemplu).<br />
<br />
De exemplu, pentru n=5 se construieste in memorie si se afiseaza matricea :<br />
1 2 3 4 5<br />
<br />
2 3 4 5 4<br />
<br />
3 4 5 4 3<br />
<br />
4 5 4 3 2<br />
<br />
5 4 3 2 1<br />
39. Scrieti programul C/C++ care citeste de la tastatura un sir s de cel mult 30 de caractere si un caracter c ; programul realizeaza dublarea fiecarei aparitii a caracterului c in s si scrie noul sir obtinut in fisierul text BAC.TXT.<br />
<br />
De exemplu, daca se citeste sirul alfabetar si caracterul a atunci fisierul BAC.TXT va contine sirul : aalfaabetaar.<br />
40. Scrieti un program care citeste de la tastatura doua siruri de caractere, fiecare sir fiind format din cel mult 100 de litere din alfabetul englez, si care afiseaza mesajul « DA » daca toate literele din primul sir se gasesc in cel de-al doilea sir, nu neaparat in aceeasi ordine si de acelasi numar de ori, sau mesajul « NU » in caz contrar. De exemplu, daca primul sir este « baraca » iar cel de-al doilea sir este « abracadabra », programul trebuie sa afiseze mesajul « DA » deoarece literele primului sir apar in cel de-al doilea sir.<br />
41. Pe prima linie a fisierului text BAC.TXT se afla un numar natural nenul n (2&lt;=n&lt;1000000), iar pe a doua linie a fisierului se afla un sir format din n numere intregi, despartite prin cate un spatiu, fiecare numar fiind format din cel mult 4 cifre. Stiind ca in fisier exista cel putin un numar strict pozitiv, se cere sa se afiseze lungimea maxima a unei secvente din sir care are proprietatea ca este formata doar din valori strict pozitive. O secventa a unui sir este format dintr-unul sau mai multe elemente aflate pe pozitii consecutive. Alegeti o metoda eficienta de rezolvare atat ca timp de executare, cat si ca gestionare a memoriei.<br />
<br />
De exemplu, daca fisierul BAC.TXT are continutul<br />
<br />
10<br />
<br />
7 22 -3 10 3 14 0 21 10<br />
<br />
atunci programul trebuie sa afiseze pe ecran doar valoarea 3, deoarece in sirul considerat exista mai multe secvente care sunt formate doar din numere strict pozitive, dar lungimea maxima a unei astfel de secvente este 3.<br />
42. Se citesc de la tastatura patru numerere naturale nenule a,b,c,d. Scrieti un program C/C++ care sa afiseze rezultatul expresiei a/b+c/d sub forma unei fractii ireductibile.<br />
43. Se citesc de la tastatura patru numerere naturale nenule a,b,c,d. Scrieti un program C/C++ care sa afiseze rezultatul expresiei a/b*c/d sub forma unei fractii ireductibile.<br />
<span>44. Se citesc de la tastatura patru numerere naturale nenule a,b,c,d cu care se formeaza numerele complexe z=(a,b) si t=(c,d). Scrieti un program C/C++ care sa afiseze pe ecran rezultatul expresiei z*t.</span><br />
<span> 45. Se citesc de la tastatura patru numerere naturale nenule a,b,c,d cu care se formeaza numerele complexe z=(a,b) si t=(c,d). Scrieti un program C/C++ care sa afiseze rezultatul expresiei z/t.</span>
    </div>
  </body>
</html>