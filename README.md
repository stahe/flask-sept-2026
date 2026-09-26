# Introduction étape par étape au framework web [Flask]

**Cours et codes (septembre 2026)** : 👉 **[https://stahe.github.io/flask-sept-2026/](https://stahe.github.io/flask-sept-2026/)**

## Auteur

Les codes et le cours ont été entièrement écrits par **Claude**, l'IA d'Anthropic, qui en est l'**auteur unique**, à la demande de Serge Tahé.

## Présentation

Ce cours présente pas à pas la construction d'une application web MVC avec le framework **Flask** (Python). Les pages HTML sont fabriquées par le serveur, avec des vues **Jinja2**, sans framework JavaScript côté navigateur.

Il fait suite au cours [Introduction étape par étape au framework web [Spring MVC]](https://stahe.github.io/springmvc-sept-2026/), dont il reprend exactement la progression. Ce cours faisait lui-même suite aux cours [ASP.NET Core MVC](https://stahe.github.io/aspnetcoremvc-sept-2026/) et [NestJS](https://stahe.github.io/nestjs-html-sept-2026/). Les exemples portent les mêmes numéros et traitent les mêmes sujets : un lecteur qui connaît l'un de ces cours peut comparer les frameworks exemple par exemple.

Le cours se déroule en deux temps :

- **28 petits exemples**, chacun centré sur une notion :
  - actions, routage, réponses et redirections ;
  - liaison et validation des paramètres (Pydantic) ;
  - vues Jinja2, gabarits, macros ;
  - formulaires WTForms, schéma Post / Redirect / Get, protection anti-CSRF ;
  - internationalisation ;
  - portées des données ;
  - cycle de vie d'une requête ;
  - authentification JWT, rôles, captcha ;
  - architecture en couches avec SQLAlchemy et MySQL.
- **Une étude de cas complète** : *RdvMedecins*, une application de prise de rendez-vous pour un cabinet médical. Elle compte trois rôles (administrateur, médecins, patients), fonctionne en français et en anglais, et est protégée contre les robots. Tous ses fichiers sont commentés dans le cours.

## Technologies

Python 3.12+ · Flask 3.1 · Jinja2 · Werkzeug · Flask-WTF / WTForms · Pydantic · SQLAlchemy 2.1 · PyMySQL · PyJWT · bcrypt · Babel · waitress · Bootstrap 5.3 · MySQL 8 / MariaDB

## Prérequis

- Python 3.12 ou plus récent ;
- Visual Studio Code, avec l'extension « Python » de Microsoft ;
- MySQL 8 (par exemple avec Laragon sous Windows) ou MariaDB ;
- curl.

L'installation de ces outils est décrite dans les annexes du cours.

## Contenu de l'archive des codes

- `exemples/` : les 28 exemples, chacun étant une petite application Flask (port 5000) ;
- `rdvmedecins2-flask/` : l'étude de cas (port 8081), avec son script SQL et son `README.md` ;
- `arborescence.txt` : l'arborescence complète.
