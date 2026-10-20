Repartiment d'escons — València

Calculadora educativa del repartiment d'escons mitjançant el mètode d'Hondt. La web està implementada en **un únic fitxer `index.html`**: HTML per a l'estructura, CSS incrustat per a l'estil i JavaScript incrustat per al càlcul. No necessita dependències ni servidor.

Funcionalitats
- Editar el nom de cada partit i el nombre de vots.
- Afegir i eliminar partits.
- Configurar el nombre d'escons i el llindar electoral.
- Veure el total de vots, els percentatges i els escons assignats.
- Recalcular els resultats automàticament al canviar les dades.
- Disseny adaptable a mòbil i ordinador.

Com obrir-la
Obri `index.html` amb qualsevol navegador modern. No cal instal·lar res ni tindre connexió a Internet.

Publicar-la a GitHub Pages
1. Crea un repositori nou a https://github.com/new (per exemple, `repartiment-escons-valencia`).
2. Puja `index.html` a l'arrel del repositori. Pots pujar també aquest `README.md`.
3. En el repositori, entra a **Settings → Pages**.
4. En *Build and deployment*, tria **Deploy from a branch**, selecciona la branca `main` i la carpeta `/(root)`, i guarda.
5. Espera que finalitze la publicació. GitHub mostrarà la URL de la web en la mateixa pàgina de Pages. Normalment serà `https://EL_TEU_USUARI.github.io/repartiment-escons-valencia/`.

Sobre el càlcul i la normativa
El mètode d'Hondt divideix els vots de cada candidatura entre 1, 2, 3… i assigna els escons als quocients més alts. El llindar configurat s'aplica al total de vots introduïts en la calculadora.

Els valors inicials (16 escons i 3%) són una referència orientativa per a una elecció al Congrés dels Diputats en la circumscripció de València; els vots d'exemple són ficticis. Per a les Corts Valencianes o una altra elecció, cal adaptar el nombre d'escons, el llindar i la base de càlcul del llindar a la normativa corresponent. Aquesta eina no és una certificació oficial de resultats electorals.

Privacitat
Les dades s'executen localment en el navegador. La pàgina no envia ni desa les dades en cap servidor.
