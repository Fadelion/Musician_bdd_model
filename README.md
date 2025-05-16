# Musician_bdd_model

Ce projet est une application Ruby on Rails pour la gestion d'albums et de pistes musicales. Nous nous intéressons ici aux fondamentaux des `models` et des `migrations` et de `sqlite3`.

## Prérequis

- **Ruby** : 3.2.2 (vérifiez avec `ruby -v`)
- **Rails** : 7.x (vérifiez avec `rails -v`)
- **Bundler** : `gem install bundler`
- **Base de données** : SQLite3 (par défaut)
- **Node.js & Yarn** : pour la gestion des assets (optionnel mais recommandé)

## Installation

1. Clonez le dépôt :
   ```bash
   git clone <repo_url>
   cd Musician_bdd_model
   ```
2. Installez les dépendances :
   ```bash
   bundle install
   ```
3. Installez les dépendances JavaScript (si nécessaire) :
   ```bash
   yarn install
   ```

## Configuration

- Modifiez les fichiers de configuration dans `config/` si besoin (ex : `database.yml`).

## Création et initialisation de la base de données

```bash
rails db:create
rails db:migrate
rails db:seed # (optionnel, pour insérer des données de test)
```

## Lancer le serveur

```bash
rails server
```

Accédez à l’application sur [http://localhost:3000](http://localhost:3000).

## Lancer la suite de tests

```bash
rails test
```

## Auteurs
- [THIAM](https://github.com/thaliou)
- [ASSY](https://github.com/AssyaJalo)
- [SOUARE](https://github.com/bbkouty)
- [FANAR](https://github.com/fanarbandia)
- [MAIGA](https://github.com/Fadelion)

## Licence

Ce projet est sous licence MIT. Consultez le fichier [LICENSE](LICENSE) pour plus de détails.

---
Développé dans le cadre d'un projet d'apprentissage de la programmation web avec Ruby on Rails

## Aide

Pour toute question, consultez la documentation officielle de Ruby on Rails ou ouvrez une issue sur ce dépôt.
