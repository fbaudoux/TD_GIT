## Message de commit

Il est important que les messages de commit soient explicites et que des conventions soient respectées par l'équipe.

```<type>(<portée>): <sujet>```

ou type peut prendre les valeurs suivantes

* build : changements qui affectent le système de build ou des dépendances externes (npm, make…)
* ci : changements concernant les fichiers et scripts d’intégration ou de configuration (Travis, Ansible, BrowserStack…)
* feat : ajout d’une nouvelle fonctionnalité
* fix : correction d’un bug
* perf : amélioration des performances
* refactor : modification qui n’apporte ni nouvelle fonctionalité ni d’amélioration de performances
* style : changement qui n’apporte aucune alteration fonctionnelle ou sémantique (indentation, mise en forme, ajout d’espace, renommante d’une variable…)
* docs : rédaction ou mise à jour de documentation
* test : ajout ou modification de tests

ou portée représente la fonctionnalité impactée

ou sujet décrit les modifications apportées en moins de 80 caractères 
* on utilise l’impératif présent : add, change, update, remove et non pas changed ou removed. add caching for better performance par exemple.