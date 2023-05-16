# py-cat

`py-cat` est une implémentation en Python d'une sous-ensemble de la fonctionnalité 'cat' de GNU. Elle offre également l'option d'insérer un délai entre les caractères.

## Prérequis

- Python 3.x

## Utilisation

```shell
python py-cat.py [OPTION]... [FILE]...
```

Cela va concaténer le(s) fichier(s) spécifié(s) et afficher leur contenu sur la sortie standard.

### Options

- `-b`, `--number-nonblank` : numérote les lignes non vides, annule `-n`.
- `-n`, `--number` : numérote toutes les lignes de sortie.
- `-r`, `--restart` : les numéros de ligne commencent à zéro, implique `-n`.
- `-s`, `--squeeze-blank` : supprime les lignes vides répétées.
- `-d`, `--delay` : insère un délai (en millisecondes) entre chaque octet.
- `-?`, `--help` : affiche l'aide et quitte.
- `--version` : affiche les informations de version et quitte.

### Exemple d'utilisation

```shell
python py-cat.py f.txt g.txt
```

Cela affiche le contenu de `f.txt`, puis le contenu de `g.txt`.

## Licence

Ce programme est un logiciel libre : vous pouvez le redistribuer et/ou le modifier sous les termes de la Licence Publique Générale GNU telle que publiée par la Free Software Foundation, soit la version 3 de la Licence, soit (à votre choix) toute version ultérieure.

Ce programme est distribué dans l'espoir qu'il sera utile, mais SANS AUCUNE GARANTIE ; sans même la garantie implicite de QUALITÉ MARCHANDE ou d'ADÉQUATION À UN USAGE PARTICULIER. Voir la Licence Publique Générale GNU pour plus de détails.

Vous devriez avoir reçu une copie de la Licence Publique Générale GNU avec ce programme. Si ce n'est pas le cas, voir <http://www.gnu.org/licenses/>.

Source : <https://mike632t.wordpress.com/2016/03/22/implementing-cat-in-python/>