
# Conference Session :

# BOF

# How to create a fluent API DSL with lambda builders? 
# Comment créer son propre langage avec un fluent API et un lambda builder ?

en_US : With the dOOv framework, we are trying to solve a common problem with software: 
performance vs. readability vs. type-safety. Since Java 8, lambdas offer the 
ability to compose functions at runtime with high performance. We built a 
fluent API using lambdas to write validation and mapping logic with a DSL. It 
enables the written application rules to be introspected and profiled by 
visiting the DSL abstract syntax tree at runtime. During this BOF we will 
discuss how the framework is designed, the issues that we encountered 
generating the natural language output, failure cause analysis, and AST 
rewriting.

fr_FR : Grâce au framwork dOOv, nous allons tester une nouvelle proche pour resoudre un problème
recurrent dans nos applications: performance vs. lisibilite vs. typage fort.
Depuis Java 8, l'API lambda permet de composer des fonctions avec d'excellentes performaces à l'exécution.
Nous avons construit un fluent API qui permet d'écrire des règles de validation et de mapping
avec une approche de DSL.
Il devient possible de parcourir l'arbre de syntaxe du DSL lors de l'exécution et d'effectuer
des réécritures dynamiquement. Pendant la session, nous presenterons comment le framework fonctionne,
les problèmes rencontrés pour générer du langage naturel, et la réécriture des arbres de syntaxe pour
les afficher sous forme canonique après leur éxécution.

## Status 

TO_SUBMIT

# Hands-On-Labs

# Getting Started with custom DSLs using the dOOv framework

Have you heard a lot about the advantages of DSLs but don't know where to 
start? In this session, we will be modernizing an e-Commerce application,
which has validation rules with BeanValidation and implements 
business logic and mapping code with plain old Java. Using dOOv, 
attendees will generate a Java-based DSL and migrate incrementally the 
logic and mapping code of the application. First, attendees will use 
dOOv to rewrite BeanValidation rules and discover the benefits of a 
strongly-typed fluent API to express constraints of a model.
Then we will migrate the application logic and the mapping code to ensure 
the compliance and governance of the partner exchanges. Finally, we will 
evaluate the performance and flexibility gains.

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

fr_FR : Nous avons développé dOOv pour migrer plus de 500 règles métier de filtrage dans un format qui permette
une maintenance aisée et une relecture efficace par des utilisateurs hors de l'équipe de développement.
Le projet est open source, nous le maintenanons et le faisons évoluer depuis plus de 2 ans.
En 2018, nous l'avons presenté dans une dizaine de conférences et nous avons capturé pas mal de retour
et d'amelioration sur le projet.
La validation et le mapping d'objet métier est un problème récurrent dans notre travail et nous espérons que
d'autres equipes pourrons bénéficier de l'expérience accumulée.
