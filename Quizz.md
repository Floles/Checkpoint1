## Qu'est ce qu’un navigateur ?

```

Un navigateur est un logiciel permettant à l'utilisateur de surfer sur interprète.
Pour cela, il interprète le HTML et le CSS pour un rendu "graphique " à l'écran.


```

________________________________________________________________________________________

## Définissez l’ensemble HTML/CSS/JavaScript et leur utilités.


```
HTML: HyperText Markup Language => permet de mettre en place la structure d'une page
CSS : Cascade StyleSheet => permet de mettre en forme la structure HTML
Javascript : Langage d'évènement qui permet de dynamiser une application web basé sur l'intéraction entre l'utilisateur et le navigateur (en front-end).



```
________________________________________________________________________________________


## Qu’est-ce qu’un élément HTML ? Un attribut ?

```
Un élément HTML est une "balise" de la structure de la page qui peut prendre plusieurs formes (block, in-line...)
Un attribut se situe dans la balise HTML, il donne une indication complémentaire à la structure (par exemple l'attribut alt "texte alternatif" pour une image).



```
________________________________________________________________________________________


## Dans quels cas utilisez-vous des id au lieu des classes (et vice-versa) ?


```
Les ID et les classes s'utilisent dans le CSS :
Les classes sont à privilégier. On les utilise et on peut les réutiliser pour donner le même style à plusieurs éléments HTML.
Les ID s'utilisent lorsque l'on veut donner un style particulier à un élément HTML


```
________________________________________________________________________________________


## Qu’est-ce que EcmaScript ?

```

EcmaScript : c'est un ensemble de normes concernant les langages ayant des script comme Javascript.
Nous en sommes à la version 6.


```

________________________________________________________________________________________

## Pourquoi est-il important de bien indenter vos fichiers ?

```

L'indentation des fichiers permet une meilleure lisibilité du code à la fois pour soi et pour les autres.


```
________________________________________________________________________________________


## Quelle est la différence entre margin et padding ? 

```

Margin: va faire une marge à l'exterieur de l'élément
Padding : va faire une marge à l'intérieur de l'élément.


```

________________________________________________________________________________________


## Citez au moins 3 types de positionnement en CSS et expliquer leurs rôles.

```
Fixed : positionne un élément de manière "fixe" sur la page et n'en bougera pas même si on scrolle la page, 
par exemple : la navbar en "fixed" est visible pendant tout le long du scroll de la page.

Relative : se positionne par rapport à l'élément parent, l'élément en position relatif se déplacera 
en fonction du point d'origine de l'élément parent et non de la page.

Absolute : positionne l'élément par rapport à la page, on peut le mettre où on veut sur la page, par contre, 
il disparaitra lors du scroll de la page.


```
________________________________________________________________________________________

## Qu’est-ce qu’une variable ?

```
une variable : élément que l'on déclare afin de pouvoir l'utiliser dans une fonction, permet de définir un paramètre
elle peut à la fois variable :-) (dingue!!) ou constante.
Déclarer en dehors d'une fonction, elle peut être reprise plus tard.
Déclarer dans une fonction, elle ne s'appliquera que pour celle-ci.

```
________________________________________________________________________________________


## Citez le plus de types JavaScript possible et définissez les rapidement.


```
type string : à mettre entre guillemets ou apostrophe pour déclarer une chaîne de caractères.
type number : sans guillemets ou apostrophes pour déclarer un nombre/chiffre.
type boolean : pour vrai ou faux
type function : pour faire une fonction
type operator : pour les opérations ('<', '>', '=', '>=', '<=', '==', '===')
type Math : pour arrondir
type Regex : pour chercher une expression réguières dans une chaîne de caractères.


```
________________________________________________________________________________________


##  À quoi sert le mot-clef “if” ?

```
"if" sert à initialiser une condition (si...alors...) 



```

________________________________________________________________________________________

##  Définissez l’objet XHR en JavaScript, son abréviation. À quoi sert-il ?


```
XMLHTTPRequest
Il sert à nous embêter (pour parler poliement) sur les quêtes !!
permet une communication entre notre site et un site distant.
On fait appel à une application extérieure (API) et on demande via une request HTTP cette application sur notre site.



```

________________________________________________________________________________________

## Qu’est-ce qu’une requête HTTP ? 

```

Une requête est une demande de données, d'informations via le protocole HTTP.


```
________________________________________________________________________________________


## Quelle sont les deux types de requêtes permettant de récupérer et d’envoyer de la donnée sur un serveur HTTP ?

```

GET : pour récupérer des données
POST : pour envoyer des données

```

________________________________________________________________________________________

## À quoi sert le Header d’une requête ? Le “Content-Type” ?

```

le header sert à regrouper les données importantes comme la request status pour savoir si les données ont 
bien été envoyées ou reçues, la méthode qui a été utilisée (GET ou POST).

Le "Content type", sais plus sorry...

```
________________________________________________________________________________________


## Donnez au moins 3 codes de réponse HTTP et définissez les.


```
200 : pour une requête aboutie
301 : rediriger de façon permanente l'URL d'un site vers un autre
404: page d'erreur (mauvaise adresse URL, par exemple). 


```
________________________________________________________________________________________


## Définissez les rôles de Scrum Master et Product Owner.


```
SCRUM Master : il est le garant des pratiques de la méthode agile, il vérifie quelles soient bien appliquées,
autant dans la SCRUM team que du côté du Product Owner.

Product Owner : il est le lien avec le client


```
________________________________________________________________________________________


## Citer 4 commandes utilisées avec GIT et expliquer leurs rôles.

```
git init = pour iniatiliser le dossier dans lequel on va travailler
git add = pour ajouter un fichier à notre repository 
git checkout -b = pour ajouter et se placer directement dans la nouvelle branche


```
________________________________________________________________________________________


## Expliquer le code suivant et indiquer le résultat retourné par la fonction.

```
function counter(){
        const sentence = "Validation de la première phase";
        const words = sentence.split(' ');
        let count = 0;


        for (let i = 0; i < words.length; i++) {
            var word = words[i];
            count += word.length;
        }
        return count;
}

```
 - On créé une fonction "counter".
 - On définit une première variable nommée "sentence" qui sera constante mais uniquement dans la fonction
 - On définit une deuxième variable nommée "words" 
 - On utilise dans cette variable "words" la méthode ".split" qui sert à diviser une chaine de caractère avec un séparateur 
dans notre cas l'espace. On transforme la chaîne de caractères en tableau.
 - On créé un compteur et on l'initialise à 0.

_Création de la boucle_
 - On créé une boucle avec le mot "for"
 - On lui indique dans les parenthèses : la variable "let" initialisée à 0, la condition de sortie de la boucle qui est la fin de la chaine de caractères de la variable "words".
 - On lui donne le "pas" (à suivre !) qui est de 1.
 - On créé la variable "word" qui est égale au tableau de la variable "words".
 - On créé l'opération qui devra être faite en disant que "count est égale à count + word.length"
 - On retourne le résultat de count

Résultat  : 31



```




```
________________________________________________________________________________________


## Algo 

Ecrire l’algorithme d’une fonction prenant en paramètre 2 arguments : le premier est une chaîne de caractère et le second correspondant au caractère recherché. Cette fonction retourne le nombre de fois que le caractère recherché est rencontré dans la chaîne de caractères.
Ex. 
   * chaîne : ‘examen’, caractère : ‘x’ => 1
   * chaîne : ‘wild code school’, caractère : ‘w’ => 1



```
Je déclare 2 arguments : bibou et carSearch
Je cherche dans la chaine de caractères un caractère spécifique,
je dois enlever les espaces
Je dois transformer la chaine de caractère en tableau
je créé une boucle pour lire chaque caractère
Quand il trouve le ou les caractère(s) il stocke dans un compteur
Je retourne le nombre de caractère trouvé

function algo (bibou, carSearch) {
	bibou = bibou.replace(/ /g, "");
	bibou = bibou.split("");
	let compt = 0;

     for (let i = 0; i<bibou.length; i++) {
	
	var toto = carSearch [i];		//Cette partie est confuse encore, je n'y arrive plus !
	toto.match(/[0-9a-z]/igm);
	compt
     };
     return compt;
};

algo('wild code school', 'w');


```


