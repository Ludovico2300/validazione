Dato il form di partenza validare i campi tale che:
 - Tutti i campi siano obbligatori.
 - I campi relativi a numero carta di credito e CVC devono avere una prima validazione sulla lunghezza e la correttezza dei valori.

Per la validazione del numero della carta e del CVC, utilizza l'attributo pattern, questo come valore prende una regular expression, cerca su internet quelle adatte per questi input