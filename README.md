Dev Conferences
===============

Annuaire des conférences et communautés de développeurs dans les différentes villes de France.

* Conférences : événements se déroulant sur un ou plusieurs jours, généralement annuellement
* Communautés : groupes d'utilisateurs se rencontrant généralement mensuellement

## Contributions

Il manque une ville ? Il manque une conférence dans votre ville ? Faites une Pull Request !

Merci à toutes les personnes ayant contribué à l'ajout de conférences et de communautés.

### Ajouter une ville

Créez une nouvelle page portant le nom de la ville dans le répertoire `pages`, puis ajoutez-y du contenu (inspirez-vous d'une page existante).

### Ajouter une conférence/communauté

Complétez la page de la ville dans laquelle se trouve la conférence.

Template HTML d'une entrée :

```html
<a name="ancre"></a>
<h2><span class="glyphicon glyphicon-chevron-right"></span> Nom de la Conférence/Communauté</h2>

<div class="row">
    <div class="col-md-2">
        <img src="logo de la Conférence/Communauté" class="img-responsive">
    </div>
    <div class="col-md-10 text-justify">
        <p>
            Description de la Conférence/Communauté
        </p>

        <p>
            <span class="glyphicon glyphicon-home"></span> <a href="website url">website url/a>
            <br>
            <i class="fa fa-twitter"></i> <a href="https://twitter.com/twitterid">@twitterid</a>
        </p>
    </div>
</div>
```

Pensez également à ajouter un lien vers l'entrée au début de la page, dans la rubrique Conférences ou Communauté : 
```html
<a class="btn btn-primary" href="#ancre">Nom de la Conférence/Communauté</a>
```

### Pour tester vos modifications

Le site est réalisé à l'aide de [Jekyll](http://jekyllrb.com/) et est déployé sur [Github Pages](https://pages.github.com/).

Pour tester localement la génération du site, [installez Jekyll](http://jekyllrb.com/docs/installation/) et lancez ensuite la commande `jekyll serve`. Le site est disponible sur `http://localhost:4000`

## TODO

- [ ] ajouter des tags (ex : jug, java, php, gdg ...)
- [ ] ajouter la possibilité d'effectuer des recherches
- [ ] ajouter des liens vers les chaînes vidéo (youtube, parleys ...) des conférences
- [ ] gérér des agendas pour chacune des villes
- [ ] automatiser l'import d'événements depuis des sites comme meetup.com, lanyrd.com ...
- [ ] automatiser l'envoi de tweets pour annoncer les prochaines sessions (via @devconferences)
- [ ] faciliter la contribution de nouvelles conférences/communautés (formulaire + authentification github par exemple)
