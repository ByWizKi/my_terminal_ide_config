# my_terminal_ide_config

## Étape 0 - Création de la nouvelle arborescence de l'utilisateur

- On supprime l'ancienne arborescence de l'utilisateur
```bash
sudo cd ~ && rm -rf Desktop Downloads Movies Pictures Documents Library Music Public
```
- On crée la nouvelle arborescence
  ```
    nono_dev
      apps
        .
        .
        .
      downloads
        .
        .
        .
      projet
        .
        .
        .
  ```
- Dans le dossier 'apps' on aura toutes les applications qu'on a besoin lié au dev
- Dans le dossier 'downloads' on aura tout nos downloads
- Dans le dossier 'projet on aura tout nos projet'

PS : Mes documents sont stocker dans le cloud voila pourquoi ici j'en est pas besoin. Les projets pourront être sauver sur github comme ca ils sont dispo sur n'importe quelle machine.

```bash
cd ~ && mkdir apps downloads projet
```

## Étape 1 - Installation de HomeBrew

- Cette commande provient directement du site officiel de HomeBrew https://brew.sh
```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
&&
brew update
&&
brew upgrade
```
### Etape 1.2 Installation de Wget -via Homebrew
```bash
brew install wget
```
