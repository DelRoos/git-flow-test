# Presentation de git flow

**Git flow**: est une méthodologie de gestion de depot git.

Cette methodologie propose deux grande famille de brannche a savoir:

* **Les branches secondaires:** elles sont utilisees generalement l'orsque le code n'est pas encore stable. on retrouve 5 branche principale ici:
  * **Features**: destiné au nouvelle fonctionalitees;
  * **Bugfix**, Hotfix: destine a la correction de bug;
  * **Release**: destine au deployement et a la production d'une nouvelle version de l'App;
  * **Support**: utilise pour l'ajout des supports telque la documentation;


* **Les branches principales** ceux sont elle qui contienne les code fontionnelle de l'application. Elle sont au nombre de 2:
  * **Master**: Contient le code source deployer en ligne;
  * ***Develop***: Contient une version en cours de traitement;

Elle permet aussi de prefixer les versions automatiquement.

installer git-flow : `brew install git-flow-avh`

initialiser un projet : `git flow init`

cree une nouvelle fonctionalite ( feature ):`git flow feature start nom_branche`


```

```
