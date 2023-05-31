# PolyglotPo

PolyglotPo est un script Python qui permet la traduction automatisée de fichiers .po en plusieurs langues en utilisant la bibliothèque Deep Translator. Il élimine le besoin de traduction manuelle, vous faisant gagner du temps et des efforts.

## Fonctionnalités

- Traduction automatique de fichiers .po en plusieurs langues.
- Utilisation de la bibliothèque Deep Translator pour une traduction fluide.
- Interface en ligne de commande simple et intuitive.
- Prise en charge d'un large éventail de langues.

## Prérequis

Assurez-vous d'avoir les éléments suivants installés :

- Python 3.x : [Téléchargement Python](https://www.python.org/downloads/)
- Bibliothèque deep_translator : Installation avec `pip install deep_translator`

## Utilisation

Pour utiliser PolyglotPo, suivez ces étapes :

1. Clonez ce référentiel GitHub sur votre machine locale :

```shell
$ git clone https://github.com/your_username/PolyglotPo.git
```

2. Accédez au répertoire du projet :

```shell
$ cd PolyglotPo
```

3. Exécutez le script avec la commande suivante :

```shell
$ python polyglot_po.py --source fichier_source.po
```

Remplacez `fichier_source.po` par le chemin du fichier .po que vous souhaitez traduire.

4. Spécifiez la ou les langues cibles à l'aide du paramètre `--language` :

```shell
$ python polyglot_po.py --source fichier_source.po --language fr de es
```

Remplacez `fr de es` par les codes des langues souhaitées (par exemple, `fr` pour le français, `de` pour l'allemand, `es` pour l'espagnol).

5. Les fichiers .po traduits seront générés dans le répertoire `translations`.

## Exemples

Voici quelques exemples d'utilisation de PolyglotPo :

- Traduire un fichier .po en français, allemand et espagnol :

```shell
$ python polyglot_po.py --source fichier_source.po --language fr de es
```

- Traduire un fichier .po en anglais et italien :

```shell 
$ python polyglot_po.py --source fichier_source.po --language en it
```

## Licence

Ce projet est sous licence MIT. La licence MIT est une licence de logiciel libre très permissive qui permet à quiconque d'utiliser, de modifier et de distribuer le logiciel, y compris à des fins commerciales, tant que la notice de copyright et la licence sont incluses dans toutes les copies du logiciel. Consultez le fichier [LICENSE](LICENSE) pour plus d'informations.

N'hésitez pas si vous avez d'autres questions !
