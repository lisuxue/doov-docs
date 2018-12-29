# Conference Session

# How to create a fluent API DSL with lambda builders? 

en_US : With the dOOv framework, we are trying to solve a common problem with software: 
performance vs. readability vs. type-safety. Since Java 8, lambdas offer the 
ability to compose functions at runtime with high performance. We built a 
fluent API using lambdas to write validation and mapping logic with a DSL. It 
enables the written application rules to be introspected and profiled by 
visiting the DSL abstract syntax tree at runtime. During this BOF we will 
discuss how the framework is designed, the issues that we encountered 
generating the natural language output, failure cause analysis, and AST 
rewriting.

# Comment créer son propre langage avec un fluent API et un lambda builder ?

fr_FR : Avec le framework dOOv, nous adoptons une nouvelle approche pour résoudre un problème
récurrent dans nos applications: conjuger performance, lisibilité et typage fort.
Depuis Java 8, les lambdas permettent de composer des fonctions avec d'excellentes performances à l'exécution.
dOOv fournit une fluent API qui permet d'écrire la logique d'une application avec un DSL 'pur Java' 
et construit des lambdas pour l'exécution.
Il devient possible de parcourir l'arbre de syntaxe du DSL lors de l'exécution et d'effectuer dynamiquement
des réécritures. Pendant la session, nous présenterons le fonctionnement du framework,
les problèmes rencontrés pour générer du langage naturel, l'instrumentation du code écrit en DSL et 
la réécriture des arbres de syntaxe pour les afficher sous forme canonique.

## Status 

TO_SUBMIT

# Hands-On-Labs

# Getting Started with custom DSLs using the dOOv framework

en_US : Have you heard a lot about the advantages of DSLs but don't know where to 
start? In this session, we will be modernizing a webshop application,
which has validation rules with BeanValidation and implements 
business logic and mapping code with plain old Java. Using dOOv, 
attendees will generate a Java-based DSL and migrate incrementally the 
logic and mapping code of the application. First, attendees will use 
dOOv to rewrite BeanValidation rules and discover the benefits of a 
strongly-typed fluent API to express constraints of a model.
Then we will migrate the application logic and the mapping code to ensure 
the compliance and governance of the partner exchanges. Finally, we will 
evaluate the performance and flexibility gains.

# Adopter une approche DDD en Java avec le framework dOOv

fr_FR : 
Avez-vous toujours voulu expérimenter avec l'approche DDD sur votre projet 
mais vous ne savez pas par où commencer ?  
Dans cette session, nous allons vous montrer comment moderniser à l'aide d'un
DSL 'pur Java', une application de e-commerce qui utilise des règles de validation
écrites avec BeanValidation et une logique métier écrite en Java.
Nous utiliserons le framework dOOv pour réécrire la partie BeanValidation et nous
découvrirons les bénéfices du fluent API fortement typé de dOOv.
Nous migrerons ensuite l'intégralité de la logique métier et du code de mapping en
permettant l'audit rapide de toute la logique en langage naturel.
Nous terminerons par la mise en place de tests de performance avec JMH sur le code migré.

## Status

TO_SUBMIT

# Conference Session

# Java genetic street art

fr_FR : Peut-on générer, faire s'affronter et sélectionner des sets de règles dynamiques
pour dessiner comme Banksy ?

Le framework dOOv permet de générer des DSL 'pur java' en partant d'un modèle objet.
Il permet de muter dynamiquement un programme écrit avec ce DSL pendant son exécution et facilite
l'écriture d'algorithmes génétiques en Java.
Dans cette présentation, nous allons utiliser dOOv pour construire un set de contraintes associées
à une image que nous allons faire évoluer incrémentalement jusqu'à obtenir un dessin identique à l'original.
 
Yes, Java can do street art !

en_GB : Can a dynamic ruleset evolve well enough to draw like Banksy ?

The dOOv framework allow us to generate pure Java DSLs from object models. With it, we can mutate and evolve programs with the DSL abstract syntax tree API and collect metrics and tracing info on rules usage.
It allow us to clearly define and monitor production systems... or evolutionary algorithms!
We are going to use dOOv to define a tree of constraints on a given image and let it evolves long enough to repoduce the original.

Yes, Java can do street art !

## Status

TO_SUBMIT

## Private message for committee

Website: http://doov.io
Github: https://github.com/lesfurets/dOOv
Slides: http://doov.io/dsl_to_go_beyond_bean_validation_english.html



en_US : We developed dOOv to migrate our 500 business validation rules to a format that
would be easy to write and to export in a human readable form. We open-sourced
our project and present it in conferences because domain object validation is a
recurrent and important problem in our work, so it might help others. We like
to get feedback on dOOv, discuss about usage and future improvements.

fr_FR : Nous avons développé dOOv pour migrer plus de 500 règles métier de filtrage dans un
format qui permette une maintenance aisée et une relecture efficace par des utilisateurs
hors de l'équipe de développement. Le projet est open source, nous le faisons évoluer depuis
plus de 2 ans.
En 2018, nous l'avons présenté dans une dizaine de conférences et nous avons capturé pas mal de retour
et d'amélioration sur le projet.
La validation et le mapping d'objet métier est un problème récurrent dans notre travail et
nous espérons que d'autres équipes pourrons bénéficier de l'expérience accumulée.
