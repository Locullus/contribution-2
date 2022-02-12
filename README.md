# contribution

- création d'un repo en local avec un fichier README.md
- initialisation du repo git :

```bash
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:mickael-Bula/contribution.git
git push -u origin main
```
## clonage depuis un autre compte

Changement de compte et création d'un repo **contribution** puis, dans celui-ci :
```bash
git clone git@github.com:mickael-Bula/contribution.git
```
Une fois la passphrass fournie, le repo est cloné.

## impossible de faire un push depuis le repo local

Du fait que c'est un compte étranger, le repo local ne possède pas les droits pour écrire dans le remote. Parfaitement logique. 
