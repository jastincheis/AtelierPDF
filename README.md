# Atelier PDF

Editor PDF care rulează complet în browser. Fișierele tale nu sunt trimise nicăieri: totul se procesează pe calculatorul tău.

Ce poți face:

- adaugi text (cu diacritice), desene libere, evidențieri și dreptunghiuri
- acoperi cu alb conținut existent din pagină
- inserezi semnătura și imagini
- completezi formulare PDF
- rotești, ștergi și reordonezi pagini, unești mai multe PDF-uri, adaugi pagini goale

---

## Cum pornești programul

Ai două variante:

**A. Online (recomandat)**
Deschide **https://jastincheis.github.io/AtelierPDF** în Chrome, Edge, Firefox sau Safari.
(Funcționează după ce GitHub Pages e activat: Settings → Pages → Deploy from a branch → `main` / `(root)` → Save.)

**B. Pe calculator, fără instalare**
1. Pe pagina repository-ului, apasă butonul verde **Code** → **Download ZIP**.
2. Dezarhivează fișierul.
3. Dă dublu-clic pe `index.html`. Se deschide în browser.

Ai nevoie de internet la prima încărcare, ca să se încarce bibliotecile PDF.

---

## Cum editezi un PDF, pas cu pas

### 1. Deschide fișierul
- Apasă **Deschide** (stânga sus) și alege PDF-ul.
- Sau trage fișierul PDF direct în fereastră.

La pornire vezi un formular de exemplu. Îl poți folosi ca să încerci uneltele înainte să deschizi fișierul tău.

### 2. Alege o unealtă din bara de sus

| Unealtă | Ce face | Cum o folosești |
|---|---|---|
| **Selectează** (V) | Mută, redimensionează și șterge elemente; completezi formulare | Clic pe element ca să-l selectezi, trage ca să-l muți, trage de cercul din colț ca să-l redimensionezi |
| **Text** (T) | Adaugă text | Clic pe pagină unde vrei textul, apoi scrie. Enter = rând nou. Clic în afară ca să termini |
| **Desen** (D) | Desen liber cu mâna | Ține apăsat și desenează |
| **Evidențiază** (H) | Marchează cu culoare transparentă | Trage un dreptunghi peste textul de evidențiat |
| **Formă** (R) | Dreptunghi cu contur | Trage pe pagină |
| **Acoperă** | Ascunde conținut existent sub un dreptunghi alb | Trage peste zona de ascuns |
| **Imagine** | Inserează o poză (PNG, JPG, WEBP, GIF) | Alegi fișierul, apoi dai clic pe pagină acolo unde o vrei |
| **Semnătură** | Semnătură desenată | Semnezi în chenar, apeși **Plasează semnătura**, apoi dai clic pe pagină (oricare) acolo unde o vrei |

### 3. Ajustează culoarea și mărimea
Pe al doilea rând alegi **culoarea**, **grosimea** liniei (pentru desen și forme) și **mărimea textului**.
Dacă ai un element selectat, schimbările se aplică direct pe el.

### 4. Modifică un text existent
PDF-urile nu permit editarea directă a textului deja scris. Procedeul este:
1. Cu **Acoperă**, trage peste textul vechi ca să-l ascunzi.
2. Cu **Text**, scrie textul nou peste zona albă.

### 5. Completează un formular
Dacă PDF-ul are câmpuri de formular, acestea apar ușor colorate în albastru.
Alege **Selectează**, apoi dă clic în câmp și scrie, bifează sau alege din listă.

### 6. Organizează paginile
În bara din stânga (pe telefon, butonul cu pagini din stânga sus) ai miniaturile paginilor. Sub fiecare:
- **↻** rotește pagina cu 90°
- **↑ / ↓** mută pagina mai sus sau mai jos (sau trage miniatura cu mouse-ul)
- **✕** șterge pagina

Butoane utile din bara de sus:
- **Unește PDF** adaugă paginile altui PDF la final.
- **Pagină goală (+)** inserează o pagină A4 albă după pagina curentă.

### 7. Salvează
Apasă **Salvează PDF** (dreapta sus). Fișierul se descarcă cu numele `numele-tău-editat.pdf`.
Originalul rămâne neatins.

---

## Scurtături utile

| Tastă | Acțiune |
|---|---|
| Ctrl+Z (⌘Z pe Mac) | Anulează ultima acțiune |
| Delete / Backspace | Șterge elementul selectat |
| Esc | Deselectează și revine la Selectează |
| V, T, D, H, R | Selectează, Text, Desen, Evidențiază, Formă |
| − / + / procentul | Micșorează, mărește, potrivește pe lățime |

---

## Bine de știut

- La salvare, câmpurile de formular pe care le-ai completat devin parte fixă din pagină și nu mai pot fi editate.
- PDF-urile protejate cu parolă nu pot fi modificate. Deschide întâi o copie fără parolă.
- **Acoperă** ascunde vizual conținutul, dar textul original rămâne în fișier. Pentru date confidențiale, folosește un program de redactare dedicat.
- Poți printa PDF-ul salvat cu toate modificările (deschizi fișierul descărcat și apeși Ctrl+P). Elementele adăugate nu mai pot fi mutate sau modificate în program după salvare, dar apar în fișier și pe hârtie.
