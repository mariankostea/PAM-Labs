
## Lab-2 RSS feed application

#### Obiectivele

- descarcarea și parsarea fisierelor **.xml**
- afisarea datelor intr-o listă
- familiarizarea cu moduri de stocare a datelor in memorie
- Facebook API

1. O simplă aplicație care ar descărca un RSS feed, l-ar parsa și ar afișa într-o lista conținutul acestuia. Fiecare item din listă trebuie să conțină o imagine, un titlu și un preview de conținut(primele câteva cuvinte din conținutul textului)  **nota 5**

2. RSS feed-ul trebuie să conțină un refresh mecanism, care ar declanșa re-descărcarea xml-ului si reafișarea datelor. **nota 6**

3. Gestionarea feed-urilor. Este posibil de adaugat/șters feed-uri, prin adăugarea/ștergerea url-ului și a unui nume unic pentru feed-ul respectiv. Feed-urile adăugate se vor păstra chiar și după închiderea aplicației. **nota 7**

4. Facebook API, implementarea mecanismului de login pentru utilizarea aplicației **nota 8**

5. Facebook API, adăugarea unui buton la ficare item din listă, care ar face share pe Facebook la itemul respectiv **nota 9**

6. Oflline support. În cazul în care nu este conexiune internet, aplicația ar avea un support offline. Asta ar însemna că fiecare feed care este downloadat, trebuie stocat într-un fisier din internal storage, iar în cazul unui offline, v-a fi citit din memoria telefonului și afișat, însă cu un mesaj care ar spune că aplicația e în offline mode. **nota 10**
