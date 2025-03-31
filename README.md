# Typologie d'erreurs

| **ERREUR** | **DETAILS OU EXEMPLES** | **TYPE(S) DE TÂCHE** |
|:-----------:|:--------------------------:|:-----------------------:|
||**VARIABLE**||
| (**VA-Err1**) Erreur de déclaration et initialisation variable | Mauvais choix du type dans la déclaration de la variable ou dans la valeur lors de l'initialisation | VA. Produire une variable (et ses fils) |
| (**VA-Err2**) Oubli incrémentation variable | Pour un compteur par exemple ; soit la variable n’est pas modifiée, soit elle est réinitialisée à chaque fois | — |
| (**VA-Err3**) Erreur dans choix du nom de la variable | Caractère interdit, mot réservé | VA. Choisir un nom valide (ne pas utiliser caractère interdit, nom réservé...) |
| **INSTRUCTION CONDITIONNELLE** |||
| (**IC-Err1**) Erreur nombre de branches IC | Oubli d’un cas ou mauvais recouvrement des branches | IC. Déterminer les branches nécessaires pour une IC<br>IC. Déterminer l'ensemble des expressions de manière à définir une partition de l'ensemble des cas d'une instruction conditionnelle |
| (**IC-Err2**) Erreur dans les instructions d’une IC | Une instruction ne se trouve pas dans la bonne branche ou se trouve en dehors de l’IC | IC. Déterminer les instructions à exécuter pour chaque branche d'une instruction conditionnelle |
|| **FONCTIONS** ||
| (**F-Err1**) Erreur définition de la fonction | Liée aux consignes de l’énoncé ou à la gestion possible avec le reste du code :<br>- oubli de paramètres ou mauvais choix de paramètres<br>- erreur sur les préconditions des paramètres<br>- erreur sur ce qui est retourné ou non | F. Déterminer les paramètres (noms, types, valeurs par défaut) d'une fonction<br>F. Déterminer les préconditions d'exécution (par exemple : tableau trié dans une recherche dichotomique...)<br>F. Déterminer, le cas échéant, les éléments à retourner par une fonction |
| (**F-Err2**) Erreur dans l’appel de la fonction | Appel avec les mauvais paramètres ou pas d'affectation du résultat de la fonction | — |
| (**F-Err3**) Erreur nom de la fonction ou des paramètres | Caractère interdit, mot réservé | F. Déterminer le nom d'une fonction<br>F. Déterminer les paramètres (noms, types, valeurs par défaut) d'une fonction |
|| **BOUCLES** ||
| (**B-Err1**) Erreur dans l'utilisation de l'itérateur de la boucle | L'apprenant s'est trompé dans les valeurs prises par l'itérateur (valeur de départ par exemple) | B. Déterminer si une (ou plusieurs) instruction(s) du corps d'une boucle bornée utilise(nt) l'itérateur |
| (**B-Err2**) Erreur nombre d’itérations de la boucle (à un près) | La boucle s'exécute une fois de trop ou une fois de moins | B. Déterminer le nombre d'itérations à réaliser pour une boucle bornée |
| (**B-Err3**) Erreur nombre d’itérations de la boucle (>2) | La boucle ne s'exécute pas le bon nombre de fois | B. Déterminer le nombre d'itérations à réaliser pour une boucle bornée |
| (**B-Err4**) Erreur condition d'arrêt de la boucle : départ | Erreur liée à la condition de départ | B. Déterminer la condition d'arrêt d'une boucle non bornée |
| (**B-Err5**) Erreur condition d'arrêt de la boucle : évolution | Erreur liée à une instruction qui n'est pas faite pour arrêter la boucle | B. Déterminer l'instruction modifiant la valeur de la condition d'arrêt d'une boucle non bornée |
| (**B-Err6**) Erreur dans le corps de la boucle : Instruction manquante et non présente | Instruction absente dans le corps de la boucle et dans le programme | B. Déterminer les instructions à exécuter à chaque itération d’une boucle bornée<br>B. Déterminer les instructions à exécuter à chaque itération pour une boucle non bornée |
| (**B-Err7**) Erreur dans le corps de la boucle : Instruction manquante et présente ailleurs dans le programme | Instruction présente ailleurs dans le programme | B. Déterminer les instructions à exécuter à chaque itération d’une boucle bornée<br>B. Déterminer les instructions à exécuter à chaque itération pour une boucle non bornée |
| (**B-Err8**) Erreur dans le corps de la boucle : Instruction erronée et proche de l’attendu | Instruction présente proche de celle manquante | B. Déterminer les instructions à exécuter à chaque itération d’une boucle bornée<br>B. Déterminer les instructions à exécuter à chaque itération pour une boucle non bornée |
| (**B-Err9**) Erreur dans le corps de la boucle : Instruction erronée et non voulue | Rien à voir avec attendu : cas instruction "en trop" | B. Déterminer les instructions à exécuter à chaque itération d’une boucle bornée<br>B. Déterminer les instructions à exécuter à chaque itération pour une boucle non bornée |
|| **EXPRESSIONS** ||
| (**EXP-Err1**) Erreur dans l'expression booléenne d'une des branches d'une IC | Test si une variable est < au lieu de ≤ par exemple | IC. Déterminer l'expression booléenne correspondant à une branche d'une instruction conditionnelle |
| (**EXP-Err2**) Erreur dans l'expression affectée à une variable | Oubli d'une partie de l'expression, ou mauvais choix du signe | VA. Affecter la valeur d'une expression à une variable |
|| **PROGRAMME ET ALGORITHME** ||
| (**PA-Err1**) Erreur de décomposition du problème ou mauvaise stratégie algorithmique | Le programme ne fait pas appel aux structures de contrôle attendues | P. Concevoir un algorithme permettant de réaliser une tâche t<br>A. Décomposer la tâche en sous-tâches t1…tn<br>A. Déterminer les instructions (affectations et structure de contrôles)<br>A. Ordonner et articuler les instructions (séquentialité et imbrication) |
| (**PA-Err2**) Erreur liée à la compréhension de la consigne | Programme correct mais fait complètement autre chose que ce qui est demandé (exemple : exécute le code de l'exemple donné) | — |
| (**PA-Err3**) Programme non terminé | Morceau de programme correct mais il manque une succession d'instructions | A. Déterminer les instructions (affectations et structure de contrôles) |
| (**PA-Err4**) Programme non optimisé | Fait la tâche demandée, mais de manière plus longue (redondance, non utilisation de boucles ou de fonctions) | P. Optimiser un programme<br>A. Modifier un algorithme existant pour répondre à des contraintes particulières |
