# Glossaire

<!-- vscode-markdown-toc -->
* 1. [Abstrait](#Abstrait)
	* 1.1. [Méthode abstraite](#Mthodeabstraite)
	* 1.2. [Classe abstraite](#Classeabstraite)
* 2. [Algorithme](#Algorithme)
* 3. [Classe](#Classe)
* 4. [Champ](#Champ)
* 5. [Compilateur](#Compilateur)
* 6. [Constante](#Constante)
* 7. [Fonction](#Fonction)
* 8. [Héritage](#Hritage)
* 9. [Implémentation](#Implmentation)
* 10. [Interface](#Interface)
* 11. [Interprète](#Interprte)
* 12. [Language de programmation](#Languagedeprogrammation)
	* 12.1. [Language Compilé](#LanguageCompil)
	* 12.2. [Language interprété](#Languageinterprt)
* 13. [Méthode](#Mthode)
* 14. [Patron de conception](#Patrondeconception)
* 15. [Polymorphisme](#Polymorphisme)
* 16. [Programme](#Programme)
* 17. [Tableau](#Tableau)
* 18. [Variable](#Variable)

<!-- vscode-markdown-toc-config
	numbering=true
	autoSave=true
	/vscode-markdown-toc-config -->
<!-- /vscode-markdown-toc -->

##  1. <a name='Abstrait'></a>Abstrait 
*Abstract, abstraction*

"En informatique, le concept d'abstraction identifie et regroupe des caractéristiques et traitements communs applicables à des entités ou concepts variés ; une représentation abstraite commune de tels objets permet d'en simplifier et d'en unifier la manipulation. " [Wikipedia](https://fr.wikipedia.org/wiki/Abstraction_(informatique))

En d'autres mots, "[une abstraction] permet de représenter une entitée en exposant seulement les informations qui sont pertinantes dans le contexte actuel, tous en cachant celles qui ne le sont pas." – [John V. Guttag](https://en.wikipedia.org/wiki/Abstraction_(computer_science)) (Traduit de l'anglais)

###  1.1. <a name='Mthodeabstraite'></a>Méthode abstraite
*Abstract method*

"Les méthodes abstraites qui sont des méthodes sans code — leur existence dans une classe suffit à déclarer qu'une classe est abstraite et contraint à introduire des classes filles pour les implémenter et les exploiter" [Wikipedia](https://fr.wikipedia.org/wiki/M%C3%A9thode_(informatique))


###  1.2. <a name='Classeabstraite'></a>Classe abstraite
*Abstract class, abstract type*

"En programmation orientée objet (POO), une classe abstraite est une [classe](#Classe) si et seulement si elle n'est pas instanciable. Elle sert de base à d'autres classes dérivées ([héritées](#Héritage)." [Wikipedia](https://fr.wikipedia.org/wiki/Classe_abstraite)

En d'autres mots, une classe abstraite peu être vue comme une classe incomplète. C'est une classe qui devra être hérité par une autre classe pour compléter ses fonctionnalités.

##  2. <a name='Algorithme'></a>Algorithme
*Algorithm*

"Un algorithme est une suite finie et non ambiguë d'instructions et d’opérations permettant de résoudre une classe de problèmes." [Wikipedia](https://fr.wikipedia.org/wiki/Algorithme)

##  3. <a name='Classe'></a>Classe
*Class, type*

"En programmation orientée objet, la déclaration d'une classe regroupe des membres, méthodes et propriétés (attributs) communs à un ensemble d'objets. " [Wikipedia](https://fr.wikipedia.org/wiki/Classe_(informatique)?tableofcontents=0)

##  4. <a name='Champ'></a>Champ
*Field, member variable*

Aussi référé comme *attribut* ou *donnée membre*.

"Dans la programmation objet, un champ est une [variable](#Variable) qui est associée à un [objet](#Objet) spécifique, et qui est accécible aux [méthodes](#Méthode) de cet objet." Traduit de l'anglais, [Wikipedia](https://en.wikipedia.org/wiki/Member_variable)

##  5. <a name='Compilateur'></a>Compilateur
*Compiler*

"Un compilateur est un programme qui transforme un code source en un code objet. Généralement, le code source est écrit dans un langage de programmation (le langage source), il est de haut niveau d'[abstraction](#Abstrait), et facilement compréhensible par l'humain. Le code objet est généralement écrit en langage de plus bas niveau (appelé langage cible), par exemple un langage d'assemblage ou langage machine, afin de créer un programme exécutable par une machine." [Wikipedia](https://fr.wikipedia.org/wiki/Compilateur)

##  6. <a name='Constante'></a>Constante
*Constant*

"Contrairement à une [variable](#Variable), une constante est un identificateur associé à une valeur fixe. Syntaxiquement, cet identificateur a tous les aspects d'une variable. Cependant, il lui est affecté une valeur définitive, c'est-à-dire constante, comme la taille d'un plateau d'échecs (8x8)."[Wikipedia](https://fr.wikipedia.org/wiki/Variable_(informatique))


##  7. <a name='Fonction'></a>Fonction
*Function, routine*

"[...] une [fonction] est une entité informatique qui encapsule une portion de code (une séquence d'instructions) effectuant un traitement spécifique bien identifié (asservissement, tâche, calcul, etc.) relativement indépendant du reste du [programme](#Programme), et qui peut être réutilisé dans le même programme."
[Wikipedia](https://fr.wikipedia.org/wiki/Routine_(informatique))

##  8. <a name='Hritage'></a>Héritage
*Inheritance*

"En programmation orientée objet, l’héritage est un mécanisme qui permet, lors de la déclaration d’une nouvelle classe, d'y inclure les caractéristiques d’une autre classe."[Wikipedia](https://fr.wikipedia.org/wiki/H%C3%A9ritage_(informatique))

##  9. <a name='Implmentation'></a>Implémentation
*Interface inheritance, subtyping, implementation*



##  10. <a name='Interface'></a>Interface
*Interface*

"Le point d'interconnection ou contact entre des entitées." [Traduit de l'anglais, Wikitionary](https://en.wiktionary.org/wiki/interface)

Il existe plusieurs types d'interfaces. (Ex: graphique, abstraite, utilisateur). Tous peuvent être vue comme un contrat servant à définir les règles d'interraction entre deux entités. 

[Définition interface dans la programmation orientée objet](https://fr.wikipedia.org/wiki/Interface_(programmation_orient%C3%A9e_objet))

##  11. <a name='Interprte'></a>Interprète
*Interpreter*

"En informatique, un interprète, ou interpréteur, est un outil dont la tâche est d'analyser, de traduire et d'exécuter les programmes écrits dans un langage informatique." [Wikipedia](https://fr.wikipedia.org/wiki/Interpr%C3%A8te_(informatique))

##  12. <a name='Languagedeprogrammation'></a>Language de programmation
*Programming language*

"Un langage de programmation est une notation conventionnelle destinée à formuler des [algorithmes](#Algorithme) et produire des [programmes](#Programme) informatiques qui les appliquent. D'une manière similaire à une langue naturelle, un langage de programmation est composé d'un alphabet, d'un vocabulaire, de règles de grammaire, de significations, mais aussi d'un environnement de traduction censé rendre sa syntaxe compréhensible par la machine."

###  12.1. <a name='LanguageCompil'></a>Language Compilé
*Compiled language*

Un language compilé est un language qui doit utiliser un compilateur pour traduire le code source en code que l'ordinateur peu comprendre. C'est aussi à l'étape de la compilation que la plupart des compilateurs enforcent certaines garenties qui sont définie par le language. Ce processus de compilation doit être exécuté avant l'exécution. Ex: les différents types sont bien utilisés au bon endroit.

###  12.2. <a name='Languageinterprt'></a>Language interprété
*Interpreted language*

Un language dont la traduction du code source en code machine se produit pendant l'exécution du [programme](#Programme) à l'aide d'un [interprète](#Interprète).

##  13. <a name='Mthode'></a>Méthode
*Method, class function*

"En programmation orientée objet (POO), une méthode est une [[fonction](#Fonction)] membre d'une classe. " [Wikipedia](https://fr.wikipedia.org/wiki/M%C3%A9thode_(informatique))

Une autre façon de voir les méthode est : une [fonction](#Fonction) qui se fait passer implicitement l'instance d'un objet.

##  14. <a name='Patrondeconception'></a>Patron de conception
*Design pattern*

"Un patron de conception (souvent appelé design pattern) est un arrangement caractéristique de modules, reconnu comme bonne pratique en réponse à un problème de conception d'un logiciel. Il décrit une solution standard, utilisable dans la conception de différents logiciels."[Wikipedia](https://fr.wikipedia.org/wiki/Patron_de_conception)

[Ressource pour en apprendre plus sur certains des patrons les plus populaires](https://refactoring.guru/fr/design-patterns)

##  15. <a name='Polymorphisme'></a>Polymorphisme
*Polymorphism*

"[Le polymorphisme] est le concept consistant à fournir une [interface](#Interface) unique à des entités pouvant avoir différents types." [Wikipedia](https://fr.wikipedia.org/wiki/Polymorphisme_(informatique))

Ex: Une [méthode](#Méthode) demande un objet qui [implémente](#Implémentation) l'interface "fruit". Nous pourrons donc fournir à cette méthode des objets de type "pomme", "banane" et "tomate" (Tant que ces classes [implémente](#Implémentation) l'interface "fruit"). 


##  16. <a name='Programme'></a>Programme
*Program*

"Un programme informatique est un ensemble d'instructions et d’opérations destinées à être exécutées par un ordinateur. "
[Wikipedia](https://fr.wikipedia.org/wiki/Programme_informatique)

##  17. <a name='Tableau'></a>Tableau
*Array*

"Un tableau est une structure de données représentant une séquence finie d'éléments auxquels on peut accéder efficacement par leur position, ou indice, dans la séquence. C'est un type de conteneur que l'on retrouve dans un grand nombre de langages de programmation." [Wikipedia](https://fr.wikipedia.org/wiki/Tableau_(structure_de_donn%C3%A9es))


##  18. <a name='Variable'></a>Variable
*Variable*

"Les variables sont des symboles qui associent un nom (l'identifiant) à une valeur. Dans la plupart des langages et notamment les plus courants, les variables peuvent changer de valeur au cours du temps (dynamique). Dans les langages de certains paradigmes, notamment la programmation fonctionnelle, leur valeur est au contraire figée dans le temps (statique). "[Wikipedia](https://fr.wikipedia.org/wiki/Variable_(informatique))




Iteration
Pointeur
Surcharge
Signature

