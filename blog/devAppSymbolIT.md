# Développer des applications chez Symbol-IT

> In progress

Intro, blabla sur la vision de symbol pour le developpement d'application et sur comment ce manifeste doit etre utiliser pour organiser les projets, accompagner les développeurs dans leur monter en competence et structurer la boite.

[Inspirer par MAIF OSS](https://maif.github.io/cards/fr/all.html)

Les cinqs piliers **trouver un autre mot / phrase**

* Time to market 
**Délai nécessaire pour le développement et la mise au point d'un projet ou d'un produit, avant qu'il puisse être lancé sur le marché**

* Ux (User Experience) 
**Désigne la qualité de l’expérience vécue par l’utilisateur dans toute situation d’interaction. L’UX qualifie l’expérience globale ressentie par l’utilisateur lors de l’utilisation d’une interface, d’un appareil digital ou plus largement en interaction avec tout dispositif ou service**

* Humain 
**Organisation et un principe a mettre en place IN PROGRESS**

* Interoperabilite 
**Capacité que possède un produit ou un système, dont les interfaces sont intégralement connues, à fonctionner avec d’autres produits ou systèmes existants ou futurs et ce sans restriction d’accès ou de mise en œuvre**

* Regles du jeu 
**il en faut bien quelques une quand meme ... IN PROGRESS**

## Time to market
* MVP (**Minimum Viable Product**) 
Le MVP permet d'éprouver le concept, son **périmètre** doit être **réduit** tout en permettant de le marketer. Il permet de récuperer rapidement des **feedbacks** auprès des **Early Adopters**. Le MVP est déployé et exploité en **production**. Le **MVP** permet de se confronter a la realite en quelques semaines. Profitez en pour recolter du feedback de vos utilisateurs et pour apprendre de vos erreurs. N'ayez pas peur de tout changer, ne l'oubliez pas, vous allez echouer!

* SASS
Les solutions SaaS sont perennes et economique, elles permetent souvent d'accelerer la mise en oeuvre d'un MVP.

* KISS (**Keep It Simple and Stupid**) 
Ne compliquez pas les choses plus que necessaire, gardez les simples. 
Si une maquette papier ou un form peuvent suffire pour eprouver concept n'allez pas plus loin. 
> /!\ toutefois simple ne veut pas dire simpliste. 

* Devops
Le déploiement en production doit être un non-événement, ils doivent s'adapter aux contraintes et besoins métier et donc être automatises et fréquents. 

* Moins de specs + de dev
Les specifications doivent se concentrer sur les **quoi** pas sur le **comment**. Le produit doit etre auto-documente, la documentation fait partie du produit et doit etre versionne au meme titre que le code.

## Ux
* Performance
* Perception
* Mesure, observabilite, feedback
* Mobile First
* Degradation

## Humain
* Feature Team
* Polyvalence et craftman
* Veille
* CoConstruction
* Devops
* Abattre les silos

## Interoperabilite
* API First
  * Controle et maitrise
  * Simple et rapide
* Multi-tenant
* Parametrable
* Documentation

## Regles du jeu
* Build vs Buy
* Open Source
* Autonome et faiblement couple
* Stockage independant
* Decoupage **Microservice**
* [Reactive](https://www.reactivemanifesto.org/pdf/the-reactive-manifesto-2.0-fr.pdf)
* Asynchrone
* Evenements
* Bac a sable
* Tolerant a la panne, resilient
* Cloud => PaaS 
* Metriques
* Qualite
* Tests
* Securite
