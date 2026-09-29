# Brief & Obbiettivo
```md
che gestionale state sviluppando e quale problema reale risolve
```
stiamo preparando un un gestionale che ha come obbiettivo principale quello di gestire le presenze con firma digitale completamente automatizzata e immutabile da parte degli studenti, supporto per il docente nel costruire il voto finale basandosi su presenza al suo modulo di lezioni, voto agli esami del suo corso e bonus e malus assegnati al singolo studente dal professore stesso.
come obbiettivi secondari abbiamo quelli di una gestione di comunicazioni broadcast da parte di professori e tutor a tutti gli studenti e da tutor a tutti i docenti, avvisi automatici per le troppe assenze.
# Ruoli Utente
```md
```
in generale gli utenti non si possono registrare, possono solo accedere dopo che la segreteria ha configurato il loro profilo, questi sono i tipi di utenti in ordine di autorità, prima quelli con più poteri poi quelli con meno, a eccezione degli studenti che funzionano in maniera particolare tutti gli altri hanno tutti i permessi di quelli sotto
1. segreteria (può creare gli utenti, esiste un utente segreteria di default, poi ne viene creato uno per ogni lavoratore della segreteria)
2. supertutor (ha accesso a tutti i corsi)
3. tutor (può sistemari eventuali problemi nelle presenze (ad esempio uno stdente che si dimentica di firmare l'ingresso o l'uscita), può modificare il calendario, creare e configurare moduli e unità formative)
4. docente (può vedere le statistiche relative alle presenze nei sui corsi, configurare quali sue lezioni sono esami e segnare sull'app premi o penalità nei punteggi degli studenti basandosi su partecipazione in classe o altre cose)
5. Studente
# Funzionalità Chiave
```md
```
Non un semplice registro presenze, ma tutto quello che vuoi/devi sapere sul tuo percorso all'ITS in un unico posto.
1. Registare presenze/assenze/ritardi in modo che siano acessibili anche per lo studente
2. Accedere al calendario delle lezioni e i dettagli sui singoli corsi 
3. Notifiche e comunicazioni in tempo reale all'interno dell'applicazione
4. Gamification, il percorso all'ITS viene scandito da un punteggio e dei badge
# demo su figma
```md
```