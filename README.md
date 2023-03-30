Soluzione proposta

La media aritmetica non offre una soluzione corretta al problema perché non tiene conto del numero di recensioni e quindi dell’affidabilità di un valore, che può essere ottenuto dalla media di due soli voti se non addirittura da un voto solo.
Ho applicato una prima correzione alla media ricorrendo all’intervallo di confidenza. Sottraendo alla media l’intervallo di confidenza i giochi con solo una recensione finiscono in fondo alla lista con score “NaN” in quanto la valutazione è completamente inaffidabile e in generale vengono svantaggiati i giochi con pochi voti proprio perché le valutazioni risultano meno affidabili.
Questo metodo però offre una classifica non troppo diversa da quella che avremmo tenendo conto della semplice media (anche i grafici risultano simili) e non perdono punti i giochi che pur avendo pochissime recensioni hanno la deviazione standard pari a 0. Difatti i primi posti della tabella sono occupati da giochi che hanno ricevuto solo 10 (il voto massimo) da pochissime persone (rispettivamente 7,4,3,2) mentre al quinto posto figura un gioco che ha uno score poco più basso di 10 ma con un numero di recensioni pari a 43.
La tabella ottenuta suggerisce che bisogna dare ulteriore peso al numero delle recensioni. Quindi lo score è stato ulteriormente corretto moltiplicandolo per il rapporto tra il numero delle recensioni del singolo gioco e il numero di recensioni massimo. Il grafico ottenuto mostra che c’è stata una modifica sostanziale e suggerisce una classificazione più affidabile in 

Lucia Galati
