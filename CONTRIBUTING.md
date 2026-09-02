# Contribuer

Les contributions sont bienvenues, des corrections de typo aux fonctionnalités.

## Avant d'écrire du code

Pour un bug, ouvrez une issue d'abord : le correctif est parfois déjà en cours.

Pour une fonctionnalité, ouvrez une issue avant de commencer. Une pull request qui arrive
sans discussion préalable risque d'être refusée sur le principe, et c'est du travail perdu
pour vous.

Les petits correctifs évidents peuvent aller directement en pull request.

## Les commits

Format [Conventional Commits](https://www.conventionalcommits.org/fr/v1.0.0/) :
`type(portée): description`.

Types acceptés : `feat`, `fix`, `refactor`, `docs`, `chore`, `style`, `test`, `perf`, `ci`,
`build`.

Le `!` de rupture est réservé aux vraies ruptures de compatibilité : suppression ou renommage
d'un champ, d'une option ou d'un endpoint existant, changement d'une valeur par défaut.
Ajouter quelque chose n'est pas une rupture.

## La pull request

- Une pull request, un sujet. Les changements sans rapport partent dans une autre.
- Le titre suit lui aussi Conventional Commits, il est vérifié en CI sur certains dépôts.
- Ajoutez des tests quand le dépôt en a, sur la logique et les cas d'erreur, pas seulement
  sur le chemin heureux.
- Lancez le formateur et le linter du projet avant de pousser.
- Laissez la CI passer au vert avant de demander une relecture.

## Le style

Suivez le style du fichier que vous modifiez plutôt qu'une préférence personnelle. Si le
projet a un formateur configuré, il fait autorité.
