# Chiffrement Cesar En Python3
Pogramme de chiffrement et déchiffrement césar d'un message en python3.

# Explication du chiffrement de César avec une complexité O(n<sup>2</sup>)
1. D’abord on donne une liste d’alphabet en minuscule et une liste d’alphabet en majuscule.

2. On parcourt tout l’alphabet et append l’alphabet en minuscule et l’alphabet en majuscule à 
chaque parcourt.

3. Ensuite nous avons notre fonction de chiffrement qui prend en paramètre le message, 
l’alphabet en minuscule, l’alphabet en majuscule et le décalage elle parcourt tout l’alphabet et 
évalue certaines conditions tel que si la lettre est un espace elle retourne un espace, et si la
lettre du message est un alphabet en minuscule elle applique le décalage à la lettre en 
minuscule et retourne le résultat, et enfin si la lettre du message est en majuscule est applique 
le décalage a la lettre en majuscule et retourne le résultat sinon c’est un symbole et elle 
retourne donc le symbole. 

4. Après nous créons un string qui s’appelle message chiffre pour chaque jeu d’essai et on utilise 
une boucle qui parcourra notre message lettre par lettre et donnera à message chiffré chaque 
lettre chiffrée à l’aide de la fonction chiffrement message crée précédent qui prendra en 
paramètre lettre, alphabet, alphabet2 et notre décalage saisi précédemment par l’utilisateur, et 
enfin on affichera notre message chiffré.

5. Par la suite on crée un string qui s’appelle message_chiffré et on utilise une boucle qui parcourra
notre message_chiffré lette par lettre et donnera à message_déchiffré chaque lettre déchiffrée
à l’aide de la fonction chiffrement_message créée précédemment qui prendra en paramètre la 
même chose que précédemment mais juste avec le décalage en négatif, et enfin on affichera 
notre message déchiffré.

# Execution
`python3 Chiffrement_Cesar.py`
