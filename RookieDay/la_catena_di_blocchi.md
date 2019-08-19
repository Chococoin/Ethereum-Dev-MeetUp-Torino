# La blockchain

_(ovvero la cattena di blocchi)_

## Storia

I primi referimenti della blockchain datano dal anno 1991 in un documento firmato in per Stuart Haber and W. Scott Stornetta, come una soluzione per evitare la falsificazione di documenti. Per in anno 1992 hanno publicato un secondo documento dove si proponeva l'utilizzo della structura di dati del Albero di Merkle per migliorare ancora le prestazioni. Fino a questo punto possimamo parlare della Blockchain come una architetura di dati con delle propietà particulari. 

Non è fino al anno 2009 quando Satoshi Nakamoto utilizza questa architectura di dati resistente a le manomisioni per forgiare la prima moneta eletronica, cioè Il Bitcoin. Allora la catena di blocchi del Bitcoin e diventato il primo libro mastro digitale dove si poteva avere la contabilità dei bitcoin sparpagliati nel pianeta.  

## Cosa sono i blocchi di questa catena

Avviamo parlato che la blockchain è nata per protegere documenti. E che il primo documento importante diventato catena di blocchi è stato il libro di contabile del bitcoin. Allora il primo bloccho di la catena bitcoin è il primo documento che certifica la prima transazione fata su un indirizzo Bitcoin. Questo docuento ha il nome di bloccho genesis. Il secondo bloccho contiene altre transazione e si colega con il primo bloccho grazie a il numero hash.

## Hash

Il protocollo di hashing oppure _Secure Hash Algorithm_ è la prima tecnologia di criptagio che permete questo miracolo della blockchain. E funziona cosi. 
1) Dato un numero in input di qualsiasi lunghezza se puo calcolare un numero di lunghezza fissa come output.
2) Se questo calcolo si realiza utilizando numeri primi oppure dentro un conjunto di numeri apparteniente a una grafica di curva eliptica il calcolo sara di tipo assimetrico. Cioè, dato C come prodotto di  A x B non protremo mai sappere il valore di A dividendo C/B oppure C/A. 

Per illustrare questo imaginiamo: Tutti i numeri naturali da 1 fino al infinito possono essere rapresentati in un numero di lungueza fissa di un digito in base a un calculo. Se il numero naturale e divisibile per 2 assegniamo un 0 (pari) se il numero diviso 2 ha un resto allora è assegniamo con 1 dato che dispari. 

Nel nostro essempio abbiamo un calcolo asimetrico dato che anche se sapiamo como abbiamo realizato il calcolo (N / 2 => 1 || 0) relizzare il calcolo opposto (1 || 0 * 2 != N ) non ci restituira in valore essato del numero N.

E anque su questo si basa il principio della criptografia delle firme digitale con chiave Privata, che puo essere confirmata usando il prodotto (il messagio) e la chiave pubblica, ma insieme non possono servire par calcolare la chiave privata. 

Oggi troviamo diversi algoritmi di hash MD5, SHA-1, SHA-2, SHA-16, SHA-512 e quello che usa il bitcoin il SHA-256. Che fino a oggi no ha presentato collisioni. 