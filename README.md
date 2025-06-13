# Il Problema degli N-Corpi

Un'esplorazione interattiva e didattica della danza gravitazionale tra corpi celesti. Questa applicazione web permette di simulare il comportamento di sistemi a N-corpi, dal semplice sistema Terra-Sole a configurazioni personalizzate e interattive.

## Funzionalità Principali

*   **Menu Principale**: Avvia simulazioni predefinite (Terra & Sole, Terra, Luna & Sole, Sistema Solare), crea simulazioni personalizzate con un numero variabile di corpi, o accedi alla sezione didattica.
*   **Sezione Didattica**: Spiegazioni sul problema dei due e tre corpi, la teoria del caos, i Punti di Lagrange e video educativi.
*   **Simulazioni Predefinite**: Osserva orbite stabilite e sistemi noti.
*   **Simulazione Personalizzata**: Genera un universo con un numero specifico di corpi e osserva le loro interazioni casuali.
*   **Simulazione Interattiva**: Aggiungi corpi manualmente cliccando sul canvas. I corpi iniziano da fermi e interagiscono con il sistema esistente.
*   **Lancio Nuovo Corpo**: Lancia un corpo da un punto casuale dello schermo, con massa e velocità calcolate per interagire con il corpo più piccolo esistente, creando orbite o impatti.
*   **Controllo della Velocità**: Modifica la velocità di simulazione in tempo reale.
*   **Traccia ON/OFF**: Attiva una traccia continua "a matita" per visualizzare le traiettorie complete dei corpi. Quando disattivata, le tracce hanno una lunghezza limitata.
*   **Leggenda e Timeline**: Monitora i corpi nella simulazione e il tempo simulato.

## Come Avviare l'Applicazione

1.  Scarica o clona il repository contenente `3bp.html` e `central_force.js`.
2.  Apri il file `3bp.html` nel tuo browser web preferito.

Non sono necessarie dipendenze o server web, l'applicazione funziona direttamente nel browser.

## Utilizzo

*   **Navigazione**: Usa i pulsanti nel menu principale per scegliere la modalità di simulazione.
*   **Controlli di Simulazione**:
    *   **<- Menu**: Torna al menu principale.
    *   **Riavvia**: Resetta la simulazione corrente.
    *   **Velocità +/-**: Aumenta o diminuisce la velocità di simulazione.
    *   **TRACCIA ON/OFF**: Attiva/disattiva la visualizzazione della traccia continua per i corpi.
    *   **LANCIA NUOVO CORPO**: Lancia un nuovo corpo nel sistema con massa e velocità dinamiche.
    *   **AGGIUNGI CORPO (MOUSE)**: Abilita/disabilita la modalità per aggiungere corpi cliccando sul canvas.

## Crediti

*   Ispirazione per l'interattività e l'aggiunta di corpi via mouse dalla logica trovata in `central_force.js` (Processing).

---

# N-Body Problem Simulator

An interactive and educational exploration of the gravitational dance between celestial bodies. This web application allows you to simulate the behavior of N-body systems, from the simple Earth-Sun system to custom and interactive configurations.

## Key Features

*   **Main Menu**: Start predefined simulations (Earth & Sun, Earth, Moon & Sun, Solar System), create custom simulations with a variable number of bodies, or access the educational section.
*   **Educational Section**: Explanations on the two and three-body problem, chaos theory, Lagrange Points, and educational videos.
*   **Predefined Simulations**: Observe established orbits and known systems.
*   **Custom Simulation**: Generate a universe with a specific number of bodies and observe their random interactions.
*   **Interactive Simulation**: Add bodies manually by clicking on the canvas. Bodies start from rest and interact with the existing system.
*   **Launch New Body**: Launch a new body into the system with dynamic mass and velocity calculated to interact with the smallest existing body, creating orbits or impacts.
*   **Speed Control**: Adjust the simulation speed in real-time.
*   **Trail ON/OFF**: Toggle a continuous "pencil-like" trail to visualize the complete trajectories of the bodies. When off, trails have a limited length.
*   **Legend and Timeline**: Monitor bodies in the simulation and simulated time.

## How to Run the Application

1.  Download or clone the repository containing `3bp.html` and `central_force.js`.
2.  Open the `3bp.html` file in your preferred web browser.

No dependencies or web servers are required; the application runs directly in the browser.

## Usage

*   **Navigation**: Use the buttons in the main menu to choose the simulation mode.
*   **Simulation Controls**:
    *   **<- Menu**: Return to the main menu.
    *   **Restart**: Reset the current simulation.
    *   **Speed +/-**: Increase or decrease the simulation speed.
    *   **Trail ON/OFF**: Toggle the continuous trail visualization for bodies.
    *   **LAUNCH NEW BODY**: Launch a new body into the system with dynamic mass and velocity.
    *   **ADD BODY (MOUSE)**: Enable/disable the mode for adding bodies by clicking on the canvas.

## Credits

*   Inspiration for interactivity and adding bodies via mouse from the logic found in `central_force.js` (Processing).

## 🚀 Deploy su GitHub Pages

1. Assicurati di avere i seguenti file nella repository:
   - `index.html` (o `space_iphone.html` rinominato)
   - `space_iphone.js`
   - `README.md`

2. Vai nelle impostazioni della repository (Settings)
3. Nella sezione "Pages" (sotto "Code and automation")
4. In "Source" seleziona "Deploy from a branch"
5. Seleziona il branch "main" e la cartella "/ (root)"
6. Clicca "Save"

Il gioco sarà disponibile all'URL: `https://[tuo-username].github.io/[nome-repository]`

## 🎮 Come Giocare (versione mobile touch)

- **Muovi il cannone**: usa le frecce touch in basso a sinistra e destra
- **Spara**: premi il pulsante centrale giallo
- **Rigioca**: premi il pulsante "Rigioca" che appare a fine partita
- Il cannone e le barriere sono sempre posizionati sopra i controlli touch
- Il layout si adatta automaticamente a qualsiasi schermo

## 🎯 Caratteristiche

- 6 righe e 8 colonne di nemici, sempre centrati
- Barriere colorate con resistenza crescente
- 5 tipi diversi di nemici con sprite uniche
- Effetti sonori per ogni azione
- Sistema di punteggio
- Livelli progressivi con **aumento di difficoltà lineare** (la velocità degli invasori cresce gradualmente)
- Pulsante "Rigioca" per ripartire facilmente
- Responsive e ottimizzato per smartphone

## 🛠️ Tecnologie Utilizzate

- p5.js per la grafica
- Web Audio API per gli effetti sonori
- HTML5 e CSS3 per l'interfaccia mobile
- JavaScript per la logica di gioco

## 📱 Compatibilità

Il gioco è ottimizzato per:
- Smartphone (iOS e Android)
- Tablet

## 🎨 Personalizzazione

Puoi modificare:
- Colori delle barriere
- Velocità dei nemici
- Dimensione dello schermo
- Effetti sonori

## 📝 Licenza

Questo progetto è rilasciato sotto licenza CC0-1.0 - vedi il file [LICENSE](LICENSE) per i dettagli.

## 🤝 Contribuire

1. Fai il fork del progetto
2. Crea un branch per la tua feature (`git checkout -b feature/AmazingFeature`)
3. Commit delle tue modifiche (`git commit -m 'Add some AmazingFeature'`)
4. Push sul branch (`git push origin feature/AmazingFeature`)
5. Apri una Pull Request

## 📧 Contatti

Per domande o suggerimenti, contattami su GitHub! 