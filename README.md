# 🎯 ENS AVALUEM - Web App d'Autoavaluació (PCMAT)

Una aplicació web interactiva i lleugera dissenyada per a l'alumnat de primària i secundària dins del marc del **Programa PCMAT (Departament d'Educació)**. Permet realitzar una autoavaluació inicial o final de conceptes matemàtics i de manipulació/robòtica (com la successió de Fibonacci, angles de gir, patrons i treball cooperatiu) i exportar el resultat directament com a imatge en format PNG/PDF per al seu lliurament o coavaluació.

---

## 📸 Característiques Principals

- **Fidelitat al disseny original:** Manté l'estètica oficial de les fitxes del programa PCMAT (colors, banners estil pinzellada, logotips i tipografies).
- **Interactivitat d'un sol clic:** Sistema de caselles de selecció d'opció única per fila amb tics vectorials centrats d'alta precisió.
- **Exportació d'alta resolució:** Integració amb `html2canvas` per descarregar la fitxa omplerta amb el nom de l'alumne/a sense desplaçaments visuals.
- **Comptador de progrés:** Mostra en temps real quants ítems s'han avaluat.
- **Sense backend ni dependències complexes:** Funciona directament a qualsevol navegador web sense necessitat d'instal·lar servidors ni bases de dades. Ideal per a entorns d'aula amb tauletes o ordinadors.

---

## 🛠️ Tecnologies Utilitzades

- **HTML5:** Estructura semàntica del document i la taula d'avaluació.
- **CSS3 / Tailwind CSS:** Disseny *responsive*, flexbox, estils vectorials per als requadres de selecció i la capçalera personalitzada.
- **JavaScript (Vanilla):** Lògica de selecció interactiva, control de progrés i gestió de la data actual.
- **[html2canvas](https://html2canvas.hertzen.com/):** Llibreria per a la conversió del node DOM a imatge descarregable (PNG).

---

## 🚀 Com Utilitzar l'Aplicació

### Opció A: En local (sense connexió a Internet)
1. Descarrega o clona aquest repositori:
   ```bash
   git clone https://github.com/el-teu-usuari/ens-avaluem-pcmat.git
   ```
2. Obre el fitxer `index.html` amb qualsevol navegador web (Google Chrome, Mozilla Firefox, Safari, Microsoft Edge).

### Opció B: Desplegament a GitHub Pages
1. Aneu a la secció **Settings** del repositori a GitHub.
2. Navegueu a **Pages** (al menú lateral esquerre).
3. A **Branch**, seleccioneu `main` (o `master`) i feu clic a **Save**.
4. En pocs minuts tindreu un enllaç públic web per compartir amb l'alumnat.

---

## 📋 Criteris d'Avaluació Inclosos

L'aplicació inclou els 8 ítems d'autoavaluació inicials:
1. Concepte de successió numèrica i cerca de regles.
2. Continuació de successions.
3. Concepte de la successió de Fibonacci.
4. Identificació de regularitats i prediccions.
5. Relació entre nombres i formes geomètriques.
6. Comprensió i mesura d'angles de gir.
7. Programació i instruccions precises a robots.
8. Treball cooperatiu i planificat.

---

## 📄 Llicència

Aquest projecte és de lliure ús educatiu. Desenvolupat per a l'aula en el marc del projecte d'aprenentatge matemàtic **PCMAT**.