# Progetto_PMO
Progetto "Simulazione Ristorante" - PMO
***
Nome : Francesco Pio Rossi
Titolo del progetto : Simulazione Ristorante.
Specifica : L'applicazione simula il comportamento di un cliente in un Ristorante.
Ogni giorno il ristorante  prevede "Il menù del giorno" il quale è composto da 3 portate :  un primo, un secondo e un dolce scelti casualmente dal menù. 
All'inizio della simulazione il cliente può scegliere se ordinare il menù del giorno oppure ordinare le varie portate singolarmente.
Le 3 portate del  "menù del giorno" hanno un piccolo sconto rispetto alle portate ordinate singolarmente.
I piatti ordinati dal cliente vengono serviti nell'ordine classico : primi, secondi, e infine dolci. 
Ogni volta che il cliente termina di mangiare una pietanza, può chiamare il cameriere per ordinare qualcos'altro.
In cucina ci sono tre cuochi : uno per i primi, uno per i secondi e uno per i dolci. Il cuoco dei primi è il più lento, il cuoco dei secondi è il più veloce, e il cuoco dei dolci è il più gentile, infatti offre sempre una fetta di torta al cliente ogni volta che ordina un dolce.
Il cliente passa quindi attraverso 4 stati : Ordinazione -> attesa -> consumazione -> pagamento. 
Durante l'attesa i cuochi cucinano. Una volta che una portata arriva al cliente, esso inizia a mangiare entrando nello stato "Consumazione", dopodichè ritorna nello stato attesa, nel quale può scegliere se chiamare il cameriere per ordinare altro o attendere semplicemente le altre portate ordinate precedentemente.
Il software termina quando tutti i piatti sono stati serviti, viene stampato il conto e il cliente paga.
