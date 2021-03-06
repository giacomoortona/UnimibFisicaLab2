# Esercizi per la lezione 7

## Esercizio 7.1

Si scriva una funzione ```somma``` che,
utilizzando la tecnologia ```template```,
sia applicabile a qualunque tipo numerico del ```C++```.

![linea](../immagini/linea.png)

## Esercizio 7.2 

Si testi la funzione ```somma``` sviluppata nell'esercizio precedente
sulla classe dei numeri complessi sviluppata durante la Lezione 3,
aggiungendo anche una specializzazione per un tipo a piacere.

![linea](../immagini/linea.png)

## Esercizio 7.3

Si costruisca la classe ```SimpleArray```, templata sul tipo degli oggetti che contiene, 
implementando le funzioni definite nel prototipo presentato a lezione.
  * Si ricordi di utilizzare correttamente l'allocazione dinamica della memoria.
  * Si aggiungano alla classe anche metodi che permettano di accedere agli elementi della classe
    in caso vengano chiamati su un oggetto ```const```.
  * Si faccia in modo che i metodi di accesso al contenuto del ```SimpleArray``` 
    controllino il valore dell'indice
    prima di accedere all'array salvato in memoria.
  * Si verifichi che la classe ```SimpleArray``` puo' essere templata sulla classe dei numeri complessi
    sviluppata durante la Lezione 3.
    
![linea](../immagini/linea.png)

## Esercizio 7.4

Si implementi una classe templata dal nome ```DynamicArray``` che inizialmente
non contenga alcun elemento ed abbia un metodo ```push_back ()``` che permetta di aggiungere 
un elemento in fondo all'array degli elementi gia' esistenti.
  * Si progetti un meccanismo che, rimpiazzi l'array che contiene gli elementi quando e' pieno,
    sostituendolo con uno piu' capiente.
  * Si aggiunga un metodo che permetta anche di svuotare l'oggetto di tipo ```DynamicArray```.

![linea](../immagini/linea.png)

## Esercizio 7.5

Si implementi la classe templata ```vettore``` definita nella lezione.
  * Si ricordi di controllare che gli indici passati ai metodi della classe siano entro i limiti 
    della memoria occupata dagli oggetti di tipo ```vettore```
  * Si aggiungano gli **operatori algebrici** necessari per la definizione di uno spazio vettoriale

![linea](../immagini/linea.png)

## Esercizio 7.6

Si implementi la classe templata ```matrice``` delle matrici quadrate di dimensione *N*, 
templata sulla dimensione delle matrici, 
definendo anche le operazioni fra matrici.
  * Si definiscano gli operatori di moltiplicazione fra matrici e vettori,
    utilizzando anche la classe ```vettore```.
