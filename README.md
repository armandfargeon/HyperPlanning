# HyperPlanning Marks Monitoring
Permet de notifier un étudiant sur son adresse email académique lorsqu'une nouvelle note est saisie sur HyperPlanning.

## Démarrage
Lancement: `python hp_scraper.py`<br />
Le programme attend ensuite la saisie de l'identifiant et du mot de passe HyperPlanning

## Dépendances
- Selenium pour simuler les actions utilisateurs (en mode headless donc sans navigateur): `pip install selenium`
- Le navigateur Chrome
- Selenium à besoin de chromedriver, à placer dans la variable d'environnement PATH. La version de chromedriver doit être la même que celle de chrome. https://chromedriver.chromium.org/
