# La Table

Un jeu de rôle à jouer entre amis : Claude raconte et arbitre, la table lance les dés. De 2 à 8 joueurs, des secrets, des trahisons, une histoire jamais jouée.

## Télécharger

**[Dernière version pour Windows](https://github.com/nathangerardeaux/la-table/releases/latest)** : dans « Assets », clique sur `LaTable-x.y.z.exe`.

L'exe est portable : rien ne s'installe, il se lance directement. Au premier lancement, il propose d'ajouter un raccourci sur le Bureau.

Windows 10 et 11, environ 200 Mo.

## Avertissement de Windows

Le jeu est récent et pas encore connu de Windows, qui peut afficher « Windows a protégé votre ordinateur » : clique sur **Informations complémentaires**, puis **Exécuter quand même**.

Pour vérifier que le fichier est bien l'original, compare son empreinte SHA-256 avec celle indiquée dans la release :

```powershell
Get-FileHash .\LaTable-0.1.2.exe -Algorithm SHA256
```

## Jouer

- **Rejoindre** : un ami héberge, tu colles son code, tu entres à la table. Rien d'autre à installer, aucun abonnement.
- **Héberger** : le maître du jeu tourne avec ton abonnement Claude (Pro ou Max) et Claude Code installé sur ton PC. L'appli te guide.

Le guide complet des règles : [nybo.fr/la-table](https://nybo.fr/la-table)

---

La Table, créé par Nathan Gerardeaux, [nybo.fr](https://nybo.fr). Ce dépôt ne contient que les versions publiées du jeu.
