# Proiect-individual
DentalFS
![](RackMultipart20220104-4-1mzywmj_html_a0d28d9785ef96ed.png)

**UNIVERSITATEA DE VEST DIN TIMIȘOARA**

**FACULTATEA DE MATEMATICĂ ȘI INFORMATICĂ**

**INFORMATIC**** Ă APLICATĂ**

**SG. 3**

# **Documentație**

# **DENTALFS**

_ **Proiect Individual 2021-2022** _

**Student: DUTCĂ COSMINA-LAVINIA**

Timișoara

IANUARIE 2022

# Cuprins

Introducere

Capitolul 1. ………………………………………………………………………………………………………………………………………

Capitolul 2. ………………………………………………………………………………………………………………………………………
 2.1. Funcționalitățile aplicației
 2.2. Dependințe și tehnologii folosite
 2.3. Configurația sistemului
 2.4. Setul de date

Capitolul 3. ………………………………………………………………………………………………………………………………………
 3.1. Manual de utilizare

Capitolul 4. ………………………………………………………………………………………………………………………………………

Capitolul 5. ………………………………………………………………………………………………………………………………………

Capitolul 6. ………………………………………………………………………………………………………………………………………

Referințe bibliografice

# Introducere

- Motivația alegerii temei:

Am ales această temă pentru a veni în ajutorul medicilor stomatologi cu o variantă mai simplă și mai utilă de contorizare a datelor și materialelor necesare gestionării unui cabinet. Aplicația va trebui să fie funcțională, să preia toate informațiile din bazele de date, să aibă o interfață grafică ușor de utilizat și cu cât mai multe facilități.

- Scopul și obiectivele lucrării:

Lucrarea este destinată introducerii în utilizarea aplicației DENTALFS și urmărește evoluția proiectului în amănunt.

- Ce se dorește a fi implementat:

Aplicație desktop pentru gestionarea datelor din cadrul unui cabinet stomatologic.

- Potențiali utilizatori / domeniu de aplicabilitate:

Medicină dentară – medici stomatologi care dețin un cabinet stomatologic.

- Scurtă prezentare a lucrării pe capitole:

Va fi prezentată aplicația și avantajele pe care aceasta le aduce(cap.1), funcționalitățile, tehnologiile și limbajele introduse, structura arhitecturală a proiectului prin diagrame și schițe ale claselor/ bazelor de date(cap.2), iar mai apoi va fi prezentat stadiul actual al proiectului prin imagini cu interfața grafică(cap.3). Spre final va putea fi observat traseul parcurs pentru realizarea proiectului. (cap.4) Apoi vom avea detalii despre ce s-a implementat și direcții viitoare ale aplicației(cap.5 + cap.6)

# Capitolul 1.

Consider mult mai utilă și avantajoasă stocarea informațiilor necesare gestionării unui cabinet medical în cadrul unei aplicații web. Astfel, sunt excluse hârtiile și dosarele, fiind necesar doar un calculator.

Pe piață există o varietate de produse utilizate în domeniu, însă această aplicație va fi una mult mia simplu de utilizat și mult mai compactă. (https://www.jotform.com/blog/dental-app/)

1. Solutionreach

![](RackMultipart20220104-4-1mzywmj_html_735eb704b7db746f.png)

### 2. RevenueWell

![](RackMultipart20220104-4-1mzywmj_html_1e7da67c0f164c7d.png)

3. LocalMed

![](RackMultipart20220104-4-1mzywmj_html_767844fdcfdce3ef.png)

# Capitolul 2.

## Aplicația este realizată cu ajutorul IntelliJ pentru Java, completat de SceneBuilder pentru JavaFX și XAMPP pentru localhost și baze de date.

## 2.1. Funcționalitățile aplicației

- Patients:

  - Vizualizarea tuturor pacienților
  - Vizualizare fișe medicale
  - Adăugare pacient
  - Căutare pacient după nume sau după număr de telefon

- Appointments:

  - Vizualizarea tuturor programărilor
  - Vizualizarea tuturor programărilor dintr-o zi
  - Adăugare programare
  - Actualizare programare existent
  - Anulare programare existentă

- Instruments:

  - Vizualizare stoc instrumente
  - Adăugare instrument nou
  - Adăugare stoc nou
  - Vizualizare sterilizări
  - Adăugare sterilizări

### 2.2. Dependinte si tehnologii folosite

Limbaje utilizate pentru realizarea proiectului: Java, JavaFX, MySQL.

Pentru bazele de date se utilizeaza XAMPP pentru local host. (fisierele cu toate comenzile MySQL pentru generarea bazei de date vor fi atașate la proiect)

## 2.3 Configurația sistemului

![](RackMultipart20220104-4-1mzywmj_html_34db693035ef4f6a.png)

![](RackMultipart20220104-4-1mzywmj_html_9d020d0d05111fc6.png)

## 2.4 Setul de date

![](RackMultipart20220104-4-1mzywmj_html_f9904aa0e25ed990.png)

# Capitolul 3.

## A fost realizată toată implementarea proiectului.

![](RackMultipart20220104-4-1mzywmj_html_6b883acc25a68f15.png)

![](RackMultipart20220104-4-1mzywmj_html_b530dec4bcc062d5.png) ![](RackMultipart20220104-4-1mzywmj_html_e151a3a6c77ad322.png)

![](RackMultipart20220104-4-1mzywmj_html_a6e0c971aa16bbc4.png) ![](RackMultipart20220104-4-1mzywmj_html_690c5efe563bd2cb.png)

![](RackMultipart20220104-4-1mzywmj_html_5b2d03820c070936.png)

![](RackMultipart20220104-4-1mzywmj_html_9825d80093504d43.png)

![](RackMultipart20220104-4-1mzywmj_html_d25c66b7c5038977.png)

![](RackMultipart20220104-4-1mzywmj_html_f10d263a7d1f674.png)

![](RackMultipart20220104-4-1mzywmj_html_de7f7243910be9e7.png) ![](RackMultipart20220104-4-1mzywmj_html_6cc1e3816dad6e84.png) ![](RackMultipart20220104-4-1mzywmj_html_3ae1d79e4a8a169c.png)

## 3.1. Manualul de utilizare (DOAR PENTRU VARIANTA FINALĂ)

Informații legate de unde se găsește(Link Github), cum se instalează, cum se foloseste.

# Capitolul 4.

| **ID** | **Data** | **Obiectiv** | **Descriere** | **Status** | **Obs.** |
| --- | --- | --- | --- | --- | --- |
| 1 | 01.10.2021 | Definirea temei | Alegere temă | Done | - |
| 2 | 28.10.2021 | Predare Livrabil1
 Tema de proiect | Finalizare schiță 1 proiect | Done | -clase
 -baze de date
 -funcționalități |
| 3 | 10.11.2021 | Identificarea functionalităților | Funcționalități mai detaliate | Done | - |
| 4 | 13.11.2021 | Documentare utilizare JavaFX pentru GUI | - | Done | - |
| 5 | 14.11.2021 | Documentare utilizare program pentru implementare GUI | Realizare proiecte tip „schiță&quot; pentru acomodare | Done | - |
| 6 | 17.11.2021
 18.11.2021 | Schiță GUI pagină de start | Interfață + funcții pentru deschidere categorii mari | Done | - |
| 7 | 19.11.2021 | Schiță GUI secțiune &quot;PATIENTS&quot; | - | Done | - |
| 8 | 20.11.2021 | Conectare bază de date | - | Done | - |
| 9 | 21.11.2021 | Schiță GUI secțiune &quot;INSTRUMENTS&quot; | - | Done | - |
| 10 | 22.11.2021 | Schiță GUI secțiune &quot;APPOINTMENTS&quot; | - | Done | - |
| 11 | 23.11.2021 | Prezentare versiune BETA | - | Done | - |
| 12 | 24.11.2021
 25.11.2021 | Finalizare schiță GUI generală | Realizarea interfeței cât mai apropiat de viziunea finală | Done | - |
| 13 | 30.11.2021 | Funcționalități secțiune &quot;INSTRUMENTS&quot; | - | Done | - |
| 14 | 31.11.2021 | Funcționalități secțiune &quot;APPOINTMENTS&quot; | - | Done | - |
| 15 | 01.12.2021 | Funcționalități secțiune &quot;PATIENTS&quot; | - | Done | - |
| 16 | 05.12.2021 | Legături baze de date secțiune&quot;INSTRUMENTS&quot; | - | Done | - |
| 17 | 06.12.2021 | Legături baze de date secțiune&quot;APPOINTMENTS&quot; | - | Done | - |
| 18 | 07.12.2021 | Finalizare date necesare pentru tabele | - | Done | - |
| 19 | 10-17.12.2021 | Completare GUI
 -structura- | - | Done | - |
| 20 | 10-17.12.2021 | Finalizare funcționalități | - | Done | - |
| 21 | 02-03.01.2022 | Finalizare interfață | - | Done | - |
| 22 | 03.01.2022 | Finalizare proiect | - | Done | - |

# Capitolul 5

Am reușit să implementez în proporție de 90%, procent care mă mulțumeste dat fiind faptul că a trebuit să învăț să lucrez cu JavaFX și conexiunea la baza de date. Am atins toate punctele importante, deși consider că ar mai trebui finisat la capitolul performanță, design și ar mai putea fi introduse funcționalități.

# Capitolul 6.

Ca și funcționalități pe care doresc să le implementez, avem în primul rând o galerie foto (poze tip BEFORE and AFTER). Aceasta va fi introdusă în secțiunea &quot;Patients&quot;. Timpul și cunoștințele nu mi-au fost îndeajuns pentru a studia și această parte.
 Mai apoi, aș dori funcționalitate pentru notificări în afara aplicației, pentru ca medical să fie constant pus la curent cu programările.

Design-ul aplicației este și acesta pe lista de viitoare modificări, dorind să aduc posibilitatea de a da RESIZE ferestrelor și de a modifica interfața pentru a da o notă mai rafinată.

Referințe bibliografice

1. JDBC Connection: [https://www.youtube.com/playlist?list=PLkAM0IRskGFo\_RPWzU7qHS6uEoVxsdmF](https://www.youtube.com/playlist?list=PLkAM0IRskGFo_RPWzU7qHS6uEoVxsdmF)6
2. JavaFX:

[https://www.youtube.com/watch?v=fl6Wp1I9wHQ&amp;ab\_channel=GenuineCoder](https://www.youtube.com/watch?v=fl6Wp1I9wHQ&amp;ab_channel=GenuineCoder)
