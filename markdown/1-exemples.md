# Exemples de contenu

## Slide simple

Ceci est une slide simple avec différents niveaux de titre

### Titre 3

Contenu du titre 3

#### Titre 4

Contenu du titre 4

## Bloc de code

Les blocs de codes sont supportés avec la coloration syntaxique, un exemple en `langage c` :  

```c {.number-lines}
#include <stdio.h>

int main(void)
{
    printf("Hello, World!\n");

    return 0;
}
```

## Image et colonnes

:::::::::::::: {.columns}
::: {.column width="50%"}
Voici un exemple de présentation par colonne grâce au code suivant : 

`````markdown
:::::::::::::: {.columns}
::: {.column width="50%"}
Voici un exemple de présentation par colonne grâce au code suivant : 


```markdown
:::::::::::::: {.columns}
::: {.column width="50%"}
Voici un exemple de présentation par colonne grâce au code suivant : 

:::
::: {.column width="50%"}
![Logo de Synoptik Labs](assets/logo_slabs.png "Logo de Synoptik Labs"){ width=70% }
:::
::::::::::::::
```

:::
::: {.column width="50%"}
![Logo de Synoptik Labs](assets/logo_slabs.png "Logo de Synoptik Labs"){ width=70% }
:::
::::::::::::::
`````

:::
::: {.column width="50%"}
![Logo de Synoptik Labs](assets/logo_slabs.png "Logo de Synoptik Labs"){ width=70% }
:::
::::::::::::::

## Mode présentateur

- Ouvrez le mode présentateur avec la touche \``S`\`
- Une seconde fenêtre s'ouvre avec : 
    - la prévisualisation de la prochaine slide
    - un timer
    - les notes de la slide en cours

:::notes
Ici s'affiche les notes visibles uniquement par le présentateur.
:::

## Liste incrémentale et export en PDF

Pour exporter le contenu en PDF il faut : 

:::incremental
1. Ajouter `?print-pdf` à l'URL juste après l'extension `.html` du fichier
2. Utiliser la fonction d'impression de votre navigateur
3. Enregistrer la prévisualisation au format PDF
:::
