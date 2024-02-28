# PLSQL-SGBD
Sisteme de Gestiune a Bazelor de Date

Proiectați și implementați o bază de date relațională folosind SGBD-ul Oracle Database versiunea 11g sau o versiune ulterioară acesteia (minim 6 entități independente în diagrama entitate-relație (ERD) și cel puțin o relație de tip many-to-many).

Cerințe obligatorii pentru a lua în considerare proiectul:
1. Prezentați pe scurt baza de date (utilitatea ei).
2. Realizați diagrama entitate-relație (ERD): entitățile, relațiile și atributele trebuie definite în limba
română (vezi curs SGBD / model de diagrama ERD; nu se va accepta alt format).
3. Pornind de la diagrama entitate-relație realizați diagrama conceptuală a modelului propus, integrând
toate atributele necesare: entitățile, relațiile și atributele trebuie definite în limba română.
4. Implementați în Oracle diagrama conceptuală realizată: definiți toate tabelele, definind toate
constrângerile de integritate necesare (chei primare, cheile externe etc).
5. Adăugați informații coerente în tabelele create (minim 5 înregistrări pentru fiecare entitate
independentă; minim 10 înregistrări pentru tabela asociativă).
6. Formulați în limbaj natural o problemă pe care să o rezolvați folosind un subprogram stocat
independent care să utilizeze toate cele 3 tipuri de colecții studiate. Apelați subprogramul.
7. Formulați în limbaj natural o problemă pe care să o rezolvați folosind un subprogram stocat
independent care să utilizeze 2 tipuri diferite de cursoare studiate, unul dintre acestea fiind cursor
parametrizat, dependent de celălalt cursor. Apelați subprogramul.
8. Formulați în limbaj natural o problemă pe care să o rezolvați folosind un subprogram stocat
independent de tip funcție care să utilizeze într-o singură comandă SQL 3 dintre tabelele definite.
Definiți minim 2 excepții proprii. Apelați subprogramul astfel încât să evidențiați toate cazurile
definite și tratate.
9. Formulați în limbaj natural o problemă pe care să o rezolvați folosind un subprogram stocat
independent de tip procedură care să utilizeze într-o singură comandă SQL 5 dintre tabelele
definite. Tratați toate excepțiile care pot apărea, incluzând excepțiile NO_DATA_FOUND și
TOO_MANY_ROWS. Apelați subprogramul astfel încât să evidențiați toate cazurile tratate.
10. Definiți un trigger de tip LMD la nivel de comandă. Declanșați trigger-ul.
11. Definiți un trigger de tip LMD la nivel de linie. Declanșați trigger-ul.
12. Definiți un trigger de tip LDD. Declanșați trigger-ul.
Cerințe opționale pentru nota finală N >= 6:
13. Definiți un pachet care să conțină toate obiectele definite în cadrul proiectului
