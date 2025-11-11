# Proiect: Automatizarea unui Manipulator cu Două Grade de Libertate

## Descriere generală
Acest proiect face parte din disciplina **Automate și Microprogramare (AMP)** și are ca obiectiv **proiectarea comenzii automate pentru un manipulator cu două grade de libertate**, destinat deservirii a trei mașini-unelte. Proiectul integrează concepte teoretice și practice de **automatizare industrială**, **sinteză logică**, **programare microprocesor**, și **control secvențial al proceselor**.

Manipulatorul este capabil să deplaseze piese între trei mașini-unelte (MU1, MU2, MU3), efectuând cicluri complete de preluare, transport și așezare automată. Sistemul implementează atât un **mod automat**, cât și un **mod manual de comandă și testare**, controlat printr-o interfață logică și un releu programabil.

---

## Metodologie și etape de lucru
Proiectul a fost dezvoltat în mai multe faze, reflectate în documentația tehnică:

1. **Modelarea procesului**
   - Descrierea detaliată a secvenței tehnologice (avans, retragere, prindere, eliberare).
   - Definirea variabilelor primare de intrare și ieșire (senzori, comenzi, acționări).

2. **Sinteza comenzii logice**
   - Elaborarea **grafului de tranziții** și a versiunii reduse.
   - Asignarea stărilor, derivarea funcțiilor de control și implementarea lor cu circuite **SSI** și **MSI**.
   - Construirea **schemelor logice de comandă** și a diagramei de stări.

3. **Implementare pe echipament AP Micro și releu EASY**
   - Programarea microprocesorului utilizând **instrucțiuni simbolice (LC, AND, OR, STO, J)**.
   - Crearea programului de lucru secvențial și a logicii de control pentru modurile Automat / Manual / Reset / Test.
   - Testarea funcționării pe simulatorul **easySoft-Pro v6.98**, utilizând echipamentul **EASY 819-DC-RC**.

---

## Rezultate și concluzii
Rezultatul final constă într-un **sistem complet automatizat** capabil să controleze mișcările manipulatorului în condiții sigure, cu verificarea pozițiilor și sincronizarea ciclurilor de lucru ale mașinilor-unelte.  
Proiectul demonstrează capacitatea de a:
- transforma un proces tehnologic într-un **model automat secvențial**;
- realiza sinteza logică completă (de la graful de tranziții până la implementarea fizică);
- programa și testa controlul pe echipamente **AP MICRO** și **PLC EASY**;
- documenta și optimiza funcțiile de control pentru eficiență și siguranță operațională.

---

## Tehnologii și instrumente utilizate
- **easySoft-Pro v6.98** – dezvoltare și simulare PLC  
- **EASY 819-DC-RC** – releu de control programabil  
- **Diagrame logice și scheme SSI/MSI** – sinteză logică combinatorie  
- **Cod simbolic microprogramat** – limbaj de asamblare pentru controlul secvențial  

---

## Autor
**Chiriac Mihai-Iulian**  
Facultatea de Automatică și Calculatoare – Universitatea Tehnică „Gheorghe Asachi” din Iași  
Proiect realizat în 2025, verificat de conf. dr. ing. Pricop Andrei-Traian.
