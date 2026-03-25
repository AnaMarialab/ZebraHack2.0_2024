# ZebraHack2.0_2024

ZebraHack Challenges
Challenge 4: Aplicație pentru raportarea și gestionarea produselor defecte | Alumil Romania
Descriere
Creează o platformă intuitivă care să permită utilizatorilor să raporteze produse defecte către echipele responsabile și să faciliteze gestionarea eficientă a reclamațiilor. Platforma trebuie să acopere întregul flux al raportării, de la introducerea detaliilor problemei până la analiză și soluționare.

Produsul final trebuie să aibă următoarele funcționalități:

Interfață pentru raportare: Utilizatorii să poată încărca poze cu produsul defect, să descrie problema și să trimită reclamația.
Notificări către responsabili: Reclamațiile să fie trimise direct pe mail către responsabilii cu asigurarea calității
Dashboard pentru analiza reclamațiilor:
Vizualizarea statisticilor (numărul reclamațiilor, tipuri de defecte, timpi de soluționare).
Categorii și filtre pentru o mai bună gestionare a reclamațiilor.
Feedback utilizator: Responsabilii să poată marca reclamațiile ca soluționate, iar utilizatorii să fie notificați.
Important

Se va implementa exclusiv partea de front-end (HTML, CSS, JavaScript);

NU se vor include funcționalități care implică procesare pe server sau integrare cu backend.

Task 1: Header-ul platformei
Header-ul platformei ar trebui să includă identitatea vizuală a platformei cu un logo, un titlu și un meniu de navigare care să permită utilizatorilor să acceseze diferite pagini ale aplicației.

Criterii de acceptare:
Structura de navigare este creată și permite utilizatorilor să acceseze paginile: Acasă, Raportare, Dashboard, Contact.
Header-ul include logo-ul aplicației.
Header-ul include titlul aplicației („Raportează Defecte”).
Meniul de navigare evidențiază pagina curentă pe care se află utilizatorul.
Pe dispozitive mobile, meniul de navigare se restrânge într-un meniu tip hamburger.

Task 2: Pagină de raportare defecte
Pagina principală de raportare defecte trebuie să permită utilizatorilor să trimită reclamații privind produsele defecte.

Criterii de acceptare:
Pagina include un formular vizual care permite utilizatorilor să încarce până la 3 imagini per produs (simulare fără funcționalitate efectivă de upload).
Formularul conține următoarele câmpuri:
Un câmp text pentru descrierea problemei.
O listă derulantă pentru selectarea categoriei defectului (e.g., „Defect estetic”, „Funcționalitate”, „Ambalaj”).
Un buton vizual pentru trimiterea raportului.
Formularul este complet static și nu include procesare backend.
Pagina este complet responsive, adaptându-se corect la diferite dimensiuni de ecran (desktop, tabletă, mobil).
Toată implementarea se face exclusiv în HTML, CSS și JavaScript.

Task 3: Notificare responsabili
Adaugă funcționalitatea vizuală care indică trimiterea reclamației către responsabilii cu asigurarea calității (se implementează exclusiv partea de front-end, axată pe interfața vizuală).

Criterii de acceptare:
După apăsarea unui buton de trimitere, se afișează un mesaj vizual static pe ecran (e.g., „Raportul a fost trimis cu succes!”).
Trimiterea email-ului se realizează cu ajutorul unui formular ce folosește un link de mailto (exemplu)
Mesajul vizual include un buton de închidere manuală și dispare automat după 5 secunde.
Formularul este resetat vizual după afișarea mesajului, simulând o stare inițială (nu implică procesare backend).
Toate elementele și interacțiunile sunt realizate exclusiv în HTML, CSS și JavaScript, fără funcţionalităţi backend.

Task 4: Dashboard de analiză
Creează un dashboard care prezintă vizual statisticile despre reclamații (se implementează exclusiv partea de front-end, axată pe interfața vizuală).

Criterii de acceptare:
Dashboard-ul afișează următoarele informații într-o formă vizuală:
- Numărul total de reclamații trimise, evidențiat în format text.
- Tipurile de defecte reprezentate printr-un grafic static (e.g., bar chart sau pie chart).
- Timpul mediu de soluționare afișat într-o secțiune separată.
Sunt incluse filtre vizuale (dropdown sau butoane) pentru sortarea și organizarea reclamațiilor după tipul defectului sau status.
Dashboard-ul este responsive, adaptându-se corect la diferite dimensiuni de ecran (desktop, tabletă, mobil).
Toate elementele sunt implementate exclusiv folosind HTML, CSS și JavaScript, fără funcționalități backend sau procesare server-side.

Task 5: Feedback pentru utilizatori
Adaugă o funcționalitate vizuală care permite responsabililor să marcheze reclamațiile ca „Soluționate” (se implementează exclusiv partea de front-end, concentrată pe interfața vizuală).

Criterii de acceptare:
Fiecare reclamație afișează statusul actual sub formă de text vizibil („În procesare” sau „Soluționat”).
Responsabilii pot schimba statusul printr-un buton vizibil pe dashboard, simulând o actualizare vizuală.
După schimbarea statusului, este afișată o notificare vizuală statică pentru utilizator (e.g., „Reclamația dumneavoastră a fost soluționată!”).
Notificarea include un buton de închidere manuală și dispare automat după câteva secunde.
Toate elementele și interacțiunile sunt implementate exclusiv în HTML, CSS și JavaScript, fără funcționalități backend sau procesare server-side.

Task 6: Design interfață utilizator (UI)
Interfața vizuală a aplicației trebuie să fie modernă și intuitivă.

Criterii de acceptare:
Toate paginile aplicației utilizează o paletă de culori coerentă și unitară.
Sunt implementate componente interactive, precum butoane cu efecte hover și carduri pentru organizarea informațiilor.
Fonturile utilizate sunt lizibile și uniforme pe toate paginile aplicației.
Bara de navigare este responsive și adaptabilă la diferite dimensiuni de ecran, cu o distribuție vizuală echilibrată a elementelor.

Task 7: Modificare responsive pentru experiențe variate
Aplicația este complet responsive și funcționează eficient pe toate tipurile de dispozitive.

Criterii de acceptare:
Aplicația se afișează corect și funcționează optim pe telefoane, tablete și desktop-uri.
Tabelele mari sunt transformate vizual în liste simplificate pe dispozitive mobile.
Elementele interactive, precum butoanele și formularele, sunt adaptate pentru interacțiuni pe ecrane tactile.
Aplicația se afișează corect și funcționează optim pe telefoane, tablete și desktop-uri.
Tabelele mari sunt transformate vizual în liste simplificate pe dispozitive mobile.
Elementele interactive, precum butoanele și formularele, sunt adaptate pentru interacțiuni pe ecrane tactile.
