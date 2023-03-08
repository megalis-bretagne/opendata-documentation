# Installation poste de dev


**Prérequis**
Installer `docker`, `git`, `virtualenv` et `npm`

**docker-compose**
docker pour déployer localement mysql, apache solr, redis, flower cf ce repo

## opendata-extraction

    # Clone the code repository into ~/dev/opendata-extraction
    mkdir -p ~/dev
    cd ~/dev
    git clone https://github.com/megalis-bretagne/opendata-extraction.git opendata-extraction

    # Create the 'my_app' virtual environment
    mkvirtualenv -p PATH/TO/PYTHON opendata-extraction

    # Install required Python packages
    cd ~/dev/opendata-extraction
    pip install -r requirements.txt

Nous préconisons l'utilisation de l'IDE pycharm. Les configs de lancement pour pycharm des applications sont disponible dans le dossier runConfigurations du projet opendata-extraction

## opendata-front

Le projet a été généré avec Angular CLI version 11.2.3.

### Development server
Run ng serve for a dev server. Navigate to http://localhost:4200/. The app will automatically reload if you change any of the source files.
### Code scaffolding
Run ng generate component component-name to generate a new component. You can also use ng generate directive|pipe|service|class|guard|interface|enum|module.


## marque blanche actes

La documentation se trouve directement au sein du projet: https://github.com/megalis-bretagne/mq-actes


**TODO** fournir un docker-compose

