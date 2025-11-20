# Esercizio: Our Team

**Repo:** `js-our-team`

---

## 🎯 Obiettivo

Dato un array di oggetti che rappresenta il team di un'azienda, creare una pagina web che mostri una "card" per ciascun membro del team, popolata con le sue informazioni.

Si consiglia di partire con una struttura HTML e CSS minimale, per poi arricchirla.
L'array di oggetti del team è fornito all'interno della cartella di progetto.

---

## ⚙️ Logica di Sviluppo

1.  **Setup Iniziale**:

    - Creare i file `index.html`, `style.css` e `main.js`.
    - Collegare i file CSS e JavaScript all'interno dell'HTML.

2.  **Dati del Team**:

    - In `main.js`, definire l'array di oggetti fornito. Ogni oggetto rappresenta un membro del team con proprietà come `nome`, `ruolo` e `immagine`.

3.  **Manipolazione del DOM**:
    - Selezionare l'elemento contenitore nel DOM (es. un `div` con una classe specifica) dove verranno inserite le card.
    - Creare un ciclo (`for` o `forEach`) per iterare su ogni oggetto (membro) nell'array.
    - All'interno del ciclo, generare dinamicamente il markup HTML per ogni card, utilizzando i dati dell'oggetto corrente.
    - Aggiungere l'HTML generato al contenitore nel DOM.

---

## 🏆 Bonus

### Bonus #1: Layout Responsive

Rendere la pagina responsive, facendo in modo che le card si dispongano su più righe e si adattino a schermi di dimensioni diverse (es. smartphone e tablet). Questo può essere ottenuto facilmente utilizzando **CSS Flexbox** o **Grid**.

### Bonus #2: Aggiunta di un nuovo membro

1.  Aggiungere un pulsante "Aggiungi Membro" all'HTML.
2.  Al click del pulsante, creare un nuovo oggetto con i tuoi dati (o dati a piacere).
3.  Aggiungere questo nuovo oggetto all'array del team.
4.  Eseguire nuovamente la logica di rendering per aggiornare la pagina e mostrare anche la nuova card, senza dover ricaricare.

---

### 🖼️ Esempio del risultato

Ecco uno screenshot di come potrebbe apparire il risultato finale:

![Screenshot del progetto](./screenshot.png)
