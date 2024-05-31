# 1. La description du projet 'Maroc-data-visualisation'

<p>
  Ce projet est sous forme d'une application Bokeh qui sert à analyser une dataset marocaine. La data choisie vise à capturer divers aspects du paysage du développement logiciel au Maroc, en se concentrant sur quatre domaines principaux : <strong>Éducation, Travail, Technologie et Communauté</strong>.
  <br><br> Notre objectif était d'utiliser les données de ce dataset pour réaliser des visualisations concrètes et informatives qui peuvent aider à mieux comprendre l'état actuel et les tendances du développement logiciel au Maroc.
  <br> À travers ces visualisations, nous espérons fournir des insights précieux aux développeurs, aux éducateurs, aux employeurs et à tous les membres de la communauté technologique marocaine.
</p>
<p>
  Le projet contient trois fichiers, chacun ayant un rôle spécifique :
  <ul>
    <li>
      Le premier fichier est un fichier Jupyter Notebook <strong>'Notebook.ipynb'</strong> qui offre une vue claire sur le dataset utilisé. Ce fichier vise principalement à explorer notre dataset avant de l'utiliser et de créer des visualisations. Il est essentiel de vérifier si le dataset est utile pour les visualisations et de le nettoyer si nécessaire. Ce fichier contient également des visualisations simples pour tester le dataset avant et après le nettoyage.
    </li>
    <li>
      Le deuxième fichier est un fichier Python <strong>'main.py'</strong> qui contient notre application Bokeh. Dans ce fichier, vous pouvez voir toutes les visualisations que nous avons réalisées. Vous pouvez ainsi obtenir une idée générale et aussi détaillée concernant les résultats de  la première enquête <em>"State of Dev Survey"</em> lancée par Developer Circles Morocco.
    </li>
  </ul>
</p>


## 3. Installation et configuration

<p>
  Pour utiliser cette application, suivez les étapes ci-dessous :
  <ol>
    <li>Clonez le dépôt depuis GitHub : <code>git clone https://github.com/najiaamghouz/maroc-data-visualization</code></li>
    <li>Accédez au répertoire du projet : <code>cd Maroc-data-visualisation</code></li>
    <li>Installez les dépendances nécessaires : <code>pip install -r requirements.txt</code></li>
    <li>Lancez l'application Bokeh : <code>bokeh serve --show main.py</code></li>
  </ol>
</p>

## 4. Contribuer

<p>
  Les contributions sont les bienvenues ! Si vous souhaitez contribuer à ce projet, veuillez suivre les étapes ci-dessous :
  <ul>
    <li>Forkez le dépôt sur GitHub.</li>
    <li>Créez une nouvelle branche pour votre fonctionnalité ou correction de bug : <code>git checkout -b nom-de-la-branche</code></li>
    <li>Apportez vos modifications et committez-les : <code>git commit -m "Description de vos modifications"</code></li>
    <li>Push la branche sur votre fork : <code>git push origin nom-de-la-branche</code></li>
    <li>Soumettez une pull request pour révision.</li>
  </ul>
</p>
> [!TIP]
> Helpful advice for doing things better or more easily.


## 5. Licence

<p>
  Ce projet est sous licence MIT. Veuillez consulter le fichier <strong>LICENSE</strong> pour plus de détails.
</p>

## 6. Les visualisations

### Voici la première visualisation

![V1](https://github.com/najiaamghouz/maroc-data-visualization/assets/171170836/525e9f45-38cc-4f49-bd42-9a6cd6fd2643)
 
<p>
  la premiere visualisation simple elle contient juste la distribution des niveaux d'éducation dans l'ensemble de données présenté.
  <ul>
     <li> La visualisation montre une tendance claire où la majorité des développeurs ont un niveau Bac +5, suggérant peut-être une préférence ou une exigence pour ce niveau dans le contexte étudié.</li>
    <li> Le faible nombre de développeurs avec un niveau Bac +8 pourrait indiquer une plus grande rareté de ce niveau d'éducation ou des exigences spécifiques et plus élevées pour atteindre ce niveau.</li>
  </ul>
</p>


### Voici la deuxième visualisation


![V2](https://github.com/najiaamghouz/maroc-data-visualization/assets/171170836/12009e1a-1e51-45d0-a183-f417320d2e8f)

<p>
 La deuxième visualisation sert à représenter la distribution des développeurs entre ceux qui préfèrent immigrer en dehors du Maroc et ceux qui préfèrent rester au Maroc.
  <ul>
     <li>La visualisation montre une tendance claire où la majorité des développeurs back-end (environ 200 personnes) envisagent l'immigration, ce qui pourrait suggérer des facteurs comme de meilleures opportunités de travail, des conditions de vie, ou d'autres motivations personnelles ou professionnelles.</li>
    <li> Le nombre plus faible de développeurs back-end (environ 80 personnes) sans plans d'immigration pourrait indiquer une satisfaction avec leur situation actuelle ou des obstacles à l'immigration. </li>
  </ul>
</p>

