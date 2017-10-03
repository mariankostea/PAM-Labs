
## Lab-2 Organiser Mobile Application (DAILY PLANNER)

#### Obiectivele

De realizat aplicație tip Organiser pe platforma aleasă.
La formarea și proiectarea aplicațiilor sunt introduse puncte stricte,
ce sunt obligatorii de respectat. La discreția personală rămâne designul aplicației
și API-ul/Framework-ul în care va fi dezvoltată aplicația. Componentele și 
structura fiecărei Activități va fi descrisă mai jos.

UI Components
Aplicația va conține minim 3 Activități de baza care vor fi numerotate în lucrare sub forma:

**1. MainActivity (structura/componente)**
- Calendar View (custom or default)
- Buttons (Add/Remove/Update)
- Căutare (caută conform cuvintelor cheie)

**2. Add Activity**
- Data/Time controller
- Info TextBox
- Buttons (și altele la discreție conform specificului aplicației)

**3. Update Activity** - practic e una și aceeași activitate de la Add, doar ca completata deja.

Datele operaționale din interiorul aplicației vor fi stocate în fișier/e XML forma cărora rămâne la discreția 
personală. 

**Logical/Operational Component**

Toate evenimentele și acțiunile de notificare/semnalizare (sonore/vizuale) intreprinse în Organiser
vor fi tratate într-un serviciu aparte, care logic funcțional va extrage datele din acel fișier XML.
