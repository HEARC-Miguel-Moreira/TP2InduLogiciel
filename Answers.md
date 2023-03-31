Quelles étapes sont réalisées par cette action ?
- Setup Python
- Install dependencies
- Lint with flake8
- Test with pytest

Une étape est définie au minimum par 2 paramètres, lesquels sont-ils
et à quoi servent-ils ?
- name et run

La première étape contient un paramètre ‘with’, a quoi sert-il ?
- permet de définir la version de python

Sur l’onglet Summary d’une analyse de code, SonarCloud fournit 4 indicateurs. Quels sont-ils et quelles sont leurs utilités ?
- Reliability : permet de voir si le code est fiable, "A coding error that will break your code and needs to be fixed immediately."
- Security : permet de voir si le code est sécurisé, "Code that can be exploited by a hacker."
- Maintainability : permet de voir si le code est maintenable, "Code that is confusing and difficult to maintain."
- Security Review : permet de voir si du code nécessite une revue manuelle pour vérifier s'il est fiable, "Security-sensitive code that requires manual review to assess whether or not a vulnerability exists."

À quoi sert l’indicateur Quality Gate ?
- permet de voir si le code est de bonne qualité, s'il est prêt pour la production

Quelle est la différence entre les sections New code et Overall Code dans l’onglet Summary ?
- New code : permet de voir les nouvelles erreurs, bugs, etc. introduits par le code
- Overall code : permet de voir les erreurs, bugs, etc. du code en général

Y a-t-il des Code Smells ? Si oui, combien et pour quelle(s) raisons(s) ?
- 3, Remove the unused function parameter "deffered" x2, Update this function so that its implementation is not identical to spend_cash on line 16

Y a-t-il des Security Hotspots ? Si oui, combien et pour quelle(s) raison(s) ?
- 1, the python image runs with root as the default user.
