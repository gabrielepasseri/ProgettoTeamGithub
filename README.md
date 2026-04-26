# 🐙 DevArchitect — Portfolio Base

> Progetto base per il laboratorio di Git & GitHub  
> **Platone HES/PSW — IefP ELIS Roma · 2025/2026**

---

## 📁 Struttura del progetto

```
devarchitect/
├── index.html          # Struttura HTML del sito
├── css/
│   └── style.css       # Stili, tema dark, animazioni CSS
├── js/
│   └── script.js       # Interazioni, typing effect, scroll reveal
└── README.md           # Questo file
```

---

## 🌐 Anteprima

Il sito include le seguenti sezioni:

| Sezione | Descrizione |
|---|---|
| **Hero** | Titolo con typing effect animato |
| **Chi sono** | Bio, avatar e statistiche |
| **Skills** | Barre di progresso per HTML, CSS, JS, Git |
| **Progetti** | Card con link live e GitHub |
| **Blog** | Card articoli |
| **Contatti** | Link email e social |

---

## 🚀 Come usare questo progetto

### Per gli studenti — flusso completo

> ⚠️ **Non clonare e non modificare questo repository direttamente.**  
> Il Team Lead del tuo gruppo deve fare il **fork** e invitarti come collaboratore.

#### 1. Il Team Lead fa il fork
1. Clicca **Fork** in alto a destra in questa pagina
2. Lascia le impostazioni di default e conferma
3. Il fork viene creato nel suo account: `github.com/team-lead/devarchitect`

#### 2. Il Team Lead invita il team
`Settings` → `Collaborators` → `Add people`

| Chi | Ruolo GitHub |
|---|---|
| 4 compagni del team | Write |
| Docente | Maintain |

#### 3. Il Team Lead crea i branch
Dal selettore branch del fork, creare un branch per ruolo:

```
feature/html-dev
feature/css-dev
feature/js-dev
feature/content-dev
```

#### 4. Ogni membro accetta l'invito e lavora sul suo branch

---

## 👥 Ruoli del team

| Ruolo | File di competenza | Compito principale |
|---|---|---|
| 👑 **Team Lead** | — | Fork, inviti, branch, review, merge |
| 🌐 **HTML Dev** | `index.html` | Contenuti, testi, card progetti |
| 🎨 **CSS Dev** | `css/style.css` | Palette colori, stili, animazioni |
| ⚡ **JS Dev** | `js/script.js` | Typing effect, scroll animations |
| 📄 **Content Dev** | `team.html` *(da creare)* | Pagina presentazione del team |

> **Regola fondamentale:** ogni membro modifica **solo** il file del suo ruolo.

---

## 🛠️ Tecnologie usate

- **HTML5** — struttura semantica
- **CSS3** — custom properties, flexbox, grid, animazioni
- **JavaScript ES6+** — IntersectionObserver, DOM manipulation
- **Google Fonts** — Space Grotesk, Inter
- **Material Symbols** — icone Google

---

## 📋 Task disponibili per il laboratorio

I task sono assegnati dal docente. Ogni membro lavora sul task corrispondente al suo ruolo.

### 🌐 HTML Dev — Personalizzazione contenuti
- [ ] Cambiare nome nell'effetto typewriter (`script.js` → coordina con JS Dev)
- [ ] Aggiornare bio e statistiche nella sezione *Chi sono*
- [ ] Aggiungere almeno un progetto reale nella sezione *Progetti*
- [ ] Aggiornare i link email e social nella sezione *Contatti*

### 🎨 CSS Dev — Personalizzazione stile
- [ ] Scegliere una palette colori diversa da quella base (modifica le variabili in `:root`)
- [ ] Personalizzare il font o i pesi tipografici
- [ ] Aggiungere o modificare le animazioni hover sulle card

### ⚡ JS Dev — Animazioni e interazioni
- [ ] Personalizzare le parole nel typing effect con termini del team
- [ ] Aggiungere l'animazione progressiva alle barre delle skill (IntersectionObserver)
- [ ] Aggiungere i contatori animati nella sezione *Chi sono*

### 📄 Content Dev — Pagina team
- [ ] Creare `team.html` con una card per ogni membro (nome, ruolo, emoji)
- [ ] Collegare la pagina dall'`index.html` (coordina con HTML Dev)
- [ ] Stilare la pagina riciclando le classi CSS già presenti

---

## 🔀 Flusso di lavoro Git (solo browser)

```
main  ←  merge finale (solo Team Lead)
  ├── feature/html-dev     ← HTML Dev apre PR quando ha finito
  ├── feature/css-dev      ← CSS Dev apre PR quando ha finito
  ├── feature/js-dev       ← JS Dev apre PR quando ha finito
  └── feature/content-dev  ← Content Dev apre PR quando ha finito
```

**Ordine consigliato per i merge:** CSS → HTML → JS → Content

---

## 📝 Convenzioni commit

```
feat: aggiunge sezione interessi con 4 card
fix:  corregge link GitHub nel progetto 1
style: aggiorna palette colori in verde e teal
```

---

## 🌍 Deploy con GitHub Pages

1. Vai su `Settings` → `Pages`
2. In **Source** seleziona `Deploy from a branch`
3. Branch: `main` — Cartella: `/ (root)`
4. Clicca **Save**

Il sito sarà disponibile su:  
`https://[username].github.io/devarchitect/`

---

## 📖 Risorse utili

| Risorsa | Link |
|---|---|
| Guida al progetto team (PDF) | *fornita dal docente* |
| GitHub Docs | [docs.github.com](https://docs.github.com) |
| MDN Web Docs | [developer.mozilla.org](https://developer.mozilla.org) |
| CSS Tricks | [css-tricks.com](https://css-tricks.com) |

---

<div align="center">

Fatto con ❤️ e tanto `console.log()` — IefP ELIS Roma

</div>
