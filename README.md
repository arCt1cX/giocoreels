# Gioco dell'Impostore

Un semplice gioco da party per gruppi di amici, dove un giocatore riceve un prompt leggermente diverso dagli altri e il gruppo deve scoprire chi è l'impostore.
Qui il link per giocare direttamente dal tuo smartphone: arct1cx.github.io/giocoreels/

## Come giocare

1. Apri il file `index.html` in un browser web sul tuo smartphone
2. Scegli il numero di giocatori (minimo 3)
3. Inizia il gioco cliccando su "Inizia Gioco"
4. Passa il telefono al primo giocatore, che vedrà il suo prompt
5. Dopo aver letto il prompt, il giocatore preme "Ho Visto" e passa il telefono al giocatore successivo
6. Ogni giocatore scrive la propria risposta su un foglio di carta
7. Quando tutti i giocatori hanno visto il loro prompt, l'app mostrerà una schermata che invita tutti a scrivere le proprie risposte
8. Dopo che tutti hanno scritto le risposte, cliccate su "Rivela il Prompt del Gruppo" per vedere il prompt comune
9. I giocatori discutono e cercano di scoprire chi è l'impostore
10. Infine, premete "Rivela l'Impostore" per scoprire chi era l'impostore e quale prompt ha ricevuto

## File inclusi

- `index.html`: Struttura HTML del gioco
- `styles.css`: Stili CSS per rendere l'app mobile-friendly
- `scripts.js`: Logica JavaScript del gioco
- `frasi_gioco_impostore.txt`: File contenente le coppie di frasi (gruppo | impostore)

## Note tecniche

- L'app funziona completamente in locale, senza necessità di connessione internet (dopo il caricamento iniziale)
- È ottimizzata per smartphone e tablet
- Il gioco seleziona casualmente l'impostore e il prompt per ogni partita 
