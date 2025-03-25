# Analysis and Simplification of Boolean Logic Functions

Il progetto **"Fondamenti di Informatica"** si concentra sull'analisi e la semplificazione di una funzione logica booleana `f(x, y, z, d)`. Il lavoro si articola in varie fasi, inclusa la definizione e il calcolo della funzione, la semplificazione attraverso teoremi dell'algebra booleana e metodi tabellari, e la rappresentazione finale mediante schemi logici.

## Calcolo della funzione

La funzione `f(x, y, z, d)` è determinata a partire dal resto della divisione del numero di matricola (`0500843`) per `65536`, ottenendo `42091` in decimale (`1010010001101011` in binario).  
Viene costruita una **tabella di verità** che descrive i valori della funzione in relazione a tutte le combinazioni possibili delle variabili booleane `x`, `y`, `z` e `d`.

## Minterm e Maxterm

Per la rappresentazione in forma canonica, vengono individuati:

- **Minterm**: combinazioni in cui la funzione assume valore `1`, esprimendo la funzione come una **somma di prodotti** (SOP).
- **Maxterm**: combinazioni in cui la funzione assume valore `0`, esprimendo la funzione come un **prodotto di somme** (POS).

## Semplificazione della funzione

La semplificazione della funzione booleana avviene sia attraverso:

- l'uso dei **teoremi dell'algebra booleana**,
- l'impiego della **mappa di Karnaugh**, che facilita l'individuazione dei raggruppamenti per minimizzare la funzione.

Nel metodo della **mappa di Karnaugh**, vengono raggruppati i termini per ottenere una rappresentazione più compatta della funzione.  
Il metodo tabellare di **Quine-McCluskey** viene utilizzato per determinare gli **implicanti primi** e individuare i **termini essenziali** che coprono tutte le combinazioni della funzione.

## Schema logico

Infine, la funzione viene espressa sia in forma di **minterm** che **maxterm**.  
Lo **schema logico finale** riflette la funzione semplificata, ottenuta combinando i vari termini ridotti.

## Realizzazione in LaTeX

Per una presentazione ordinata e professionale del progetto, l'intero elaborato è stato redatto in **LaTeX**, un linguaggio di markup ideale per la documentazione tecnica.  
Questo ha permesso di:

- inserire formule logiche in modo chiaro e leggibile,
- organizzare tabelle e mappe di Karnaugh in maniera strutturata,
- generare un file PDF con formattazione precisa e ben impaginata.

Grazie a LaTeX, è stato possibile presentare in modo efficace tutti i passaggi, dalla definizione della funzione alla sua semplificazione e implementazione logica.

