Pour utiliser Git, il faut avant tout créer un dossier avec la console : mkdir + nom du dossier 
Un répertoire de dossier géré par Git s’appelle un repository
Pour activé un repository, on tape en commande sur Git : git init
Pour créer un dossier on tape la commande : git add  +nom de fichier.extension
On modifie un fichier en tapant git commit. En tapant : git commit -m « » on laisse le message que l’on veut en indiquant les modifications faites entre les «  »
Pour voir toutes les modifications faites, il suffit de taper : git log
On peut alors mettre à jour un fichier avec la commande : git commit -a-m
Pour se positionner sur un commit donné il suffit d’utiliser la commande : git checkout SHA (le SHA étant le n° identifiant le commit) et pour le commit le plus récent : git checkout master

ATTENTION ! On ne peut pas réellement supprimer un commit mais plusieurs options s’offre alors
- git revert SHA   (ce qui crée alors un nouveau commit)
- git commit --amend -m "Votre nouveau message" (ce qui peut se faire uniquement si l’on n’a pas « pushé » le commit)
- git reset –hard‌ (dans la cas où l’on n’a pas fait de nouveau commit et que l’on veut annulé les commits non commités…
