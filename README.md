# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...

exercice hybride [bâtard mixte hétéroclite] par combinaison avec des .
repérer les 

Production HYBRIDE

  la décomposer en PROJETS

    ces projets en métiers
      ces métiers en spécialités [essentielles / adjacentes (de moindre importance, cf. possibilités inexploitées)]
        ces spécialités en génériques (listes) de tâches

le faire à rebours (énumérer les tâches, à terme les regrouper en spécialités > métiers)
  
dessiner l'ARC DE RÉALISATION (± le comment du pourquoi pas à pas)
  énumérer les routines issues de mes (ré-)apprentissages
  noter les possibilités inexploitées
gamma = publier le résultat
betas successives = réviser le résultat & puiser dans le réservoir des possibles
alphas successives = publier par avancées (révision et ou possible exploité)

PROJETS
  app

1-formatter (jeu de mots sur 'formateur' [éducateur] & 'formatage' [dispositio]) - extract, transform, and load (ETL) contents

  profil (métier) : MARKETEUR
  Arc de réalisation, étape 0 : segmenter (formation initiale ? continue ? langue maternelle ? situation géographique ? âge ? spécialité ?)
  gamma => je laisse tomber [choix arbitraire : orth. niveau formation continue & fle des affaires] ; beta => décliner des gammes

  profil (métier) : - ÉDUCATEUR POLYVALENT [collège -> univ., cours du soir, fle]
                    - disposant de compétences informatiques adjacentes (de relative importance)

  Arc de réalisation, étape 1 : RASSEMBLER DES CONTENUS PÉDAGOGIQUES CHOISIS : les penser, les classer, les formater
    créer / récupérer des contenus numériques ou statiques : ocr / wget
    les hasher (trouver un formatage commun : JSON)
    les scanner (ruby text processing : Regexp, StringScanner, etc.)

    
  profil (métier) : DÉVELOPPEUR (Unix command line, Rails [Ruby, minitest], HTML, CSS, JavaScript, SQL [Postgresql])

  Arc de réalisation, étape 2 : créer l'outil pour nourrir rationnellement la base de données de travail

2-authenticator [RORT]

n-dictator

  profil (métier) : - ÉDUCATEUR POLYVALENT [collège -> univ., cours du soir, fle]
                    - disposant de compétences informatiques adjacentes (de relative importance)

  Arc de réalisation, étape 1 : DictationParser (StringScanner, diff-lcs)

  profil (métier) : DÉVELOPPEUR {rails, javascript}
  Arc de réalisation, étape 2 : créer l'outil de dictées en ligne
