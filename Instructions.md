Voici le projet 1 de fin de nouveau d'entrée. Il est recommandé que vous réalisiez une reproduction presque parfaite du capture d'écran du site. (nommé <<capture après réalisation>>).

Pour faciliter votre travail, le code HTML, index.html est partagé dans ce répertoire. Le code source CSS serait partagé dans peu de temps.

Veuillez commencer votre CSS ainsi:

```
*{
    box-sizing: border-box;
    margin: 0;
    padding: 0;
    font-family: 'Yu Gothic Medium', 'Arial Narrow', Arial, sans-serif;
}
*,
*::before,
*::after {
    box-sizing: border-box;
}
body, html {
    width: 100%;
    background-color: #e4eef8;
}
.wrapper {
    width: 90%;
    margin: 0 auto;
}
```

Voici les couleurs utiliséés ci-dessous; Veuillez vous en servir pour votre réalisation du projet.

* Background - #E4EEF8 ou #FFF
* ``` <a> ``` et ``` <input> ``` - #1F1F1F
* ``` <h6> ``` et ``` <p> ``` - #262729B3
* La bordure du bouton "Get Started" - #258AFF
* Bouton "Subscribe" - #FA593C

Veuillez trouver une description de la structure du site ci-dessous:

* Pour la 
```<nav class="parent-nav"> ```, 
employez le Flex avec des propriétés et positionnements nécéssaires.

* Pour la 
``` <nav class="child-nav"> ``` 
employez le Flex avec des propriétés et positionnements nécéssaires. 
    NB: Employez la propriété ```flex-grow: 1``` pour que la barre s'élargisse en largeur.

* Pour le container 
``` <ul> ``` 
employez le flex.

* Pour le 
``` <div class="hero-container"> ``` 
employez le Flex avec des des propriétés et positionnements nécéssaires.
    NB: Employez la propriété ```flex-direction: column``` pour une structure et organisation verticale de ses enfants.

* Pour le 
``` <form> ``` 
employez le Flex avec des des propriétés et positionnements nécéssaires.

* Pour le 
``` <div class="features"> ``` 
employez le Flex avec des des propriétés et positionnements nécéssaires.

* Pour le 
``` <div class="feature"> ```
employez le Flex avec des des propriétés et positionnements nécéssaires.
